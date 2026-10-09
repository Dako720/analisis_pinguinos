CONFIGURACIÓN DE ENTORNO VIRTUAL PARA ANALISIS DE DATOS PARA PINGUINOS

COMO CRER UN ENTORNO VIRTUAL:

1. Primero debes crear una carpeta con el nombre del proyecto
2. Luego abre esa carpeta en tu editor de codigo de preferencia
3. En la terminal del editor, ingresa este codigos:

python -m venv .venv
.\nombre_entorno\Scripts\Activate.ps1

en la terminar aparecerá (.venv) eso quiere decir que el entorno virtual está activado y verás que se creó la carpeta .venv con sus respectivas subcarpetas

NOTA: Al momento de subir tu proyecto a Github no se puede subir la carpeta .vent ya que esta contiene solamente el entorno virtual y cada usuario debe instalarlo en su ordenador, lo que generalmente se debe subir en el archivo requirements.txt y los archivos .py del proyecto

5. Lo siguiente es instalar las dependencias que necesites, generalmente son:

– pandas (para manipulación de datos).
– matplotlib (para visualización).
– seaborn (para visualizaciones estadísticas más atractivas).

y el codigo para instalar todos las dependencias al tiempo es:

pip install pandas matplotlib seaborn

Para desactivar el entorno viartual el comando es : deactivate
