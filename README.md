<p align="center">
  <img src="https://logodix.com/logo/1758841.png" width="200px">
</p>

# API de Autenticação  

Uma das etapas que não pode faltar no desenvolvimento de APIs é a configuração da autenticação de usuários. A autenticação é um mecanismo de segurança indispensável para aplicações modernas. Por isso, este repositório traz um exemplo prático da configuração de autenticação de usuários por meio do framework **Django**.O próprio framework facilita esse processo com poucas linhas de código, pois, por padrão, já traz uma estrutura pronta para autenticação.

O projeto utiliza as bibliotecas de autenticação:
- **allauth**
- **dj-rest-auth**
-  **rest-framework-token**

## Instalação  

```bash
git clone https://github.com/Nathan-cardoso/auth-django-rest.git
```

Crie e ative um ambiente virtual:  

```bash

python3 -m venv venv

source venv/bin/activate  # Linux/macOS
venv\Scripts\activate  # Windows

pip install -r requirements.txt #Baixe as dependências no arquivo requirements.txt
```

## Rotas 
**Registro de usuário**
```bash
http://127.0.0.1:8000/api/auth/register/

```

**Login**
```bash
http://127.0.0.1:8000/api/auth/login/

```

**Logout**
```bash
http://127.0.0.1:8000/api/auth/logout/

```

## Sites de Apoio

- [Dj-Rest-Auth - Documentação de Instalação](https://dj-rest-auth.readthedocs.io/en/latest/installation.html)  
- [Dj-Rest-Auth - Documentação Completa](https://dj-rest-auth.readthedocs.io/en/latest/)  
- [Django-Allauth - Documentação](https://django-allauth.readthedocs.io/en/latest/)  
- [Artigo base ensinando a usar a autenticação no django.](https://testdriven.io/blog/django-rest-auth/)  
