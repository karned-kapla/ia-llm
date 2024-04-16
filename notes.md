# notes de dev

Ollama permet de faire des tests en local et de lancer facilement un Docker avec un LLM.

LangChain permet d'intégrer un LLM dans un script python

## références
https://hub.docker.com/r/ollama/ollama

https://python.langchain.com/docs/get_started/introduction/

## LLM en local avec Ollama
https://github.com/ollama/ollama/blob/main/docs/api.md

https://python.langchain.com/docs/guides/development/local_llms/

https://python.langchain.com/docs/integrations/providers/openllm/
https://python.langchain.com/docs/integrations/llms/openllm/

## WIP
lancement avec uvicorn app:app --reload dans le dossier ia-llm

pas concluant pour le moment ! il y a de la latence au lancement, le modèle n'est pas téléchargé par défaut ce qui provoquera son téléchargement à chaque lancement du Docker

tester

pip install "openllm[mistral]"