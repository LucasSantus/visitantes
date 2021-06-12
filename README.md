## Controle de Visitantes

Se você quiser dar uma olhada em todas as telas do aplicativo, elas estão [aqui] (link).

--------------------------------------------------------------------------------------

### Sobre o Projeto

A ideia é:

_"Criar uma aplicação de Controle de Visitantes onde a mesma tenha um design simples e belo, com intuito de promover o aprendizado utilizando o framework Django"_

Este repositório tem foco, na criação de uma aplicação de Controle de Visitantes de um condomínio, interligado a um banco de dados provido pelo próprio Framework Django facilitando dessa forma a manipulação de seus dados.

--------------------------------------------------------------------------------------

### Por Que?

Este projeto faz parte do meu portfólio pessoal, então, ficarei feliz caso você forneça algum feedback, código, estrutura, funcionalidade ou qualquer funcionalidade/melhoria que você possa relatar para melhora-lo.

Você pode usar este projeto como quiser, seja para estudar, fazer melhorias, você que manda!

Este é um projeto totalmente grátis!

--------------------------------------------------------------------------------------

### Instalando o Projeto

#### Linux

> **Observação:** Foi utilizado a distro Linux Mint(versão 20.1), caso ocorra algum problema na instalação, pesquise por conta própria a resolução do mesmo!

**Clonando o Repositório**
Dentro da pasta onde o projeto irá ficar armazenado, abra o terminal.

```
git init

git clone git@github.com:LucasSantus/controle-visitantes.git

cd controle-visitantes
```

**Instalando Ambiente Virtual**
```
sudo apt-get install python3-venv
```

**Preparando Ambiente Virtual**
```
python3 -m venv env

source env/bin/activate

python -m pip install --upgrade pip

pip install -r requirements.txt
```

**Preparando o Projeto**
```
python manage.py makemigrations cadastro

python manage.py makemigrations administracao

python manage.py migrate

python manage.py createsuperuser
```

**Rodando o Projeto**
```
python manage.py runserver
```

**Acessando o Projeto**

Visualize o projeto no navegador: http://127.0.0.1:8000/

**Acessando o Admin**

Adicione 'admin/' há URL:

http://127.0.0.1:8000/admin/

--------------------------------------------------------------------------------------

### Autor(es)
 
- **Lucas Santos:** [GitHub](https://github.com/LucasSantus)
 
Siga-me no github!

Obrigado por me visitar e boa codificação!

--------------------------------------------------------------------------------------

### License

Este projeto está licenciado sob a Licença MIT License - veja o [LICENSE.md](https://github.com/LucasSantus/controle-visitantes/blob/master/LICENSE) para melhores detalhes.
