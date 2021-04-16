# websocket
Apresentação prática do protocolo websocket
Conexão web de time line longo

É um protocolo de comunicação Full Duples baseado no protocolo TCP.
Possibilita conexões longas entre cliente e servidor.
Torna os servidores não pasivos.
A única relação entre ele e o protocolo HTTP é o handshake.
Baseado na comunicação pela porta 80 o que é útil para evitar firewalls de conteúdo diferente de web.
Comunica o server-side com o client-side através de javascript.
	O lado servidor pode estar usando qualquer linguagem de programação ou via biblioteca a comunicação via websocket.

index.html

id="inbox" exibe as mensagens

chat.js => implementa a aplicação do chat

chatdemo.py => espera a solicitação no servidor e envia as mensagens para todos que estão conectados no socket
