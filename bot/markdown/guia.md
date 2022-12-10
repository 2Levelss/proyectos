# Guia de uso para el bot de Discord

### Requisitos para instalar

* Editor de codigo. Ej: Visual Studio Code
* tener python instalado con la version 3.7
* Tener cuenta en Discord

### Requisitos para ejecutar el bot
## Debemos tener un Token para Ejecutar el bot:

1. buscar en google Discord Developer con la sesion iniciada
![googel](google.png)

2. entreamos en web de discord developer y entramos en la seccion de "aplication"
![aplication](aplication.png)

3. debemos crear una aplicacion donde se alojara el bot
![create](create%20aplication.png)

4. Selecionamos la aplicacion que creamos y selecionamos la seccion que dice "bot"
![bot](bot%20aplication.png)

5. selecionamos en el apartado de "reset token"
![token](paso5.png)

6. abrimos visual studio y creamos un archivo ".env" en la carpeta donde se encuentra el archivo del bot
![guardarToken](guardarToken.png)


### Ejecutar el bot

1. debemos instalar las dependencias que se mostraran a continuacion: 

![Import para el bot de discord](import.png)

2. para instalar las dependencias de python usaremos el terminal de Visual Studio Code: 

![abrir terminal](terminal.png)

3. hacemos click en el apartado que dice "Terminal"

![mostrar terminal](terminalDos.png)

4. escribimos el comando "pip install" y procedemos a intalar las dependencias mostradas en el paso 1

![instalar](pip.png)

5. cuando tengamos todos los componentes de python requeridos procedemos a ejecutar el bot en el terminal:

![Ejecutar bot](ejecutar.png)

### Comandos del bot de Discord

1. !registro: este comando le permitira registrarse en el bot
   * Ejemplo de como debe usarse: !registro Nombre correo contrasena confirmar contrasena
   * Ejemplo practico: !registro jhon correo@ejemplo.com 12345678 12345678
![!registro](!registro.png)

2. en caso de que el usuario ya este registro saldra el siguiente mensaje: 

![el usuario ya existe](existe.png)

3. el comando !eliminar permitira eliminar el usuario creado:
   * Ejemplo: !eliminar
![usuario eliminado](eliminado.png)

4. el comando !inicar le permitira tener acceso a la informacion del mundial y sus equipos
  * Ejemplo: !iniciar
![iniciar](iniciar.png)

5. el comando !equipo muestra la informacion del equipo asi como su grupo:
  *Ejemplo: !equipo spain
![equipo](equipo.png)