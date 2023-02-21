# TutorialGIT

Para iniciar un repositorio, lo primero que debes hacer es crearlo en tu perfil de la siguiente manera:
1. Ingresa a tu perfil de GitHub y selecciona la opción Repositories
![Captura de Pantalla 2023-02-20 a la(s) 9 33 14 a  m](https://user-images.githubusercontent.com/125481093/220134827-135a8f5b-f28e-44db-81ae-6819fc4b3451.png)


2. Oprime el botón 'New'
![Captura de Pantalla 2023-02-20 a la(s) 9 37 21 a  m](https://user-images.githubusercontent.com/125481093/220135968-d8372f74-9de1-469b-a3d1-a65e86ff1efa.png)


3. Ponle un nombre a tu proyecto (preferiblemente sin espacios), selecciona si deseas que sea público o privado y la opción de 'Add a README file' (esto te permitirá editarlo más adelante)
![Captura de Pantalla 2023-02-20 a la(s) 9 42 22 a  m](https://user-images.githubusercontent.com/125481093/220136707-aaf0643b-e387-4979-8520-b7257271ae32.png)


4. Oprime el botón 'Create repository' y ¡listo!
![Captura de Pantalla 2023-02-20 a la(s) 9 43 53 a m](https://user-images.githubusercontent.com/125481093/220137474-6366b959-2a01-40a0-86f1-fe2c80d2a9ff.png)


Ahora, para subir un proyecto local a tu repositorio de GitHub ya creado, deberás seguir los siguientes pasos:

1. Abre la terminal de tu computador en la carpeta donde están los archivos de tu proyecto (HTML-CSS-img) y escribe el siguiente código para iniciar git en dicha carpeta:

'git init'
Eso permite



2. Debes subir los cambios a GitHub. Para ello tienes que saber la ruta del repositorio (acabada en .git) que está en Clone or Download, el botón verde de la página del proyecto. Luego añade el repositorio desde la terminal con este comando:

git remote add origin "URL repo"



3. git status



4. git fetch origin main



5. git pull origin main



6. git status



7. Se habrá creado la carpeta .git con la información del proyecto. Añade los ficheros para subir el mismo con este comando:

git add .



8. git status



9. Prepara los ficheros que quieres subir con una pequeña explicación acerca de los cambios:

git commit -m "Fist Commit"



10. Sube los cambios con el siguiente comando:

git push -u origin main
