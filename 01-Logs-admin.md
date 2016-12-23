<p align="left">
<img src="https://s28.postimg.org/ux8l1tv6l/imagengit.png">
</p>
### **0.1-Logs-Admin.md**

_Relativo al proceso de implementación del servicio de Administración de sitios_






| Versión |Cambios y/o evoluciones |Autor|Fecha|
|:------------- |:---------------|:---------------|:---------------
| 8.0.007    | Theme: Instalación de Listable (Padre) e instalación y activación de Listable (Hijo/Child). |Hugo Miller. Incluye "Activación para la red"|23/12/2016|
| 8.0.006    | Usuarios: Hugo y soporte ya son Súper Administradores, pero aún tienen que ser dados de alta como usuarios Administradores de www.lifemycar.com y www.tartiere.lifemycar.com. |José Manuel|23/12/2016|
| 8.0.005    | Usuarios + Seguridad: Borrado del primer usuario y se añaden a sopporte y hugo como Súper Administradores del MU. Se cumple con la condición de seguridad planteada en 6.0.067 y 8.0.001. |José Manuel|23/12/2016|
| 8.0.004    | Seguridad: edición el archivo .htaccess para evitar el acceso a la web desde Rusia, ya que parece que no es eficaz el bloqueo de todo un país desde Hide My WP/IDS Firewall/Blocked Coutries Code. Se siguen las indicaciones y datos obtenidos en las siguientes páginas:</br></br>- https://boluda.com/tutorial/bloquear-el-spam-en-tu-web/</br>- https://www.ip2location.com/blockvisitorsbycountry.aspx</br></br>- NOTA: En caso de preferir un Plugin para que haga esta tarea, el recomendado por las webs anteriores es IP2Location Country Blocker. |José Manuel|23/12/2016|
| 8.0.003    | Sitios: Añadir nuevo sitio:</br></br>- URL: tartiere.lifemycar.com (NOTA: Esta opción no estaría disponible sin los pasos anteriores)</br>- Título del sitio: Grupo Tartiere</br>- Correo electrónico: soporte@lifemycar.com |Hugo Miller|22/12/2016|
| 8.0.002    | Tenemos una instalación normal de WordPress => Hay que pasarla a Multisite. Para ellos trabajaremos con un software de gestión FTP (Coda, en nuestro caso):</br></br>- Borrar el archivo public_html/wp-config-sample.php</br>- Editar (y después salvar, para que se apliquen los cambios) el archivo public_html/wp-config.php , añadiendo la línea...</br>define ('WP_ALLOW_MULTISITE', true);</br>... justo antes de la línea (ya presente en el archivo)...</br>/* That's all, stop editing! Happy blogging. */</br>NOTA: ¿Qué hemos ganado al añadir esa instrucción? Pues si vamos al Menú HERRAMIENTAS, ahora aparece una opción que antes no estaba, CONFIGURACIÓN DE LA RED.</br>- CONFIGURACIÓN DE LA RED: escogemos la opción SUBDOMINIOS</br>- CONFIGURACIÓN DE LA RED: Título de la red: Concesionarios de LifeMyCar</br>- CONFIGURACIÓN DE LA RED: Correo: soporte@lifemycar.com</br>- Seguimos las instrucciones en pantalla para editar el archivo public_html/wp-config.php , añadiendo las líneas que nos dicen justo donde nos indican.</br>- Seguimos las instrucciones en pantalla para editar el archivo .htaccess , sustituyendo todo su contenido por las líneas que nos dicen.</br>NOTA: ¿Qué hemos ganado con estos cambios? Pues que en el Menú aparece MIS SITIOS.  |Hugo Miller|22/12/2016|
| 8.0.001    | Nueva instalación de WordPress:</br></br>- <strong>NO Habilitar Multisite (WPMU)</strong></br>- El nombre del primer usuario no debe ser el de uno de los Administradores, ya que se va a acabar borrando en función de 6.0.067 |Hugo Miller|22/12/2016|
