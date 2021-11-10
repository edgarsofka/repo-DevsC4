# ACTIVIDAD GIT Y GITHUB

* Crear un repositorio local con mínimo 3 ramas adicionales a la master( en total 4 ramas) y realice operaciones básicas sobre los archivos en cada rama, al final haga un merge local y después subirlo a un repo en la nube de github.
Documentar toda la traza de los comandos y las respuestas que devuelve. (utilice capturas de pantallas para demostrar todo el proceso) adicional a esto comparta el link de su repo de github.

## Comandos Usados

Clonar repositorio
```
$	git clone git@github.com:davidangarita1/repo-DevsC4.git
```

Ingresar a la carpeta
```
$	cd repo-DevsC4
```

Crear Ramas
```
$	git checkout -b Dev
$	git checkout -b Test
$	git checkout -b issues
```

Moverse a la rama Dev
```
$ git checkout Dev
$ git commit -am "Agregue texto en etiqueta P"
```	

Moverse a la rama Test
```
$ git checkout Test
$ git  commit -am "Agregue Prueba de texto y script"
```	

Moverse a la rama issues
```
$ git checkout issues
$ git commit -am "Agregue texto que dara error en merge"
```	

Moverse a la rama main
```
$ git checkout main
$ git commit -am "Agregue readme.md"
```	

* PARA RESOLVER ESTE EJERCICIO CADA UNO DE LOS APRENDICES DEBE crear una carpeta con su nombre dentro de esta carpeta y colocar la solución de su ejercicio.