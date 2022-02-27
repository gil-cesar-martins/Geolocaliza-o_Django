# Geolocalizacao_Django
Projeto que informa ao usuário pontos de localização em um mapa após especificar o nome do serviço que deseja e uma capital.

Para acessar a API disponível pelo site `https://www.yelp.com.br` , vá até Programadores e crie uma conta.

Vá no arquivo `settings` de seu projeto e cole a API_Key fornecida.

### Deploy local 
Instale as seguinte bibliotecas com o comando pip:

`pip install django geoip2 requests`

Instale as dependências no **requirements.txt**:
 
`pip freeze > requirements.txt`
 
migre os **models** para o banco de dados:
 
`python manage.py migrate`
 
Crie um superusuário para o gerenciamento do banco de dados:
 
`python manage.py createsuperuser`
 
Execute sua aplicação:
 
`python manage.py runserver`
 
Para acessar vá no seu navegador e  digite [http://localhost:8000](http://localhost:8000)

 
