# PrimerRepositorio --- RAMA
Este es el primer repositorio que creo

Comandos GtHub
--------------
-------------
1. Instalar Git
    Los comandos se ingresan desde GitCMD para comandos Windows
                                   GitBash para comandos linux

2. Configuracion Git
    configurar el nombre de usuaroi y contraseña para la conexión del equipo

    git config --lobal user.name "UserName"
    git config --lobal user.email "Email"

3. Genera una clave publica  de conexion del pc con git

    ssh Publc key
    ssh-keygen

4. leer la clave para copiar a GitHub
    cat ~/.ssh/id_rsa.pub

5. Arrancar el proyecto con un repositorio local 

    git init

    5.1. Crear un archivo

      touch Nombre_Archivo

      add Nombre_Archivo    <-- Agrega el archivo al repositorio

      git commit -m "tu primer commit"

6. Agregar al repositorio Git

    git push origin master

7. Conectar a un repositorio Remoto

    git remote add <URL remote repositori>

// RAMAS

8. Crear una nueva rama 
    
    git branch Nombre_Rama

9. Posicionarse en una rama

    git checkout Nombre_Rama

//Este archivo se guarda estando en una de las ramas