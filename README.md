## RAG usando langchain, base de datos vectorial Chroma, sentence-embeddings de HuggingFace y API de Gemini:
*  Se lee el archivo de evaluación: contiene preguntas sobre cada archivo con las respuestas correctas.
*  Se leen 5 transcripciones de cada podcast, se splitean y se guardan en la base de datos Chroma, usando un modelo de sentence-embedding.
*  Se crea el RAG: al hacer una pregunta, se consulta a la base de datos, se crea un prompt y se obtiene una respuesta de Gemini.