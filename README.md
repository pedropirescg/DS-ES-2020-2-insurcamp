# DS-ES-2020-2-Insurcamp
Projeto de Design de Software para o curso de Engenharia de Software da UFG.

O Insurcamp é um software de análise de riscos securitários para o mercado de agronegócios. 
Este software será utilizado para medir o risco de uma lavoura com base em diversos critérios e, 
por meio desta análise, as companhias seguradoras terão maior assertividade em precificar a 
taxa do seguro para determinado perfil de lavoura.

# Linguagem
Desenvolvido com o framework [Django](https://www.djangoproject.com/).

## Escopo
Um sistema Back-end que provê acesso a dados relativos a Relatórios, 
restrito as Api's da plataforma insurcamp ou àquelas por
ela concedido acesso.

## Front End
Atualmente concede acesso às seguintes api's:
- appv2.insurcamp.com.br

## Tecnologias
- Django 3+
- DjangoRestFramework 3
- Python-decouple 3
- MongoDb 4
- MongoEngine 0.2
- DjangoRestFrameworkMongoEngine 3

## Como instalar
Baixe ou clone este repositório usando 
`https://github.com/pedropirescg/DS-ES-2020-2-insurcamp`.

## Instalando as Dependências
Dentro do diretório do sistema, instale as dependências usando
 `pip install -r requirements.txt`.

## Como executar
Execute `python3 manage.py runserver`. 
Depois acesse `http://localhost:8000/`.

## Dúvidas
Para obter ajuda consulte:
- [Python](https://www.python.org/).
- [Django](https://www.djangoproject.com/).
- [MongoDb](https://www.mongodb.com/try/download/community).

