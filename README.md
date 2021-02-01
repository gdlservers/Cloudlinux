cPanel CloudLinux Installer
Este script instala y configura CloudLinux con los parámetros recomendados por WNPower

Este script requiere que se ejecute dos veces:

La primera instala los paquetes básicos de CloudLinux y el kernel customizado de CloudLinux (al finalizar reinicia el servidor para aplicar los cambios)
Una vez reiniciado hay que ejecutarlo una segunda vez para que configure todos los servicios de CloudLinux
wget https://raw.githubusercontent.com/gdlservers/Cloudlinux/main/install_cloudlinux.sh && bash install_cloudlinux.sh

NOTA: Tené la licencia activa antes de iniciar el instalador: https://cln.cloudlinux.com/

Tareas que realiza
Instala CloudLinux sobre cPanel (en modo licenciamiento por Key o por IP, pregunta durante la instalación)
Instala y configura CageFS: https://docs.cloudlinux.com/index.html?cagefs.html
Configura Apache con mod_lsapi: https://docs.cloudlinux.com/index.html?apache_mod_lsapi.html
Configura todos los php.ini con los parámetros recomendados
Configura SecureLink: https://www.cloudlinux.com/getting-started-with-cloudlinux-os/41-security-features/933-activating-securelink
Instala y configura MySQL Governor: https://docs.cloudlinux.com/index.html?mysql_governor.html
Configura parámetros de CSF 
