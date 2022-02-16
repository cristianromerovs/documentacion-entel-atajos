[Volver a documentacion](https://github.com/cristianromerovs/documentacion-entel-atajos/blob/main/README.md)

# DESARROLLO ENTEL SNIPPETS | ACTUALIZACION

Documentacion con los pasos a seguir para poder crear un nuevo `Release`.

> Guiarse por esta documentacion, para poder crear una nueva version del proyecto de manera correcta y poder mantener el orden de este.


## Requerimientos

1.  Instalar **Node JS**
2.  Instalar **VSCE**
    `npm install -g vsce`
3.  [Descargar proyecto](https://entel.digitalbeat.cl/md/documentacion/dsp/extensiones/)

## Edición de archivos

Para agregar un nuevo Snippet debes editar el archivo:
`/snippets/snippets.code-snippets`
Puedes utilizar [esta herramienta](https://snippet-generator.app/) para crear un snippet con el formato correcto.
Luego debes ir al archivo:
`package.json` y editar el campo: **"version": "X.X.X"** con la versión actual.
Finalmente en el archivo: `CHANGELOG.md` debes agregar un resumen del update.

## Creacion de package .VSIX

Para poder crear un package debemos abrir un terminal (integrado o VSC) y debemos posicionarnos dentro de el directorio del proyecto
`cd entel-atajos` en el terminal ejecutar el siguiente comando `vsce package`, este creará un archivo llamado **entel-atajos-x.x.x.vsix**
Este es el archivo que debemos subir a la documentacion para que los equipos puedan descargar la extensión.

-----------------------------------------------------------------------------------------------------------

### Para más información

* [Para consultas sobre esta extensión](mailto:mut_cromero@externos.entel.cl)

**Enjoy!**
