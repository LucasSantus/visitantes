## Controle de Visitantes

![License](https://img.shields.io/github/license/LucasSantus/controle-visitantes)
![Languages](https://img.shields.io/github/languages/count/LucasSantus/controle-visitantes)
![GitHub repo size](https://img.shields.io/github/repo-size/LucasSantus/controle-visitantes)

Se você quiser dar uma olhada em todas as telas do aplicativo, elas estão [aqui] (link).

--------------------------------------------------------------------------------------

### Sobre o Projeto

A ideia é:

_"Criar uma aplicação de Controle de Visitantes onde a mesma tenha um design simples e belo, com intuito de promover o aprendizado utilizando o framework Django"_

Este repositório tem foco, na criação de uma aplicação de Controle de Visitantes de um prédio, interligado a um banco de dados provido pelo próprio Django Framework facilitando dessa forma a manipulação de dados.

--------------------------------------------------------------------------------------

### Por Que?

Este projeto faz parte do meu portfólio pessoal, então, ficarei feliz caso você fornecer algum feedback sobre o mesmo, código, estrutura, funcionalidade ou qualquer coisa que você possa relatar para melhora-lo.

Você pode usar este projeto como quiser, seja para estudar, fazer melhorias, você que manda!

Este é um projeto totalmente grátis!

--------------------------------------------------------------------------------------

### Instalando o Projeto

#### Linux

> **Observação:** Foi utilizado a distro Linux Mint(versão 20.1), caso ocorra algum problema na instalação, pesquise por conta própria a resolução do mesmo!

**Clonando o Repositório**

Dentro da pasta onde o projeto irá ficar armazenado, abra o terminal PowerShell (opcional, qualquer terminal funcionará), {Shift + Botão Direito Mouse}

```
$ git init

$ git clone git@github.com:LucasSantus/controle-visitantes.git

$ cd controle-visitantes
```

**Preparando Ambiente Virtual**

Com o terminal aberto, digite:

```
$ sudo apt-get install python3-venv

$ python3 -m venv env

$ source env/bin/activate

$ python -m pip install --upgrade pip

$ pip install -r requirements.txt
```

**Preparando o Projeto**

```
$ python manage.py migrate

$ python manage.py createsuperuser
```

**Rodando o Projeto**

```
$ python manage.py runserver
```

para visualizar o projeto: http://127.0.0.1:8000/

--------------------------------------------------------------------------------------

### Autor(es)
 
- **Lucas Santos:** [GitHub](https://github.com/LucasSantus)
 
Siga-me no github!

Obrigado por me visitar e boa codificação!

--------------------------------------------------------------------------------------

### License

Este projeto está licenciado sob a Licença MIT License - veja o [LICENSE.md](https://github.com/LucasSantus/controle-visitantes/blob/master/LICENSE) para melhores detalhes.
