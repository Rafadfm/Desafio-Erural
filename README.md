# Desafio-Erural
Projeto para criação de uma sala para assistir vídeos em grupo
Como estou iniciando na prática da codificaçã eu fiz um projeto simples em html css e JavaScript onde criei duas paginas html, uma para criação de uma sala e outra para assistir e pesquisar videos do you tube, criei até uma API para buscar alguns dados mas não conseguir em tempo hábil fazer a integração das paginas html para a API. Funcionaria da seguinte maneira:
1. Criaria uma página HTML, com um campo para carregar um vídeo. Botar pra inserir um link pro vídeo ,colocaria um campo para inserir o "room-name" para o vídeo.
2. Enviaria esse link para a API, e na API simplesmente salvaria esse link e o "room-name" em um objeto javascript.
3. Criaria um outro endpoint na API para buscar vídeos pelo room-name, tipo: GET /video/:room-name 
4. Criaria uma página HTML para a sala. A página precisaria também do parâmetro "room-name" na URL, tipo: http://localhost:3000/video/roomsale 
5. Ao entrar nessa página, o site faria uma requisição à API, busca o link do vídeo, e colocaria na tela.
