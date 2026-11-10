# TPE Fundamentos de la Ciencia de Datos (2026)
---
## Grupo 8
## Maidana; Segonds; Gutheim

> Este trabajo contiene el desarrollo de un análisis exploratorio, limpieza de los datos, reducción de dimensionalidad y test de hipótesis sobre el dataset: "Global Food & Nutrition Database 2026 – Health Scores & Allergens".

---
## Organizacion del notebook
El analisis esta estructurado en secciones.
- **Secciones 1 a 4** 
 Limpieza y preprocesamiento (descarga del dataset y eliminacion de columnas intrascendentes), análisis de nulos,   filtrado de valores irreales/imposibles y detección de outliers mediante (con IQR).   
 - **Secciones 5 a 8**
  Análisis Exploratorio (EDA) y PCA: Matrices de dispersión para entender las relaciones bivariadas entre nutrientes. Tambien se realizo una reducción de dimensionalidad mediante un Análisis de Componentes Principales (PCA) con datos estandarizados.   
- **Secciones 9 a 14**
 Pruebas de Hipótesis Estadísticas: Tests de normalidad (shapiro) y pruebas paramétricas/no paramétricas. Hipótesis univariadas (9, 12), bivariada (10, 13) y multivariadas (11, 14).

---
## Pasos para comenzar
1. Clonar este repositorio:
   ```bash
   git clone https://github.com/lucianagutheim-sudo/TPE_FundamentosCD_Grupo8.git
    ```
[Enlace al repositorio](https://github.com/lucianagutheim-sudo/TPE_FundamentosCD_Grupo8)

2. Entrar al directorio del proyecto:
   ```bash
   cd TPE_FundamentosCD_Grupo8
   ```
3. Crear un entono virtual y activarlo:
    - en Windows:
        ```bash
        python -m venv venv_tpe
        venv_tpe\Scripts\activate
        ```
    - en Linux/Mac:
        ```bash
        python3 -m venv venv_tpe
        source venv_tpe/bin/activate
        ```
4. Instalar las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
5. Abrir y ejecutar el notebook:
    ```bash
    jupyter notebook TPE_Fundamentos_grupo8.ipynb
    ```
(Se incluye el archivo food_dataset.csv con los datos, pero tambien incluye la descarga automática en caso de no encontrarse localmente)

---
## Requerimientos
Esta implementado con **Python3** en un notebook de Jupyter. Utiliza las siguientes dependencias:
- `jupyter`
- `notebook`
- `ipykernel`
- `pandas`
- `numpy`
- `openpyxl`
- `wget`
- `matplotlib`
- `scikit-learn`
- `scipy`
- `statsmodels`
*El archivo requirements.txt contiene las librerias e instalaciones necesarias.*
