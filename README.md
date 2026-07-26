# DevmanExtensiones Extensions

Repositorio de pruebas para guardar únicamente los ZIP finales aprobados generados con `devman-ext`.

## Organización

Cada extensión se guarda según su tipo, nombre y versión:

```text
modules/<nombre>/<version>/<archivo>.ocmod.zip
shipping/<nombre>/<version>/<archivo>.ocmod.zip
payment/<nombre>/<version>/<archivo>.ocmod.zip
total/<nombre>/<version>/<archivo>.ocmod.zip
feed/<nombre>/<version>/<archivo>.ocmod.zip
fraud/<nombre>/<version>/<archivo>.ocmod.zip
```

Ejemplo:

```text
modules/whatsapp-flotante/1.0.0/whatsapp_flotante.ocmod.zip
shipping/envio-personalizado/1.1.0/envio_personalizado.ocmod.zip
```

## Flujo

1. Crear y probar el módulo con `/devman-ext`.
2. Verificar que todo funcione correctamente.
3. Pedir confirmación antes de publicar.
4. Subir únicamente el ZIP final a la carpeta correspondiente.
5. Para una nueva versión, crear otra carpeta de versión sin reemplazar la anterior.

Este repositorio es público y se usa solo para ejemplos y pruebas. No subir credenciales, licencias, UUID reales de clientes ni información privada.
