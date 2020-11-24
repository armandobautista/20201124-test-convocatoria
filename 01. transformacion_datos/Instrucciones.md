# Transformacion de datos

**Contexto del Negocio**: La empresa requiere diseñar un proceso de transformacion, limpieza y estandarizacion de datos para que sean almacenados en el Data Warehouse de la compañia.

Los requerimientos son los siguientes

1. Tranformar los nombres de las columnas.
2. Renombrar los nombres de las columnas.
3. Crear o eliminar columnas de acuerdo con el dataset final.
4. Convertir las columnas de fecha en formato "%Y-%m-%d".
5. De la columna 'StrParadero' obtener solo los digitos.
6. De la columna 'StrLinea' obtener solo el texto.
7. Proceso de guardado de resultado.

Ayuda: El nombramiento de las columnas es el siguiente

- FechaClearing: FechaContable 
- DíaTrx: FechaTransaccion
- HoraTrx: HoraTransaccion 
- Operador: Empresa
- RutaModificada: RutaSae 
- LineaSae: Linea
- Parada: StrParadero
- Vehiculo: Bus
- TipoDeViaje: TipoValidacion 
- Linea: StrLinea

**Set datos**: en la carpeta se encuentran dos archivos:

1. data_org: Datos que viene de la fuente para ser transformados
2. data_fnl: Datos de ejemplo de como deben quedar despues del proceso de transformacion.