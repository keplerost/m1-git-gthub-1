# Comandos y configuración Git y Github
## Crear un nuevo repositorio
- Crear un repositorio en su cuenta de github
- Crear un archivo llamado (README.md) en su proyecto local
- Crear un archivo (.gitignore) en su proyecto local para ingnorar los archivos y carpetas que no queremos subir

## Inicializar un nuevo repositorio GIT
- Para inicializar un repositorio de manera local debemos ejecutar el siguiente comando.

```
git init
```
## Refrencia del repositorio local al repositorio remoto de (GITHUB)

```
git remote add origin https://github.com/keplerost/m1-git-gthub-1.git
```
- Para verificar ejecutar los siguientes comandos:
```
git remote
git remote -v
```
### Los siguientes comandos son ya para finalizar, son 3 comandos utilizados constantemente.
```
git add
git commit -m "descripcion de lo que hicieron"
Ojo: git push lo que hace es subir esos cambios realizados al github
git push origin master
```