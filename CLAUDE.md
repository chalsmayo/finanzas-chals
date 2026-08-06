# App Finanzas Chals

App de finanzas personales en HTML/JS con Supabase.
Archivo principal: App Finanzas Chals.html

## Cambios aplicados
- Detección de cantidad en descripción: "2 Camel 23 13,2€" → se registra como 2 entradas de 6,6€
- Ahorros aparece en el desglose de ingresos

## Flujo de trabajo
- El archivo desplegado es `index.html`. Todos los cambios se hacen ahí directamente
- Git gestiona el versionado: cada cambio = un commit con mensaje descriptivo
- Tras cada cambio, hacer commit y push a GitHub automáticamente
- Si un cambio no gusta, revertir con `git revert` al commit anterior

## Notas
- Los datos viven en Supabase, no en localStorage