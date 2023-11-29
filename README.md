### COMANDOS ÚTILES DE GIT

1. **`git init`**: Inicializa un nuevo repositorio Git en el directorio actual.

2. **`git add .`**: Agrega todos los cambios en el directorio de trabajo al área de preparación (staging area) para el próximo commit.

3. **`git reset .`**: Deshace los cambios en el área de preparación, dejando los archivos sin cambios.

4. **`git commit -m "mensaje"`**: Guarda los cambios en el repositorio con un mensaje descriptivo.

5. **`git checkout -- .`**: Descarta los cambios locales y restaura los archivos al último commit.

6. **`git log`**: Muestra el historial de commits.

7. **`git checkout -b nombre-de-la-rama`**: Crea y cambia a una nueva rama con el nombre especificado.

8. **`git checkout nombre-de-la-rama`**: Cambia a la rama especificada. Dicho de otra manera, permite cambiar a la rama especificada, brindando la flexibilidad de moverse entre ramas según sea necesario.

9. **`git merge nombre-de-la-rama`**: Fusiona los cambios de una rama con la rama actual.

10. **`git branch -d nombre-de-la-rama`**: Elimina la rama especificada.

11. **`git push`**: Sube los cambios locales al repositorio remoto.

12. **`git commit -am "mensaje"`**: Agrega y guarda automáticamente los cambios en los archivos seguidos de un commit con un mensaje.

13. **`git branch -m nuevo-nombre`**: Cambia el nombre de la rama actual.

DATOS ADICIONALES (…or create a new repository on the command line)

echo "# mp" >> README.md
  git init
  git add README.md
  git commit -m "first commit"
  git branch -M main
  git remote add origin https://github.com/Bjorkey/mp.git
  git push -u origin main


  …or push an existing repository from the command line
  
git remote add origin https://github.com/Bjorkey/mp.git
  git branch -M main
  git push -u origin main

Estos comandos son herramientas esenciales para trabajar con Git y te permitirán gestionar y colaborar eficientemente en proyectos de desarrollo de software.
