<div align="center">
  <img height="30" alt="Mongdb" src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white">
</div>

<h3 align="center">MongodbAtlas</h3>

<p align="center">
Tutorial de como criar uma conta no MongodbAtlas
  <br>
</p>

<h3>Informações gerais</h3>

![GitHub estrelas](https://img.shields.io/github/stars/gabrielogregorio/MongodbAtlas)
![GitHub last commit](https://img.shields.io/github/last-commit/gabrielogregorio/MongodbAtlas?style=flat-square)
![GitHub contributors](https://img.shields.io/github/contributors/gabrielogregorio/MongodbAtlas)
![GitHub language count](https://img.shields.io/github/languages/count/gabrielogregorio/MongodbAtlas)
![GitHub repo size](https://img.shields.io/github/repo-size/gabrielogregorio/MongodbAtlas)

### Introdução

### Como criar uma conexão no Mongodb Atlas
#### Crie uma conta
1. Acesse o site do mongodb cloud e crie uma conta grátis [https://www.mongodb.com/cloud/atlas]( https://www.mongodb.com/cloud/atlas)
2. Crie um projeto, defina um nome e os usuários que terão acesso!
3. Crie uma database!
4. Escolha o plano free
5. Escolha um servidor, e salve o nome do Cluster.
6. O Cluster demorará uns 5 minutos para ser criado. Crie um usuário para acessar o cluster.
7. Defina um usuário e uma senha segura para o seu projeto.
8. Volte na opção DATABASES e espere o cluster ser criado por completo, depois clique em connect.
9. Clique no botão "Add Your Current IP Address", depois em "Add IP Address", ele serve para pegar o seu endereço de IP e permite que somente ele tenha acesso ao banco de dados.
10. Com tudo configurado, clique em Escolher o método de conexão e escolha conectar a sua aplicação.
11. Escolha a opção nodeJs e copie a String de conexão do mongodb.
12. Configure a sua String de conexão.
13. Agora adicione a String no arquivo ".env"
