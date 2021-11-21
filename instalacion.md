# Instalación de un SO en una Raspberry PI
como seguramente haremos la instalación desde debian, explicare los pasos de instalación en linux.
Tal vez, mas adelante, explique los metodos de instalación desde windows y mac.
Importante tener una micro SD, pues se deberá instalar desde aquí.
## Instalación desde Linux
Primero de todo necesitaremos disponer de Flash para empezar con la instalación.
Ejecuta estos comandos:
1. Instalaremos las dependencias necesarias mediante los siguientes comandos en terminal:
- `sudo apt-get install -y pv curl python-pip unzip`
- `sudo pip install awscli`
2. A continuación, ejecutaremos el comando:
- `uname -s`
3. Y lo que nos devuelva, lo sustituiremos por Darwin en el primero de los siguientes comandos que debemos ejecutar:
- `wget https://raw.githubusercontent.com/hypriot/flash/master/Darwin/flash`
- `chmod +x flash`
- `sudo mv flash /usr/local/bin/flash`
Tras todo esto, solo falta tener un dispositivo de lectura de de micro ssd
