<h1>⚡Curso de FastAPI - Sincrono</h1>

<br>


# Sobre
Instrutor: Eduardo Mendes<br />
Canal: Eduardo Mendes <br />
Plataforma: YouTube
Aula: 0/14<br />
⭐⭐⭐⭐⭐<br />

SUMÁRIO:
- [Sobre](#sobre)
- [Objetivo](#objetivo)
- [Outros Materiais:](#outros-materiais)
- [O que não vai ter](#o-que-não-vai-ter)
- [Tecnologias](#tecnologias)
- [Aulas](#aulas)
- [Comandos utilizados ()](#comandos-utilizados-)
  - [Ambiente Virtual](#ambiente-virtual)
    - [Configurar o Python no projeto com Pyenv](#configurar-o-python-no-projeto-com-pyenv)
    - [Criar a estrutura do projeto com Poetry](#criar-a-estrutura-do-projeto-com-poetry)
  - [Criar o ambiente virtual com Poetry:](#criar-o-ambiente-virtual-com-poetry)
    - [Ativando ambiente virtual criado pelo Poetry](#ativando-ambiente-virtual-criado-pelo-poetry)
    - [Adicionar um pacote ao projeto com poetry:](#adicionar-um-pacote-ao-projeto-com-poetry)
    - [Rodar o arquivo app.py no terminal](#rodar-o-arquivo-apppy-no-terminal)
    - [Rodar uma aplicação com fastapi](#rodar-uma-aplicação-com-fastapi)
  - [Documentação](#documentação)


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

# Aulas
| Status | Aula  | Vídeo                                                   | Duração |
|--      |--     |--                                                       |--       |
|✅     | 00    | Aula de abertura. O que vamos aprender?  Aula 00         |01:05:04|
|✅     | 01   | Configuração do ambiente e hello world com testes Aula 01 |02:15:19 |


# Comandos utilizados ()

Enquanto o repositório estiver desenvolvido vou colocar os comandos por aqui para facilitar a consulta.

## Ambiente Virtual

Instalação do Python no Pyenv:
```txt
pyenv install 3.12.4
```

### Configurar o Python no projeto com Pyenv
```txt
pyenv local 3.12.4
```
### Criar a estrutura do projeto com Poetry
```txt
poetry new nome_projeto
```

## Criar o ambiente virtual com Poetry:
Navegue pelo terminal até a pasta onde está o arquivo .toml e use o comando abaixo para criar um ambiente virtual com Poetry:
```txt
poetry install
```
### Ativando ambiente virtual criado pelo Poetry
```txt
poetry shell
```
### Adicionar um pacote ao projeto com poetry:
```txt
poetry add nome_pacote
```
Exemplo:
```txt
poetry add fastapi
```
### Rodar o arquivo app.py no terminal
No terminal, navegue até a pasta do projeto e aplique o comando abaixo:
```py
python -i fast_zero/app.py
```
-i significa interactive.

Depois use:
```py
read_root()
```
O resultado esperado é a exibição da mensagem que está no arquivo.

### Rodar uma aplicação com fastapi
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
