<h1 align="center">Visitantes</h1>

<p align="center">
 <a href="#sobre">Sobre</a> &nbsp;|&nbsp;
 <a href="#porque">Por Que</a> &nbsp;|&nbsp;
 <a href="#tecnologias">Tecnologias</a> &nbsp;|&nbsp;
 <a href="#funcionalidades">Funcionalidades</a> &nbsp;|&nbsp;
 <a href="#autor">Autor</a> &nbsp;|&nbsp;
 <a href="#license">Licença</a>
</p>

<h6 align="center"> 
	Se você quiser visualizar as imagens do aplicativo, clique <a href="github/images/README.md">aqui</a>.
</h6>

<h3 id="sobre">:information_source: Sobre</h3>

> Este projeto foi desenvolvido utilizando o Django como framework back-end e o Bootstrap como framework front-end. 

A ideia é:

_"Criar uma aplicação de Controle de Visitantes onde a mesma tenha um design simples e belo, com intuito de promover o aprendizado utilizando o framework Django."_

Este repositório tem foco, na criação de uma aplicação de Controle de Visitantes de um condomínio, interligado a um banco de dados provido pelo próprio Framework Django facilitando dessa forma a manipulação de seus dados.

--------------------------------------------------------------------------------------

<h3 id="porque">:question: Por Que</h3>

Este projeto faz parte do meu portfólio pessoal, então, ficarei feliz caso você forneça algum feedback, código, estrutura, funcionalidade ou qualquer funcionalidade/melhoria que você possa relatar para melhora-lo.

Você pode usar este projeto como quiser, seja para estudar, fazer melhorias, você que manda!

Este é um projeto totalmente grátis!

--------------------------------------------------------------------------------------

<h3 id="tecnologias">:rocket: Tecnologias</h3>

As seguintes ferramentas foram usadas na construção do projeto:

- [Django Framework](https://www.djangoproject.com/)
- [Bootstrap](https://getbootstrap.com/)

--------------------------------------------------------------------------------------

<h3 id="funcionalidades">:sparkles: Funcionalidades</h3>

:construction: - As Funcionalidades será construída em breve...

--------------------------------------------------------------------------------------

<h3 id="instalando">:computer: Instalando o Projeto</h3>

**Clonando o Repositório**

```
git clone git@github.com:LucasSantus/visitantes.git

cd visitantes
```
#### Preparando Projeto

#### Windows

> **Observação:** Foi utilizado o Windows(versão 10), caso ocorra algum problema na instalação, pesquise por conta própria a resolução do mesmo!

**Preparando Ambiente Virtual**

```
$ python -m venv env

$ env\Scripts\activate

$ python -m pip install --upgrade pip

$ pip install -r requirements.txt
```

#### Linux

> **Observação:** Foi utilizado a distro Linux Mint(versão 20.1), caso ocorra algum problema na instalação, pesquise por conta própria a resolução do mesmo!

**Instalando Ambiente Virtual**

Caso não tenha um ambiente virtual instalado, digite no terminal:

```
sudo apt-get install python3-venv
```

**Preparando Ambiente Virtual**

Com o terminal aberto, digite no terminal:

```
python3 -m venv env

source env/bin/activate

python -m pip install --upgrade pip

pip install -r requirements.txt
```

#### Rodando o Projeto

**Iniciando**

```
python manage.py makemigrations dashboard

python manage.py makemigrations porteiros

python manage.py makemigrations usuarios

python manage.py makemigrations visitantes

python manage.py migrate

python manage.py runserver
```

**Criando Super Usuário**

```
python manage.py createsuperuser
```

**Acessando o Projeto**

para visualizar o projeto: http://127.0.0.1:8000/

**Acessando o Admin**

Com o projeto rodando, adicione o 'admin/' dps da URL:

http://127.0.0.1:8000/admin/

--------------------------------------------------------------------------------------

<h3 id="autor">:bust_in_silhouette: Autor</h3>

<div align="left"> 
	<a href="https://github.com/LucasSantus">
		<img style="border-radius: 50%;" src="https://github.com/LucasSantus.png" width="100px;" alt=""/>
		<br />
		Lucas Santus
	</a>
</div>
<br />
Feito com ❤️ por Lucas Santus!<br />
Obrigado por visitar e boa codificação!<br />

--------------------------------------------------------------------------------------

<h3 id="license">:memo: License</h3>

Este projeto está licenciado sob a Licença MIT License - veja o [LICENSE.md](https://github.com/LucasSantus/visitantes/blob/master/LICENSE) para melhores detalhes.
