# Configuração PYENV diferentes projetos

### Crie uma pasta para trabalhar no projeto

```
mkdir <nome_projeto>
```

### Listar versões do python instalados

```
pyenv versions
```

### Baixar versão do python que preciso (trabalhar com Pandas)

```
pyenv install 3.12.1
```

### Baixar versão do python que preciso (trabalhar com Streamlit)

```
pyenv install 3.11.5
```

### Baixar versão do python que preciso (trabalhar com django)

```
pyenv install 2.7
```

### Configurar Versão Global do python na minha máquina

```
pyenv global 3.12.1
```

### Configurar versão do python para trabalhar com Pandas

```
cd projeto_pandas
pyenv local 3.12.1
```

### Configurar versão do python para trabalhar com Streamlit

```
cd projeto_streamlit
pyenv local 3.11.5
```

### Configurar versão do python para trabalhar com Django

```
cd projeto_django
pyenv local 2.7
```
