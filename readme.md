# Uso LangChain junto a OpenIAChat, para consultas y respuestas, Consulta a Google y Wikipedia
## Herramienta:
En este ejemplo a través del prompt y de preguntas de lenguaje natural, se le puede pedir al modelo que respondan a interrogantes consultando Google Search y Wikipedia. 
* Se ha usado la API de OpenAI junto a LangChain y el modelo "gpt-3.5-turbo-16k".
* Para dar más precisión a los resultados se ha utilizado un agente de OpenAI lo que nos permite poder hacer preguntas en un lenguaje mas natural y con respuestas mas precisas.
* Se ha tomado como ejemplo la empresa VHNGROUP.
## Uso:
* Se debe contar con Jupyther notebok o Google Colab, para poder ejecutar de forma dinamica el archivo "Agentes_LangChain.ipynb".
* Se debe contar con una cuenta de OpenAI y crear en ella un proyecto y crear una contraseña de API, usar la variable "OPENAI_API_KEY".
* Se debe contar con una cuenta de Google y crear las credenciales de API  de CSE_ID, pueden encontrar mas información en la siguiente URL: [Documentación](https://python.langchain.com/v0.2/docs/integrations/tools/google_search/)
* Se se utiliza dotenv se debe crear un archivo .env y crear la variable OPENAI_API_KEY donde se establezca la clave de la API de OpenAI, GOOGLE_CSE_ID y GOOGLE_API_KEY para el caso de Google.