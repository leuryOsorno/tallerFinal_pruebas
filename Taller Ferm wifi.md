1. Iniciamos abriendo una terminal en modo super usúario o usúario **root,** con el comado **sudo su.**


![](Aspose.Words.74f0a2dc-cb22-4643-9801-8ffb80ad1383.001.png)
**


1. Con el comando **airmon-ng,** listamos las targetas de red que tenemos disponibles

`	`![](Aspose.Words.74f0a2dc-cb22-4643-9801-8ffb80ad1383.002.png)




3. Ubicamos el nombre de la interfas de red con la que  deseamos trabajar, luego con el comando **ip link set interfas down, (**en nuestro caso “**ip link set wlan0 down**”), para cambiar el estado del dispositivo.

` `![](Aspose.Words.74f0a2dc-cb22-4643-9801-8ffb80ad1383.003.png)

3. Con el comando **ip link set interfaz name “interfaz+mon” (**en nuestro caso “**ip link set wlan0 neme wlan0mon**”), para cambiar el nombre de la interfaz que simplemente . Se nombrara el nombre de la interfaz , adjuntandole la palaba “mon”.


`	`![](Aspose.Words.74f0a2dc-cb22-4643-9801-8ffb80ad1383.004.png)

5. Pasamos para la aplicación **Ferm wifi  cracker**, Alli selecionamos la interfaz que renombramos y con la que vamos a trabajar, luego presionamos el segundo boton para iniciar la busqueda de redes, un poco mas abajo nos habilitara un boton que nos muesta las conexiones detectadas.



`	`![](Aspose.Words.74f0a2dc-cb22-4643-9801-8ffb80ad1383.005.png)



6. presionamos el boton que se acaba de habilitar, para entrar donde estan todas las coneciones detectadas, seleccionamos la red que queremos atacar, muy importante cargamos el diccionario con el que vamos hacer el **Maching**, en  nuestro caso “**rockyou.txt**”.

`	`![](Aspose.Words.74f0a2dc-cb22-4643-9801-8ffb80ad1383.006.png)

7\.	Presionamos el botón **wifi attack**, esperamos que la aplicación encuentre el resultado esperado.

![](Aspose.Words.74f0a2dc-cb22-4643-9801-8ffb80ad1383.007.png)
