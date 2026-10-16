MONTAÑO CONSTRUCCIONES - WEB EDITABLE PARA NETLIFY

CONTENIDO
index.html: web pública
contenido.json: textos, imágenes y proyectos
admin/: panel Decap CMS
assets/: logo y fotos nuevas

PARA PUBLICAR
1. Creá un repositorio GitHub y subí TODO el contenido de esta carpeta (no el ZIP cerrado).
2. En Netlify, elegí importar proyecto desde GitHub y seleccioná el repositorio.
3. En admin/config.yml, reemplazá TU_USUARIO/TU_REPOSITORIO por tu repositorio real, por ejemplo montano/montano-web. Hacé commit del cambio.
4. Configurá autenticación para el backend GitHub de Decap CMS mediante OAuth compatible con GitHub. Sin OAuth configurado, /admin/ no permitirá iniciar sesión ni guardar cambios. El alojamiento gratuito por sí solo NO habilita la autenticación.
5. Una vez configurado, ingresá a https://TU-SITIO.netlify.app/admin/ e iniciá sesión con una cuenta autorizada para editar el repositorio.
6. Guardar/Publicar en el panel crea un commit en GitHub y Netlify vuelve a desplegar el sitio automáticamente.

IMPORTANTE
- Esta entrega incluye el panel y su configuración, pero NO está conectada a tu cuenta GitHub, Netlify ni a un proveedor OAuth. No es una web online lista para iniciar sesión sin configurar esos servicios.
- Para ver la web localmente usá un servidor HTTP; abrir index.html como file:// no permite leer contenido.json con fetch en muchos navegadores.
- Las fotografías de ejemplo son ilustrativas; reemplazalas por fotos propias.
- No publiques la versión anterior con #administrar, porque no tiene autenticación real.
