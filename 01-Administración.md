<p align="left">
<img src="https://s28.postimg.org/ux8l1tv6l/imagengit.png">
</p>
### **0.1-Administración.md**

_Relativo al proceso de implementación del servicio de Administración de sitios_






| Versión |Cambios y/o evoluciones |Autor|Fecha|
|:------------- |:---------------|:---------------|:---------------|
| 10.0.004    | - CONFIGURACIÓN DE LA RED: escogemos la opción SUBDOMINIOS</br>- CONFIGURACIÓN DE LA RED: Título de la red: Concesionarios de LifeMyCar</br>- CONFIGURACIÓN DE LA RED: Correo: soporte@lifemycar.com</br>- Seguimos las instrucciones en pantalla para editar el archivo public_html/wp-config.php , añadiendo las líneas que nos dicen justo donde nos indican.</br>- Seguimos las instrucciones en pantalla para editar el archivo .htaccess , sustituyendo todo su contenido por las líneas que nos dicen.</br>NOTA: ¿Qué hemos ganado con estos cambios? Pues que en el Menú aparece MIS SITIOS.  |Hugo Miller|27/12/2016|
| 10.0.003    | IMPORTANTE: ahora es cuando hay que eliminar el usuario   |Hugo Miller|27/12/2016|
| 10.0.002    | Tenemos una instalación normal de WordPress => Hay que pasarla a Multisite. Para ellos trabajaremos con un software de gestión FTP (Coda, en nuestro caso):</br></br>- Borrar el archivo public_html/wp-config-sample.php</br>- Editar (y después salvar, para que se apliquen los cambios) el archivo public_html/wp-config.php , añadiendo la línea...</br>define ('WP_ALLOW_MULTISITE', true);</br>... justo antes de la línea (ya presente en el archivo)...</br>/* That's all, stop editing! Happy blogging. */</br>NOTA: ¿Qué hemos ganado al añadir esa instrucción? Pues si vamos al Menú HERRAMIENTAS, ahora aparece una opción que antes no estaba, CONFIGURACIÓN DE LA RED.  |Hugo Miller|27/12/2016|
| 10.0.001    | Nueva instalación de WordPress:</br></br>- <strong>NO Habilitar Multisite (WPMU)</strong></br>- El nombre del primer usuario no debe ser el de uno de los Administradores, ya que se va a acabar borrando en función de 6.0.067 |Hugo Miller|27/12/2016|
| 9.0.011    | Versión cancelada. |Hugo Miller|27/12/2016|
| 9.0.010    | Plugin: Instalación y activación para la red de Code Snippets 2.8.0. |Hugo Miller|27/12/2016|
| 9.0.009    | Plugin: Borrado de JetPack (por incompatibilidad con FacetWP). |Hugo Miller|26/12/2016|
| 9.0.008   | Plugin: Instalación y activación de Akismet 3.2. Introducción de API (en los 3 sitios)</br> |Hugo Miller|26/12/2016|
| 9.0.007   | Plugin: IgniteUp 3.2: Configuración CSS</br> |Hugo Miller|26/12/2016|
| 9.0.006    | Plugin: Instalación y activación de Plugins asociados al Theme Listable:</br></br>- Customify 1.3.1</br>- PixTypes 1.4.4</br>- WP Job Manager 1.25.2</br>- Category Icon 0.6.0</br>- Comments Ratings 1.1.5</br>- Login with Ajax 3.1.6</br>- Nav Menu Roles 1.8.6</br>- WooCommerce 2.6.10 |Hugo Miller|26/12/2016|
| 9.0.005   | Usuarios: Creación de los usuarios "Hugo", "José Manuel", "Soporte", todos ellos con perfiles de "SuperAdministradores". |Hugo Miller |26/12/2016|
| 9.0.004   | Sitios: Creación de los sitios (Child) "tartiere.lifemycar.com" y "pruebas.lifemycaer.com" además del sitio (Parent) "www.lifemycar.com". |Hugo Miller |26/12/2016| 
| 9.0.003   | cPanel: Desde cPanel creo el subdominio "pruebas.lifemycar.com". |Hugo Miller |26/12/2016|
| 9.0.002    | Tenemos una instalación normal de WordPress => Hay que pasarla a Multisite. Para ellos trabajaremos con un software de gestión FTP (Coda, en nuestro caso):</br></br>- Borrar el archivo public_html/wp-config-sample.php</br>- Editar (y después salvar, para que se apliquen los cambios) el archivo public_html/wp-config.php , añadiendo la línea...</br>define ('WP_ALLOW_MULTISITE', true);</br>... justo antes de la línea (ya presente en el archivo)...</br>/* That's all, stop editing! Happy blogging. */</br>NOTA: ¿Qué hemos ganado al añadir esa instrucción? Pues si vamos al Menú HERRAMIENTAS, ahora aparece una opción que antes no estaba, CONFIGURACIÓN DE LA RED.</br>- CONFIGURACIÓN DE LA RED: escogemos la opción SUBDOMINIOS</br>- CONFIGURACIÓN DE LA RED: Título de la red: Concesionarios de LifeMyCar</br>- CONFIGURACIÓN DE LA RED: Correo: soporte@lifemycar.com</br>- Seguimos las instrucciones en pantalla para editar el archivo public_html/wp-config.php , añadiendo las líneas que nos dicen justo donde nos indican.</br>- Seguimos las instrucciones en pantalla para editar el archivo .htaccess , sustituyendo todo su contenido por las líneas que nos dicen.</br>NOTA: ¿Qué hemos ganado con estos cambios? Pues que en el Menú aparece MIS SITIOS.  |Hugo Miller|26/12/2016|
| 9.0.001    | Nueva instalación de WordPress:</br></br>- <strong>NO Habilitar Multisite (WPMU)</strong></br>- El nombre del primer usuario no debe ser el de uno de los Administradores, ya que se va a acabar borrando en función de 6.0.067 |Hugo Miller|26/12/2016|
| 8.0.011   | Plugin: Enhanced Media Library 2.3.6 y "Activación para la Red". |Hugo Miller |23/12/2016|
| 8.0.010   | Plugin: Instalación de Akismet 3.2. y "Activación para la Red". |Hugo Miller |23/12/2016|
| 8.0.009    | Plugin: Instalación y activación de IgniteUp 3.2. |Hugo Miller |23/12/2016|
| 8.0.008    | Borrado de resto de temas: Twenty Fifteen, Twenty Seventeen, Twenty Sixteen. |Hugo Miller |23/12/2016|
| 8.0.007    | Theme: Instalación de Listable (Padre) e instalación y activación de Listable (Hijo/Child). Incluye "Activación para la red". |Hugo Miller |23/12/2016|
| 8.0.006    | Usuarios: Hugo y soporte ya son Súper Administradores, pero aún tienen que ser dados de alta como usuarios Administradores de www.lifemycar.com y www.tartiere.lifemycar.com. |José Manuel|23/12/2016|
| 8.0.005    | Usuarios + Seguridad: Borrado del primer usuario y se añaden a sopporte y hugo como Súper Administradores del MU. Se cumple con la condición de seguridad planteada en 6.0.067 y 8.0.001. |José Manuel|23/12/2016|
| 8.0.004    | Seguridad: edición el archivo .htaccess para evitar el acceso a la web desde Rusia, ya que parece que no es eficaz el bloqueo de todo un país desde Hide My WP/IDS Firewall/Blocked Coutries Code. Se siguen las indicaciones y datos obtenidos en las siguientes páginas:</br></br>- https://boluda.com/tutorial/bloquear-el-spam-en-tu-web/</br>- https://www.ip2location.com/blockvisitorsbycountry.aspx</br></br>- NOTA: En caso de preferir un Plugin para que haga esta tarea, el recomendado por las webs anteriores es IP2Location Country Blocker. |José Manuel|23/12/2016|
| 8.0.003    | Sitios: Añadir nuevo sitio:</br></br>- URL: tartiere.lifemycar.com (NOTA: Esta opción no estaría disponible sin los pasos anteriores)</br>- Título del sitio: Grupo Tartiere</br>- Correo electrónico: soporte@lifemycar.com |Hugo Miller|22/12/2016|
| 8.0.002    | Tenemos una instalación normal de WordPress => Hay que pasarla a Multisite. Para ellos trabajaremos con un software de gestión FTP (Coda, en nuestro caso):</br></br>- Borrar el archivo public_html/wp-config-sample.php</br>- Editar (y después salvar, para que se apliquen los cambios) el archivo public_html/wp-config.php , añadiendo la línea...</br>define ('WP_ALLOW_MULTISITE', true);</br>... justo antes de la línea (ya presente en el archivo)...</br>/* That's all, stop editing! Happy blogging. */</br>NOTA: ¿Qué hemos ganado al añadir esa instrucción? Pues si vamos al Menú HERRAMIENTAS, ahora aparece una opción que antes no estaba, CONFIGURACIÓN DE LA RED.</br>- CONFIGURACIÓN DE LA RED: escogemos la opción SUBDOMINIOS</br>- CONFIGURACIÓN DE LA RED: Título de la red: Concesionarios de LifeMyCar</br>- CONFIGURACIÓN DE LA RED: Correo: soporte@lifemycar.com</br>- Seguimos las instrucciones en pantalla para editar el archivo public_html/wp-config.php , añadiendo las líneas que nos dicen justo donde nos indican.</br>- Seguimos las instrucciones en pantalla para editar el archivo .htaccess , sustituyendo todo su contenido por las líneas que nos dicen.</br>NOTA: ¿Qué hemos ganado con estos cambios? Pues que en el Menú aparece MIS SITIOS.  |Hugo Miller|22/12/2016|
| 8.0.001    | Nueva instalación de WordPress:</br></br>- <strong>NO Habilitar Multisite (WPMU)</strong></br>- El nombre del primer usuario no debe ser el de uno de los Administradores, ya que se va a acabar borrando en función de 6.0.067 |Hugo Miller|22/12/2016|


_Bugs pendientes de resolver del Servicio de Administración_




| # | Descripción  |Autor|Fecha|
|:------------- |:------------- |:---------------|:---------------|
|001| Inicio (Sin Bugs)|Hugo Miller|23/12/2016|

