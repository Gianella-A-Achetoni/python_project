 # Game project

_Para correr el juego se debe seguir las instrucciones_

_Para correr en terminal:_

```sh
cd game
python3 main.py
```

_Y a jugar_


# Entorno Virtual en Python

<br>Comenzamos con el entorno virtual en Python, para ingresar al repo después de un tiempo tuve que hacer lo siguiente, abri la terminal de Ubuntu desde window como administrador:</br>



# Archivo requirements.txt
 <br>Vamos a ver este archivo, este gestiona todas las dependencias y en que versiones se necesitan, vamos a dejar aquí los comandos para alguien logre contribuir en este proyecto, los comandos son los siguientes:</br>

 ```sh
    git clone https://...
    cd app
    python3 -m venv env #Se debe crear el entorno virtual, este no se comparte desde GitHub
    source env/bin/activate #Activamos el entorno en linux
    venv/Script/activate #Activa el entorno en window
    pip3 install -r requirements.txt #Instala las dependencias el -r significa reutilizar
    python3 main.py #Ejecutamos el programa
 ```