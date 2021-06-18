# Iniciar proyecto de git
git init

# Preparar archivos que se convertirán en commit
git add .

# Crear commit con su mensaje
git commit -m "Aqui va el mensaje"

# Agregar remoto "Solo la primera vez"

git remote add origin https://github.com/TonnyHernandez/santander-front.git

# Enviar commits al servidor de Github

git push -u origin master
