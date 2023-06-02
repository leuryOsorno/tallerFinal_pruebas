# tallerFinal_pruebas

1. Iniciamos abriendo una terminal en modo super usúario o usúario **root,** con el comado **sudo su.**

![Aspose Words 74f0a2dc-cb22-4643-9801-8ffb80ad1383 001](https://github.com/leuryOsorno/tallerFinal_pruebas/assets/91139219/3ae2dbaa-4f54-4f8d-99ef-b6a3d3e67079)

2. Con el comando **airmon-ng,** listamos las targetas de red que tenemos disponibles

![Aspose Words 74f0a2dc-cb22-4643-9801-8ffb80ad1383 002](https://github.com/leuryOsorno/tallerFinal_pruebas/assets/91139219/aa56e442-2bf1-41c6-a829-7b531c210c31)

3. Ubicamos el nombre de la interfas de red con la que deseamos trabajar, luego con el comando **ip link set**  **interfas** **down, (**en nuestro caso " **ip link set wlan0 down**"), para cambiar el estado del dispositivo.

![Aspose Words 74f0a2dc-cb22-4643-9801-8ffb80ad1383 003](https://github.com/leuryOsorno/tallerFinal_pruebas/assets/91139219/10e6e4c3-5f70-4ab0-8d2a-cac79a1b0282)

4. Con el comando **ip link set**  **interfaz**  **name "**** interfaz+mon****" (**en nuestro caso " **ip link set wlan0 neme wlan0mon**"), para cambiar el nombre de la interfaz que simplemente . Se nombrara el nombre de la interfaz , adjuntandole la palaba "mon".

![Aspose Words 74f0a2dc-cb22-4643-9801-8ffb80ad1383 004](https://github.com/leuryOsorno/tallerFinal_pruebas/assets/91139219/00792dd0-765c-4471-9ea0-e38a30a18438)

5. Pasamos para la aplicación **Ferm wifi cracker** , Alli selecionamos la interfaz que renombramos y con la que vamos a trabajar, luego presionamos el segundo boton para iniciar la busqueda de redes, un poco mas abajo nos habilitara un boton que nos muesta las conexiones detectadas.

![Aspose Words 74f0a2dc-cb22-4643-9801-8ffb80ad1383 005](https://github.com/leuryOsorno/tallerFinal_pruebas/assets/91139219/0f29ad90-dcbc-4242-a99a-d769ab94df07)

6. presionamos el boton que se acaba de habilitar, para entrar donde estan todas las coneciones detectadas, seleccionamos la red que queremos atacar, muy importante cargamos el diccionario con el que vamos hacer el **Maching** , en nuestro caso " **rockyou****.txt**".
![Aspose Words 74f0a2dc-cb22-4643-9801-8ffb80ad1383 006](https://github.com/leuryOsorno/tallerFinal_pruebas/assets/91139219/5f43e836-f00e-4d51-9f4c-5a86d69e8cea)


7. Presionamos el botón **wifi attack** , esperamos que la aplicación encuentre el resultado esperado.

![Aspose Words 74f0a2dc-cb22-4643-9801-8ffb80ad1383 007](https://github.com/leuryOsorno/tallerFinal_pruebas/assets/91139219/7c8df852-9c25-41c0-8314-4085b2667a66)
