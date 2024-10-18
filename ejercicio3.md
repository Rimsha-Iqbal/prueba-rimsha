# Ejercicio 3  
<!-- Crea una rama que se llame primera en un repositorio local, y ejecuta la instrucción necesaria para comprobar que se ha creado -->
Voy a mi repositorio **preuba_rimsha**  

![alt text](img/ej3-1.png)  

Con el comando **git branch** podemos ver las ramas que tenemos    

![alt text](img/ej3-2.png)    

con el comando **git branch primera** creamos una rama  

![alt text](img/ej3-3.png)  

Con el comando **git checkout primera** cambiamos a rama primera  

![alt text](img/ej3-5.png)  

Con **git branch** confirmamos cambio de rama

![alt text](img/ej3-6.png)  
<!-- Crea un nuevo fichero en esta rama y fusiónalo con la principal. ¿Se ha producido conflicto? Razona la respuesta.
Borra la rama primera. -->
en este rama voy a crear un fichro **fich_pri.txt**

![alt text](img/ej3-7.png)  

Con el comando **git add .** Agregamos los archivos modificados o creados a la cola para que se confirmen más tarde.Los archivos no se confirman.

![alt text](img/ej3-8.png)  

Con **git commit** confirmamos los archivos que se han agregado y crea una nueva revisión con un registro

![alt text](img/ej3-9.png)  

Con **git checkout main** cambio la rama a main

![alt text](img/ej3-10.png)  

Con el comando **git merge primera** fusiónamos los modificaciones con la rama principal(main)

![alt text](img/ej3-11.png)  
<!-- Borra la rama primera.-->
Con el comando **git branch -d** eliminamos la rama primera  
No se ha producido conflicto porque el nuevo fichero no existía en la rama principal, por lo que Git puede realizar una fusión sin problemas.  

![alt text](img/ej3-12.png)  
<!-- Crea una rama que se llame segunda, y modifica un fichero en ella para producir un conflicto al unirlo a la rama principal. Entrega el contenido del fichero donde se ha producido el conflicto. -->
Otra vez creamos una rama uneva se llama **"Segunda"**  
Modificamos el fichero **fich_pri.txt** que hemos creado anteriormente.  

![alt text](img/ej3-13.png)  

Modifico fichero **fich_pri.txt**

![alt text](img/ej3-14.png)  

Con el comando **git add .** Agregamos el archivo modificado a la cola para que se confirmen más tarde.El archivos no se confirman.

![alt text](img/ej3-15.png) 

Con **git commit** confirmamos el archivo que se he modificado y crea una nueva revisión con un registro.

![alt text](img/ej3-16.png)  

Cambio la rama a main  

![alt text](img/ej3-17.png)  

Aqui tambien modifico este mismo fichero **fich_pri.txt**

![alt text](img/ej3-18.png)  

Con el comando **git add .** Agregamos el archivo modificado a la cola para que se confirmen más tarde.El archivos no se confirman.  

![alt text](img/ej3-19.png)  

Con **git commit** confirmamos el archivo que se he modificado y crea una nueva revisión con un registro. 

![alt text](img/ej3-20.png)  

Aqui aparece un conflicto porque es como diferentes personas estan trabajando con el mismo archivo simultáneamente y cuando se realizan cambios en paralelo en diferentes ramas que afectan a las mismas líneas de código.

![alt text](img/ej3-21.png)  

Borramos que no queremos por ejemplo linea de  **HEAD**, **Ultima linea** y una en la media. y como este resolvemos el conflicto. Y ahora podemos ralizar cambios sin problema.


![alt text](img/ej3-22.png)  

Con el comando **git add .** Agregamos los archivos modificados o creados a la cola para que se confirmen más tarde.Los archivos no se confirman.

![alt text](img/ej3-23.png)  

Con **git commit** confirmamos los archivos que se han agregado y crea una nueva revisión con un registro


![alt text](img/ej3-24.png)  
  
Ahora podems hacer merge sin problemas.  

![alt text](img/ej3-25.png)  
  
vamos a rama segunda para confirmar que si tiene mismo contenido. 
![alt text](img/ej3-26.png)

**¡FINSH!**