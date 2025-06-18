Sistema de Búsqueda Booleana de Documentos
Este proyecto implementa un sistema básico de recuperación de información utilizando el Modelo Booleano de Claves para realizar búsquedas en un conjunto de documentos. Permite a los usuarios consultar la información utilizando operadores booleanos como AND, OR y NOT.

Características
Preprocesamiento de Texto: Tokenización, normalización a minúsculas, eliminación de signos de puntuación y stopwords (palabras vacías) usando NLTK.
Índice Invertido: Creación de un índice que mapea cada término a los documentos en los que aparece.
Consultas Booleanas: Soporte para operaciones lógicas AND, OR y NOT en las consultas de usuario.
Documentos de Ejemplo
El sistema opera sobre los siguientes 5 documentos de muestra relacionados con inteligencia artificial y aprendizaje automático:

"doc1": "La inteligencia artificial está revolucionando la tecnología."
"doc2": "El aprendizaje automático es clave en la inteligencia artificial."
"doc3": "Procesamiento del lenguaje natural y redes neuronales."
"doc4": "Las redes neuronales son fundamentales en deep learning."
"doc5": "El futuro de la IA está en el aprendizaje profundo."
Requisitos
Python 3.x
NLTK (Natural Language Toolkit)
