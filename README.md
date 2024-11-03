## RAG usando langchain, base de datos vectorial Chroma, embedding de HuggingFace y una API de Gemini (LLM de Google):
*  Se lee el archivo de evaluación: contiene preguntas sobre cada archivo con las respuestas correctas.
*  Se leen 5 transcripciones de cada podcast, se splitean y se guardan en la base de datos Chroma, usando un embedding de HuggingFace.
*  Se crea una función para consultar a Gemini haciendo uso del RAG.

#### Se chequeó que funciona bastante bien para varias de las preguntas de evaluación.
#### Como trabajo a futuro, se podría hacer una estadística de performance del RAG.
