Caso 1: Ventas no sincronizan con el servidor

Contexto:
Sistema ERP utilizado por múltiples sucursales.

Problema:
Las ventas realizadas en una estación no se reflejan en el sistema central.

Impacto:
- Descuadre en reportes
- Problemas contables
- Pérdida de trazabilidad

Análisis:
- Se revisan logs del sistema y del servicio
- Se detectan errores de conexión intermitente
- Se identifica posible falla en servicio de sincronización

Hipótesis:
El servicio encargado de enviar los datos al servidor se encuentra detenido o mal configurado.

Validación:
- Se verifica el estado del servicio
- Se realizan pruebas de conectividad
- Se revisa la configuración del sistema

Solución:
- Reinicio del servicio de sincronización
- Corrección de parámetros de conexión
- Verificación de envío correcto de datos

Resultado:
Las ventas comienzan a reflejarse correctamente en el sistema central.
