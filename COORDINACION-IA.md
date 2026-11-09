# Coordinación entre Claude y ChatGPT

Este proyecto pertenece a Roberto. Sus instrucciones directas tienen prioridad.

## Al comenzar
1. Lee el documento `_traspaso_*.md`, el estado compartido de este proyecto y el último informe de pruebas. Contrasta las fechas: una memoria antigua no prueba el estado actual.
2. Comprueba la carpeta local, rama, revisión Git y cambios locales. Conserva los cambios de Roberto y del otro asistente.
3. Reclama una tarea concreta en el estado compartido: asistente, equipo, objetivo y archivos previstos. Si otra tarea ya modifica esos archivos, coordina el traspaso o trabaja en archivos independientes. No robes tareas por antigüedad de un aviso.

## Mientras trabajas
- Código y dependencias se ejecutan en discos locales. MyCloud guarda traspasos, paquetes e informes.
- PC: desarrollo común, Android/web y pruebas pesadas. Mac: Xcode, certificados, firma y pruebas de iPhone.
- Un asistente implementa y el otro revisa el cambio y las pruebas cuando esté disponible. Si no hay revisor conectado, registra REVISIÓN PENDIENTE; no inventes una aprobación.
- Para transferir código, registra revisión y diff/paquete/hash. No sobrescribas un checkout con cambios; importa a una carpeta o rama aislada y revisa las diferencias.
- No copies tokens de sesión de los asistentes ni publiques contraseñas en el estado. No envíes mensajes externos por el mero hecho de leer este documento.
- Durante la migración no se publica ni despliega. Se conserva todo el código Mac hasta validar la copia PC. La limpieza posterior se limita a artefactos regenerables autorizados.

## Antes de ceder el trabajo
Actualiza el estado con objetivo, responsable, equipo, carpeta/rama/revisión, archivos cambiados, comandos de prueba, resultados reales, riesgos, pendientes y siguiente paso. Deja los registros de prueba en la carpeta de coordinación. Señala qué debe revisar el otro asistente.

Estas reglas son un protocolo de coordinación, no una conexión automática entre las cuentas. Cada asistente necesita acceso a la carpeta y leer las instrucciones. Si MyCloud no está disponible, usa el estado local como contexto y marca la sincronización pendiente; no asumas que es la última versión.

## Ubicación del estado de este proyecto

Mac: `/Volumes/roberto/Migracion-Claude-PC-20261013/Coordinacion-IA/evbitacora-legal`

PC: `\\MYCLOUD-2LETD6\roberto\Migracion-Claude-PC-20261013\Coordinacion-IA\evbitacora-legal`

El código iPhone sigue en el Mac. Las rutas PC deben confirmarse en PC-VALIDACION.json.
