<p align="left">
<img src="https://s28.postimg.org/ux8l1tv6l/imagengit.png">
</p>
### **03-Grupo Tartiere**

_Relativo al proceso de implementación del servicio del Grupo Tartiere_






| Versión |Cambios y/o evoluciones |Autor|Fecha|
|:------------- |:---------------|:---------------|:---------------
| 10.002.059    | Plugin: Legacy - White Label WordPress Admin Theme 5.1: Configuración:</br></br>- Importación de la configuración del sitio parent LifeMyCar</br></br>+ Según lo visto en 10.001.059, vamos en LifeMyCar a la sección Legacy Admin: Importar/Exportar: Opciones de Exportación: Copy Export URL</br>+ De vuelta en Grupo Tartiere, vamos a Legacy Admin: Importar/Exportar: Opciones de Importación: Importar desde URL</br>+ Si no importa la configuración bien al primer intento, insistir.</br></br>- Legacy Admin: Logo Settings => Quitar el logo del parent y utilizar en su lugar Google Drive/01-TRABAJOS/2-APPs_Services/2.02-LifeMyCar/04-Imagen Gráfica/Backend/Logo-BACKEND-GRUPOTARTIERE.png|Hugo Miller|11/1/2017|
| 10.002.058    | Plugin: Legacy - White Label WordPress Admin Theme 5.1: Activación. |Hugo Miller|11/1/2017|
| 10.002.055    | Apariencia: Custom CSS (se llama así, independientemente de que tengamos instalado el plugin SiteOrigin CSS 1.1.2 y no cualquier otro plugin que se llame precisamente Custom CSS -que existen varios-): Añado líneas al CSS para eliminar (realmente ocultar) publicidad (y tutoriales) de Google Analytics.</br></br><strong>4 NOTAS IMPORTANTES:</strong></br></br><strong>1</strong>- Los pasos de este GitHub en los que se indiquen retoques de CSS no hace falta repetirlos en caso de tener que empezar una nueva versión de la web desde cero. ¿Por qué? Porque bastará con importar el CSS de la página y ahí estarán ya todos los cambios aplicados.</br><strong>2</strong>- ¿Cómo saber qué líneas hay que añadir al CSS? Empleamos la extensión de Google Chrome "Stylebot":</br>+ Open Stylebot: Sección "Basic" (en la parte inferior de la columna de Stylebot)</br>+ Seleccionar con el mouse el bloque de publicidad que queremos ocultar</br>+ Layout & Visibility => Hide</br>+ Cambio a la sección "Edit CSS"</br>+ Copiar en el portapapeles el código que ahí aparece</br>+ Copiar ese código en Apariencia: Custom CSS, poniendo antes un comentario explicando su función</br><strong>3</strong>- Si en algún momento nos bloqueamos trabajando con un plugin y no sabemos por dónde seguir averiguando aspectos de su funcionamiento, habrá que recordar si hemos eliminado algún vídeo tutorial explicativo al ocultar secciones de publicidad (como en este caso con Google Analytics)</br><strong>4</strong>- En ocasiones podemos encontrarnos con un bug consistente en que no se muestran correctamente los escritorios de WordPress o de los plugins: que no podemos añadir/quitar elementos mediante "Opciones de pantalla", etc. El causante de ese mal comportamiento es el haber empleado recientemente "Stylebot". Para solucionarlo, basta con arrancarlo en la página donde tengamos el bug y hacer clic en la opción inferior "Reset page"|Hugo Miller|11/1/2017|
| 10.002.053   | Recibimos una cuenta de Google Analytics (NO VÍA BROADCAST) desde LifeMyCar (ver 10.001.053). |Hugo Miller|11/1/2017|
| 10.002.052   | Snnipet. Definición de colores distintos para cada site en el back-end. Snippet guardado en Google Drive/01-TRABAJOS/2-APPs_Services/2.02-LifeMyCar/16-Snnipets y PHP. Activación para la red.|Hugo Miller|10/1/2017|
| 10.002.046    | Apariencia. Subimos logos (naranja el de arriba) y (azul el de abajo) de la librería de medios (filtro "logotipos"), también subimos del mismo lugar el Favicon. |Hugo Miller|10/1/2017|
| 10.002.045    | Recibimos un Broadcast desde LifeMyCar (ver 10.001.045).|Hugo Miller|10/1/2017|
| 10.002.039    | Plugin: SiteOrigin CSS 1.1.2: Añado CSS (Versión 01) => Se almacena en formato xml en la carpeta Google Drive/01-TRABAJOS/2-APPs_Services/2.02-LifeMyCar/14-CSS/LifeMyCar (Versión 01).css.|Hugo Miller|28/12/2016|
| 10.002.036    | Medios: Upload de medios (imágenes y vídeos) correspondientes a las categorías de Medios (ETIQUETADO): "Blog", "Categorías", "Coches en alquiler", "Equipamientos", "Explicativos", "Fondos de la Página Principal", "Logotipos", "Marcas", "Modo de Mantenimiento", "Vídeos". Previo borrado de las imagenes de Listable que se alojan en la Librera de Medios después de la carga del material de DEMO de Listable. Para Subir los videos (y ya que exceden del peso máx por defecto que es de 1 Mb hay que modificar en SITIOS->AJUSTES->Tamaño máximo permitido 6 Mb. Y sin modificar ese ajuste, se pueden subir "desde el navegador" esto es "seleccionando uno a uno y dando a subir" en lugar de arrastrándolos a la zona punteada.|Hugo Miller|27/12/2016|
| 10.002.026    | Plugin: Configuración de Maintenance 3.2:</br></br>- Descripción: ¡Pronto estaremos en la carretera!</br>- Logo: Google Drive/01-TRABAJOS/2-APPs_Services/2.02-LifeMyCar/04-Imagen Gráfica/Usado en V10/Modo de Mantenimiento/logo.png</br>- Fondo: Google Drive/01-TRABAJOS/2-APPs_Services/2.02-LifeMyCar/04-Imagen Gráfica/Usado en V10/Modo de Mantenimiento/FondoOffline.jpg</br>- CSS Personalizado: Google Drive/01-TRABAJOS/2-APPs_Services/2.02-LifeMyCar/04-Imagen Gráfica/Usado en V10/Modo de Mantenimiento/Css de Mantenimiento.css|Hugo Miller|27/12/2016|
| 10.002.023    | Sitios/Galería de medios: Sitios (clic en el nombre de cada sitio) (clic en Grupo Tartiere): Información: Dirección del sitio (URL): https://tartiere.lifemycar.com/. Es decir, si el dominio Parent es https, los Child no pueden ser http. Por ejemplo, si no se hace este cambio, no se pueden subir archivos a la galería de medios.|Hugo Miller|27/12/2016|
| 10.002.017     | Theme: Activamos Listable <strong>Hijo/Child</strong>. |Hugo Miller|27/12/2016|
| 10.002.016     | Apariencia: Personalizar: Theme options: Demo Data: Import Demo Data. |Hugo Miller|27/12/2016|
| 10.002.015     | Plugin: Activación de Plugins asociados al Theme Listable, propuestos una vez que está activado:</br></br>- Customify 1.3.1</br>- PixTypes 1.4.4</br>- WP Job Manager 1.25.2</br>- Category Icon 0.6.0</br>- Comments Ratings 1.1.5</br>- Login with Ajax 3.1.6</br>- Nav Menu Roles 1.8.6</br>- WooCommerce 2.6.10</br></br> NOTA: estos Plugins sólo hemos tenido que activarlos, no instalarlos y activarlos. ¿Por qué? Porque ya estaban instalados en el dominio Parent LifeMyCar. |Hugo Miller|27/12/2016|
| 10.002.014     | Theme: Activamos Listable <strong>Padre</strong>. |Hugo Miller|27/12/2016|
| 10.002.001    | Inicio. El .002 se debe a que se trata del sitio nº 2. |Hugo Miller|27/12/2016|
| 8.002.004    | Versión cancelada.|Hugo Miller|23/12/2016|
| 8.002.003    | Plugin: Instalación y activación de IgniteUp 3.2. DEPRECADO. Ahora Utilizamos MAINTENANCE. Ver Instalción en el Sitio LifeMyCar.|Hugo Miller|23/12/2016|
| 8.002.002    | Theme: Instalación de Listable (Padre) e instalación y activación de Listable (Hijo/Child).|Hugo Miller|23/12/2016|
| 8.002.001    | Inicio. El .002 se debe a que se trata del sitio nº 2.|Hugo Miller|23/12/2016|

 

 
