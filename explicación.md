##Ejercicio1

primero haces un git branch clone y clonas el repositorio
segundo te metes y haces un "git branch -a" y miras las ramas que estan en el otro repositorio
tercero haces un "git checkout -a" para añadir la rama lo haces "origin/trilogia_original"
Cuarto añadimos la rama "trilogia_original" a "main" con git merge "trilogia_original"
Quinto en "trilogia_precuelas" hacemos un "git rebase main" nos aparecera conflictos vamos al archivo y los quitamos hacemos un "git add ." hacemos "git rebase --continue" arreglo conflictos y "git add ." lo hacemos hsata donde nos deje de salir conflictos
Sexto cuando ya no nos da conflictos nos vamos a main "git chekout main" ahi hacemos  "git merge triloga_precuelas"
Septimo es lo mismo "git checkout trilogia_secuelas" hacemos "git rebase main" y resolvemos conflictos y despues  "git rebase --continue " y "git add . " hasta que se resuelvan los conflictos aqui hay una trampa la quitas y ya 
Octavo nos vamos a main "git checkout main" y hacemos un "git merge trilogia_secuelas"

##Ejercicio 2

Primero vamos a antologia "git checkout antologia" metemos una pelicula "git add ." y despues un commit "git comit -m "1""
Segundo vamos a antologia "git checkout antologia" metemos una pelicula "git add ." y despues un commit "git comit -m "2""
Tercero vamos a antologia "git checkout antologia" metemos una pelicula "git add ." y despues un commit "git comit -m "3""
Cuarto "git log"
Quinto quitamos los commit "git reset  --soft HEAD~3"
Sexto metemos todas las pelicula en un commit  "git commit -m "peliculas""
Septimo hacemos un "git rebase main" nos vamos a main y hacemos un "git merge "
Octavo añadimos todos los cambios "git add ."

##Ejercicio 3

hacemos una rama "git branch series" comprobaos que existe "git branch" nos metemos en la rama series "git checkout series"
hacemos un fichero llamado series.txt en git-wars
añadimos las series
añadimos cambios "git add ." "git commit -m """
Sacamos el primer link "git log"

