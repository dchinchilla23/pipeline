# Proyecto de Ingesta de Datos en PostgreSQL

Este proyecto se enfoca en cargar datos en una base de datos PostgreSQL utilizando Python y Pandas. 🐍🐘

## Requisitos 📋

- Python 3.x
- Pandas
- PostgreSQL (asegúrate de tener una base de datos llamada "Prueba_diego" configurada)

## Configuración ⚙️

1. Asegúrate de tener PostgreSQL instalado y configurado correctamente.
2. Crea una base de datos llamada "Prueba_diego".
3. Ejecuta el script SQL proporcionado para crear la tabla `Prueba_diego_ingesta`.
4. En mi caso use PGAdmin 4 y cree la tabla mencionada y el schema prueba y luego crear la tabla Prueba_diego_ingesta

## Uso 🚀

1. Clona este repositorio.
2. Abre el archivo `Lectura_archivos_01.ipynb` y el archivo `Lectura_archivo_validation_02.ipynb`.
3. Modifica las credenciales de conexión a PostgreSQL en la función `connect_to_postgres`.
4. Ejecuta el script para cargar los datos en la tabla.

## Funciones 🔍

### `connect_to_postgres()`

Esta función establece una conexión a la base de datos PostgreSQL. Asegúrate de proporcionar las credenciales correctas.

### `load_data_to_postgres(connection, merged_df)`

Carga los datos del DataFrame `merged_df` en la tabla `Prueba_diego_ingesta`.

## Resultados 📊

- Número total de filas cargadas: **{count}**
- Valor medio del campo 'price': **{total_price / count:.2f}**
- Valor mínimo del campo 'price': **{min_price:.2f}**

¡Buena suerte con tu despliegue ! 🚀🍀
