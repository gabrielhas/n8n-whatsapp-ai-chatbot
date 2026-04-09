# 🤖 WhatsApp AI Chatbot com n8n

Projeto de automação de atendimento utilizando IA, integrando WhatsApp, processamento de linguagem natural e persistência de dados.

## 🚀 Funcionalidades

- Recebimento de mensagens via webhook
- Filtro inteligente (evita loops, grupos e mensagens inválidas)
- Processamento com IA (respostas naturais e contextuais)
- Memória de conversa por sessão
- Persistência de contatos em Google Sheets
- Resposta automática via API

## 🧠 Arquitetura

Fluxo principal:

Webhook → Validação → Normalização → Persistência → IA → Resposta

## 🛠️ Tecnologias

- n8n (orquestração de workflow)
- API WhatsApp (Periskope)
- Groq (modelo de linguagem)
- Google Sheets (armazenamento)

## 🔒 Segurança

- Uso de variáveis de ambiente para credenciais
- Tokens e dados sensíveis anonimizados

## 📂 Estrutura

- `/workflow` → JSON do n8n
- `/docs` → arquitetura e imagens
- `/video` → demonstração

## 📈 Possíveis melhorias

- Banco de dados (PostgreSQL / MongoDB)
- Deploy em cloud (Docker)
- Integração com CRM
- RAG (contexto personalizado)

## 🎥 Demonstração

<img width="1650" height="680" alt="Workflow_n8n-Whatsapp-chatbot" src="https://github.com/user-attachments/assets/cf3e711f-6bba-45bf-acd8-e2bfd22c2cd3" />

## 📬 Contato

Aberto a oportunidades e colaborações.
