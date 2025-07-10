# Primer README
Día 1 de inducción en Arventis

Configurar localmente Git:
git config --global user.name "Nombre"
git config --global user.email "email@dominio.com"
git config --list (Verificar configuración)

Etapas de Git y Github:
Directorio de trabajo (Working Directory): Carpeta local del proyecto. Donde se realizan cambios en los archivos del proyecto.
Área de preparación (Staging Area): En este espacio se preparan los cambios de la etapa anterior para que sean parte del histprial de Git. Es decir se "marcan" los archivos. Una vez realizado esto estos archivos están listos para commit.
  comando: git add "archivo"
Repositorio: Al hacer commit los archivos ya preparados se guardan de forma permanente en el repositorio local. En este lugar se conserva el historial de todas las versiones del proyecto.
  comando: git commit -m "mensaje de commit"
Repositorio remoto: Después de hacer un commit local, se puede subir los cambios al repositorio remoto.
  comando: git push origin main


  
Comandos útiles de Git:

