# Contribución

## Flujo obligatorio

1. Crear una rama por módulo o cambio.
2. Guardar cada módulo en `modules/<codigo>/`.
3. Mantener `specification.yaml` actualizado.
4. No modificar core de OpenCart ni de Journal.
5. Validar sintaxis PHP, XML, Twig/JavaScript y búsquedas OCMOD.
6. Confirmar que los cambios aparecen en `storage/modification` cuando aplique.
7. Ejecutar pruebas antes de abrir el Pull Request.
8. No fusionar ni publicar sin aprobación explícita.

## Nombres de ramas

```text
agent/<codigo>-build
agent/<codigo>-fix
agent/<codigo>-release
```

## Repositorio público

Este repositorio es de ejemplos y pruebas. No incluir datos de clientes, credenciales, licencias reales, UUID privados ni paquetes comerciales.
