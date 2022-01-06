# emailSender

1. Para executar o projeto vá na pasta raiz e digite o comando **docker-compose up -d --scale worker=3**
2. Para simular envio de e-mail acessar **localhost:80**
3. Para acompanhar logs do servidor **docker-compose logs -f -t**
4. Para verificar se houve sucesso na inserção do e-mail no banco de dados **docker-compose exec db psql -U postgres -d email_sender -c 'select * from emails'**
