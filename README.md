# SIMULADO1-computa-onuvem
Qual a diferença entre nginx:alpine e o contêiner comunicado?
R=nginx a imagem é usada como base para criar o container.
o comunicado é o nome dado do container que esta usando a imagem
O que significa o mapeamento 8090:80?
R= é a porta do host
Qual saída comprova que a página solicitada respondeu?
R= o comando curl

RESPOSTAS DA ATIVIDADE PRATICA DO SIMULADO DE SISTEMAS DISTRIBUIDOS
Qual processo iniciou a conexão?
R=O cliente.py iniciou a conexão, usando cliente.connect(("127.0.0.1", 5005))

Qual processo recebeu PEDIDO-42 e produziu a resposta?
R=O servidor.py recebeu o código por meio de recv(). Depois, criou a resposta: Recebido pelo servidor: PEDIDO-42

Por que o cliente não conseguiria realizar esse teste se o servidor não estivesse em
execução?
R=porque o cliente tenta estabelecer uma conexão TCP com 127.0.0.1 na porta 5005. Se nenhum servidor estiver escutando nessa porta a conexão não será estabelecida e o connect() do cliente apresentará um erro
