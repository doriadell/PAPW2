Para crear un nuevo repositorio en Github:
Primero hay que crearse una cuenta , hacer un log in en el perfil y confirmar la cuenta de correo.
Luego, hay que ir al apartado de crear nuevo repositorio y darle click, escoger el nombre el cual se le va a tener a este repositorio y asegurarte de escoger que tipo de seguridad va a tener (si es SHL o HTTP, en caso de la clase va a ser HTTP), junto con una pequeña descripción.
Después de eso hay que escoger el tipo de visibilidad (privado o público, público para la clase).
Para finalizar se le da click en crear repositorio.

Para crear la rama local  en Git (en este caso desde CMD/bash)
Entras a la carpeta que contiene el repositorio y de ahí se le da el comando >>git checkout -nombreDeNuevaRama   [-m "descripción opcional"]<<
    Si la rama no existe se va a crear y se va mover a ella
    Si la rama ya existe se va a mover a esa rama

Para subir al archivo a un repositorio remoto
    Ya teniendo el repositorio local y el remoto, se va al repositorio local y se le da el commando >>git remote add origin direccion.repositorio.git <<.
    Teniendo ya el repositorio remoto configurado se va haciendo lo normal para incluir todos los archivos que se van a guardar
    Luego se hace el commit para guardar todo
    Para finalizar se usa el commando >>git push [nombreDeRepositorioRemoto] [nombrederama] << para subirlo