# FundacaoCERTI
## Introdução
Essa coleção contem casos de teste que executam cenários validando o serviço implementado que converte números decimais em sua versão por extenso.

## Tipos de execução
1. Postman
2. Linha de comando via newman

### Executando pelo Postman
#### Pre requisitos
- **ter o Postman instalado**;
#### Instruções para execução:
1. Realizar o download da collection `FundacaoCERTI.postman_collection.json`;
2. Acionar opção "Import" no Psotman;
3. Selecionar a collection `FundacaoCERTI.postman_collection.json` e importar;
4. Acionar opção "Runner" no Psotman;
5. Selecionar a collection "FundacaoCERTI";
6. Acionar opção "Run FundacaoCERTI";
7. Será executado os casos de teste e no fim será apresentado o relatório com os resultados.
### Executando via Newman
#### Pre requisitos
- **ter o Node.js instalado**;
#### Instruções para execução:
1. Realizar o download da collection `FundacaoCERTI.postman_collection.json`;
2. Executar o comando: `$ npm install -g newman`;
3. Executar o comando: `$ newman run FundacaoCERTI.postman_collection.json`;
4. Será executado os casos de teste e no fim será apresentado o relatório com os resultados;