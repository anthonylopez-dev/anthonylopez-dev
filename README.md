# ¡Hola! Soy Anthony López Guerrero 👋

<p align="left">
  <a href="https://linkedin.com/in/anthonylpz" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:anthonyxm15@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

### 🚀 Data Scientist | Especialista en Machine Learning & IA
Ingeniero en Tecnologías de la Información con doble posgrado en **Visual Analytics, Big Data e Inteligencia Artificial**. Me especializo en construir soluciones *end-to-end* robustas, desde la ingesta de datos a gran escala hasta el despliegue de modelos predictivos y arquitecturas de microservicios en producción.

* 📍 Ambato, Ecuador (Disponible para roles remotos internacionales)
* 🛠️ Entorno local: VS Code + Miniforge3 + Python (Git Bash workflow)
* 🧠 Enfocado en optimización de código, explicabilidad de modelos (SHAP) y eficiencia en producción.

---

## 🌟 Proyecto Destacado: TechPulse — Product Intelligence Platform

<p align="left">
  <a href="https://techpulse-intelligence.streamlit.app/" target="_blank"><img src="https://img.shields.io/badge/Live_App-Streamlit-10B981?style=flat-square&logo=streamlit" alt="Streamlit App"></a>
  <a href="https://techpulse-api-xxxr.onrender.com/docs" target="_blank"><img src="https://img.shields.io/badge/API_Docs-FastAPI-06B6D4?style=flat-square&logo=fastapi" alt="FastAPI Docs"></a>
  <a href="https://github.com/anthonylopez-dev/techpulse-product-intelligence"><img src="https://img.shields.io/badge/Repo-GitHub-022C22?style=flat-square&logo=github" alt="GitHub Repo"></a>
</p>

Plataforma bilingüe (ES/EN) de inteligencia de productos digitales que analiza **152,556 productos** lanzados en Product Hunt (2014–2024). Incluye *forecasting* de tendencias, segmentación semántica de mercado y un motor de recomendación híbrido optimizado para entornos con restricciones de memoria.

### 📊 Logros Técnicos & Decisiones de Arquitectura:
* **Despliegue Defensivo (Render Free):** Implementación de fallback mediante **TF-IDF (8000 features)** e índice *lite* de 30k productos para mitigar el límite de 512MB de RAM (evitando errores OOM de PyTorch).
* **Modelado Avanzado:** Segmentación de mercado en 10 clusters (MiniBatchKMeans + reducción de dimensionalidad con UMAP) y *forecasting* robusto mediante Holt-Winters (descartando Prophet por incompatibilidades de dependencias Stan en entornos Windows).
* **Entregables de Negocio:** Pipeline automatizado bilingüe para la generación de reportes ejecutivos en PDF de alta fidelidad utilizando **ReportLab**.

---

## 🛠️ Más Proyectos del Portafolio

### 🩺 01. Riesgo de Diabetes con XGBoost y SHAP
* **Stack:** Python, XGBoost, SHAP, SMOTE, Streamlit, Power BI.
* **Métricas:** **ROC-AUC de 0.8900** y CV ROC-AUC (5-fold) de **0.9383 ± 0.007**.
* **Impacto:** Explicabilidad clínica completa aislando la glucosa como la variable de mayor impacto (SHAP=1.3447).
* 🔗 [Ver Repositorio](https://github.com/anthonylopez-dev/diabetes-prediction-xgboost-shap)

### 📈 02. Mercado Laboral y Pobreza en Ecuador (2007–2024)
* **Stack:** Python, Scikit-learn, Power BI, ReportLab, API Banco Mundial.
* **Modelo:** Regresión Lineal validada mediante **LOOCV** ($R^2=0.903$, MAE=0.717pp).
* **Impacto:** Dashboard interactivo en Power BI (3 páginas) e informe automatizado analizando el impacto del COVID-19 y la brecha rural-urbana.
* 🔗 [Ver Repositorio](https://github.com/anthonylopez-dev/ecuador-empleo-pobreza-analysis)

### 🗺️ 03. Percepción Digital del Turismo (TripAdvisor NLP)
* **Stack:** TextBlob, pysentimiento (BERT), Langdetect, Looker Studio.
* **Modelo:** Clasificador dual ES/EN con **74.4% de precisión global** sobre reseñas de destinos clave de Ecuador.
* 🔗 [Ver Repositorio](https://github.com/anthonylopez-dev/tripadvisor-ecuador-tourism-sentiment)

---

## 🧰 Toolkit Tecnológico

| Área | Tecnologías |
|---|---|
| **Lenguajes & Core** | Python, SQL, Git, Git Bash |
| **Data Science & ML** | SciKit-Learn, XGBoost, UMAP, SMOTE, SHAP, Statsmodels |
| **NLP & Deep Learning** | Sentence Transformers, PySentimiento (BERT), TextBlob |
| **Ingeniería & Deploy** | FastAPI, Streamlit, Render, Streamlit Cloud, Miniforge3 |
| **BI & Visualización** | Power BI, Looker Studio, Plotly, ReportLab (PDF Generation) |

---

## 📊 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=anthonylopez-dev&show_icons=true&theme=tokyonight&count_private=true" alt="Anthony's Stats" height="160">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=anthonylopez-dev&layout=compact&theme=tokyonight&hide=html,css,tex" alt="Top Languages" height="160">
</p>

---
<p align="center">
  <i>"La consistencia en la arquitectura y la claridad en los datos definen el éxito en producción."</i>
</p>
