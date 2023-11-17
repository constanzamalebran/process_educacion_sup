## Paso 1: Redirigirse a la carpeta del proyecto

## Paso 2: Cree el ambiente virtual
python -m venv myenv

## Paso 3: activar el entorno virtual
myenv\Scripts\activate


### observacion: si esta en MacOs o linux debe usar
source myenv/bin/activate

## Paso 4: instalar las librerias del archivo requirements.txt
pip install -r requirements.txt

## Paso 5: luego descargar el csv mas reciente
https://datosabiertos.mineduc.cl/titulados-en-educacion-superior/

## Paso 6: ejecutar la aplicacion 
python get_excel_resumen_es.py
