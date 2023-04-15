# practica_github
blabla

Federico Moretto
<<<<<<< HEAD
Thomas Agustin Luna
=======

Pasos para hace rel Git Merge y unir sus ramas individuales al Main / Master

-Una vez que tiene terminada toda tu rama le dan el 
  --git add .
  --git commit -m "Lo que quieran poner para detallar"
  --git push
-Cambian a la rama principal con
  --git checkout main
-Primero tiene que poner el siguiente comando apra que les traiga todos los cambis que se hayan generado en la rama main (por ejemplo el error que nos salia el otro dia era porque habia hecho un merge y se habia actuializado el main, pero el resto de nosotros que no habiamos hecho el merge lo teniamos desactualizado por eso tiraba el error. Entonces tenemos que actualizar el main)
  --git pull origin main
-Ahora si se tira el merge
  --git merge [nombre de la rama de cada uno]
-Y finalmente un push ( a veces tira error que lo solucinamos con un forced push)
  --git push (noraml)
  --git push -f (forzado)
>>>>>>> Fede-Moretto
