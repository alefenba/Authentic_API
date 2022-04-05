# Authentic_API
Criação de uma API de login com autenticação, utilizando FastAPI + MySQL


### <strong>Instruções para instalação</strong>:

#### Criar e ativar ambiente virtual Python (venv):
```python -m venv .venv```

```source .venv/bin/activate```

#### <strong>Instalar dependências</strong>:

```pip install requirements.txt```

### <strong> Trocar os dados de models de acordo com o banco de dados de sua preferência </strong>:

```
USUARIO = 'USUARIO'
SENHA = 'SENHA'
HOST = 'HOST'
BANCO = 'BANCO'
PORT = 'PORT'
```

#### <strong>Iniciar servidor no uvicorn </strong>:
```uvicorn main:app --reload```

#### <strong>Abrir o servidor </strong>:
```http://127.0.0.1:8000/docs```

