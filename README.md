# Teste Scond

Requisitos: - Instalar Python 3.7 ou superior
            - Django versão compativel
            
Baixar o projeto local e executar com o comando 
Executar <python3.7 manage.py migrate> para executar as migrations, o banco configurado é o sqlite3

Para testar se o projeto esta executando acessar: http://localhost:8000/dashboard/ a mensagem deve ser: Teste SCOND.

Deve ser implmentado:
Em dashboard/views.py implmentar metodo/utilizar metodo utilizando conceitos rest, que retorne um Json e popule um gráfico ao acessar ao http://localhost:8000/dashboard/

O gráfico a ser utilizado é o seguinte: https://www.highcharts.com/demo/column-basic
A biblioteca javascript do highcharts deve ser adicionada ao projeto e os dados a serem populados no grafico, não devem estar fixos no html ou no javascript e sim retornados do metodos criado no arquivo views.py.

Ao final fazer pull request

Att
