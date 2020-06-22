# FGR_fenotipos
Este repositorio corresponde al trabajo de final de máster de Ciencia de Datos, mediante el cual se intentará construir un modelo y localizar los fenotipos que, con un cierto grado de confianza, logren predecir cuándo un neonato nacerá por debajo del percentil 10 de crecimiento, y su grado de restricción asociado.


# Introducción
El objetivo principal de este proyecto es detectar patrones en los datos cedidos por un centro de investigación médica de prestigio, con el fin de averiguar si la relación entre los ellos es determinante o explicativa de la Restricción de Crecimiento Intra-Uterino (FGR) [1], una de las causas más significativas de morbilidad neonatal, para tratar de predecir de manera temprana esta restricción.

# Resultado deseado
El resultado que se desea obtener en este trabajo es predecir con un cierto grado de confianza si existe relación significativa entre la información de los fenotipos de los neonatos diagnosticados con FGR, con el fin de intentar pronosticar la posible ocurrencia futura o de detectarlos precozmente.

# Documentación
Los productos que se obtendrán al final del desarrollo del proyecto son los siguientes:
-   FGR_fenotipos.part1 y FGR_fenotipos.part2: Al descomprimir estos ficheros se obtendrá el fichero "FGR_fenotipos.ipynb"que contiene  el código del desarrollo del proyecto en lenguaje Python.

-	Memoria.docx: Documento de extensión .docx que describe el desarrollo del proyecto.

-	Anexo.docx: Documento de extensión .docx que complementa el apartado 2 “Estado del arte o análisis de mercado” de la memoria.

-	Memoria.pdf: Documento de extensión .pdf que describe el desarrollo del proyecto.

-	Anexo.pdf: Documento de extensión .pdf que complementa el apartado 2 “Estado del arte o análisis de mercado” de la memoria.

-	Imagenes: Carpeta que contiene los diagramas de los árboles XGBoost que, debido a su gran tamaño, se han agregado como enlace después de cada ejecución de técnica XGBoost para que se pueda hacer un zoom y ver al completo su contenido.

-	Modelos: Carpeta que contiene los modelos construidos a lo largo del proyecto. Concretamente se construye los siguientes 3 modelos:
    - Modelo 1: Predicción prematura de nacimiento de neonato con o sin FGR y grado de FGR: Unión de los modelos xgboost_model1 y xgboost_model2.
    - Modelo 2: Predicción no prematura de nacimiento de neonato con o sin FGR y grado de FGR (Prueba Ecografía Doppler): Unión de los modelos xgboost_model_vars_periodico1 y xgboost_model_vars_periodico2.
    - Modelo 3: Predicción prematura de nacimiento de neonato con o sin FGR y grado de FGR (Prueba ecografía fetal tercer trimestre): Unión de los modelos xgboost_model_vars_periodico_3trim2_1 y xgboost_model_vars_periodico_3trim2_2.
