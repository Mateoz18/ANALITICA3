## ANALITICA3

# Configuración del usuario 

Se realiza una sola vez por computador o cuándo se quiera cambiar de usuario

git config --global user.name  'usuario’ 

git config --global user.email ' correo

# Copia local del repositorio
Cuando yo necesito tener una copia local de un repositorio y actualizar los cambios, pero no necesito hacer contribuciones, ejemplo: repositorio profesor: 

1. Configuración de copia local (se realiza una sola vez por computador): En esta configuración se crea una conexión entre el repositorio remoto (github) y una carpeta local del pc.
git clone “url repositorio”

2. Actualizar en carpeta local los cambios que están en la nube (github):
git pull origin main

# Despues de configurar la cuenta y el repositorio

1.git pull origin main:  Hacerlo siempre antes de hacer cambios para evitar errores y antes de enviar cambios.

2.git add . : ## cuando termine cambios importantes.

3.git commit –m  “descripción de cambios” : Empaquete cambios en un commit. 

4.git push origin main:  Enviar cambios a repositorio remoto.




