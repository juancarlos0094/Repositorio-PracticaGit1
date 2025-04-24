# Usa una imagen base de Ubuntu
FROM ubuntu:latest

# Instala bash y cualquier otra dependencia necesaria
RUN apt-get update && apt-get install -y bash

# Copia el archivo script.sh a la imagen
COPY script.sh /script.sh

# Da permisos de ejecución al script
RUN chmod +x /script.sh

# Ejecuta el script cuando se inicie el contenedor
CMD ["/script.sh"]
