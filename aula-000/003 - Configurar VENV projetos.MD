# Configurar VENV para cada projeto

### Configurar VENV projeto pandas

```
cd projeto_padas
python -m venv .venv
source .venv/bin/activate
pip install pandas
```

### Configurar VENV projeto streamlit

```
deactivate
cd ../projeto_streamlit
python -m venv .venv
source .venv/bin/activate
pip install streamlit
```
