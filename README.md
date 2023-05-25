# MA102
Proyecto Final MA102

## Descripción
Este proyecto 

## Requisitos Técnicos
Python (>= versión 3)
Django

## Instalación
Instalar Python 3 y correr los siguientes:

pip install --user pipenv

# Resolución de Problemas

En mac, la version de Python por defecto es 2.7. Dado que no podemos actualizar python a una versión más reciente (algunos componentes del Sistema Operativo dependen de la versión antigua) entonces podemos instalar la versión reciente
aparte, la cual será accessible por medio del comando "python3". Sin embargo, si queremos usar el comando "python" podemos crear un alias como sigue a continuación:

which python3   # /usr/local/bin/python3
which pip3      # /usr/local/bin/pip3

# Linux or other bash environment
echo "alias python=/usr/local/bin/python3" >> ~/.bashrc
echo "alias pip=/usr/local/bin/pip3" >> ~/.bashrc

# Mac OS or other zsh environment
echo "alias python=/usr/local/bin/python3" >> ~/.zshrc
echo "alias pip=/usr/local/bin/pip3" >> ~/.zshrc

# finalmente, source en ambos
source ~/.bashrc
source ~/.zshrc