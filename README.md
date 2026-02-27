# Teste para desenvolvimento android


### O Desafio

Desenvolver um aplicativo que liste os clientes retornados no serviço indicado.


### Começando

Utilize o seguinte [endpoint](https://raw.githubusercontent.com/newloran2/testApp2026/main/service.json) para o carregamento inicial da listagem clientes.
O app deve fornecer uma webview que carregue o profileLink do usuário e uma forma de mostrar em tela cheia o profileImage do usuário.
Tanto o carregamento do profileImage quanto o profileLink devem ser exibidos em uma tela separado do app. 

Os campos obrigatórios são *name*, *status*, *email*, e *id* 

O app deve manter uma conexão persistente ao websocket wss://ws.postman-echo.com/raw e mandar um hello e esperar a resposta a cada 30 segundos.


### Itens obrigatórios

- Tratamento para problemas de rede, com possibilidade de recarregar o serviço
- Tratamento de falha de carregamento de imagens com uso de imagem ghost em caso de falha
- Deve mostrar todos os campos disponíveis de cada usuário na listagem 
- Responsividade
- se preocupe com a bateria do usuário


### arquitetura

- Use a arquitetura que achar mais relevante


### Itens desejáveis

- Testes unitários
- Criatividade


### Finalizando

Ao finalizar seu teste nos envio o link do projeto no github no email indicado.
