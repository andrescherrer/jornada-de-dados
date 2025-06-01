# Instalar e Utilizar Poetry

### Instalação do Poetry

```
pipx install poetry
```

### Configuração do Poetry para lidar com ambiente virtual

```
poetry config virtualenvs.in-project true
```

### Criar novo projeto

```
poetry new <nome_do_projeto>
```

### Setar alguns parâmetros do projeto

```
pyenv local 3.12.1
poetry env use 3.12.1
poetry add django
```
