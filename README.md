# FundacaoCERTI

- Introdução
	Essa coleção contem casos de teste que executam cenários validando o serviço implementado que converte números decimais em sua versão por extenso.

- Tipos de execução
	1. Postman
	2. Linha de comando via newman

1. Executando pelo Postman
	- Pre requisitos: ter o Postman instalado;
	- Instruções para execução:
		a) Realizar o download da collection `FundacaoCERTI.postman_collection.json`;
		b) Acionar opção "Import" no Psotman;
		c) Selecionar a collection `FundacaoCERTI.postman_collection.json` e importar;
		d) Acionar opção "Runner" no Psotman;
		e) Selecionar a collection "FundacaoCERTI";
		f) Acionar opção "Run FundacaoCERTI";
		g) Será executado os casos de teste e no fim será apresentado o relatório com os resultados.

2. Executando via Newman
	- Pre requisitos: ter o Node.js instaldo;
	- Instruções para execução:
		a) Realizar o download da collection `FundacaoCERTI.postman_collection.json`;
		b) Executar o comando: `$ npm install -g newman`;
		c) Executar o comando: `$ newman run FundacaoCERTI.postman_collection.json`;
		d)  Será executado os casos de teste e no fim será apresentado o relatório com os resultados;