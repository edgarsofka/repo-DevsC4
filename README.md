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
$	git checkout Dev
$	git commit -am "Agregue texto en etiqueta P"
```	
Codigo:
```html
<html>
<head>
  <title>Mi pagina DangWebs</title>
</head>
<body>
  <h1>Mi pagina web sofkiana</h1>
  <p>Hola Mundo Me llama David Angarita</p>
</body>
</html>

```

Moverse a la rama Test
```
$	git checkout Test
$	git  commit -am "Agregue Prueba de texto y script"
```	
Codigo:
```html
<html>
<head>
  <title>Mi pagina web1</title>
</head>
<body>
  <h1>Mi pagina web sofkiana</h1>
  <p id="txt">Hola Mundo Me llamo David</p>
  
  <script>
    let texto = document.getElementById("txt").innerHTML;
    if(texto == "Hola Mundo Me llamo David"){
      console.log("El texto es correcto");
    }else{
      console.log("El texto es incorrecto");
    }
  </script>
</body>
</html>

```

Moverse a la rama issues
```
$	git checkout issues
$	git commit -am "Agregue texto que dara error en merge"
```
Codigo:
```html
<html>
<head>
  <title>Mi pagina Tiene un error</title>
</head>
<body>
  <h1>Mi pagina web sofkiana</h1>
  <p>Al hacer merge me generara un error</p>
</body>
</html>
```

Moverse a la rama main
```
$	git checkout main
$	git commit -am "Agregue readme.md"
$	git commit -am "Agregue cambios de readme.md"
$	git commit -am "Cambios nuevos del readme.md"
```	

* PARA RESOLVER ESTE EJERCICIO CADA UNO DE LOS APRENDICES DEBE crear una carpeta con su nombre dentro de esta carpeta y colocar la solución de su ejercicio.