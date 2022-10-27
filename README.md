
# Preparació de l'entorn

## Entorn virtual (Ubuntu)

### Crear entorn virtual

`py -m venv venv`

### Activar entorn creat

`source venv/bin/activate`

### Instal·lar les dependències del fitxer de requeriments

`python3 -m pip install -r requeriments.txt`

### Instal·lar llibreries noves

`pip install --upgrade <new-library>`

### Guardar dependències utilitzades al fitxer de requeriments

`pip freeze > requeriments.txt`
