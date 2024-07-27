![](img/dunosauro-fastapi-sincrono-python.jpg)
<h1>Curso de FastAPI - Sincrono</h1>

<br>


# Sobre
Instrutor: Eduardo Mendes<br />
Canal: Eduardo Mendes <br />
Plataforma: YouTube
Aula: 0/14<br />
⭐⭐⭐⭐⭐<br />

# Objetivo

Construir um "todo list", uma ferramenta para gerenciar as tarefas "a fazer".

# Outros Materiais:

Playlist: [https://www.youtube.com/playlist?list=PLOQgLBuj2-3IuFbt-wJw2p2NiV9WTRzIP](https://www.youtube.com/playlist?list=PLOQgLBuj2-3IuFbt-wJw2p2NiV9WTRzIP)

Documentação das aulas: [https://fastapidozero.dunossauro.com/](https://fastapidozero.dunossauro.com/)

Slides: [https://github.com/dunossauro/fastapi-do-zero/tree/main/slides/pdf](https://github.com/dunossauro/fastapi-do-zero/tree/main/slides/pdf)


# O que não vai ter

* front-end
* CD
* deploy de modelos
* integrações
* bots

# Tecnologias
* SO: Windows 11
* Linguagem: Python 3.12.4
* Framework: FastAPI
* Gerenciador de pacotes: Poetry

Em construção...


# Anotações

# Comandos utilizados ()

Enquanto o repositório estiver desenvolvido vou colocar os comandos por aqui para facilitar a consulta.

## Ambiente Virtual

Instação do Python no Pyenv:
```txt
pyenv install 3.12.4
```

Configurar o Python no projeto:
```txt
pyenv local 3.12.4
```

Criar o ambiente virtual com Poetry:
```txt
poetry new nome_projeto
```

Ativar o ambiente virtual criado com Poetry:
```txt
poetry shell
```

Adicionar um pacote ao projeto com poetry:
```txt
poetry add nome_pacote
```

Rodar uma aplicação com fastapi:
```txt
# fastapi dev nome_ambiente/arquivo.py
fastapi dev fast_zero/app.py
```

## Documentação
Existe mais de uma forma de visualizar a documentação:

Swagger
```txt
http://127.0.0.1:8000/docs
```
Redoc
```txt
http://127.0.0.1:8000/redoc
```
1:21:21