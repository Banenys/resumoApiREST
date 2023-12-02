# resumoApiREST



# Api REST e RESTFul


	Uma API REST (Interface de Programação de Aplicações em Transferência de Estado Representacional) é um conjunto de princípios arquitetônicos para o
 	desenvolvimento de serviços da web. Ele utiliza o protocolo HTTP para comunicação e é baseado em conceitos como recursos, Identificadores Uniformes
	de Recursos (URI), representação e manipulação de estado.


## Diferenças entre REST e RESTFul


	REST (Transferência de Estado Representacional) é uma arquitetura de comunicação que define um conjunto de princípiospara a criação de serviços web.
	Ele usa métodos HTTP e é baseado em conceitos como recursos, URIs (Uniform Resource Identifiers), representações e ações em recursos. REST não é uma
	implementação específica, mas um conjunto de instruções.
	RESTful refere-se à implementação desses princípios, na prática. Uma API é considerada RESTful quando segue os princípios e práticas recomendadas 
	definidos pelo REST. Isso inclui o uso de URIs adequados para identificar recursos, escolher os métodos HTTP corretos para executar operações de
	recursos (GET, POST, PUT, DELETE, etc.) e manipular adequadamente os códigos de status HTTP.
	

	- REST: Esta é uma arquitetura de comunicação que define os princípios para a criação de serviços web, mas não especifica a implementação detalhada.   
	- RESTful: refere-se à implementação prática destes princípios, seguindo os princípios REST.   
	- REST: Pode ser mais teórico, abrangendo conceitos e princípios básicos. 
	- RESTful: envolve a aplicação prática destes conceitos em uma API específica, garantindo conformidade com os princípios REST.  

	Resumindo, a diferença fundamental entre REST e RESTful está na implementação real. REST é um conjunto de princípios, enquanto RESTful representa a
	aplicação desses princípios na criação de serviços web. Ambas são plataformas para desenvolvimento de APIs eficientes e escaláveis.
    

## HTTP verbs


    Os verbos HTTP são métodos que indicam a ação solicitada em um recurso. Alguns dos verbos mais comuns são:   

	- GET: Obtenha dados de um recurso;  
	- POST: Crie um novo recurso;
	- PUT: Atualiza um recurso existente;
	- DELETE: Exclua um recurso;
	- CONNECT: Estabelece um túnel de conexão para um servidor com base em um recurso;
	- OPTIONS: Utilizado para definir as opções para comunicação com um determinado recurso;
	- TRACE: Realiza um teste de loopback para verificar se uma mensagem consegue chegar a um determinado destino;
	- PATCH: Aplica modificações parciais em um determinado recurso;
	- HEAD: Similar ao Get, mas não requer um corpo da resposta.


## HTTP Status Code


    Código de status HTTP retornado como parte da resposta a uma solicitação HTTP, indicando o resultado da operação. Alguns códigos comuns incluem:   
	- 200 OK: Solicitação bem-sucedida;
	- 201 Criado (CREATED): a solicitação foi bem-sucedida e o novo recurso foi criado;
	- 400 Bad Request: A solicitação está malformada ou não pode ser processada;
	- 404 Not Found: O recurso solicitado não foi encontrado;
	- 500 Erro interno do servidor: indica um erro do servidor.


    ---


    Autor do resumo: Rhauana Flórido Lima - 01508064

