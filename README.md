<img src="html/img/icono.png" alt="Descripción de la imagen" width="80" > Servidor Local Ardilla

Desarrollo de un servidor local de uso hogareño, con ayuda de Apache servidor web HTTP de código abierto (https://httpd.apache.org/ ) y Home Assisten software gratuito y de código abierto que se utiliza para la automatización del hogar (https://www.home-assistant.io/).

Objetivos :
Facil ,amigable e intuitivo de usar para todos los integrantes de una familia.
Compatibilidad con cualquier marca de dispositivo de IoT.
Se espera que el proyecto finalmente se porte a una Raspberry Pi o dispositivo similar, y no dependa de un ordenador de uso frecuente.

Ingreso al sitio :

Usando un acortador web , los integrantes de la familia pueden ingresar con un hypervinculo a la direccion ip del servidor ,sin necesidad de tipiar la dirección en el navegador de forma manual.

Se opto por utilizar el acortador web Tinyurl: https://tinyurl.com/

Servidor Local : 

![imagen](https://github.com/user-attachments/assets/218859a9-a7e7-440c-8e0e-3143bd6ef88d)


Mediante Apache version Apache/2.4.61 (Debian) , se crea en la carpeta /var/www , un directorio donde se guarda el sitio web, con su pagina por defecto index.html , su carpeta de recursos (imagenes ,etc) y un archivo con el codigo de estilos CSS.

Home Assisten:

![imagen](https://github.com/user-attachments/assets/faf02e63-179a-44e1-abbf-aac32f59d27a)


Mediante este software se configuran los dispositivos IoT , de cualquier fabricante.



