# Border_Router_IoT
configurar router de borde en laboraratorio FIT/IOT-LAB usando nodo openmote-b

1. Para la configuracion de este laboratorio primero se tiene que crear una cuenta en FIT/IOT-LAB para poder crear el experimento.
2. configurar el acceso SSH con una maquina virtual en este caso con VirtualBox con un SO Kali-Linux

3.1. CREAR UN PAR DE CLAVES SSH
escriba el siguiente comando en una terminal:

# you@yourpc:~$ ssh-keygen -t rsa

you@yourpc:~$ ls ~/.ssh/

you@yourpc:~$ cat ~/.ssh/id_rsa.pub

ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDUFTThdYbsbrm1wjVlQ7rv+boH1wfWRLrNEOwAaWAiKbYBB9LPaHUhfyqZZ2jczCnb/UKHTkSFk4XNlYALzGwgQoP0j68OLQoXVBtRRxxP8D0kSP+lYfJTH3DccXjRKm6U6NDFjg6WkRKqKmMoIwjqkPpGnl/cDe7vJwCdH73ehisqLvM7JjD5+LPi+InO/AkFv+CKuJJ4gVg8Qs4HlCHZ/+bW0uJqiEZvAaE570f4DbPdK2YP6q5c+5a5RZBGJZxa/a9tPhuVoyy4Ew3t4TP5FAOwxtqcS1VvAtUSed2p6EX7I6/n8qQWfMnmoELIjSY5vMlUjpu4+spLfQhp1K4wuy57wcKbjP+wD6DbFEGMnilAL1nmgSRwbbXyHjbDnaXPXnYsQCFg0v+V2cCFI7ZXR3F9CwN7nx7xa2Vx6echoX4QcVfFXcYFfqv6dViOvhFl6oCtK/rf7Twvs1fm75GaHeA3V/06K8uxEstp+GmvYjGNawdsLshsW1+zfRku72c= root@edwin

3.2. la clave SSH es diferente para cada usuario debe copiar esa clave ir al usaurio en FIT/IOT-LAB y en la pestaña de SSH Keys, se pega la clave y en la pestaña de UPDATE SSH Keys
