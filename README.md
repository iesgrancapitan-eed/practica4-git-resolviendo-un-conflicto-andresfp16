## Tarea 4.11. Practica4. Git. Resolviendo un conflicto
En esta práctica vas a trabajar sobre un repositorio con varias ramas. 
- master (la de por defecto)
- rama-1
- rama-2

Generarás un conflicto en un fichero y lo resolverás. Cuando hayas fusionado todos los cambios de forma correcta eliminarás las ramas correctamente fusionadas para quedarte SOLO con la rama master. Una vez realizada la práctica harás una copia en este repositorio remoto

Documenta los siguientes pasos:

1. Asegúrate de que tienes configurado el editor Visual Studio Code como tu editor de Git. (git config --global core.editor "code --wait")



2. Crea un repositorio local y avanza en la rama "master" añadiendo un fichero "index.html" con la estructura básica html. El body estará vacío

![img](img/2.png)

3. Crea y salta a "rama-1". Avanza en un commit con tu nombre de pila en un párrafo dentro del body

![img](img/3.png)

4. Vuelve a la rama master

![img](img/4.png)

5. Crea y salta a "rama-2". Avanza en un commit con tu apellido en un párrafo dentro del body

![img](img/5.png)

6. Muestra el estado del repositorio de forma gráfica y resumida

![img](img/6.png)

7. Haz un merge a rama-1. Intentas fusionar ambas ramas. Aparecerá un conflicto porque ambos commits trabajan en la misma porción <body></body> de un mismo archivo index.html. Git no será capaz de fusionarlas directamente. 

![img](img/7.png)

8. El editor VS Code reconoce los conflictos de fusión. Las diferencias se resaltan y hay acciones en línea para aceptar los cambios. Deja un único párrafo con tu nombre de pila y apellido.

![img](img/8.png)

9. Una vez que se resuelto el conflicto confirma el archivo en conflicto para que pueda realizar esos cambios

![img](img/9.png)

10. Muestra de nuevo el estado del repositorio de forma gráfica y resumida

![img](img/10.png)

11. Vuelve a la rama master y realiza otro merge. Es una fusión fast-forward. Los dos commits a fusionar tienen relación de ancestro. Entonces el merge no produce un commit nuevo, sencillamente avanza la rama, "avance rápido"

![img](img/11.png)

12. Visualiza las ramas que han sido fusionadas con la rama master

![img](img/12.png)

13. Elimina las ramas correctamente fusionadas (sin asterisco) para quedarte SOLO con la rama master. 

![img](img/13.png)

14. Realiza una copia a este repositorio remoto

![img](img/14.png)

15. Recuerda añadir estas instrucciones con los pantallazos en el fichero README.md

16. En GitHub entra en Insights/network y visualiza el gráfico del repositorio con los merge y cinco commits  

![img](img/Network.png)

Enlace: https://github.com/iesgrancapitan-eed/practica4-git-resolviendo-un-conflicto-andresfp16

