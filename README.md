# 📘 Análisis de Sesgos en Modelos de Lenguaje Generativo

Este Trabajo de Fin de Grado analiza comparativamente cómo distintos modelos de lenguaje de gran escala (LLMs) generan biografías, con el objetivo de detectar patrones de sesgo (ideológico, de género, de tono y objetividad) en sus respuestas. Se han consultado los modelos ChatGPT, Gemini, DeepSeek, Phi y LLaMA a través de la plataforma OpenRouter, y las respuestas han sido procesadas con herramientas de análisis textual en Python.

El trabajo se estructura en varias fases, cada una implementada en su propio bloque de código o capítulo del análisis.

---

## 🧭 Estructura del proyecto

1. **📋 Generación de listas de personajes**
   - Consultas parametrizadas por país, siglo, ámbito y género.
   - Selección cruzada de personajes más mencionados por varios modelos.

2. **📝 Generación de biografías**
   - Biografías de 300 palabras por personaje y por modelo.
   - Recogida automatizada y almacenamiento en formato CSV.

3. **📊 Extracción de métricas**
   - Aplicación de VADER, TextBlob y TF-IDF.
   - Cálculo de polaridad, objetividad, palabras clave, y participación.

4. **📈 Interpretación de resultados**
   - Análisis por país y ámbito.
   - Estudio de sesgo de género y tonalidad.
   - Evaluación comparativa de modelos (objetividad, estilo, sesgos).

---

## 🛠️ Tecnologías utilizadas

- Python (3.9+)
- Jupyter Notebook
- OpenRouter API
- VADER
- TextBlob
- TF-IDF (scikit-learn)
- pandas, matplotlib, seaborn, plotly, networkx

---

## 📂 Contenido del repositorio

- `personajes/` → Scripts y datos de generación de personajes.
- `biografias/` → Generación de biografías por modelo.
- `metricas/` → Cálculo y análisis de sentimientos y objetividad.
- `visualizaciones/` → Gráficos y figuras del estudio.
- `datos/` → CSVs procesados.
- `TFG.pdf` → Documento final del trabajo.

---

## 📄 Licencia

Este proyecto se distribuye con fines académicos. Uso libre con atribución.

---

## 🙋‍♂️ Autor

**Alejandro Coman Venceslá**  
Universidad de Granada  
Doble Grado en Ingeniería Informática y ADE  
