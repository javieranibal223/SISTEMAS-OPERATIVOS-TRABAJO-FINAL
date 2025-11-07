# SISTEMAS-OPERATIVOS-TRABAJO-FINAL
Descripción breve del proyecto

Este proyecto consiste en un conjunto de scripts Bash que automatizan tareas básicas de administración del sistema utilizando Git Bash en Windows.
Su objetivo es aplicar los conceptos de automatización, scripting y gestión de procesos aprendidos durante la cursada de Sistemas Operativos.

El sistema presenta un menú interactivo, desde el cual el usuario puede:

Realizar respaldos automáticos de un directorio.

Generar un informe con el uso actual de CPU, memoria y disco.

Eliminar archivos temporales del sistema para liberar espacio.

Cada tarea está implementada en un script separado y puede ejecutarse individualmente o a través del menú principal.

Instrucciones de uso
Requisitos previos

Tener Git Bash instalado en Windows.

Tener habilitadas las utilidades GNU básicas (tar, find, df, top, free, rm).

Descargar o clonar el proyecto

Cloná el repositorio desde GitHub o descargá el ZIP:

git clone https://github.com/<tu_usuario>/Proyecto_TIF.git
cd Proyecto_TIF

Dar permisos de ejecución
chmod +x *.sh

Ejecutar el menú principal
./menu_sistemas.sh

 Ejemplos de uso
 Opción 1 – Respaldo automático

Genera un archivo comprimido con la fecha y hora actual:

backup_20251107_1230.tar.gz


Guardado en:

/c/Users/<usuario>/Desktop/backups

 Opción 2 – Informe del sistema

Crea o actualiza el archivo:

/c/Users/<usuario>/Desktop/informe_sistema.log


Con datos de CPU, memoria y disco.

Opción 3 – Limpieza de temporales

Elimina los archivos de:

/c/Windows/Temp
/c/Users/<usuario>/AppData/Local/Temp

Cómo colaborar con el proyecto:

Si querés colaborar o mejorar el código:

Hacé un fork del repositorio.

Creá una rama nueva para tus cambios:

git checkout -b mejora-nueva


Realizá tus modificaciones y hacé commit:

git commit -m "Mejoras en validación del menú"


Enviá un pull request con una breve descripción del cambio.

Licencia

Este proyecto se distribuye sin licencia, lo que permite su uso, modificación y distribución libre con fines educativos y personales, siempre que se mantenga el crédito a los autores originales.

Archivos de apoyo

El proyecto incluye archivos auxiliares generados durante su ejecución:

Desktop/informe_sistema.log → Log con información de CPU, memoria y disco.

Desktop/backups/backup_YYYYMMDD_HHMM.tar.gz → Archivo de respaldo comprimido.

docs/memoria_tecnica.pdf → Memoria técnica en formato PDF.

Autores: Javier Rios y Axel Rios
