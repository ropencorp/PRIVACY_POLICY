# Política de Privacidad para Gestor de Credenciales by Ropencorp

**Fecha Efectiva:** 21 de Abril de 2025

Esta Política de Privacidad describe cómo Ropencorp (referido como "desarrollador", "nosotros", "nuestro") maneja la información en relación con la extensión de Chrome "Gestor de Credenciales by Ropencorp" (la "Extensión").

Creemos firmemente en la privacidad del usuario. Nuestro objetivo es ayudarte a gestionar tus credenciales de forma segura y local, con la opción de usar la sincronización de Chrome si así lo decides.

Aclaración sobre Distribución:
> _Esta extensión está destinada a un uso limitado y se distribuye de forma privada o no listada. Solo los usuarios que reciban un enlace directo o autorización específica del desarrollador podrán instalarla y utilizarla._

**1. Información que la Extensión Almacena**

La Extensión está diseñada para ayudarte a gestionar tus credenciales de inicio de sesión. La información que almacena es **proporcionada directamente por ti** a través de la interfaz de la extensión:

* **Credenciales de Usuario:**
    * Alias (un nombre para identificar la credencial)
    * URL (la dirección web del sitio asociado)
    * Nombre de Usuario
    * Contraseña
    * Carpeta (nombre opcional para organización)
* **Preferencias de la Extensión:**
    * Tu elección sobre si deseas activar la sincronización (`userPrefersSync`).

La extensión **NO recopila automáticamente** ninguna otra información personal, de navegación, de actividad, ubicación, o contenido de sitios web.

**2. Cómo y Dónde se Almacena la Información**

La Extensión utiliza las APIs de almacenamiento seguro proporcionadas por el navegador Google Chrome. **El desarrollador NO tiene acceso a las credenciales que tú almacenas.**

* **Almacenamiento Local (`chrome.storage.local`):** Por defecto, o si eliges no sincronizar, tus credenciales y preferencias se guardan cifradas por el navegador **únicamente en tu dispositivo local**. Solo tú, a través de tu perfil de navegador, tienes acceso a ellas.
* **Almacenamiento Sincronizado (`chrome.storage.sync`):** Si habilitas explícitamente la función de sincronización en la extensión, tus credenciales se almacenarán utilizando la infraestructura de sincronización de Google Chrome, vinculada a tu cuenta de Google. Google se encarga de la sincronización y seguridad de estos datos conforme a sus propias políticas de privacidad. El desarrollador sigue **sin tener acceso** a estas credenciales sincronizadas. La activación de esta función es totalmente opcional.

**3. Cómo se Utiliza la Información Almacenada**

La información que guardas se utiliza **exclusivamente** para proporcionarte la funcionalidad de la Extensión:

* Mostrarte tu lista de credenciales en el popup.
* Organizar las credenciales en carpetas.
* Abrir la URL correspondiente en una nueva pestaña al hacer clic en un alias.
* Autocompletar el nombre de usuario y contraseña en las páginas web compatibles cuando inicias la navegación desde el popup (leyendo datos temporales guardados localmente).
* Mostrar una lista desplegable con alias y nombres de usuario relevantes (NO contraseñas) en páginas de inicio de sesión compatibles cuando haces foco en un campo, para que selecciones cuál usar.
* Obtener la contraseña correspondiente (sin mostrarla) únicamente después de que seleccionas un item del desplegable, para rellenar el campo de contraseña.
* Permitir la importación y exportación de tus credenciales directamente en tu navegador.
* Verificar el estado de sesión de Chrome (usando `chrome.identity`) *solo* para determinar si la opción de `storage.sync` está disponible. No se almacena tu identidad.

**4. Compartición de Datos**

**NO vendemos, alquilamos, ni compartimos tus credenciales o información personal con ningún tercero.**

* Si utilizas la función de sincronización, los datos son manejados por Google según su política de privacidad.
* La extensión no incluye rastreadores, análisis de terceros ni envía tus datos a servidores externos controlados por el desarrollador.

**5. Seguridad**

La seguridad de tus datos depende de la seguridad intrínseca de tu navegador Chrome y, si usas la sincronización, de la seguridad de tu cuenta de Google. Te recomendamos usar una contraseña maestra para tu cuenta de Google y mantener tu navegador actualizado.

**6. Control y Eliminación de tus Datos**

Tú tienes el control total:

* Puedes **ver, editar y eliminar** credenciales individuales en cualquier momento desde el popup de la extensión.
* Puedes **borrar todos los datos** almacenados por la extensión (local o sync) a través de las herramientas de gestión de datos de extensiones en la configuración de Chrome.
* **Desinstalar** la extensión eliminará todos los datos almacenados localmente. Los datos sincronizados permanecerán en tu cuenta de Google (gestionados por Google) a menos que los elimines desde allí.

**7. Cambios a esta Política**

Si realizamos cambios importantes en esta política, actualizaremos la fecha de efectividad y lo notificaremos a través de la ficha de la extensión en la Chrome Web Store.

**8. Contacto**

Si tienes preguntas sobre esta Política de Privacidad, puedes contactar con:
Ropencorp Email: rts@ropencorp.com

---
