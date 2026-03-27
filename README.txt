PROYECTO: Modelos de Machine Learning y Deep Learning (LLM + CNN Transfer Learning)

DESCRIPCIÓN:
Este repositorio contiene dos notebooks desarrollados en Google Colab:

1. LLM.ipynb
   - Uso de modelos de lenguaje (LLM)
   - Integración con APIs (OpenAI / HuggingFace)
   - Procesamiento de texto y generación de respuestas

2. CNN+TRANSFERLEARNING-INFILTRACION_PULMONAR.ipynb
   - Modelo de Deep Learning con CNN
   - Uso de Transfer Learning con TensorFlow/Keras
   - Clasificación de imágenes médicas (infiltración pulmonar)

REQUISITOS:
- Ejecutar en Google Colab (recomendado)
- Python 3.10+
- GPU opcional pero recomendada para el modelo CNN

CONFIGURACIÓN EN GOOGLE COLAB:

1. Subir los notebooks a Google Drive o Colab
2. Instalar dependencias:
   !pip install -r requirements.txt

3. Configurar variables de entorno si aplica:
   - API KEY de OpenAI
   - Token de HuggingFace

4. Montar Google Drive (si se usan datos externos):
   from google.colab import drive
   drive.mount('/content/drive')

LIBRERÍAS PRINCIPALES:
- TensorFlow / Keras
- Scikit-learn
- Pandas / NumPy
- Matplotlib / Seaborn
- HuggingFace / OpenAI
- Gradio (interfaces)

NOTAS:
- Algunos notebooks usan archivos externos (dataset o modelos), asegúrate de tener las rutas correctas.
- Para entrenamiento CNN, activar GPU en:
  Entorno de ejecución > Cambiar tipo de entorno > GPU

AUTOR:
Proyecto orientado a aprendizaje de Machine Learning aplicado.