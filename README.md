# ICN292-Lab3-Suarez-Javiera-

# Laboratorio 3 - Automatización del proceso de devoluciones mediante n8n
- Nombre: Javiera Suárez 
- Rut: 21342846
- Fecha: 22 de septiembre de 2026 
- Asignatura: ICN292
## Datos
- S = 846
- U = $76.000
- D = 21 días

## Descripción
En este laboratorio se desarrolló un sistema de automatización en n8n para procesar las solicitudes de devolución de AndesHogar. El sistema clasifica las solicitudes según las reglas establecidas, registra los resultados y envía una notificación al cliente. Además, se implementó un workflow para generar un resumen diario de las solicitudes procesadas.

## Archivos 
- Informe PDF y Word: desarrollo del laboratorio, resultados y evidencias.
- Workflows/: archivos JSON de los tres workflows desarrollados en n8n:
    - TRIAGE.json: workflow principal de clasificación de solicitudes.
    - EMISOR.json: workflow utilizado para enviar las solicitudes de prueba.
    - RESUMEN_DIARIO.json: workflow de generación del resumen diario.
- solicitudes.xlsx: datos utilizados durante el laboratorio.
- Ejecuciones_exitosas/: capturas de las ejecuciones exitosas de los workflows.
- Ejecuciones_fallidas/: capturas de los errores y pruebas realizadas durante el laboratorio.
  
## Cómo reproducir el laboratorio 
1. Importar los tres archivos JSON de los workflows en n8n.
2. Configurar el webhook del workflow principal y actualizar su URL en el workflow emisor.
3. Configurar los servicios de notificación y la tabla de registro.
4. Ejecutar el workflow emisor para enviar las solicitudes de prueba.
5. Ejecutar el workflow de resumen para revisar los resultados registrados.
Las carpetas de ejecuciones contienen las capturas utilizadas para documentar los resultados y errores obtenidos durante el laboratorio.
