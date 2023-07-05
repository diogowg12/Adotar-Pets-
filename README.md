# Adoção de Pets

Sistema Integrado para adoção de pets baseado em Django

Projeto independente  desenvolvido em Python 3 no Windows, testado no  Windows.


## Dependências

- [Python](https://www.python.org/downloads/) - Versão 3.11+
- [django](http://www.djangoproject.com) ==  4.2.2

## Instalação:


2. Edite o conteúdo do arquivo **djangosige/configs/configs.py**

3. Gere um `.env` local

```bash
python contrib/env_gen.py
```


4. Sincronize a base de dados:

```bash
python manage.py migrate
```

5. Crie um usuário (Administrador do sistema):

```bash
python manage.py createsuperuser
```

6. Teste a instalação carregando o servidor de desenvolvimento (http://localhost:8000 no navegador):

```bash
python manage.py runserver
```

## Implementações

- Cadastro de clientes e pets
- Login/Logout
- Criação de perfil para cada usuário.
- Definição de permissões para usuários.
- Criação para adicionar novo pet,listar,remover,buscar,solicitar,remover,ver pedidos
- Criação de dashboard do numero de adoção 
- Interface simples e em português


## Ajuda

Para relatar bugs ou fazer perguntas utilize o [Issues](https://github.com/thiagopena/djangoSIGE/issues) ou via email 
diogowg.lima89@gmail.com

