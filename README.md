# Healthia Bot

Agente conversacional construido con n8n (railway) + Telegram + Gemini + Supabase.

## Funcionalidades

* Registro de usuarios mediante póliza médica
* Vinculación automática de Telegram ID
* Recomendación de especialidad médica mediante IA
* Estimación de copago y cobertura
* Consulta contextual según plan de seguro asociado

## Stack Tecnológico

* n8n
* Telegram Bot API
* Google Gemini
* Supabase
* Railway

## Flujo

1. Usuario inicia conversación con `/start`
2. Ingresa su póliza médica
3. El sistema vincula su Telegram ID
4. El usuario consulta síntomas
5. La IA recomienda especialidad y cobertura

## Demo

Bot desplegado en Railway.
<img width="1913" height="990" alt="image" src="https://github.com/user-attachments/assets/b54f1f03-2688-4dd4-b879-2d4880a3747a" />

Bot en funcionamiento.
<img width="702" height="1600" alt="image" src="https://github.com/user-attachments/assets/f1fdd2e2-90b5-408a-a0e1-10d489154210" />

## Arquitectura

Telegram → n8n → Supabase → Gemini → Telegram
