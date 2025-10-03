Atividade Assíncrona da Disciplina Administração de Sistemas Abertos

Ataulizar conforme a atividade.

1) Criar um Dockerfile em : C:\Users\Computador\Documents    (Criado)
2) docker build -t nginx_v1 .
   docker image ls (para verificar a criação da imagem)
3) Criar container a paratir da imagem nginx_v1
   docker run -d --name Servidor_Nginx -p 8080:80 nginx_v1
   docker ps (verificar container criado e rodando)
4) Executar o container
   docker container exec -it 769e1320328d bash

