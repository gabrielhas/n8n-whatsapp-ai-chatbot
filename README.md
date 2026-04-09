# 🤖 WhatsApp AI Chatbot com n8n

Automação de atendimento via WhatsApp com IA, construída no n8n, integrando APIs, processamento de linguagem natural e persistência de dados com foco em aplicações reais.

---

## 📸 Demonstração do Workflow

<p align="center">
  <img width="800" alt="Workflow n8n WhatsApp Chatbot" src="https://github.com/user-attachments/assets/cf3e711f-6bba-45bf-acd8-e2bfd22c2cd3" />
</p>

---

## 💡 Sobre o projeto

Projeto desenvolvido com foco em aprendizado prático de automação, integração de sistemas e uso de IA em cenários reais.

---

## 🚀 Funcionalidades

- Recebimento de mensagens via webhook  
- Filtro inteligente (evita loops, grupos e mensagens inválidas)  
- Processamento com IA (respostas naturais e contextuais)  
- Memória de conversa por sessão  
- Persistência de contatos em Google Sheets  
- Resposta automática via API  

---

## 🧠 Arquitetura

Pipeline do fluxo:

Webhook → Validação → Normalização → Persistência → Processamento com IA → Resposta  

---

## ⚙️ Como executar

1. Importe o arquivo JSON localizado em `/workflow` no n8n  
2. Configure as credenciais necessárias:
   - URL do Webhook  
   - API_KEY (API de WhatsApp)  
   - Credenciais do Google Sheets  
   - Credenciais do modelo de IA (ex: Groq)  
3. Configure as variáveis de ambiente no n8n  
4. Ative o workflow  

---

## 🛠️ Tecnologias

- n8n (orquestração de workflows)  
- API de WhatsApp (Periskope)  
- Groq (modelo de linguagem)  
- Google Sheets (armazenamento)  

---

## 🔒 Segurança

- Uso de variáveis de ambiente para credenciais  
- Tokens e dados sensíveis anonimizados  

---

## 📂 Estrutura

- `/workflow` → JSON do n8n  
- `/docs` → imagens e arquitetura  

---

## 📚 Aprendizados

- Estruturação de workflows automatizados  
- Integração entre APIs REST  
- Tratamento e validação de dados em fluxo  
- Controle de execução para evitar loops  
- Uso prático de IA em automações reais  

---

## 📈 Possíveis melhorias

- Integração com banco de dados (PostgreSQL / MongoDB)  
- Containerização com Docker  
- Deploy em ambiente cloud  
- Integração com CRM  
- Implementação de RAG para contexto avançado  

---

## 📬 Contato

LinkedIn: https://www.linkedin.com/in/gabriel-henrique-alves-silva-b08628206/

Aberto a oportunidades como desenvolvedor júnior nas áreas de programação e automação.
