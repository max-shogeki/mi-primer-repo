# Pruebas de regresión — Ejemplo 9

## ¿Qué son?
Las pruebas de regresión consisten en volver a ejecutar pruebas ya realizadas después de modificar el código para comprobar que las funciones que antes funcionaban continúan funcionando.

## Lista de comprobación para este proyecto
- [ ] Abrir `index.html` en un navegador y verificar que aparece “¡Hola Mundo!”.
- [ ] Verificar que el título de la pestaña sea “Mi Primer Proyecto”.
- [ ] Comprobar que el documento usa codificación UTF-8 y muestra correctamente los caracteres en español.
- [ ] Después de cada modificación, repetir las comprobaciones anteriores.
- [ ] Revisar el cambio con `git diff`, guardar un commit y subirlo con `git push`.

## Importancia de Git y GitHub
Git conserva el historial de cambios mediante commits, por lo que ayuda a identificar cuándo se introdujo un error y permite comparar versiones. GitHub mantiene una copia remota del repositorio y facilita compartir el código, revisar cambios y coordinar el trabajo. Juntos ayudan a documentar las modificaciones y a volver a una versión anterior si es necesario. Sin embargo, Git y GitHub no ejecutan automáticamente pruebas de regresión por sí solos: las pruebas deben realizarse manualmente o configurarse mediante herramientas de automatización.

## Ejemplo
Si se cambia el texto o la estructura de `index.html`, se vuelve a abrir la página y se revisa que el título, el texto y los caracteres sigan mostrándose correctamente. Si algo deja de funcionar, se revisa el cambio con `git diff` y el historial con `git log --oneline`.
