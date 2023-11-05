<!DOCTYPE html>
<html>
<head>
    <title>Escola Django REST API</title>
</head>
<body>
    <h1>Escola Django REST API</h1>
    <p>Este projeto é uma API REST construída com Django que permite consultar um banco de dados de uma escola. Ele fornece endpoints para acessar informações sobre alunos, professores, cursos e muito mais.</p>

    <h2>Requisitos</h2>
    <p>Antes de executar este projeto, você precisa ter o seguinte software instalado:</p>
    <ul>
        <li>Python (de preferência a versão 3.7 ou superior)</li>
        <li>Django</li>
        <li>Django REST framework</li>
        <li>Um banco de dados (por exemplo, SQLite, PostgreSQL, MySQL)</li>
    </ul>

    <h2>Configuração</h2>
    <ol>
        <li>Clone o repositório:
            <code>git clone git@github.com:LucasSilvaO/api-escola.git</code></li>
        <li>Acesse o diretório do projeto:
            <code>cd escola-django-rest-api</code></li>
        <li>Crie um ambiente virtual:
            <code>python -m venv venv</code></li>
        <li>Ative o ambiente virtual:
            <code>source venv/bin/activate (no macOS e Linux)</code></li>
        <li>Instale as dependências:
            <code>pip install -r requirements.txt</code></li>
        <li>Configure as variáveis de ambiente em um arquivo <code>.env</code> na raiz do projeto. Você pode usar um arquivo como <code>.env.example</code> como modelo. Certifique-se de definir variáveis como <code>DJANGO_SECRET_KEY</code>, <code>DEBUG</code>, <code>DATABASE_URL</code>, e outras conforme necessário.</li>
        <li>Aplique as migrações:
            <code>python manage.py migrate</code></li>
        <li>Crie um superusuário para acessar a área de administração:
            <code>python manage.py createsuperuser</code></li>
        <li>Inicie o servidor de desenvolvimento:
            <code>python manage.py runserver</code></li>
    </ol>

    <p>A API agora estará acessível em <a href="http://localhost:8000/">http://localhost:8000/</a>.</p>

    <h2>Uso</h2>
    <ul>
        <li>Acesse a área de administração em <a href="http://localhost:8000/admin/">http://localhost:8000/admin/</a> para adicionar e gerenciar dados da escola.</li>
        <li>Explore a API em <a href="http://localhost:8000/api/">http://localhost:8000/api/</a>. Aqui você encontrará informações sobre os endpoints disponíveis e como usar a API.</li>
    </ul>

    <h2>Documentação da API</h2>
    <p>A documentação da API pode ser encontrada em <a href="http://localhost:8000/api/docs/">http://localhost:8000/api/docs/</a>. Esta documentação é gerada automaticamente com base nas configurações do Django REST framework.</p>

    <h2>Contribuição</h2>
    <p>Fique à vontade para contribuir para este projeto. Sinta-se à vontade para abrir problemas, solicitações de pull ou fornecer feedback.</p>

    <h2>Licença</h2>
    <p>Este projeto está licenciado sob a Licença MIT. Consulte o arquivo <code>LICENSE</code> para obter mais detalhes.</p>
</body>
</html>
