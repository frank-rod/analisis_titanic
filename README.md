# Análisis de Supervivencia en el Titanic 🚢

## Descripción del Proyecto

Este proyecto analiza el famoso conjunto de datos del Titanic para descubrir los factores que influyeron en la supervivencia de los pasajeros durante este trágico acontecimiento histórico.

A través de análisis exploratorio de datos (EDA) y técnicas de visualización, buscamos responder a la pregunta: **¿Qué factores determinaron quién sobrevivió y quién no?**

## Contenido del Proyecto

- **analisis_titanic.ipynb**: Notebook principal que contiene todo el análisis y visualizaciones
- **df_titanic.csv**: Conjunto de datos con información sobre los pasajeros
- **logo.png**: Logo utilizado en la presentación
- **README.md**: Documentación del proyecto

## Características Exploradas

- **Demográficas**: Género, edad, clase social
- **Familiares**: Tamaño de familia, pasajeros viajando solos vs. con familia
- **Geográficas**: Puerto de embarque
- **Otras**: Tarifa pagada, título (extraído del nombre)

## Técnicas y Herramientas Utilizadas

- **Lenguaje**: Python 3.12
- **Bibliotecas principales**:
  - Pandas y NumPy para manipulación de datos
  - Matplotlib y Seaborn para visualizaciones

## Hallazgos Principales

- Las mujeres tuvieron una tasa de supervivencia significativamente más alta que los hombres (72.7% vs 19.1%), confirmando la política "mujeres y niños primero"
- Los pasajeros de Primera Clase sobrevivieron en mayor proporción que los de Tercera Clase (61.9% vs 25.5%)
- Los bebés y niños tuvieron mayores probabilidades de supervivencia que los adultos, con los bebés alcanzando un 66.1% de supervivencia
- Las familias medianas (3-4 miembros) mostraron las mejores tasas de supervivencia
- Combinaciones críticas: ser mujer en primera clase ofrecía una impresionante tasa de supervivencia del 96.5%, mientras que ser hombre en tercera clase resultaba en solo 15.2%

## Cómo Usar Este Proyecto

1. Clone este repositorio:
```
git clone https://github.com/frank-rod/analisis_titanic.git
```

2. Instale las dependencias necesarias:
```
pip install pandas numpy matplotlib seaborn jupyter
```

3. Abra el notebook en Jupyter:
```
jupyter notebook analisis_titanic.ipynb
```

## Contexto Histórico

El RMS Titanic era un transatlántico británico que se hundió en las primeras horas del 15 de abril de 1912, después de chocar con un iceberg durante su viaje inaugural desde Southampton a Nueva York. De las 2,224 personas a bordo, 1,502 murieron, convirtiendo esta tragedia en uno de los naufragios más mortíferos de la historia marítima comercial en tiempos de paz.

El análisis de los datos nos permite entender no solo los patrones estadísticos de supervivencia, sino también vislumbrar la dinámica social y los valores de la época. La priorización de mujeres y niños, así como las ventajas conferidas por la clase social, son un reflejo de la sociedad de principios del siglo XX.

## Contacto

Javier Rodríguez - [mail](mailto:fjrodriguez00@outlook.com) - [web](https://www.fjrod.com/) - [GitHub](https://github.com/frank-rod)

---

### Nota para Personas interesadas

Este proyecto demuestra habilidades en:
- Análisis exploratorio de datos y visualización
- Limpieza y transformación de datos
- Interpretación y comunicación de resultados
- Narración de historias basadas en datos

Estas competencias son directamente transferibles a problemas de negocio reales que requieren análisis de datos para informar la toma de decisiones.