# Primer README
Día 1 de inducción en Arventis</br></br>

Configurar localmente Git:</br>
git config --global user.name "Nombre"</br>
git config --global user.email "email@dominio.com"</br>
git config --list (Verificar configuración)</br>

Etapas de Git y Github:</br>
-Directorio de trabajo (Working Directory): Carpeta local del proyecto. Donde se realizan cambios en los archivos del proyecto.</br>
-Área de preparación (Staging Area): En este espacio se preparan los cambios de la etapa anterior para que sean parte del histprial de Git. Es decir se "marcan" los archivos. Una vez realizado esto estos archivos están listos para commit.</br>
  comando: git add "archivo"</br>
-Repositorio: Al hacer commit los archivos ya preparados se guardan de forma permanente en el repositorio local. En este lugar se conserva el historial de todas las versiones del proyecto.</br>
  comando: git commit -m "mensaje de commit"</br>
-Repositorio remoto: Después de hacer un commit local, se puede subir los cambios al repositorio remoto.</br>
  comando: git push origin main</br></br>
  
Trabajar con repositorios en Github:</br>
-Conectar repositorio local con Github: git remote add origin https://github.com/usuario/repositorio.git</br></br>

Obtener cambios de repositorio remoto y fusionarlos con local:</br>
-git pull origin main</br></br>

Trabajar con branches (ramas):</br>
Crear rama nueva: git checkout -b nombre-de-la-rama</br>
Cambiar entre ramas: git checkout nombre-de-la-rama</br>
Eliminar una rama: git branch -d nombre-de-la-rama</br></br>

Clonar repositorio y traerlo a local:</br>
git clone "repo https .git"</br></br>

Comandos de Git:</br>
-Ver estado del repositorio: git status</br>
-Ver historial de commits: git log</br>
-ver ramas existentes: git branch</br>
-Ver remotos configurados: git remote -v</br>
-Ver configuración de git: git config --list</br>

