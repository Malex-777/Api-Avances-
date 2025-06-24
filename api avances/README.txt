# API GPT - Asistente Virtual con Flask y OpenRouter

Este proyecto es una API web construida con Flask que utiliza la API de OpenRouter (compatible con OpenAI) para crear un asistente virtual basado en modelos GPT.

## Características

- Interfaz web simple para interactuar con el asistente.
- Comunicación con modelos GPT a través de OpenRouter.
- Manejo seguro de claves API usando variables de entorno.

## Requisitos

- Python 3.8+
- Una clave de API de [OpenRouter](https://openrouter.ai/)
- (Opcional) Entorno virtual recomendado

## Instalación

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/Malex-777/Api-Avances-.git 
   cd tu-repo
   ```

2. **Crea un entorno virtual y actívalo:**
   ```bash
   python -m venv venv
   venv\Scripts\activate   # En Windows
   # source venv/bin/activate  # En Linux/Mac
   ```

3. **Instala las dependencias:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configura tus variables de entorno:**
   - Crea un archivo `.env` en la raíz del proyecto con el siguiente contenido:
     ```
     OPENROUTER_API_KEY=tu_clave_de_api_aqui
     ```

## Uso

1. **Inicia la aplicación:**
   ```bash
   python app.py
   ```

2. **Abre tu navegador en:**  
   [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

3. **Envía mensajes al asistente desde la interfaz web.**

## Estructura del Proyecto

```
api-gpt/
│
├── app.py
├── requirements.txt
├── .env.example
├── .gitignore
├── templates/
│   └── index.html
└── README.md
```

## Notas

- No subas tu archivo `.env` ni compartas tu clave de API.
- Puedes cambiar el modelo GPT en `app.py` según tus necesidades y acceso.

---

Desarrollado con ❤️ usando flask y OpenRouter.
