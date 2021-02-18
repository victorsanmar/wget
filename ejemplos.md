# Ejemplos

## Usando el comando Wget para descargar archivos individuales

Uno de los ejemplos más básicos de este comando es descargar un único archivo y almacenarlo en su directorio de trabajo actual. Por ejemplo, puede obtener la última versión de WordPress usando lo siguiente:
```
wget https://wordpress.org/latest.zip
```

## Usar el comando Wget para obtener archivos bajo nombres diferentes

En este ejemplo de wget, guardaremos un archivo usando un nombre diferente con la ayuda de la opción -O:

```
wget -O wordpress-install.zip https://wordpress.org/latest.zip
```

## Usar el comando Wget para guardar archivos en el directorio especificado

Puedes utilizar wget para colocar un archivo en otro directorio usando la función -P:

```
wget -P documents/archives/ https://wordpress.org/latest.zip
```

## Usar el comando Wget para limitar la velocidad de descarga

Con wget, también puedes limitar la velocidad de descarga. Esto es útil cuando recuperas archivos grandes y evitará que use todo tu ancho de banda. Este ejemplo de wget establecerá el límite a 500k:

```
wget --limit-rate=500k https://wordpress.org/latest.zip
```

## Uso del comando Wget para establecer cantidad de reintento

Los problemas de conexión a Internet pueden hacer que la descarga se interrumpa. Para abordar este problema, podemos aumentar la cantidad de reintentos usando la función -tries:

```
wget -tries=100 https://wordpress.org/latest.zip
```

## Conclusión
¡Felicitaciones! Has aprendido varios usos para el comando wget.
