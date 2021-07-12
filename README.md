# GRUPO F - Practica de red usando Mininet
En esta practica vamos a usar mininet junto con miniedit con el fin de desarrollar topologias.
***
## Requisitos:
[Mininet](https://github.com/mininet/mininet/wiki/Mininet-VM-Images)

[VM VirtualBOX](https://www.virtualbox.org/)

## Instalacion:
* Abriremos el archivo .ovf del cual virtualbox se encargara de su instalacion.
* Iniciaremos la maquina virtual e iniciaremos sesion con "mininet" tanto para el usuario como la contraseña.
* Instalaremos la interfaz grafica con el comando:
    > sudo apt-get update && sudo apt-get install xinit lxde virtualbox-guest-dkms
* La iniciaremos con el comando:
    > startx

## Creacion de red:
Nos moveremos hacia el fichero home/mininet/mininet/examples con el comando CD

Aqui aplicaremos el comando LS para ver los archivos
![a](https://user-images.githubusercontent.com/87292016/125231202-ebe0fc80-e29f-11eb-8400-ae22ccb751a4.png)

Seguido de esto aplicaremos el comando python miniedit.py para ejecutar el miniedit.
![b](https://user-images.githubusercontent.com/87292016/125231407-4b3f0c80-e2a0-11eb-98e6-175c9af2a6e6.png)

Dentro del Miniedit realizaremos la topologia, en nuestro caso decidimos usar una topologia aplicable a una oficina con una parte administrativa con servidoes y otra parte dedicada a la ofimatica.
![c](https://user-images.githubusercontent.com/87292016/125232419-319ec480-e2a2-11eb-855a-69be26a7b0bb.png)
