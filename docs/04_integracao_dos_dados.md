# Item 2 — Integração dos Dados na Dadosfera

## Fonte de Dados
Os dados utilizados neste projeto são provenientes de uma planilha
publicada publicamente no Google Sheets, contendo informações de
desempenho e produtividade de funcionários.

A planilha foi disponibilizada como fonte pública para fins de
integração e ingestão na plataforma Dadosfera.

## Tipo e Formato
- Tipo de fonte: Arquivo tabular
- Origem: Google Sheets
- Formato lógico: CSV
- Estrutura: dados estruturados

## Granularidade
- 1 registro por funcionário
- Não se trata de dado transacional ou temporal

## Estratégia de Ingestão
Os dados serão ingeridos inicialmente na camada RAW da Dadosfera,
sem aplicação de transformações ou tratamentos, preservando o
conteúdo conforme disponibilizado na fonte.

Embora o dataset já apresente padronização de colunas e métricas
calculadas, ele será tratado como RAW no contexto da plataforma,
com eventuais validações e transformações ocorrendo em etapas
posteriores do projeto.

## Objetivo da Integração
Disponibilizar os dados na plataforma Dadosfera como base para:
- Catalogação
- Validações de qualidade
- Modelagem de dados
- Análises e visualizações
