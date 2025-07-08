# Trabajo Final

## 🎯 Objetivo del trabajo

Este trabajo tiene como objetivo explorar y aplicar técnicas de ciencia de datos, desde el preprocesamiento de los datos hasta la evaluación de un modelo de análisis de sentimientos, con el fin de identificar las mejores estrategias para realizar predicciones precisas en el ámbito del análisis de texto.

## 👥 Alumnos participantes

- Natalia Milagros Huamanchumo Arroyo – U20221C602
- Mireya Nicole Sihuincha Schermuly – u20221A963
- Jorge Piero Chipoco Mejía – u202210236
  
## 📄 Descripción del dataset

El dataset utilizado en este trabajo es el **Tweet Sentiment Extraction Dataset**, proporcionado por Kaggle. Contiene publicaciones reales de Twitter con la siguiente información:

- `text`: contenido original del tweet.
- `sentiment`: sentimiento general (positivo, negativo o neutral).
- `selected_text`: fragmento del tweet que expresa el sentimiento (solo en los datos de entrenamiento).
  
## ✅ Conclusiones

A través del desarrollo de este proyecto se concluyó que:

La arquitectura multitarea (clasificación + extracción) resultó efectiva para entender no solo el sentimiento, sino también su causa textual.

El uso de DistilBERT permitió velocidad de inferencia < 50ms, haciéndolo viable para aplicaciones en tiempo real.

El enfoque tiene aplicaciones prácticas en marketing, atención al cliente y monitoreo de reputación online.

Como mejora futura, se podría ajustar el modelo BETO para mejor adaptación al español y ampliar el análisis a otras plataformas.
  
## 📜 Licencia

Este proyecto se desarrolla con fines educativos como parte del curso **CC219 - Aplicaciones de Data Science** de la Universidad.  
El uso del dataset está sujeto a la licencia original publicada por los organizadores de la competencia en Kaggle.  
Todos los modelos y scripts pueden ser reutilizados con fines académicos, mencionando la fuente correspondiente.
