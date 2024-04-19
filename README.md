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

Para ejecutar el ejercicio debe configurar la variable de entorno os.environ["OPENAI_API_KEY"] = "", o en su defecto reemplazar las comillas por el valor de la llave que obtenga para OpenAI API Key.

![firstProgram.png](Imagenes%2FfirstProgram.png)

#### Segundo ejercicio

Escriba un RAG simple utilizando una base de datos vectorial en memoria. El desarollo de este corresponde al archivo llmMemoryDatabase.py.

Para ejecutar el ejercicio debe configurar la variable de entorno os.environ["OPENAI_API_KEY"] = "", o en su defecto reemplazar las comillas por el valor de la llave que obtenga para OpenAI API Key.

![inmemoryDataBase.png](Imagenes%2FinmemoryDataBase.png)

#### Tercer ejercicio

Escriba un RAG usando Pinecone.El desarrollo de este corresponde al archivo llMRAG.py.

Para ejecutar el ejercicio debe configurar las variables de entorno os.environ["OPENAI_API_KEY"] = "" y os.environ["PINECONE_API_KEY"] = "", o en su defecto reemplazar las comillas por el valor de la llave que obtenga para OpenAI API Key y el que obtenga en pinecone para PINECONE_API_KEY.

El programa carga documentos de un archivo de texto, que en este caso corresponde a Conocimiento.txt, los procesa, calcula embeddings utilizando un modelo de lenguaje de OpenAI, y luego los indexa en Pinecone para permitir búsquedas de documentos similares basadas en una consulta de búsqueda, que es "What is a gene therapy".

Al ejecutar el programa encontrara la siguiente salida,que incluirá la lista de índices disponibles, así como el contenido del documento que coincide con la consulta de búsqueda

![llmRag1.png](Imagenes%2FllmRag1.png)

![llmRag2.png](Imagenes%2FllmRag2.png)

En las siguientes imagenes puede ver los fragmentos extraidos del archivo Conocimiento.txt

![pinecone1.png](Imagenes%2Fpinecone1.png)

![pinecone2.png](Imagenes%2Fpinecone2.png)

![pinecone3.png](Imagenes%2Fpinecone3.png)

## Construido Con

* [Python 3.12](https://www.python.org/) - Python es un lenguaje de programación de alto nivel. Ampliamente utilizado en las aplicaciones web, el desarrollo de software, la ciencia de datos y el machine learning (ML)
* [PyCharm](https://www.jetbrains.com/es-es/pycharm/) - PyCharm es un entorno de desarrollo integrado utilizado en programación informática, concretamente para el lenguaje de programación Python.
* [Pip](https://pypi.org/project/pip/) - Pip es un sistema de gestión de paquetes utilizado para instalar y administrar paquetes de software escritos en Python
* [OpenAI API Key](https://openai.com/blog/openai-api) - La API de OpenAI (Interfaz de programación de aplicaciones) es una herramienta que permite a los desarrolladores integrar y utilizar los modelos de lenguaje avanzados desarrollados por OpenAI en sus propias aplicaciones, servicios o productos.
* [Pinecone API Key](https://www.pinecone.io/) - Pinecone actúa como una base de datos vectorial, almacenando y recuperando vectores de alta dimensión de manera eficiente. La Pinecone API Key es una clave de autenticación que se utiliza para interactuar con los servicios proporcionados por Pinecone.

## Autor

* **Laura García** - [lgar000](https://github.com/lgar000)
