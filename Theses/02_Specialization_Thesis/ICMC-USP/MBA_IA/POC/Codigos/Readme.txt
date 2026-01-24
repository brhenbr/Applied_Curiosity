> Criar o direotrio:
/content/drive/MyDrive/00_Projeto_ICMC

> Colocar os arquivos no diretorio:
plataforma_dados_metadados_catalogo.csv
plataforma_dados_modelo_logico.csv
modelo_logico_ontologia_empresa.ttl


> O banco de dados relacional sera criado no mesmo diretorio

> Banco de Grafo:
Utilizado Neo4J Aura DB. É preciso criar uma conta e uma instacia (free funciona já)
https://neo4j.com/product/auradb

> Hugging face
Necessidade de criar conta para que alguns modelos rodem

> LLM
Utilizado gemini do google

> Tokens necessarios
GOOGLE_API_KEY => Token API do google studio
HF_TOKEN => Token de autenticacao hugging face
NEO4J_PASSWORD => Informacoes obtidas na criacao da instancia AuraDB
NEO4J_URI  => Informacoes obtidas na criacao da instancia AuraDB
NEO4J_USERNAME  => Informacoes obtidas na criacao da instancia AuraDB

================================================================================================
>>> Atualizacao de codigo: V2 para V3 <<<

A atualizacao foi necessaria devido a mudancas relevantes nos frameworks Langchain e Pydantic, por isso a criacao da V3. A V2 sera mantida no repo para fins didaticos e de rastreamento.

Devido aos ajustes, alguns casos de teste tiveram seu resultado apresentado de maneira diferente do demonstrado na pesquisa, nao necessariamente no resultado final esperado em si, mas 
sim na forma (o que faz todo sentido, uma vez que trabalhamos com processos estocasticos e nao deterministicos).

Mesmo assim, o prototipo segue sendo interessante para analise e exploracao na busca de novas descobertas.

Have fun!!!


