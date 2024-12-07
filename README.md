# Configuración de un servidor web Apache en Ubuntu

Este repositorio contiene los archivos relacionados con el ejercicio de configuración de un servidor web Apache en Ubuntu. El ejercicio cubre la instalación de Apache, la configuración para que escuche en múltiples puertos, la creación de sitios web en diferentes directorios y la configuración de un servidor con dos tarjetas de red.

## Descripción del ejercicio

### 1. **Instalación y configuración de Apache**
- Instalación del servidor Apache en Ubuntu y comprobación de las carpetas de configuración (`/etc/apache2`) y directorios web (`/var/www`).
- Arranque del servicio y comprobación del funcionamiento a través de la dirección `http://<IP_del_servidor>`.

### 2. **Servidor con múltiples puertos**
- Configuración de Apache para que escuche en los puertos **3000** y **5000**.
- Creación de archivos de configuración para cada web en `/etc/apache2/sites-available`.
- Activación de los sitios con el comando `a2ensite`.

### 3. **Servidor con dos tarjetas de red**
- Adición de una nueva tarjeta de red a la máquina virtual.
- Configuración de IP estática y uso de `VirtualHost` para asignar una página web diferente a cada tarjeta de red.

## Capturas de pantalla
Puedes ver las capturas de pantalla y explicaciones detalladas del ejercicio en el siguiente archivo PDF adjuntado

## Autor
- **Cecilia Molina**
