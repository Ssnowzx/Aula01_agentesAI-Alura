# Sistema de Triagem Automática de Mensagens de Clientes

Este projeto implementa um sistema básico de triagem automática para mensagens de clientes de um e-commerce, utilizando um modelo de linguagem grande (LLM) do Google Gemini através da biblioteca Langchain. O objetivo é classificar as mensagens dos clientes em categorias como `AUTO_RESOLVER`, `PEDIR_INFO` ou `ABRIR_CHAMADO`, auxiliando na otimização do atendimento.

## Funcionalidades

*   Classificação automática de mensagens de clientes.
*   Definição de níveis de urgência para cada mensagem.
*   Identificação de informações faltantes para a resolução do problema.
*   Utilização do modelo Google Gemini para a inteligência de classificação.
*   Estruturação da saída da classificação em formato JSON.

## Tecnologias Utilizadas

*   Python
*   Google Colab
*   Langchain
*   Google Generative AI (Gemini)
*   Pydantic

## Como Configurar e Executar

1.  **Abra o notebook no Google Colab:** Faça o upload do arquivo `.ipynb` para o Google Colab.
2.  **Instale as dependências:** Execute a célula que instala as bibliotecas necessárias:
