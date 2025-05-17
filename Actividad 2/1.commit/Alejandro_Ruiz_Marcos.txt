Ejercicio 1
1.1. Preguntas
    1. ¿Cómo se inicializa un repositorio local? (que comando se debe ejecutar?)
git init
    2. ¿Cómo hago para que un directorio deje de ser controlado por git? (que comando se debe ejecutar?) 
rm -rf .git
    3. Si agrego un archivo a un directorio que ya está siendo controlado por git, ¿está siendo controlado por git?
No automáticamente. Hay que agregarlo manualmente con git add "nombre_del_archivo"
    4. ¿Qué comando se utiliza para agregar un archivo al repositorio local? 
git add
    5. ¿Cómo determino que archivos fueron modificados? (que comando se debe ejecutar?)
git status
    6. ¿Qué comando se utiliza para hacer un commit? 
git commit -m "mensaje descriptivo"
    7. En sus propias palabras, ¿qué es un commit? 
Es una captura del estado del proyecto en un momento específico. Guarda los cambios preparados en el historial del repositorio.
