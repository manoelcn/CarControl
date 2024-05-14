# Carros

## Descrição

Este é um projeto simples desenvolvido com o framework Django para fins de estudo. O projeto é sobre uma pequena gestão de carros, com funcionalidades básicas como cadastrar, listar, editar e excluir carros. 
Também inclui o cadastro e login de usuário, além de algumas pequenas funcionalidades adicionais. O projeto conta ainda com a página de administração do Django.

## Instalação

Siga os passos abaixo para clonar e executar o projeto no seu computador:

**Observação:** este passo a passo é destinado a computadores Windows.

1. ##**Clone o repositório**
   
   ``` git clone https://github.com/seu-usuario/Carros.git ```

2. ##**Crie um ambiente virtual**
   
   ``` python -m venv venv ```

3. ##**Ative o ambiente virtual**
   
   ``` .venv\Scripts\activate ```

4. ##**Instale as dependências**
   
   ``` pip install -r requirements.txt ```

5. ##**Realize as migrações do banco de dados**
    
   ``` python manage.py migrate ```

6. ##**Crie um superusuário (opcional, para acessar o admin do Django)**
    
   ``` python manage.py createsuperuser ```

7. ##**Inicie o servidor de desenvolvimento**
    
   ``` python manage.py runserver ```

8. ##**Acesse o projeto no seu navegador**
    
   Abra o navegador e digite **http://127.0.0.1:8000** para ver o projeto em execução
