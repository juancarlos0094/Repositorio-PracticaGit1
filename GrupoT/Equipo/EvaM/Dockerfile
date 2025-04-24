FROM debian:bullseye

# Establece el directorio de trabajo (crea /app si no existe)
WORKDIR /app

# Copia el script al contenedor
COPY script.sh /app/script.sh

# Da permisos de ejecución al script
RUN chmod +x /app/script.sh

# Ejecuta el script cuando el contenedor se inicie
CMD ["/app/script.sh"]
