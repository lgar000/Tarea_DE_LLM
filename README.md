# Tarea: Large Language Model

En este taller se implementarán una serie de ejercicios en los que se va a hacer uso de LangChain, Pinecone y OpenAI, para poner en práctica  habilidades del procesamiento de lenguaje natural, tales como utilizar modelos de lenguaje para responder preguntas mediante la búsqueda en documentos o dividir los documentos en fragmentos. 

### Prerrequisitos

- Python
- Pip
- Entorno virtual de python
- OpenAI API Key
- Pinecone API Key
- Git

### Instalación

Para hacer uso del proyecto clone el repositorio usando el siguiente comando

```
git clone https://github.com/lgar000/Tarea_DE_LLM.git
```

Ubiquese en la carpeta en la cual clono el repositorio. A continuación
acceda a la carpeta principal del proyecto mediante el siguiente comando

```
cd Tarea_DE_LLM
```
Cree un nuevo entorno virtual de Python

```
python -m venv venv
```

Active el entorno virtual 

```
venv\Scripts\activate
```

Instale los paquetes o dependencias de Python, necesarias para el funcionamiento del proyecto

```
pip install -r requirements.txt
```
Para ejecutar los respectivos programas haga uso de los siguentes comandos

```
py firtsProgram.py
```

```
py llmMemoryDatabase.py
```

```
py llMRAG.py
```

### Funcionamiento

#### Primer ejercicio

Usando Python, escriba un programa para enviar mensajes a Chatgpt y recuperar respuestas. El desarrollo de este corresponde al archivo firstProgram.py.

![firstProgram.png](Imagenes%2FfirstProgram.png)

#### Segundo ejercicio

Escriba un RAG simple utilizando una base de datos vectorial en memoria. El desarollo de este corresponde al archivo llmMemoryDatabase.py.

![inmemoryDataBase.png](Imagenes%2FinmemoryDataBase.png)

#### Tercer ejercicio

Escriba un RAG usando Pinecone.El desarrollo de este corresponde al archivo llMRAG.py.

![llmRag1.png](Imagenes%2FllmRag1.png)

![llmRag2.png](Imagenes%2FllmRag2.png)

![pinecone1.png](Imagenes%2Fpinecone1.png)

![pinecone2.png](Imagenes%2Fpinecone2.png)

![pinecone3.png](Imagenes%2Fpinecone3.png)

## Construido Con

* [Python 3.12](https://www.python.org/) - Python es un lenguaje de programación de alto nivel. Ampliamente utilizado en las aplicaciones web, el desarrollo de software, la ciencia de datos y el machine learning (ML)
* [PyCharm](https://www.jetbrains.com/es-es/pycharm/) - PyCharm es un entorno de desarrollo integrado utilizado en programación informática, concretamente para el lenguaje de programación Python.
* [Pip](https://pypi.org/project/pip/) - Pip es un sistema de gestión de paquetes utilizado para instalar y administrar paquetes de software escritos en Python
* [OpenAI API Key](https://openai.com/blog/openai-api) - La API de OpenAI (Interfaz de programación de aplicaciones) es una herramienta que permite a los desarrolladores integrar y utilizar los modelos de lenguaje avanzados desarrollados por OpenAI en sus propias aplicaciones, servicios o productos.
* [Pinecone API Key](https://www.pinecone.io/) - Entorno de desarrollo integrado para el desarrollo de programas informáticos

## Autor

* **Laura García** - [lgar000](https://github.com/lgar000)