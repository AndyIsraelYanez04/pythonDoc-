# pythonDoc-

Instalacion de python pafra linux  link .

$ sudo add-apt-repository ppa:deadsnakes/ppa
$ sudo apt update
$ sudo apt install python3.11


Para ver una lista de todos los archivos binarios de Python instalados en su sistema, ejecute el siguiente comando ls.

$ ls -l /usr/bin/python*
lrwxrwxrwx 1 root root      10 Apr 22  2022 /usr/bin/python3 -> python3.10
-rwxr-xr-x 1 root root 5901416 Apr  2  2022 /usr/bin/python3.10
-rwxr-xr-x 1 root root 6705016 Oct 24 15:56 /usr/bin/python3.11
-rwxr-xr-x 1 root root     960 Dec 23  2020 /usr/bin/python3-futurize
-rwxr-xr-x 1 root root     964 Dec 23  2020 /usr/bin/python3-pasteuriz

Para usar Python 11, invoque el siguiente comando.

$ python3.11 
Python 3.11.0 (main, Oct 24 2022, 19:56:13) [GCC 11.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> print ("TecMint #1 Linux Blog");
TecMint #1 Linux Blog
>>> quit()

Para salir del intérprete de Python, escriba el siguiente comando y presione Entrar.

quit()
OR
exit()
Establecer la versión predeterminada de Python en Ubuntu
Si ha instalado varias versiones de Python en su sistema Ubuntu y desea configurar solo una versión como predeterminada, debe realizar algunos pasos adicionales como se muestra.

$ python3 --version
$ sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.10 1
$ sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.11 2
$ sudo update-alternatives --config python3
$ python3 --version


EN ALGUNOS DE LOS CASOS ES NECESARIO INTALAR PIP 

sudo apt install python3-pip



https://es.linux-console.net/?p=2171#gsc.tab=0
