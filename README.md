# meeting-doc-generator
Este proyecto “Generador de Documentos de Reunión” responde a la necesidad de transformar grabaciones post‑reunión en documentos estructurados y ofrecer un chat inteligente para consultas específicas.

# Entornos de desarrollo
poetry init   # responde a prompts, añade FastAPI, uvicorn, azure-sdk
poetry add fastapi uvicorn azure-storage-blob azure-ai-speech pydantic sqlalchemy
poetry shell  # entra en el entorno


npm init -y
npm install react react-dom axios
opcional: create-react-app o Vite para scaffold rápido
