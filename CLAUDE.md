# App Finanzas Chals

App de finanzas personales en HTML/JS con Supabase.
Archivo principal: App Finanzas Chals.html

## Cambios aplicados
- Detección de cantidad en descripción: "2 Camel 23 13,2€" → se registra como 2 entradas de 6,6€
- Ahorros aparece en el desglose de ingresos

## Flujo de trabajo
- NUNCA sobreescribir el archivo principal. Crear un archivo nuevo versionado (ej: `App Finanzas Chals v2.html`) con los cambios
- Tras cada cambio, hacer commit y push a GitHub automáticamente

## Notas
- Los datos viven en Supabase, no en localStorage