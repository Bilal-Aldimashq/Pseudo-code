# Calculer le nombre de bonbons 

début  candys (entier bonbon)
bonbon = 0
argent > 0
prix > 0 
    si argent>0 && prix>0
        tant que argent > prix
            argent<- argent - prix 
            bonbon <- bonbon + 1
        fin tant que
    retourner bonbon
fin candys
