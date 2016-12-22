<p align="left">
<img src="https://s28.postimg.org/ux8l1tv6l/imagengit.png">
</p>
### **Log LifeMyCar - Control de Cambios**

_Relativo al proceso de Desarrollo de LifeMyCar.com y su control de versiones_






| Versión |Cambios y/o evoluciones |Autor|Fecha|
|:------------- |:---------------|:---------------|:---------------
| 8.0.001    | Nueva instalación de WordPress:</br></br>- <strong>NO Habilitar Multisite (WPMU)</strong></br>- El nombre del primer usuario no debe ser el de uno de los Administradores, ya que se va a acabar borrando en función de 6.0.067 |Hugo Miller|22/12/2016|
| 7.0.003    | Versión cancelada: Al instalar con la opción "Habilitar Multisite (WPMU)" marcada, no nos deja Añadir Nuevos Sitios según el patrón nombredelsitio.lifemycar.com, si no que el patrón que nos imponene es lifemycar.com/nombredelsitio , y ese patrón no nos interesa para nustro propósito. |Hugo Miller|22/12/2016|
| 7.0.002    | Seguridad: edición el archivo .htaccess para evitar el acceso a la web desde Rusia, ya que parece que no es eficaz el bloqueo de todo un país desde Hide My WP/IDS Firewall/Blocked Coutries Code. Se siguen las indicaciones y datos obtenidos en las siguientes páginas:</br></br>- https://boluda.com/tutorial/bloquear-el-spam-en-tu-web/</br>- https://www.ip2location.com/blockvisitorsbycountry.aspx</br></br>- NOTA: En caso de preferir un Plugin para que haga esta tarea, el recomendado por las webs anteriores es IP2Location Country Blocker. |José Manuel|22/12/2016|
| 7.0.001    | Nueva instalación de WordPress:</br></br>- Habilitar Multisite (WPMU)</br>- El nombre del primer usuario no debe ser el de uno de los Administradores, ya que se va a acabar borrando en función de 6.0.067 |Hugo Miller|22/12/2016|
| 6.0.136    | Versión cancelada: Necesitamos trabajar con la opción de Multisite (WPMU), para que así podamos gestionar varios concesionarios desde un único sitio. |Hugo Miller|22/12/2016|
| 6.0.135    | Plugin: Actualización de WooCommerce 2.6.10. |José Manuel|22/12/2016|
| 6.0.134    | Listings: Listing campos: Primera versión de los campos que incluirá el formulario de "Anuncia tu coche". Las capturas de pantalla y textos están en /Google Drive/01-TRABAJOS/2-APPs_Services/2.02-LifeMyCar/11-BackUps/Manuales/Versión 0.6/Capturas/Listings/. |José Manuel|22/12/2016|
| 6.0.133    | Plugin: Actualización de Above The Fold Optimization a la versión 2.7.1. |José Manuel|22/12/2016|
| 6.0.132    | Problema detectado: Cualquier configuración de Hide My WP estropea el CSS de las páginas de anuncios (listings; páginas con las que no se había trabajado hasta ahora). Es más, alguna de las configuraciones estropea incluso el HOME (no se había descubierto hasta ahora porque esas configuraciones no habían sido las escogidas en la configuración inicial de 6.0.079 y por ello el HOME se veía bien; pero es muy probable que las páginas de anuncios siempre hayan estado estropeadas). Se ha consultado a su creador oficial para obtener una solución.</br></br>- http://support.wpwave.com/forums/topic/problem-with-css#post-13678 |José Manuel|21/12/2016|
| 6.0.131    | Apariencia: CSS retocado para distribuir elementos del "menú legal". |Hugo Miller|20/12/2016|
| 6.0.130    | Listings: Campos de la empresa: Tal y como viene la configuración por defecto, estos campos (orientados al mundo de las empresas que publican anuncios) aparecerían en el formulario de "Añadir coche". Como no nos interesan, los vamos a ocultar a los usuarios normales. Para ello, se editan todos los "campos de la empresa", forzando que su Visibilidad esté marcada para el modo Admin Only. Además, se cambian sus prioridades a las siguientes:</br></br>- company_tagline => 98.1</br>- company_logo => 98.2</br>- main_image => 98.3</br>- company_phone => 98.4</br>- company_website => 98.5</br>- company_twitter => 98.6</br>- products => 98.7</br></br>IMPORTANTE: Como no son necesarios, es tentador borrarlos. No hacerlo en NINGÚN CASO, ya que pueden producirse errores de funcionamiento en el Formulario. |José Manuel|20/12/2016|
| 6.0.129    | Error detectado y solucionado: el cambio realizado en 6.0.076 no estaba activo. Se activa de nuevo. |José Manuel|20/12/2016|
| 6.0.128    | Problema solucionado (ver 6.0.121): Los consejos del servicio de soporte de Hide My WP no han sido efectivos. Finalmente se ha resuelto modificando el archivo .htaccess, eliminando las líneas añadidas en 6.0.068. De este modo, .htaccess solamente tiene las modificaciones hechas por Hide My WP más las añadidas en 6.0.114. |José Manuel|20/12/2016|
| 6.0.127    | Apariencia: CSS retocado para colores de azul el icono de notificaciones (contenedor de campana) de la página principal. |Hugo Miller|19/12/2016|
| 6.0.126    | Apariencia: CSS retocado para colores de azul los iconos del menú social al pasar el ratón sobre ellos Queda pendiente ver el tipo de azul. |Hugo Miller|19/12/2016|
| 6.0.125    | Apariencia: CSS retocado para acercar menú legal a Footer. Quizs haya que retocar las distancias posteriormente cuando ya estén los menús hechos. |Hugo Miller|19/12/2016|
| 6.0.124    | Apariencia: CSS retocado para que las Marcas (iconos) del Widget "marcas" del HomePage sea azules al pasar el ratón sobre ellas.|Hugo Miller|19/12/2016|
| 6.0.123    | Apariencia: CSS retocado para que las Categorías (iconos) del HomePage sea azules al pasar el ratón sobre ellas.|Hugo Miller|19/12/2016|
| 6.0.122    | Páginas: Creación de Páginas: "Aviso Legal", "Sobre Nosotros", "Regulación". Siguiendo patrón de Social Car. Posteriormente se asignan dichas páginas al "Menú legal"|Hugo Miller|19/12/2016|
| 6.0.121    | Problema detectado: Un usuario del frontend no puede subir fotografías a su perfil. El perfil de los usuarios lo gestiona Ultimate Member, que sabemos hacía perfectamente esta tarea en versiones anteriores del website. Todo indica que el problema debe causarlo el plugin Hide My WP. Se ha consultado a su creador oficial para obtener una solución.</br></br>- http://support.wpwave.com/forums/topic/unable-to-upload-images-from-the-frontend#post-13601 |Hugo Miller / José Manuel|19/12/2016|
| 6.0.120    | Plugin: Hide My WP: Actualización oficial a las versiones oficiales Hide My WP 5.5 y 5.5.1.|José Manuel|18/12/2016|
| 6.0.119    | Plugin: Hide My WP 5.1.2: Desinstalación de la versión torrent, compra de la versión oficial, instalación, activación y configuración básica:</br>- IDS Firewall: Blocked Countries Code: Rusia (RU; hijos de Putin), Indonesia (ID) y Ucrania (UA).|José Manuel|18/12/2016|
| 6.0.118    | Iconos: Asociar iconos mediante opción "select icon" en "Menú legal".|Hugo Miller|18/12/2016|
| 6.0.117    | Menú: Creación de "Menú legal" y ubicación provisional en el Area Footer mediante el widget "Menu personalizado".|Hugo Miller|18/12/2016|
| 6.0.116    | Páginas: Creación de páginas de "Contacto" y "Política de privacidad".|Hugo Miller|18/12/2016|
| 6.0.115    | Google API KEY: Generada en el entorno de Google Developers de tuttopiasoftware@gmail.com. Almacenada en Google Drive.|Hugo Miller|18/12/2016|
| 6.0.114    | Seguridad: edición el archivo .htaccess para evitar el acceso a la web desde Rusia, ya que parece que no es eficaz el bloqueo de todo un país desde Hide My WP/IDS Firewall/Blocked Coutries Code. Se siguen las indicaciones y datos obtenidos en las siguientes páginas:</br></br>- https://boluda.com/tutorial/bloquear-el-spam-en-tu-web/</br>- https://www.ip2location.com/blockvisitorsbycountry.aspx</br></br>- NOTA: En caso de preferir un Plugin para que haga esta tarea, el recomendado por las webs anteriores es IP2Location Country Blocker.|José Manuel|18/12/2016|
| 6.0.113    | Apariencia: Página de "Ayuda". Personalización de imagen de fondo y textos.|Hugo Miller|17/12/2016|
| 6.0.112    | Apariencia: Página de "Anuncia tu coche". Personalización de imagen de fondo y textos.|Hugo Miller|17/12/2016|
| 6.0.111    | Listings: Equipamiento: Añadir 17: Aire acondicionado, Bluetooth, Cámara Visión Trasera (RVC), Control Distancia Aparcamiento, Control Velocidad, Detector Fatiga, Entrada audio/iPod, Entrada microUSB, GPS Integrado, Lector Tarjetas SD, Manejo por Voz, Manos Libres, Neunmáticos Invierno, Portaequipajes, Reproductor CD, Reproductor DVD y Start and Stop.|José Manuel|17/12/2016|
| 6.0.110    | Category Icon: equipamiento (marcar).|José Manuel|17/12/2016|
| 6.0.109    | Plugin: CPT UI (Custom Post Type UI): Add/Edit Taxonomies: Añadir "Equipamiento" (vinculada en principio sólo a Listings -se puede vincular también a Productos-).|José Manuel|17/12/2016|
| 6.0.108    | Apariencia: Fotos Provisiones en 3 Productos (Anuncios). Provisionales, sólo válidas para analizar el estado preliminar del servicio"|Hugo Miller|17/12/2016|
| 6.0.107    | Apariencia: Fotos Provisiones en Widgets del FrontPage. Tanto de las entradas del Blog como de la sección "¿Cómo funciona?"|Hugo Miller|17/12/2016|
| 6.0.106    | Apariencia: Botón de "Anuncia tu coche" non aspecto de botón. Instalar Class CSS en menú y escribir "cta" (en minúsculas). |Hugo Miller|17/12/2016|
| 6.0.105    | Redes sociales: Configuración mediante un widget (custom menu) al que se le asigna el "Menú Redes Sociales" en la sección "Footer Area". |Hugo Miller|17/12/2016|
| 6.0.104    | Menús: Configuración de Menús, lugares y condiciones. Según capturas de pantalla de Drive. |Hugo Miller|17/12/2016|
| 6.0.103    | Páginas: Configuración de Páginas "Perfil" y "Configuración" como FullWith (no title). |Hugo Miller|17/12/2016|
| 6.0.102    | Menús: Iconos en menú principal (Mediante Plugin). El plugin requerido previamente se llama "Menú Icon". |Hugo Miller|17/12/2016|
| 6.0.101    | Apariencia: Identidad del sitio. Logos y FavIcon en Listable Child. |Hugo Miller|17/12/2016|
| 6.0.100    | Plugin: Ultimate Member: Ajustes Básicos. Según capturas de pantalla guardadas en Drive.|Hugo Miller|17/12/2016|
| 6.0.099    | Plugin: Hide My WP 5.1.2: IDS Firewall: Blocked Countries Code: Rusia (RU; hijos de Putin) e Indonesia (ID).|José Manuel|16/12/2016|
| 6.0.098    | Plugin: Instalación y activación de Above The Fold Optimization 2.6.17. Sirve para tratar de alcanzar una puntuación de 100 en Google PageSpeed.|José Manuel|16/12/2016|
| 6.0.097    | Plugin: UpdraftPlus Backup/Restore 1.12.29:</br></br>- Programación de Copias de seguridad: 1 copia diaria, guardando las últimas 8 unidades</br>- Programación de Copias de seguridad de la Base de Datos: 2 copias diarias, guardando las últimas 16 unidades</br>- Selección de un almacenamiento externo => Google Drive/UpdraftPlus (no se puede cambiar el nombre de esta carpeta o su ruta sin contar con el servicio Premium) (seguir esta página de Ayuda: https://updraftplus.com/support/configuring-google-drive-api-access-in-updraftplus/ ) => Se han generado estos datos:</br>+ Cliente de OAuth</br>+ ID cliente: 1095009698030-0kkj11gnus1b3kde7r7jg4fn9vb787fu.apps.googleusercontent.com</br>+ Secreto de cliente: PMgl1ZtpNDHI0ACBwMPNuR4S|José Manuel|16/12/2016|
| 6.0.096    | Apariencia: Ajustes de color en secciones: "Cards", "Footer", "Main Content", "Other Colors", "PreFooter", "Site Header".|Hugo Miller|16/12/2016|
| 6.0.095    | Listings: Extras: Añadir 6: "Asiento infantil", "Cables Batería", "Cadenas Nieve","Kit Antipinchazo", "Portabicicletas" y "Portaesquís".|José Manuel|16/12/2016|
| 6.0.094    | Category Icon: extras (marcar).|José Manuel|16/12/2016|
| 6.0.093    | Plugin: CPT UI (Custom Post Type UI): Add/Edit Taxonomies: Añadir "Extras" (vinculada en principio sólo a Listings -se puede vincular también a Productos-).|José Manuel|16/12/2016|
| 6.0.092    | Listings: Condiciones de uso: Añadir 2: "Mascotas permitidas" y "Permite fumar".|José Manuel|16/12/2016|
| 6.0.091    | Category Icon: condiciones_uso (marcar).|José Manuel|16/12/2016|
| 6.0.090    | Plugin: CPT UI (Custom Post Type UI): Add/Edit Taxonomies: Añadir "Condiciones de uso" (vinculada en principio sólo a Listings -se puede vincular también a Productos-).|José Manuel|16/12/2016|
| 6.0.089   | Footer: Eliminación de textos comerciales de Listable en el footer. Para ello, se eliminan lineas de código de footer.php y se sube el nuevo archivo (modificado) a la misma ruta en el que se encontraba el footer original, pero ahora dentro de la carpeta correspondiente al tema "listable-child".|Hugo Miller|16/12/2016|
| 6.0.088   | Tema: Activación de Child y Redefinición de CSS.|Hugo Miller|16/12/2016|
| 6.0.087   | Apariencia: Subtexto Página Principal (Bajo el Título).|Hugo Miller|16/12/2016|
| 6.0.086   | Widgets: Personalización de textos principales y secundarios.|Hugo Miller|16/12/2016|
| 6.0.085    | FacetWP: Instalación preliminar en el Home para maquetación. Pendiente: Definir los "facets de búsqueda" más adecuados. |Hugo Miller|16/12/2016|
| 6.0.084    | Página Principal: Definición de categorías. (NOTA: Hay 9 creadas pero creo que en versiones anteriores eran 10). |Hugo Miller|16/12/2016|
| 6.0.083    | Widgets: Regiones (Usados para categorias). Asignación de fotos/fondos a las categorías.</br> |Hugo Miller|15/12/2016|
| 6.0.082    | Apariencia: Logotipos (Normal e Inverso)</br> |Hugo Miller|15/12/2016|
| 6.0.081    | Plugin: Instalación, activación y configuración bsica de UpdraftPlus Backup/Restore 1.12.29. |José Manuel|14/12/2016|
| 6.0.080   | Plugin: IgniteUp 3.2: Configuración CSS</br> |Hugo Miller|13/12/2016|
| 6.0.079    | Plugin: Configuración básica de Hide My WP 5.1.2</br></br>- Start: Import Options: -Select Sheme-: Medium Privacy - More Compatibility (Recommended)</br>- General Settings: Hide Login Page: Hide wp-login.php (marcar)</br>- General Settings: Login Query: pase_usted</br>- General Settings: Admin Login Key: 3791 [ NOTA: Current Login URL: /wp-login.php?pase_usted=3791 ]</br>- General Settings: Hide Admin: (marcar)</br>- General Settings: Spy Notify: (marcar)</br>- General Settings: Email sender name: HideMyWP</br>|Hugo Miller / José Manuel|13/12/2016|
| 6.0.078    | Listings: Types: Introducción de los modelos (180) de coches, clasificados por marcas (5):</br></br>- Audi: 59 modelos repartidos en 13 familias</br>- Opel: 31 modelos repartidos en 13 familias</br>- Seat: 16 modelos repartidos en 6 familias</br>- Škoda: 34 modelos repartidos en 11 familias</br>- Volkswagen: 40 modelos repartidos en 19 familias</br>|José Manuel|13/12/2016|
| 6.0.077    | Listings: Regions:</br>- Introducción de las 5 marcas (Regions, en el caso de este theme) con las que se trabajará: Volswagen, Audi, Seat, Škoda y Opel|José Manuel|13/12/2016|
| 6.0.076    | Listings: Configuración del Editor de campo: FacetWP:</br>- Indexación de direcciones: Sí (marcar)|José Manuel|13/12/2016|
| 6.0.075    | Listings: Configuración del Editor de campo: Listing:</br></br>- Etiqueta personalizada requiere: Permiten (marcar)</br>- Etiqueta personalizada opcional: Permiten (marcar)</br>- Botón de envío personalizado: Permiten (marcar)</br>- Título del botón enviar: Previsualizar anuncio |José Manuel|13/12/2016|
| 6.0.074    | Listings: Categories: Borrado en lote de todas las categorías instaladas por defecto + Introducción de las 9 categorías con las que se trabajará: 4x4, Berlina, Clásico, Deportivo, Descapotable, Familiar, Furgoneta, Minibús y Pequeño. |José Manuel|13/12/2016|
| 6.0.073    | Plugin: Configuración básica de Category Icon 0.6.0:</br>- Select Taxonomies: product_tag (marcar) |José Manuel|13/12/2016|
| 6.0.072    | Plugin: Configuración básica de IgniteUp 3.2. |José Manuel|12/12/2016|
| 6.0.071    | Plugin: Configuración básica de WPML Multilingual CMS 3.5.3.1. |José Manuel|12/12/2016|
| 6.0.070    | Ajustes: Enlaces permanentes:</br>- Ajustes comunes: Nombre de la entrada (marcar) |José Manuel|12/12/2016|
| 6.0.069    | Ajustes: Generales:</br></br>- Título del sitio: LifeMyCar</br>- Descripción corta: LifeMyCar es una plataforma de CarSharing para vehículos de las marcas Volkswagen, Audi, Seat, Škoda y Opel.</br>- Dirección de WordPress (URL): https://www.lifemycar.com</br>- Dirección del sitio (URL): https://www.lifemycar.com</br>- Dirección de correo electrónico: soporte@lifemycar.com</br>- Miembros: (marcado)</br>- Zona horaria: UTC + 1</br>- Formato de fecha: (4ª opción)</br>- Formato de hora: (3ª opción)</br>- La semana comienza: Lunes</br>- Idioma del sitio: Español |José Manuel|12/12/2016|
| 6.0.068    | Seguridad: Modificación manual del archivo public_html/.htaccess, según las instrucciones de Google Drive/.../12-Seguridad/.htaacess/Seguridad - Códigos para los .htacces/htaccess-de-root.txt.</br></br>NOTA: Se ha mutado la instrucción referida a los bloqueos de direcciones IP, ya que en este proyecto se puede llegar a trabajar desde más de 2 IPs simultáneamente.|José Manuel|10/12/2016|
| 6.0.067    | Seguridad: Cambio del ID de usuario de hugo desde ID=1 a ID=5. |José Manuel|10/12/2016|
| 6.0.066    | Plugin: Actualización de Facet WP 2.6.5. |José Manuel|10/12/2016|
| 6.0.065    | Plugin: Actualización de Ultimate Member - Real-time Notifications 1.4.1. |José Manuel|10/12/2016|
| 6.0.064    | Plugin: Actualización de WooCommerce 2.6.9. |José Manuel|10/12/2016|
| 6.0.063    | Plugin: Actualización de Ultimate Member 1.3.78. |José Manuel|10/12/2016|
| 6.0.062    | Plugin: Actualización de Nav Menu Roles 1.8.6. |José Manuel|10/12/2016|
| 6.0.061    | Plugin: Actualización de Menu Icons (Iconos de Menú) 0.10.2. |José Manuel|10/12/2016|
| 6.0.060    | Media: Upload Vídeos de Fondo de la Página Principal. |Hugo Miller|7/12/2016|
| 6.0.059    | Media: Upload Imágenes de Fondo de la Página Principal. |Hugo Miller|7/12/2016|
| 6.0.058    | Media: Upload Fondos de las Categorías. |Hugo Miller|7/12/2016|
| 6.0.057    | Media: Upload iconos de las Tags. |Hugo Miller|7/12/2016|
| 6.0.056    | Media: Upload iconos de las Marcas. |Hugo Miller|7/12/2016|
| 6.0.055    | Media: Upload iconos de las Categorías. |Hugo Miller|7/12/2016|
| 6.0.054    | Apariencia: Mapas: Introducción del FREE Token en el Mapbox. |Hugo Miller|7/12/2016|
| 6.0.053    | Apariencia: Cambio texto Footer. |Hugo Miller|7/12/2016|
| 6.0.052    | CSS: Página Principal: Cambio de color en "chosen-drop". |Hugo Miller|7/12/2016|
| 6.0.051    | CSS: Página Principal: Cambio de color en "Sube foto". |Hugo Miller|7/12/2016|
| 6.0.050    | CSS: Página Principal: Cambio del color en las Text Areas. |Hugo Miller|7/12/2016|
| 6.0.049    | CSS: Página Principal: Reducción de la distancia entre las Categorías y el límite de la foto del Front. |Hugo Miller|7/12/2016|
| 6.0.048    | CSS: Página Principal: Reducción del espacio en blanco entre los Widgets. |Hugo Miller|7/12/2016|
| 6.0.047    | CSS: Página Principal: Cambio del tamaño de los iconos de las categorías. |Hugo Miller|7/12/2016|
| 6.0.046    | CSS: Página Principal: Subir la posición del Título. |Hugo Miller|7/12/2016|
| 6.0.045    | CSS: Página Principal: Activar los títulos en negrita. |Hugo Miller|7/12/2016|
| 6.0.044    | CSS: Página Principal: Quitar el texto "Navega por aquí también". |Hugo Miller|7/12/2016|
| 6.0.043    | Media: Upload imágenes Página Principal. |Hugo Miller|7/12/2016|
| 6.0.042    | Plugin: Instalación y activación de Hide My WP 5.1.2. |Hugo Miller|7/12/2016|
| 6.0.041    | Plugin: Instalación y activación de WooThemes Updater. |Hugo Miller|7/12/2016|
| 6.0.040    | Plugin: Instalación y activación de WPML String Translation 2.4.2.1. |Hugo Miller|7/12/2016|
| 6.0.039    | Plugin: Instalación y activación de WPML Multilingual CMS 3.5.3.1. |Hugo Miller|7/12/2016|
| 6.0.038    | Plugin: Instalación y activación de WP Super Cache 1.4.8. |Hugo Miller|7/12/2016|
| 6.0.037    | Plugin: Instalación y activación de WP Job Manager - Products 1.4.0. |Hugo Miller|7/12/2016|
| 6.0.036    | Plugin: Instalación y activación de WP Job Manager - Predefined Regions (WP Job Manager - Locations) 1.11.0. |Hugo Miller|7/12/2016|
| 6.0.035    | Plugin: Instalación y activación de WP Job Manager - Job Tags 1.3.8. |Hugo Miller|7/12/2016|
| 6.0.034    | Plugin: Instalación y activación de WP Job Manager - Bookmarks 1.2.1. |Hugo Miller|7/12/2016|
| 6.0.033    | Plugin: Instalación y activación de WooCommerce Bookings 1.9.13. (el Plugin WooCommerce Helper 1.7.2 se instala solo)|Hugo Miller|7/12/2016|
| 6.0.032    | Plugin: Instalación y activación de Ultimate Member Job Manager 1.0.0. |Hugo Miller|7/12/2016|
| 6.0.031    | Plugin: Instalación y activación de Ultimate Member - WooCommerce 1.0.10. |Hugo Miller|7/12/2016|
| 6.0.030    | Plugin: Instalación y activación de Ultimate Member - Verified Users 1.0.3. |Hugo Miller|7/12/2016|
| 6.0.029    | Plugin: Instalación y activación de Ultimate Member - User Reviews 1.1.6. |Hugo Miller|7/12/2016|
| 6.0.028    | Plugin: Instalación y activación de Ultimate Member - Real-time Notifications 1.3.4. |Hugo Miller|7/12/2016|
| 6.0.027    | Plugin: Instalación y activación de Ultimate Member - Profile Tabs 1.2.7. |Hugo Miller|7/12/2016|
| 6.0.026    | Plugin: Instalación y activación de Ultimate Member - Profile Completeness 1.2.0. |Hugo Miller|7/12/2016|
| 6.0.025    | Plugin: Instalación y activación de Ultimate Member - Private Messages 1.1.0. |Hugo Miller|7/12/2016|
| 6.0.024    | Plugin: Instalación y activación de Ultimate Member 1.3.77. |Hugo Miller|7/12/2016|
| 6.0.023    | Plugin: Instalación y activación de Private Suite 2.1. |Hugo Miller|7/12/2016|
| 6.0.022    | Plugin: Instalación y activación de Menu Icons (Iconos de Menú) 0.10.1. |Hugo Miller|7/12/2016|
| 6.0.021    | Plugin: Instalación y activación de IgniteUp 3.2. |Hugo Miller|7/12/2016|
| 6.0.020    | Plugin: Actualización de WP Job Manager Field Editor (Editor de WP trabajo administrador campo) 1.6.4. |José Manuel|7/12/2016|
| 6.0.019    | Plugin: Instalación y activación de Facet WP - Cache 1.3.2. |Hugo Miller|7/12/2016|
| 6.0.018    | Plugin: Instalación y activación de Facet WP 2.4.5. |Hugo Miller|7/12/2016|
| 6.0.017    | Plugin: Instalación y activación de WP Job Manager Field Editor (Editor de WP trabajo administrador campo) 1.6.3. |José Manuel|7/12/2016|
| 6.0.016    | Plugin: Instalación y activación de Custom Post Type UI 1.4.3. |Hugo Miller|7/12/2016|
| 6.0.015    | Plugin: Instalación y activación de Contact Form 7 4.6. |Hugo Miller|7/12/2016|
| 6.0.014    | Plugin: Instalación y activación de Conditional Menus 1.0.6. |Hugo Miller|7/12/2016|
| 6.0.013    | Plugin: Instalación y activación de Apple Touch Icons 1.0. |Hugo Miller|7/12/2016|
| 6.0.012    | Plugin: Instalación y activación de Advanced Browser Check 4.4.1. |Hugo Miller|7/12/2016|
| 6.0.011    | Plugin: Instalación y activación de Admin Menu Editor 1.7.3. |Hugo Miller|7/12/2016|
| 6.0.010    | Theme: Importación de Listable Demo Data. |Hugo Miller|7/12/2016|
| 6.0.009    | Plugin: Número de licencia de Akismet 3.2. |José Manuel|7/12/2016|
| 6.0.008    | Theme: Número de licencia de Listable. |José Manuel|7/12/2016|
| 6.0.007    | WP: Actualización de traducciones de WordPress 4.7. |Hugo Miller|7/12/2016|
| 6.0.006    | Plugin: Instalación y activación de WooCommerce 2.6.8 + Asistente de instalación de WooCommerce. |Hugo Miller|7/12/2016|
| 6.0.005    | Theme: Borrado de temas instalados por defecto no usados. |Hugo Miller|7/12/2016|
| 6.0.004    | Plugin: Instalación y activación de Plugins asociados al Theme Listable:</br>- Customify 1.3.1</br>- PixTypes 1.4.4</br>- WP Job Manager 1.25.2</br>- Category Icon 0.6.0</br>- Comments Ratings 1.1.5</br>- Login with Ajax 3.1.6</br>- Nav Menu Roles 1.8.3</br>- WooCommerce 2.6.8 |Hugo Miller|7/12/2016|
| 6.0.003    | Theme: Instalación de Listable (Padre) e instalación y activación de Listable (Hijo/Child). |Hugo Miller|7/12/2016|
| 6.0.002    | WP: Creación de usuario Soporte. |Hugo Miller|7/12/2016|
| 6.0.001    | WP: Instalación de Wordpress 4.7. |Hugo Miller|7/12/2016|
 

 
