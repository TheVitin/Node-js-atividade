# Node-js-atividade
Tutorial

Entrar na pasta onde está o node-env, exemplo "cd node.js/"
Ativar o nodejs-env, exemplo "source ./nodejs-env/bin/activate"
Abrir o nano do arquivo e colar o codigo fornecido, com as alterações pedidas. Exemplo:

var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Vitor Hugo Alves Basso 19/09/2023');
}).listen(8008);

Ativar o arquivo do index, exemplo "node index.js"
Abrir o navegador e pesquisar "localhost:Portausada"
Se aparecer os dados fornecidos está correto
