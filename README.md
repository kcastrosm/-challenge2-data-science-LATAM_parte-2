## Challenge TelecomX
Este es un desafío de la formación en Data Science del programa ONE de Alura LATAM y Oracle y consiste en analizar el comportamiento de churn (evasión de clientes) en la empresa de telecomunicaciones TelecomX, con en fin de identificar los factores que influyen en este comportamiento y proponer estrategias que permitan reducir la tasa de churn.
Para esto, se ha utilizado un conjunto de datos que contiene información detallada sobre los clientes, incluyendo datos demográficos, servicios contratados y detalles de la cuenta.  
## Librerías utilizadas
*   **pandas**: manipulación y análisis de datos estructurados.
*   **numpy**: operaciones numéricas.
*   **matplotlib.pyplot**: visualización de datos.
*   **seaborn**:  creación de gráficos estadísticos.
## Conjunto de datos
El conjunto de datos utilizado para este análisis, "TelecomX_Data.json", fue obtenido de `https://raw.githubusercontent.com/alura-cursos/challenge2-data-science-LATAM/main/TelecomX_Data.json`. Originalmente, el archivo JSON contenía una estructura anidada que representaba 7267 registros de clientes con 6 columnas principales. Tras un proceso de normalización, se transformó en un DataFrame tabular con 7256 filas y 21 columnas, donde cada fila representa un cliente y las columnas contienen sus atributos detallados.
## Limpieza y tratamiento de datos
La fase de limpieza y tratamiento de datos incluyó los siguientes pasos clave:
*   **Extracción y Normalización**
*   **Verificación de Valores Nulos**: 
*   **Identificación de Filas Duplicadas**
*   **Tratamiento de Valores Atípicos en 'Churn'**
## Análisis exploratorio de datos:
El análisis exploratorio de datos se centró en comprender la distribución de las variables y su relación con la variable objetivo 'Churn' (evasión de clientes). En particular, se analizaron las siguientes variables:
*   **Distribución general de Churn
*   **Análisis de Variables Categóricas vs. Churn**
*   **Género (`customer_gender`)**:
*   **Tipo de Contrato (`account_Contract`)**
*   **Método de Pago (`account_PaymentMethod`)**
*   **Servicio de Internet (`internet_InternetService`)**
*   **Análisis de Variables Numéricas vs. Churn**
*   **Antigüedad del Cliente (`customer_tenure`)**
*   **Cargos Mensuales (`account_Charges_Monthly`)**
*   **Cargos Totales (`account_Charges_Total`)**


