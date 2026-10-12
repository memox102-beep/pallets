# Monitor de Pallets — puerto 8770

Descarga `Descargar_instalador_Pallets.zip`, extrae su contenido y ejecuta `Instalar_Monitor_de_Pallets_8770.cmd` en Windows.

La app usa el puerto local 8770 e identifica sus propias instancias para evitar abrir otra aplicación. El instalador verifica la identidad antes de cerrar el monitor, incluida la versión antigua en 8765. Conserva config.json y datos/ de la instalación existente. No contiene credenciales ni datos personales.

Incluye las cinco correcciones anteriores de precios, avisos y escenarios.

Validación: 24 pruebas Python y 8 casos de cálculos de interfaz. Servidor real probado en 8770 mientras otro servicio ocupa 8765. Instalación y migración PowerShell en Windows, y Telegram real, pendientes de validación.

El instalador también reconoce Monitor de Pallets en el puerto anterior 18765 para actualizarlo.
