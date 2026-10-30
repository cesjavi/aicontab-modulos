# Módulos oficiales de AIContab

Distribución pública del catálogo y paquetes firmados. El código de AIContab se mantiene en su repositorio privado.

## Instalar desde AIContab

1. Usar AIContab Desktop **0.2.19 o posterior**.
2. Abrir **Configuración → Módulos del estudio → Catálogo online**.
3. Pulsar **Descargar e instalar**, o **Descargar actualización**.
4. Habilitar el módulo para cada estudio que lo necesite.

El catálogo oficial se configura por defecto en Desktop 0.2.19:

https://github.com/cesjavi/aicontab-modulos/releases/latest/download/catalog.json

También se pueden descargar los archivos `.aicontab-module` desde [Releases](https://github.com/cesjavi/aicontab-modulos/releases) e instalarlos desde archivo.

Los paquetes se verifican mediante firma y hash. Las simulaciones se guardan localmente; descargar módulos no envía datos contables a GitHub.

## Publicación

Cada release estable debe incluir `catalog.json` y los paquetes a los que apunta. El catálogo debe usar enlaces a la versión concreta de cada paquete. Publicar primero como borrador, cargar todos los archivos y después marcar la entrega como estable más reciente.

No subir datos de clientes, claves privadas ni credenciales a este repositorio.
