# LABORATORIO 1- INTRODUCCIÓN GIT
ESCUELA COLOMBIANA DE INGENIERÍA - CICLOS DE VIDA DE DESARROLLO DE SOFTWARE

---

## Integrantes
- Geronimo Martinez Nuñez.
- Carlos David Barrero Velasquez.

---

## Respuestas ✅
### Primera parte
Creacion del repositorio de manera local 

![Text](assets/img1.png)

-	Averigua para qué sirve y como se usan estos comandos **git add** y **git commit -m “mensaje”**
Respuesta:
#### Git add
```bash
   git add .
```
Este comando se usa para añadir todos los archivos nuevos o modificados al área de preparación.

```bash
   git add NAME1, NAME2
```
También permite añadir archivos de forma manual, mencionando los nombres específicos de los archivos que queremos preparar.

#### Git Commit
```bash
   git commit -m "mensaje"
```
Este comando guarda los cambios en el repositorio, agregando un mensaje descriptivo que explique las modificaciones realizadas.

Para crear un repositorio vacío en GitHub, simplemente haz clic en el botón "Crear repositorio" y completa el formulario correspondiente, como en la imagen lo muestra.

![Text](assets/Img3.png)

Despues se conecta con el repositorio local al remoto que acabamos de crear.
```bash
   git add .
   git commit -m "Primer commit"
   git remote add origin https://github.com/MimiRandomS/CVDS_Lab01
   git push -u origin main
```

---

### Segunda parte

## :white_check_mark: 1.
1. Empezando la segunda parte del laboratorio escogimos que el owner es Geronimo Martinez y el collaborator es Carlos Barrero
## :white_check_mark: 2, 3 y 4.

Aqui podemos ver la serie de pasos 2, 3 y 4.

![Text](assets/img4.png)

## :white_check_mark: 5 y 6.

Al editar el archivo **README.md** simultáneamente en la rama principal, se generó un conflicto que requiere que quien resolvió el conflicto decida entre aceptar, descartar o combinar ambos cambios realizados.

![Text](assets/img5.png)

Estos son algunos cambios al azar que realizamos para ver que sucedia cuando editabamos al tiempo, como ya mencionamos las opciones para resolver el conflicto, en los commit esta separado por colores verde y rojo el cual informan los cambios realizados.

polin
gero
hola

### Ejemplo de como se ve el commit al aceptar los cambios, en este caso acepta los dos cambios y los combina.

![Text](assets/img2.png)
