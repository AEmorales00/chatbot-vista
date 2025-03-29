# 🤖 Chatbot del Simposio de Tecnología

Este proyecto es una implementación sencilla de un chatbot web informativo para un simposio de tecnología. El chatbot responde preguntas frecuentes sobre el evento, como horarios, ubicación, costos, expositores y temas a tratar.

---

## 🛠 Tecnologías utilizadas

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Dialogflow Messenger](https://cloud.google.com/dialogflow/es/docs/integrations/dialogflow-messenger)
- HTML5, CSS3

---

## 🚀 Cómo ejecutar el proyecto

### 1. Clona este repositorio o descarga los archivos

```bash
git clone https://github.com/tu_usuario/chatbot-simposio.git
cd chatbot-simposio
```
2. Instala las dependencias
```bash
npm install
3. Ejecuta el servidor
node server.js
```

4. Abre el navegador
```bash
Visita http://localhost:3000 para ver el chatbot funcionando.
```
📦 Estructura del proyecto
```bash
chatbot-simposio/
├── public/
│   └── index.html      # Página principal con el chatbot
├── server.js           # Servidor básico con Express
├── package.json
└── README.md           # Este archivo
```
💬 ¿Qué hace el chatbot?

El chatbot responde preguntas como:

¿Cuál es el horario del evento?
¿Dónde se realizará el simposio?
¿Cuánto cuesta la inscripción?
¿Incluye certificado?
¿Cuáles son los temas a tratar?
¿Hasta cuándo me puedo inscribir?

🔗 Integración con Dialogflow

El chatbot está integrado con Dialogflow Messenger usando el siguiente fragmento:
```bash
<df-messenger
  intent="WELCOME"
  chat-title="ChatbotSimposio"
  agent-id="98036ea4-9e44-42f2-b2bb-7e509e2ce33b"
  language-code="es"
></df-messenger>
<script src="https://www.gstatic.com/dialogflow-console/fast/messenger/bootstrap.js?v=1"></script>
```
✨ Créditos

Proyecto desarrollado por Alberto Enrique Morales Velasquez
Estudiante de Ingenieria en Sistemas
Universidad Mariano Galvez

📬 Contacto

📧 albertoenriquem98@gmail.com
📍 San Marcos, Guatemala
