# 🤖 Prisma Assistant – Agente IA com LangGraph + Gemma  

Este projeto é um **Agente IA** que utiliza **LangGraph** e **LLMs open-source (Gemma)** para responder dúvidas com base em documentos carregados em PDF.  

O fluxo segue 3 etapas principais:  
1. **Triagem da pergunta** → Classifica em categorias como metodologia, ética, etc.  
2. **RAG (Retrieval-Augmented Generation)** → Busca respostas nos PDFs carregados.  
3. **Decisão do fluxo** → Encaminha para *Auto Resolver*, *Pedir Info* ou *Finalizar*.  

---

## 🗂 Estrutura do projeto  

```markdown
📂 prisma-assistant/
 ┣ 📂 docs/              # PDFs de referência do PRISMA
 ┣ 📜 notebook.ipynb     # Código principal do agente IA
 ┣ 📜 requirements.txt   # Dependências do projeto
 ┣ 📜 README.md          # Este arquivo
```
## 🧪 Exemplo de uso

Pergunta:

Qual a diferença entre pesquisa empírica e explícita?


Resposta da IA:

A diferença é a seguinte:

- Pesquisa empírica implícita: os dados e evidências existem, mas a metodologia não é completamente apresentada.  
- Pesquisa empírica explícita: o método, instrumentos e dados estão claramente descritos.  

Em resumo, a pesquisa empírica explícita é mais detalhada e transparente em relação à metodologia utilizada.

## 🌐 Próximos passos

Adicionar uma interface web em Streamlit (app.py), para que qualquer usuário consiga interagir com o agente sem precisar abrir o notebook.

Melhorar os PDFs de contexto (ex.: adicionar explicações sobre o PRISMA, autores, objetivos, etc.).

Explorar métricas de avaliação das respostas.
