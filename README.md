
# Estoque GPT

Um assistente virtual inteligente para gerenciamento de estoque, utilizando modelos de linguagem GPT para responder perguntas sobre produtos, preços e reposição diretamente de um banco de dados.




## Descrição do Projeto

O `Estoque GPT` é uma aplicação web desenvolvida com `Streamlit`, que integra modelos de linguagem da OpenAI (GPT) para interagir com um banco de dados de estoque em linguagem natural. Ele permite que usuários façam perguntas sobre o inventário, como:

- Quais produtos estão disponíveis?
- Qual o preço de determinado item?
- Há necessidade de reposição de algum produto?
A aplicação utiliza o `LangChain` para estruturar interações com o modelo GPT e o banco de dados, garantindo respostas precisas e úteis.

## Funcionalidades

- Interface amigável desenvolvida com `Streamlit`.
- Suporte a múltiplos modelos GPT (e.g., `gpt-3.5-turbo`, `gpt-4`).
- Consulta a um banco de dados SQLite para informações sobre estoque.
- Respostas formatadas e fáceis de entender, sempre em português.
- Prompt personalizado para garantir respostas relevantes ao contexto.

## Tecnologias Utilizadas

- __Python__: Linguagem principal do projeto.
- __Streamlit__: Framework para construção da interface do usuário.
- __LangChain__: Biblioteca para integração de LLMs e agentes.
- __SQLite__: Banco de dados local para armazenar informações de estoque.
- __OpenAI GPT__: Modelos de linguagem para análise e respostas inteligentes.
- __Decouple__: Gerenciamento de variáveis de ambiente.

