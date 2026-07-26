# Seguridad

- No guardar contraseñas, tokens, claves API, licencias reales ni datos personales.
- No subir copias de tiendas, bases de datos, archivos `config.php` ni logs de clientes.
- No modificar core de OpenCart, Journal, Journal2 o Journal3.
- Producción es siempre la última opción y requiere autorización, respaldo y plan de reversión.
- La publicación FTPS debe ejecutarse únicamente desde `devman-ext` y con confirmación explícita.
- Los secretos expuestos por chat, correo o captura deben rotarse antes de volver a utilizarlos.
