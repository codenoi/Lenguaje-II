
[U1 - Lab] Módulo en Python que monta Google Drive desde Google Colab,
explora una carpeta configurada con constantes y procesa archivos de datos.

## Funcionamiento

1. Monta Google Drive en /content/drive.
2. Lee la ruta desde la constante DIRECTORIO (/content/drive/My Drive/Lenguaje II).
3. Filtra solo archivos .json y .csv.
4. Imprime tamaño en KB (os.path.getsize) y fecha de última modificación (os.path.getmtime).
5. Si existe inventario.json, lo lee con json.load() y valida que sea una lista de registros.
6. Retorna un diccionario estructurado listo para ser consumido por una API.

## Licencia

Distribuido bajo licencia MIT. Ver el archivo LICENSE.
