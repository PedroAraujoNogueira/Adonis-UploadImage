# API para analisar imagens.  
### Como executar o projeto: 
-> Digite no terminal 'npm install' para instalar todas as dependências.   
-> Digite 'node ace configure @adonisjs/lucid' e escolha o SQLite e in terminal logo em seguida.  
-> Digite 'node ace migration:run' para rodar as migrations.  
-> adicione as seguintes envs em .env:  
PORT=3333  
HOST=0.0.0.0  
NODE_ENV=development  
APP_KEY=nOQvGdzME5IpdqOlYIQHSrhkWSgwc4AA  
DRIVE_DISK=local  
-> Digite no terminal 'node ace serve --watch' para subir o serviço.     

### Descrição do projeto:  
O projeto é uma pequena aplicação feita em Adonis com o objetivo de conhecer melhor o framework. Para isso criei, 
com o Adonis, um banco com duas tabelas que tem o relacionamento entre si de 1:n. Pude entender como o Adonis trabalha
com os models e as migrations e como trabalhar com relacionamento de tabelas usando o Adonis. Também trabalhei com
upload de imagens onde pude entender como o Adonis recebe e manipula files.  

### Requisitos de software e bibliotecas:    
-> Node e NPM.    
-> Adonis.        

### Links úteis:   
Link do vídeo tutorial: https://www.youtube.com/watch?v=y8XfJJYhXPE&t=2466s     
Documentação do Adonis V5: https://docs.adonisjs.com/guides/config