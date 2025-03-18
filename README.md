# 🔍 Azure Cognitive Search: Implementação e Consulta de Dados com AI

Este repositório é parte do **Desafio #07 do Bootcamp Decola Tech 2025**, fornecendo um guia prático para aplicar técnicas de organização de documentos e realizar pesquisas eficientes com **Azure Cognitive Search**. O processo é dividido em três etapas principais:

1. Ingestão de dados com IA
2. Criação do índice de pesquisa
3. Exploração das funcionalidades de busca

## 📑 Sumário

- [🔍 Azure Cognitive Search: Implementação e Consulta de Dados com AI](#-azure-cognitive-search-implementação-e-consulta-de-dados-com-ai)
  - [📑 Sumário](#-sumário)
  - [🎯 Introdução ao Desafio](#-introdução-ao-desafio)
  - [🛠️ Ferramentas Utilizadas](#️-ferramentas-utilizadas)
  - [▶️ Configuração e Execução](#️-configuração-e-execução)
    - [1. Pré-requisitos](#1-pré-requisitos)
    - [2. Criando o Serviço de Pesquisa](#2-criando-o-serviço-de-pesquisa)
    - [3. Criando uma Conta de Armazenamento](#3-criando-uma-conta-de-armazenamento)
    - [4. Configuração e Importação de Dados](#4-configuração-e-importação-de-dados)
    - [5. Criando e Executando Pesquisas](#5-criando-e-executando-pesquisas)
  - [🚀 Vantagens do AI Search](#-vantagens-do-ai-search)
  - [💡 Aplicações Práticas](#-aplicações-práticas)
  - [📚 Conhecimentos Adquiridos](#-conhecimentos-adquiridos)

---

## 🎯 Introdução ao Desafio

O objetivo deste desafio é explorar a organização de documentos e a construção de pesquisas eficientes utilizando o **Azure Cognitive Search**. Ao final, o usuário terá experiência prática na criação de índices e na exploração de técnicas avançadas de busca, aplicáveis a diversos cenários.

---

## 🛠️ Ferramentas Utilizadas

- **Azure Cognitive Search**
- **Azure Storage Account**
- **API REST/SDK do Azure**

---

## ▶️ Configuração e Execução

### 1. Pré-requisitos

Antes de começar, certifique-se de ter:

- Uma conta ativa no **Microsoft Azure**
- Um serviço **Azure Cognitive Search** criado
- Dados para indexação (JSON, CSV ou Banco de Dados no Azure)
- Conhecimento básico do **Azure Portal e APIs REST/SDK**

### 2. Criando o Serviço de Pesquisa

1. Acesse o **Portal do Azure** e faça login.
2. Pesquise por **Cognitive Search** e clique em **Criar**.
3. Defina as configurações:
   - Nome do Serviço
   - Grupo de Recursos
   - Localização (recomendado: **East US**)
   - Plano de Preço (Free para testes, Standard para produção)
4. Clique em **Revisar + Criar** e finalize a configuração.

### 3. Criando uma Conta de Armazenamento

1. No **Portal do Azure**, pesquise por **Storage Account** e clique em **Criar**.
2. Configure os seguintes parâmetros:
   - Nome da Conta
   - Localização (recomendado: **East US**)
   - Desempenho: **Standard**
   - Redundância: **LRS**
3. Clique em **Examinar + Criar** e finalize a configuração.

### 4. Configuração e Importação de Dados

- Configurar permissões de armazenamento
- Criar um contêiner para os arquivos de dados
- Carregar os dados para indexação
- Importar os dados no Azure Cognitive Search

### 5. Criando e Executando Pesquisas

- No **Gerenciador de Pesquisa**, utilize a ferramenta integrada para testar consultas.
- Insira palavras-chave e analise os resultados no formato **JSON**.

---

## 🚀 Vantagens do AI Search

- **Análise Semântica**: Melhoria na precisão das pesquisas
- **Sugestões Inteligentes**: Autocomplete e recomendações baseadas em IA
- **Relevância Personalizada**: Ajuste do ranking dos resultados
- **Facilidade de Integração**: Compatível com aplicações web e mobile

---

## 💡 Aplicações Práticas

- **E-commerce**: Pesquisa eficiente de produtos
- **Suporte Técnico**: Consulta inteligente em bases de conhecimento
- **Gestão de Documentos**: Indexação e busca avançada
- **Pesquisa Acadêmica**: Mineração de conhecimento em artigos científicos

---

## 📚 Conhecimentos Adquiridos

Durante essa experiência, adquirimos conhecimento sobre:

- Configuração do Azure Cognitive Search
- Indexação e manipulação de dados
- Construção de consultas eficientes
- Aplicação de técnicas de AI Search para otimizar pesquisas

Com este guia, você será capaz de configurar um serviço de pesquisa, criar um repositório de dados e realizar buscas avançadas no **Azure Cognitive Search**. Essa solução pode ser aplicada a diversos cenários, tornando as pesquisas mais inteligentes e precisas!

🚀 **Vamos explorar a IA na indexação e consulta de dados!**
