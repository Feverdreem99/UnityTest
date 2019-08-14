# Guia de uso Unity-Github

Github es un repositorio de proyectos que sirve para el manejo sencillo de versiones, esto implica que el codigo fuente se almacena en el repositorio en linea y todos los contribuidores pueden tener la version mas reciente y hacer cambios propios a este proyecto.

# Git:
Para empezar, se debe descargar el software "Git" este instalara las instrucciones necesarias para manejar repositorios localmente y subir cambios al repo. La instalacion de Git puede ser estandar, seleccionando todas las opciones recomendadas. En pocas palabras solo presionando "siguiente" hasta que este instalado xd
Git: https://git-scm.com/downloads

# Github desktop:
Git se puede utilizar desde la ventana de comandos de windows, pero actualmente los add-ons nativos de github para unity tienen varios problemas que lo hace dificil de manejar, razon por la cual se utilizara el cliente de escritorio Github Desktop, con este programa se podran manejar todos los comandos de git y ver los cambios hechos al proyecto localmente asi como los cambios hechos al repo en linea.
GH Desktop: https://desktop.github.com/

# Configurar el repositorio local:
Una vez hechas las intalaciones previas se tendra que configurar el espacio donde ira el repositorio.

1)Al iniciar por primera vez Github desktop seleccionar la pestaña "File" y en "Options" loggearse con la cuenta asociada en Github en las pestañas de "Accounts" y "Git".

2)De las 3 opciones que aparecen se seleccionara la de clonar un repositorio.

3)En la pagina de este repositorio presionar el boton de "clone or download", copiar la url que aparece ahi y pegarla en github desktop.

4)Se asignara la direccion donde el proyecto se clonara y estara almacenado localmente.

5)Cuando vayamos a la direccion donde clonamos el repo se podra ver el nombre de la carpeta del proyecto de unity, esta carpeta sera el proyecto que se podra abrir y se trabajara con unity.

# Comandos de Github Desktop:
Hay 4 comandos importantes de github:

1) Commit
2) Pull
3) Push
4) Fetch

1)Commit: Cada vez que se haga un cambio en el proyecto, en Github Desktop apareceran los cambios que se han hecho de manera local en la pestaña de "changes" en la parte izquierda de la ventana, estos cambios se podran agregar a la version local del proyecto con el boton "commit". Esto significa que estamos diciendo a Github Desktop que estos cambios son lo que queremos hacer al repositorio en linea.
Para todo commit que se haga se debera agregar un titulo y una descripcion, es preferible que se listen todos los cambios importantes que se hicieron al proyecto para que sea mas facil manejar las versiones del repo en linea.

2)Pull: Este comando es el segundo mas importante, al utilizar git pull estamos diciendo a Github Desktop que descargue la version mas reciente que existe actualmente en el repositorio en linea, esto es importante porque pueden haber cambios en linea que hagan conflicto con nuestros cambios locales y al hacer pull podremos ver estos cambios y editarlos para que no haya errores al momento de subirlo. Para hacer Pull al proyecto del repo se dara clic a la pestaña repository en Github Desktop y clic en la opcion Pull.

3)Push: El comando mas importante de Git nos hace sobreescribir la version del repo en linea para sustituirla con una nueva version de nuestro proyecto local, al hacer push se subiran todos los cambios que hemos realizado. Luego de hacer commit aparecera un boton para hacer un push desde Github Desktop, lo presionaremos cuando estemos listos para subir la nueva version del proyecto al repo.

4)Fetch: Este comando unicamente es para verificar que existan cambios hechos en el repo en linea, es decir, para ver si alguien mas ha subido alguna version nueva antes que nosotros, se puede presionar antes de hacer pull para verificar los cambios pero no es tan importante.

# Cuidados importantes:

1) El orden en el que se deben utilizar estos comandos es: Fetch(Opcional), Commit, Pull y finalmente Push

2) Es importante que siempre hagamos pull antes de hacer push, asi existira siempre de manera local una copia de la version anterior a los cambios.



