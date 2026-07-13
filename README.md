# 🎬 Análisis de Sentimientos en Reseñas de Películas

Pipeline completo de NLP para clasificar reseñas de películas como positivas o negativas. Se comparan dos representaciones de texto: Bag of Words y TF-IDF, ambas combinadas con Regresión Logística.

## 📊 Dataset
IMDB Dataset — 50.000 reseñas perfectamente balanceadas (25.000 positivas / 25.000 negativas)

## 🔍 Pipeline aplicado
1. Conversión a minúsculas
2. Tokenización
3. Eliminación de stopwords
4. Lematización
5. Representación vectorial (BoW y TF-IDF)
6. Clasificación con Regresión Logística

## 📈 Resultados
- TF-IDF superó a Bag of Words en todas las métricas
- ~90% de accuracy en conjunto de prueba
- Sin evidencia de overfitting

## 💡 Palabras clave identificadas
- **Positivas:** refreshing, subtle, superb, perfectly, surprisingly
- **Negativas:** waste, disappointment, poorly, lacks, disappointing

## 🛠️ Stack
`Python` `pandas` `NLTK` `scikit-learn` `Google Colab`
