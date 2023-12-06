HACK-7 (ELIMINAR UN ARCHIVO EN EL REPOSITORIO REMOTO)

1. Crear un nuevo repositorio en github nombre: git_h-1

2. Crear un repositorio local
git init

3. Registrar el repositorio remoto con tú repositorio local
git remote add origin (pegar_la_ruta_del_repositorio_local)

4. Verificamos la ruta remota
git remote -v

5. Creamos 3 archivos "foo.txt" "bar.txt" y "qux.txt" y hacemos push, (revisamos el repositorio remoto)

6. Ahora eliminamos a "foo.txt"
git rm --cached foo.txt

7. Verificamos el stage
git status

8. Hacemos un commit y al hacer push damos de baja el archivo "foo.txt" en el repositorio remoto
git commit -m "feat: remove foo.txt"
git push 
