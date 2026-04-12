# MBA em IA e Big Data - ICMC-USP 2025

# 🤖 Text-to-SQL Assistant (Graph-Augmented GenAI)

[Português](#br-versao-em-portugues) | [English](#en-english-version)

---

### <a name="br-versao-em-portugues"></a>🇧🇷 Versão em Português

Esta pasta contém a materialização da pesquisa realizada para conclusão do curso MBA em IA e Big Data do ICMC-USP 2025. O projeto explora a convergência entre **Ciência da Informação (CI)** e **Processamento de Linguagem Natural (PLN)** através de uma solução de Text-to-Code.

## 🏗️ Estrutura do Repositório

* **`/figuras`**: Diagramas técnicos da fundamentação teórica e desenho da solução.
* **`/POC` (Prova de Conceito)**:
    * **`/Codigos`**: Scripts Python (V2 e V3) com a implementação do orquestrador.
    * **`/dados`**: Modelos lógicos, ontologias (.ttl) e metadados para reprodução.

## 🧪 Metodologia de Validação
Para garantir a acurácia científica, o desempenho do modelo foi validado através do script:
* **`PoC_Golden_Queries.ipynb`**: Contém consultas SQL "padrão ouro" geradas manualmente para comparação com os resultados do LLM, validando os casos de uso da pesquisa.

## 🛠️ A Solução Proposta
A arquitetura utiliza **Orquestração GenAI** enriquecida por grafos:
1.  **Ingestão**: Metadados e Ontologias são armazenados no **Neo4j**.
2.  **Contexto**: O orquestrador recupera relações do grafo para enriquecer o prompt.
3.  **Geração**: O **Google Gemini** converte a linguagem natural em SQL.
4.  **Execução**: Consulta realizada em banco SQLite.

## 🚀 Como Executar
1.  **Ambiente**: Desenvolvido para **Google Colab**.
2.  **Configuração**: Mover arquivos de `/dados` para `/content/drive/MyDrive/00_Projeto_ICMC`.
3.  **Serviços**: Requer instância **Neo4j AuraDB** (Free) e conta no **Hugging Face**.
4.  **Tokens (.env)**: `GOOGLE_API_KEY`, `HF_TOKEN`, `NEO4J_URI`, `NEO4J_USERNAME`, `NEO4J_PASSWORD`.

---
### <a name="en-english-version"></a>EN English Version

This repository contains the final research project for the MBA in AI and Big Data at ICMC-USP 2025. The project investigates the intersection of **Information Science (IS)** and **Natural Language Processing (NLP)** through a Text-to-Code solution.

## 🏗️ Repository Structure

* **`/figuras`**: Technical diagrams of the theoretical framework and solution design.
* **`/POC` (Proof of Concept)**:
    * **`/Codigos`**: Python scripts (V2 and V3) containing the orchestrator implementation.
    * **`/dados`**: Logical models, ontologies (.ttl), and metadata for reproduction.

## 🧪 Validation Methodology
To ensure scientific accuracy, the model's performance was validated using:
* **`PoC_Golden_Queries.ipynb`**: Contains manually curated "Golden" SQL queries used to benchmark the LLM's output against the research use cases.

## 🛠️ Proposed Solution
The architecture employs **Graph-Augmented GenAI Orchestration**:
1.  **Ingestion**: Metadata and Ontologies are stored in **Neo4j**.
2.  **Context**: The orchestrator retrieves graph relationships to enrich the prompt.
3.  **Generation**: **Google Gemini** converts natural language into SQL code.
4.  **Execution**: The query is executed against a SQLite database.

## 🚀 How to Run
1.  **Environment**: Designed for **Google Colab**.
2.  **Setup**: Move files from `/dados` to `/content/drive/MyDrive/00_Projeto_ICMC`.
3.  **Services**: Requires a **Neo4j AuraDB** instance (Free tier) and a **Hugging Face** account.
4.  **Required Tokens**: `GOOGLE_API_KEY`, `HF_TOKEN`, `NEO4J_URI`, `NEO4J_USERNAME`, `NEO4J_PASSWORD`.

---
**Have fun!!!**
