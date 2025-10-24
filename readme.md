# abrir o crear un archivo llamado "documento.md" y escribir texto
with open("documento.md", "w", encoding="utf-8") as archivo:
    archivo.write("# Título del Documento\n\n")
    archivo.write("Este es un archivo de ejemplo en formato **Markdown**.\n\n")
    archivo.write("## Sección 1\n")
    archivo.write("Aquí puedes agregar texto descriptivo, listas, o código.\n\n")
    archivo.write("- Elemento 1\n")
    archivo.write("- Elemento 2\n")
    archivo.write("- Elemento 3\n\n")
    archivo.write("## Conclusión\n")
    archivo.write("Este texto se genera automáticamente con Python.")
