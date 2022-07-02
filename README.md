<h1 align="center">
  <img alt="home" title="#home" src="./logotipo.png" width="200" height="200" />
</h1>

![Badge](https://img.shields.io/static/v1?label=licence&message=MIT&color=green&style=for-the-badge) ![Badge](https://img.shields.io/static/v1?label=PHP&message=language&color=purple&style=for-the-badge&logo=PHP) ![Badge](https://img.shields.io/static/v1?label=laravel&message=framework&color=darkred&style=for-the-badge&logo=LARAVEL) ![Badge](https://img.shields.io/static/v1?label=build&message=passing&color=green&style=for-the-badge)

## 💻 Descrição 

<p align="justify">Projeto desenvolvido aliado ao Trabalho de Conclusão do Curso Superior em Ciência da Computação pela Universidade Regional do Noroeste Gaúcho (Unijuí). Fundamentalmente, foi desenvolvido um estudo a respeito da Lei Geral de Proteção de Dados, retratando todos os seus artigos de uma forma mais acessível, no que tange a compreensão.</p>
<p align="justify">No passo complementar foi definido um guia de adequação da LGPD para instuíções em geral. Com base nessas informações, foi realizada a análise e planejamento para desenvolvimento de um web site, afim de expor os presentes dados a maior diversidade possível de pessoas. O site comportava ainda um fórum, onde a finalidade era contribuir como um recurso para construção de conteúdo e extensão da comunidade sobre a LGPD.</p>

> Status do Projeto: Concluido :heavy_check_mark:

## ⚙️ Funcionalidades

- [x] Cadastro de usuário, com definição de perfis de acesso
- [x] Cadastro, listagem e exibição de notícias
- [x] Cadastro e exibição de passos para adequação LGPD
- [x] Cadastro e exibição da LGPD comentada
- [x] Cadastro e listagem de Links Úteis
- [x] Estrtura de Fórum, com tópicos abertos, fechados e fixos, além da possibilidade de adição de comentários aos mesmos  


## ✨ Resultado

Seguem imagens que retratam o resultado do desenvolvimento do projeto, representado pelo Web Site.
<h1 align="center">
  <img alt="home" title="#home" src="./Fotos Site/home.png" width="170" height="320" />
  <img alt="home" title="#home" src="./Fotos Site/cadastro_edicao_usuario.png" width="230" height="320" />
  <img alt="home" title="#home" src="./Fotos Site/lista_noticias.png" width="240" height="320" />
  <img alt="home" title="#home" src="./Fotos Site/exibicao_noticia.png" width="210" height="320" />
  <img alt="home" title="#home" src="./Fotos Site/setor_servico.png" width="170" height="320" />
  <img alt="home" title="#home" src="./Fotos Site/forum.png" width="240" height="320" />
  <img alt="home" title="#home" src="./Fotos Site/topico_fixo.png" width="200" height="320" />
  <img alt="home" title="#home" src="./Fotos Site/lista_topicos_abertos.png" width="230" height="320" />
  <img alt="home" title="#home" src="./Fotos Site/comentarios.png" width="260" height="320" />
  <img alt="home" title="#home" src="./Fotos Site/etapas_implantacao.png" width="270" height="320" />
  <img alt="home" title="#home" src="./Fotos Site/links_uteis.png" width="290" height="320" />
</h1>

## 🛠 Tecnologias Utilizadas

[![Logo do Flutter](lib/img/flutter.jpg)](https://flutter.dev/)

* [MySql](https://www.mysql.com/)
* [PHP](https://www.php.net/) 
* HTML
* [CSS](https://www.w3schools.com/css/)
* [JavaScript](https://www.javascript.com/)
* [Laravel](https://laravel.com/)

## 📁 Acesso ao Projeto

O acesso ao código fonte do projeto pode ser realizado no Google Drive, através do [Link](https://drive.google.com/drive/folders/1_rUtRSPO23tSlZjn12oBN7N36Mnt6jvm?usp=sharing), mediante o download do projeto, ou clonando o mesmo via git.

## 🚀 Como executar o projeto

Este projeto é divido em três partes:
1. Para executar o projeto, faz necessário instalar ferramentas como Apache e PHP, de forma que algumas ferramentas indicadas são o XAMPP para Windows e WAMP, para linux;
2. Com estas duas ferramentas instaladas, a segunda etapa é baixar o projeto no link acima do Drive, e adicionar o projeto nas pasta de Execução do Apache.
3. Realizar a criação da base de Dados no gerenciador do MySql.
4. Em seguida, faz-se necessário realizar a instalação do Laravel e suas bibliotecas. O processo de instalação pode ser encontrado no site do [Laravel](https://laravel.com/docs/9.x).
5. Logo após será necessário executar o comando ```bash php artisan migrate ```, para que as tabelas do banco sejam criadas, assim como alguns registros padrão pré-definidos.
6. Por fim, executar o comando ```bash php artisan serve ```, para que o servidor apache seja utilizado na inicialização da página localmente.

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

Feito por Eduardo Mariano Dolovitsch 👋🏽 [Entre em contato!](https://www.linkedin.com/in/eduardo-dolovitsch/)
