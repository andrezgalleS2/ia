# LLM Pruebas
Repositorio de trabjo con los modelos de lenguaje largo utilizando ollama

# 1. Instalacion
Como primer paso descargamos [ollama] 
(https://ollama.com/) de su pagina web y ejecutamos el comando

````bash
curl -fsSL https://ollama.com/install.sh | sh
````

## 2. Ejecutar el servidor
Ejecutar el servidor de API REST de ollama con el siguiente comando

```` ollama serve ````

## 3. Descargar un modelo
Descarga un modelo 
```` llama pull tinyllama  ````

## 4.corre un post
````
curl -X POST http://localhost:11434/api/generate -d '{
  "model": "tinyllama",
  "prompt": "Why is the sky blue?"
}'
````
