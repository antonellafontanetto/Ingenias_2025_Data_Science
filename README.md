# Ingenias_2025_Data_Science
# 🛢️ Proyecto 4x4 YPF - Análisis de Vaca Muerta
# Grupo 3 - Fundación YPF / Programa Ingenias+

# Introducción

El proyecto 4x4 de YPF tiene como objetivo principal cuadruplicar la producción de la compañía en los próximos 4 años, enfocándose en la eficiencia operativa, la generación de valor y la concentración de esfuerzos en los activos más rentables a corto plazo, como Vaca Muerta, la principal cuenca petrolera del país.

Este trabajo busca analizar el crecimiento de la producción de petróleo y gas en la cuenca neuquina desde el año 2021 en adelante, considerando exclusivamente los datos correspondientes a YPF S.A.. El análisis se basa en indicadores clave como la producción no convencional, las principales 5 áreas de concesiones y el subtipo de recurso producido, ya sea shale o tight en los últimos años.

En el análisis, se busca aportar evidencia empírica sobre la evolución y proyección del potencial de expansión de YPF en Vaca Muerta, en línea con los objetivos planteados en su plan estratégico 4x4.

# Objetivo

El objetivo del proyecto es analizar y predecir el crecimiento de la producción de petróleo y gas por parte de YPF S.A. en la cuenca neuquina, evaluando el impacto de diferentes variables relacionadas con la actividad extractiva y operativa.

# Integrantes - Grupo 3

Este proyecto fue desarrollado por el Grupo 3 del curso de Data Science de Fundación YPF en el marco del programa Ingenias+, que busca incorporar más mujeres al mundo de la programación.

* Cyntia Nasabun – Diplomada en Análisis de Datos e IA, IFES, Neuquén. 

* Antonella Fontanetto – Licenciada en Economía, Universidad de Buenos Aires

# Datasets utilizados

Los datos provienen de fuentes públicas oficiales del Gobierno Nacional y de la Provincia del Neuquén:

* Producción de Pozos de Petróleo y Gas http://datos.energia.gob.ar/dataset/produccion-de-petroleo-y-gas-por-pozo

Mapas y documentos complementarios:

* Mapa Energía Río Negro https://mapa.rionegro.com.ar/energia

* Distribución de Fluidos – Energía Neuquén https://www.energianeuquen.gob.ar/distribucion-de-fluidos/

* Línea estratégica YPF 4x4 https://www.rystadenergy.com/news/vaca-muerta-smashes-crude-output-record-in-3q

* Presentación IR Day 2025 – YPF https://inversores.ypf.com/documents/presentaciones/YPF-IR-DAY-2025-presentation.pdf

* YPF – Mayo 2024 – IAméricas https://iamericas.org/2024/05/YPF_Horacio-Marin_Mesa-Redonda_Mayo-8-presentation.pdf

* Análisis potencial exportador de Vaca Muerta – La Nación  https://www.lanacion.com.ar/el-potencial-exportador-vaca-muerta-el-planparaalcanzarlos30milmillonesdedolares


# Estructura del repositorio

📁

├── data/           # Datasets procesados

├── Pre-Entrega-2/      # Notebooks (diferentes versiones estudiadas) y Readme

├── Pre-Entrega-3/      # Notebooks (diferentes versiones estudiadas) y Readme

├── Pre-Entrega-4/      # Notebooks (diferentes versiones estudiadas) y Readme

├── README.md       # Este archivo

# Metodología

## Análisis Exploratorio de Datos

En el análisis exploratorio de datos del proyecto de producción de petróleo y gas en Vaca Muerta, en el marco del Plan 4x4 de YPF, se integraron diferentes funciones para analizar la información que contenia el dataset de Producción de pozos no convencional de Secretaría de Energía de la Nación así como se realizaron múltiples visualizaciones para comprender la evolución y el comportamiento de variables clave como producción mensual de petróleo y gas, subtipo de recursos y áreas de yacimiento. Se aplicaron técnicas estadísticas, como describe, y gráficas para detectar tendencias mensuales y anuales, estacionalidades y anomalías, identificando un crecimiento sostenido en la actividad no convencional a partir de 2021. 

## Modelado Supervisado

En el proyecto aplicado a Vaca Muerta, los modelos supervisados se utilizaron para predecir la producción futura de petróleo y gas, por área de yacimiento o permiso de concesión. Se entrenaron algoritmos como regresión lineal, Random Forest, XGBoost y Prophet con datos históricos, permitiendo estimar el comportamiento esperado hasta 2029. Estos modelos ofrecieron métricas de rendimiento satisfactorias y permitieron proyectar distintos escenarios, brindando una herramienta estratégica para evaluar el cumplimiento de las metas del Plan 4x4 y apoyar la toma de decisiones en planificación energética.

## Modelo No Supervisado y Redes Neuronales

En el proyecto 4x4 de producción de petróleo y gas en Vaca Muerta, se aplicaron modelos no supervisados como K-Means, DBSCAN, MeanShift, PCA y GMM para identificar patrones y agrupar áreas con comportamientos similares en producción, sin necesidad de etiquetas previas. Además, se implementaron redes neuronales no supervisadas como los mapas autoorganizados de Kohonen (SOM) y autoencoders para la reducción de dimensionalidad y visualización de relaciones complejas entre variables. Estas técnicas permitieron detectar producciones estratégicas, outliers y posibles segmentos de alto rendimiento, aportando valor al análisis exploratorio y a la planificación de acciones dentro del marco del Plan 4x4.

# Herramientas utilizadas 

Lenguaje: Python 3.10+

Librerías:

Librerías: NumPy, Pandas, Geopandas, Shapely.geometry, Matplotlib, Scikit-learn, SciPy, PyTorch, TensorFlow y Keras

Modelado Supervisado: RandomForestRegressor,SVR, XGBRegressor,GridSearchCV, MultiOutputRegressor, Prophet, train_test_split, mean_absolute_error

Modelado No Supervisado: PCA, Autoencoder, GMM, KMeans, DBSCAN, PCA, MiniSOM

Visualización: matplotlib, seaborn, plotly, contextily, scipy

Otros: jupyter, google colab, GitHub

