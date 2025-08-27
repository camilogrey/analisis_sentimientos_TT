# 🗣️ Análisis de Sentimientos de Opiniones Ciudadanas con NLP y Machine Learning

## 🚀 Descripción
Este proyecto aplica **Procesamiento de Lenguaje Natural (NLP)** y **Machine Learning** para analizar reseñas de Google sobre el **Ayuntamiento de Móstoles (Madrid, España)**.  
El objetivo es evaluar la evolución de la percepción ciudadana, identificar temas recurrentes y generar **insights accionables** para mejorar la gestión pública.  

---

## 🎯 Objetivos del Proyecto
- Estimar el **sentimiento predominante** de las reseñas (positivo, neutral o negativo).  
- Analizar la **evolución temporal** de la percepción ciudadana hacia la alcaldía.  
- Identificar los **temas clave** más mencionados (infraestructura, servicios, limpieza, transporte, etc.).  
- Proveer **recomendaciones** basadas en la voz ciudadana.  

---

## 🗂️ Dataset
- **Fuente:** Reseñas públicas de Google Maps sobre el Ayuntamiento de Móstoles.  
- **Variables clave:** texto de la reseña, fecha, puntuación, autor (anonimizado).  
- **Obtención de datos:**  
  - Web Scraping con Python (BeautifulSoup / Selenium).  
  - Posible uso de APIs o herramientas de extracción.  

---

## 🛠️ Tecnologías y Herramientas
- **Lenguaje:** Python 3.x  
- **Librerías NLP:** NLTK, spaCy, scikit-learn, TextBlob / HuggingFace Transformers  
- **Visualización:** matplotlib, seaborn, Plotly  
- **Preprocesamiento:** pandas, regex, scikit-learn (TF-IDF, CountVectorizer)  
- **Modelos ML:** regresión logística, Naive Bayes, o modelos BERT para clasificación de sentimiento  

---

## 📈 Metodología
1. **Extracción de datos:** Web Scraping / API de Google Maps.  
2. **Preprocesamiento:**  
   - Limpieza de duplicados y spam.  
   - Normalización de texto (minúsculas, stopwords, stemming/lemmatización).  
   - Clasificación cronológica de reseñas.  
3. **Análisis de Sentimientos:**  
   - Modelos supervisados / lexicón basado.  
   - Clasificación en positivo, neutral y negativo.  
4. **Análisis Temático:**  
   - Topic Modeling (LDA / BERTopic).  
   - Identificación de temas clave (infraestructura, servicios, transporte, etc.).  
5. **Visualización:**  
   - Tendencias temporales de sentimiento.  
   - Distribución de temas y subtemas.  
6. **Insights y Recomendaciones:**  
   - Diagnóstico de satisfacción ciudadana.  
   - Propuestas de mejora para la gestión municipal.  

---

## 📊 Resultados esperados
- Identificación de los principales **drivers de satisfacción/insatisfacción**.  
- Visualizaciones sobre la evolución de la percepción ciudadana en el tiempo.  
- Insights prácticos para mejorar áreas críticas como limpieza, seguridad o transporte.  

---

## 💡 Posibles Usos
- Herramienta de **inteligencia ciudadana** para gobiernos locales.  
- Soporte en **toma de decisiones de políticas públicas**.  
- Análisis de reputación online de instituciones públicas.  

---

## 📌 Próximos pasos
- Ampliar el análisis a otros municipios de Madrid.  
- Implementar dashboards interactivos (Power BI / Tableau / Streamlit).  
- Automatizar la recolección periódica de nuevas reseñas.  

---

## 👤 Autor
**[Camilo García Rey]**  
- LinkedIn: https://www.linkedin.com/in/camilo-garcia-rey/  
- GitHub Portfolio: https://github.com/camilogrey?tab=repositories 
