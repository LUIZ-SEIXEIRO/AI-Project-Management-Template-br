# 🚀 AI-Driven Project Management & Local Infrastructure Hub (LibreChat + Gemini + GSD)

> Um framework de produtividade, governança e infraestrutura local para gestão avançada de projetos utilizando inteligência artificial generativa.

---

## 💡 Sobre o Projeto
Este repositório documenta a implementação de um ambiente de trabalho unificado, seguro e privado para gestão de projetos e automação de fluxos com IA. A solução integra a interface profissional do **LibreChat** rodando via contêineres **Docker (WSL2)** na máquina local, conectada diretamente à API oficial do Google (**Gemini 3 Flash Preview**), combinada à metodologia estruturada de execução de projetos (**GSD**).

O objetivo é resolver o problema de fragmentação de histórico, perda de contexto e dependência de interfaces web genéricas, proporcionando um painel corporativo próprio, privado e de altíssima velocidade.

---

## 🛠️ Arquitetura da Solução
* **Interface Visual:** LibreChat (v0.8.7) com autenticação local segura e histórico persistente.
* **Orquestração:** Docker Compose (MongoDB para persistência de dados + MeiliSearch para indexação e busca).
* **Motor Cognitivo:** Google Gemini API (*gemini-3-flash-preview*), otimizado para raciocínio multimodal, análise técnica e desenvolvimento rápido.
* **Metodologia:** Abordagem GSD (*Get Stuff Done*), focada em escopo controlado, etapas sequenciais e documentação viva (`PROJECT.md` e `ROADMAP.md`).

---

## 📁 Estrutura do Repositório
```text
📁 AI-Project-Management-Template/
│
├── 📁 docs/
│   ├── manual_operacional_librechat.pdf       # Rotina diária, comandos e boas práticas
│   └── manual_replicacao_librechat.pdf      # Guia técnico de instalação do zero (WSL/Docker)
│
├── 📁 templates/
│   ├── PROJECT.md                           # Esqueleto de escopo e visão geral do projeto
│   └── ROADMAP.md                           # Esqueleto de fases e entregas
│
├── .env.example                             # Modelo seguro de variáveis de ambiente
└── README.md                                # Documentação principal do repositório