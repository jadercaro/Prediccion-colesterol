# Descripción del problema
El conjunto de datos de enfermedades cardíacas es una colección que aborda el diagnóstico de enfermedades cardíacas mediante el análisis de varios atributos médicos. Recopilado de cuatro instituciones médicas distintas, este conjunto de datos contiene información de pacientes de diversas ubicaciones, incluidos Cleveland, Budapest, Long Beach (California) y Zurich (Suiza). Con un total de 76 atributos, se ha utilizado una selección de 14 de ellos en investigaciones anteriores. El objetivo principal de estas investigaciones ha sido predecir la el colesterol sérico en mg/dl. Es importante destacar que, aunque se han realizado estudios previos con este conjunto de datos, la mayoría de ellos se han centrado en la base de datos de Cleveland.

![image](https://github.com/jadercaro/Prediccion-colesterol/assets/96452959/854e1c87-30c8-4811-a67b-e79506dcce2e)

# Variables 
### Variable objetivo
Colesterol (chol), el colesterol normalmente puede variar entre 100 mg/dl y 189 mg/dl 

### Variables predictoras 
| Atributo   | Descripción                                                                                   |
|------------|-----------------------------------------------------------------------------------------------|
| **Age**        | Edad del paciente en años.                                                                   |
| **Sex**        | Sexo del paciente. 1 = masculino, 0 = femenino.                                             |
| **CP**         | Tipo de dolor en el pecho.                                                                   |
|            | - Valor 1: Angina típica.                                                                    |
|            | - Valor 2: Angina atípica.                                                                   |
|            | - Valor 3: Dolor no anginal.                                                                 |
|            | - Valor 4: Asintomático.                                                                     |
| **Trestbps**   | Presión arterial en reposo en mm Hg al ingreso al hospital.                                  |
| **FBS**        | Nivel de azúcar en sangre en ayunas. 1 = verdadero, 0 = falso.                               |
| **Restecg**    | Resultados electrocardiográficos en reposo.                                                  |
|            | - Valor 0: Normal.                                                                           |
|            | - Valor 1: Con anormalidad en la onda ST-T.                                                 |
|            | - Valor 2: Probable o definitiva hipertrofia ventricular izquierda.                          |
| **Thalach**    | Frecuencia cardíaca máxima alcanzada.                                                        |
| **Exang**      | Angina inducida por ejercicio. 1 = sí, 0 = no.                                               |
| **Oldpeak**    | Depresión del segmento ST inducida por el ejercicio relativa al reposo.                       |
| **Slope**      | La pendiente del segmento ST durante el ejercicio.                                            |
|            | - Valor 1: Ascendente.                                                                       |
|            | - Valor 2: Plano.                                                                            |
|            | - Valor 3: Descendente.                                                                     |
| **CA**         | Número de vasos principales (0-3) coloreados por fluoroscopía.                                |
| **Thal**       | Resultados de la prueba de thalium.                                                          |
|            | - Valor 3: Normal.                                                                           |
|            | - Valor 6: Defecto fijo.                                                                     |
|            | - Valor 7: Defecto reversible.                                                               |
| **Num**        | Diagnóstico de enfermedad cardíaca (estado angiográfico).                                     |
|            | - Valor 0: Menos del 50% de estrechamiento del diámetro en cualquier vaso importante.         |
|            | - Valor 1: Más del 50% de estrechamiento del diámetro en cualquier vaso importante.           |


# Relación entre variables númericas-númericas
## Matriz de dispersión
![image](https://github.com/jadercaro/Prediccion-colesterol/assets/96452959/02157996-23dd-47b5-b508-d7efe92257e0)
## Mapa de calor 
![image](https://github.com/jadercaro/Prediccion-colesterol/assets/96452959/0974a2d5-257b-4533-9b09-78a68fc68bc7)

# Relación entre variables númericas-categóricas
![image](https://github.com/jadercaro/Prediccion-colesterol/assets/96452959/82358ade-6f4e-47f1-a90a-9f7f980d31b7)


# Modelos
|Modelo               |   Paramétros          |Resultado              |
|---------------------|-----------------------|-----------------------|
|Regresión lineal     |tasa aprendizaje = 0.6 y grado = 1   |RECM:       47.63|
|K-Vecinos cercanos   |vecinos = 18           |RECM:       58.25|
|Ventana de Parzen    |H = 1.5                             |RECM:                          52.44|
||||




