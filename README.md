# Projeto e-diaristas


## **Instalando o projeto**

###  Clonar o projeto
``` git
git clone https://github.com/biocommons/biocommons.git
```

### Instalar dependências
``` bash
pip install -r requirements.txt
```

### Alterar configurações do BD no arquivo `settings.py`
``` python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'nome_do_bd',
        'USER': 'host_do_bd',
        'PASSWORD': 'porta_do_bd',
        'HOST': 'usuario_bd',
        'PORT': 'senha_bd',
    }
}
```

### Migrar o banco de dados
``` bash
python manage.py migrate
```

### Iniciar o servidor
``` bash
python manage.py runserver
```