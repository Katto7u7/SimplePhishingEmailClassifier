# Detección de Correos de Phishing con Redes Neuronales

Este proyecto implementa un pipeline completo de detección de correos electrónicos de tipo **phishing** utilizando técnicas de procesamiento de lenguaje natural (NLP), **TF-IDF** para vectorización de texto y una **red neuronal artificial** construida con Keras implementando **ML** (Machine Learning).

---

##  Contenido del proyecto

- Carga y preprocesamiento de dataset con correos electrónicos
- Limpieza de texto (HTML, puntuación, URLs, emails, stopwords)
- Vectorización del texto con **TF-IDF (Unigramas y Bigramas)**
- Entrenamiento de red neuronal secuencial con **Keras**
- Evaluación del modelo con métricas de clasificación
- Visualización de resultados: precisión, matriz de confusión, nube de palabras, matriz de correlación

---

##  Dataset

El dataset utilizado es un archivo CSV con los campos:

- `body`: contenido del correo electrónico
- `label`: 0 (legítimo) o 1 (phishing)

> NOTA: Asegúrate de tener tu archivo CSV montado en Google Drive (o localmente si ejecutas en otro entorno).

---

## Requisitos

- Python 3.10 (Recomendado)
  o
- Google Colab / Jupyter Notebook
- Bibliotecas:
  - `pandas`, `numpy`
  - `nltk`
  - `sklearn`
  - `tensorflow`
  - `matplotlib`, `seaborn`
  - `bs4` (BeautifulSoup)
  - `wordcloud`

### Instalación de librerías (si no las tienes):

```bash
pip install nltk wordcloud beautifulsoup4 seaborn
