---
title: "RAG Multi-Agente para Conhecimento Organizacional"
date: 2025-07-01
description: "Coautor de artigo científico focado em agentes de IA para processamento de documentos extensos, publicado no XIX WESAAC."
tags: ["Python", "LangGraph", "ChromaDB", "Llama3", "IA Generativa"]
showDate: true
---

Sistemas de busca tradicionais muitas vezes falham em extrair informações precisas de documentos corporativos longos. Este artigo propõe uma arquitetura <abbr title="Retrieval-Augmented Generation">RAG</abbr> multi-agente para resolver esse problema.

---

### Implementação
- <kbd>Orquestração</kbd>: **LangGraph** + **LangChain** foi utilizado para gerenciar o fluxo de trabalho e a comunicação entre agentes especializados;
- <kbd>Embeddings</kbd>: Implementação de banco de dados vetorial com **ChromaDB** e modelos **MistralAI**;
- <kbd>LLM</kbd>: Uso do modelo **Llama3** com regras internas para mitigar alucinações e garantir a relevância das respostas.

---

Este 
<a href="https://sol.sbc.org.br/index.php/wesaac/article/view/37548" target="_blank" rel="noopener noreferrer">artigo</a>
foi escrito em conjunto com <a href="https://www.linkedin.com/in/guimoretti/" target="_blank" rel="noopener noreferrer">Guilherme Moretti</a> e <a href="https://www.linkedin.com/in/kalmax-sousa/" target="_blank" rel="noopener noreferrer">Kalmax Sousa</a>
para o XIX <a href="https://sol.sbc.org.br/index.php/wesaac" target="_blank" rel="noopener noreferrer">WESAAC</a>;

