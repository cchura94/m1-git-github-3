# Actividades
## 1. Inicialización de un repositorio GIT
**Objectivo**: Aprender a crear un repositorio Local
**Instrucciones**
1. Abrir una Terminal
2. Navegar a la carpeta del proyecto
```bash
cd mi_proyecto
```
3. Inicializar el repositorio GIT con el comando:
```bash
git init
```
4. Verificar el estado con:
```
git status
```
## 2. Realizar el primer commit
**Objectivo**: Realizar el primer commit local
**Instrucciones**
1. Crear un archivo index.html o README.md.
2. Agregar contenido a los archivos.
3. Usa `git add .` para añadir el archivo al area de preparación
4. Realizar un commit con el comando
```bash
git commit -m "Mi Primer Commit"
```
5. Verificar el estado con:
```bash
git log
```
Para asegurarse de que el commit se realizó correctamente


## 3. Creación y conexion a un repositorio GITHUB
**Objectivo**: Crear un repositorio remoto en github y vicular con el repositorio local
**Instrucciones**
1. Crear una cuenta en GITHUB [GITHUB](https://github.com)
2. Crear un nuevo repositorio en GITHUB (sin inicializar el README ni archivos).
3. En la terminal, añade el respositorio remoto 
```
git remote add origin su_direccion_url_github
```
4. Verificar que se haya añadido correctamente
```bash
git remote -v
```
5. Sube el primer commit a GITHUB con
```bash
git push origin master
```

## 4. Crear y trabajar con ramas
**Objectivo**: Aprender a crear y trabajar con ramas
**Instrucciones**
1. Crear una nueva rama llamada `ramaDesarrollo`

```bash
git branch ramaDesarrollo
```
2. Cambiar a la `ramaDesarrollo` con:
```bash
git checkout ramaDesarrollo
```
3. Realizar cambios en sus archivos 
4. Añade y realizar un commit de los cambios
```bash
git add .
git commit -m "Cambios en la ramaDesarrollo"
```
4. Volver a la rama `master`
```bash
git checkout master
```
5. Sube el primer commit a GITHUB con
```bash
git push origin master
```