## Mejora (2026-04-30T02:15:00Z)
- Añadida funcionalidad de caché de HTML para reducir peticiones redundantes y acelerar búsquedas.
- Implementado `extract_contact_forms` para detectar formularios de contacto y capturar sus URLs de acción.
- Mejorada la gestión de reintentos y registro de errores en los fetchers.
- Extendida la función de alto nivel `search_company_contacts` para incluir `contact_forms` en el resultado.
- Actualizado `state.json` para incluir la empresa **Microsoft** en la cola de pendientes, permitiendo la expansión del conjunto objetivo sin depender de la ejecución directa de Python en el entorno.