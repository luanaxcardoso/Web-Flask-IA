*** No PowerShell ***
# mkdir para criar a pasta do projeto

# Criar ambiente virtual
python -m venv venv

# Ativar ambiente virtual
.\venv\Scripts\activate

/////////////////////////////////////////////////////////
# Criar arquivo requirements.txt
# Adicionar as dependências
flask
python-dotenv
requests

Instalar dependências
# pip install -r requirements.txt


////////////////////////////////////////////////////////////
# Criar arquivo app.py
# Criar pasta templates e adicionar os arquivos *** index.html e results.html ***
# Criar arquivo .env *** --> Adicionar a chave da API ***


////////////////////////////////////////////////////////////
*** Adicionei upper em results.html para mostrar o idioma em maiúsculo ***
{{ target_language|upper }}

////////////////////////////////////////////////////////////

Para rodar o projeto:
# flask run

E acessar
# http://127.0.0.1:5000
