# agenda_node

![node](https://user-images.githubusercontent.com/50559406/210902989-ccf2b339-c3b2-47e1-a24d-9e17cf520953.jpg)


banco de dados criado através do PRISMA, criar banco no Postgre de nome "agenda".

modificar o arquivo .env no projeto com dados de seu DB

modificar os campos PASSWORD para a senha do seu DB e a PORTA

DATABASE_URL="postgresql://postgres:PASSAWORD@localhost:PORTA/agenda?schema=public"

comando a criar a tabela através do PRISMA: yarn prisma migrate dev
