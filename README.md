# BMW Pricing 🚗💰

<img src="img/bmw.png" alt="Logo BMW" width="300">

## Descripción del Proyecto 📝

Este proyecto tiene como objetivo predecir el precio de los coches BMW en función de varias características del vehículo, utilizando un conjunto de datos con información detallada sobre modelos, kilometraje, potencia, tipo de combustible, entre otras variables. El proyecto incluye el proceso de limpieza y preprocesamiento de datos, seguido de un análisis exploratorio de los datos y la construcción de un modelo predictivo.

### Pasos realizados en este proyecto 🔄

1. **Limpieza de Datos** 🧹:
   - Eliminación de valores nulos o irrelevantes.
   - Reemplazo de valores faltantes por la media o moda según corresponda.
   - Transformación de variables categóricas y numéricas.
   - Manejo de valores atípicos y outliers.

2. **Análisis Exploratorio** 📊:
   - Visualización y análisis de la correlación entre las variables y el precio (target).
   - Estudio de la distribución de variables clave como potencia, kilometraje y tipo de gasolina.

3. **Preprocesamiento** 🔧:
   - Conversión de variables de fecha a tipo datetime.
   - Creación de nuevas variables derivadas como "antigüedad" (diferencia entre fecha de venta y fecha de registro).
   - Agrupación de categorías poco frecuentes en variables categóricas (por ejemplo, "otros_modelos" para modelos con menos de 50 registros).

4. **Modelado Predictivo** 🤖:
   - Entrenamiento de modelos predictivos para estimar el precio del vehículo.

## Características del Dataset 🗂️

- **Modelos**: La columna de modelo se limpia agrupando aquellos con pocos registros en la categoría "otros_modelos".
- **Kilometraje (km)**: Se sustituyen valores negativos y nulos por la media del kilometraje.
- **Potencia**: Se sustituyen valores atípicos y nulos por la media o la moda dependiendo del contexto.
- **Precio**: Se eliminan valores atípicos muy altos (superiores a 100,000) y se mantienen los precios bajos sin eliminarlos.

## Resultados 📈

- Se observa una correlación positiva entre la potencia y el precio del coche.
- Se observa una correlación negativa entre el kilometraje y el precio.
- Se eliminan columnas con baja correlación con el precio (como 'gps').

## Instalación y Requisitos ⚙️

Para ejecutar este proyecto, asegúrate de tener las siguientes librerías instaladas:

- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- **scikit-learn**

## **Autor** ✍️

Juan Natoli
