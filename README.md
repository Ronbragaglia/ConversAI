# 🤖 ConversAI: Chatbot Inteligente com GPT

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com)
[![Flask](https://img.shields.io/badge/Flask-Web%20App-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![crewAI](https://img.shields.io/badge/crewAI-Multi--Agent-FF4B4B?style=for-the-badge&logoColor=white)](https://crewai.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

> Chatbot inteligente construído do zero com Python e crewAI: agentes autônomos que colaboram para gerar respostas contextuais via GPT, servidos por uma interface web com Flask.

---

## ✨ Funcionalidades

- 🧠 **Agentes IA autônomos** com crewAI: múltiplos agentes colaborando em pipeline
- 💬 **Respostas contextuais** via API da OpenAI (GPT-3.5 / GPT-4)
- 🌐 **Interface web** com Flask exposta via ngrok (acesso externo instantâneo)
- 🔄 **Histórico de conversa** mantido entre turnos
- ⚡ Setup simples: rodando em minutos

---

## 🛠️ Tech Stack

| Camada | Tecnologia |
|--------|-----------|
| IA / Agentes | OpenAI GPT + crewAI |
| Backend | Python 3.x + Flask |
| Exposição | Flask-Ngrok |
| Interface | HTML/CSS embutido no Flask |

---

## 🚀 Como Usar

### 1. Clone o repositório
```bash
git clone https://github.com/Ronbragaglia/ConversAI.git
cd ConversAI
```

### 2. Instale as dependências
```bash
pip install openai flask flask-ngrok crewai
```

### 3. Configure sua chave de API
No arquivo principal, substitua:
```python
openai.api_key = "SUA_CHAVE_DE_API"
```

### 4. Execute
```bash
python app.py
```

O ngrok vai gerar um link público: acesse no navegador e comece a conversar.

---

## 🏗️ Arquitetura

```
Usuário → Formulário HTML (Flask)
             ↓
         Agente crewAI
             ↓
         OpenAI GPT API
             ↓
         Resposta exibida na interface
```

---

## 📁 Estrutura

```
ConversAI/
├── app.py          # Aplicação Flask + lógica dos agentes
├── requirements.txt
└── README.md
```

---

## 🤝 Contribuições

Pull requests são bem-vindos! Abra uma issue para discutir melhorias antes.

---

<div align="center">
  <sub>Feito com 🤖 por <a href="https://github.com/Ronbragaglia">Rone Bragaglia</a> · ML Engineer & Fundador <a href="https://cobrancaauto.com.br">CobrançaAuto</a></sub>
</div>
