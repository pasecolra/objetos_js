# objetos_js

# Objeto Navigator

El objeto del navegador JavaScript se utiliza para la detección del navegador. Se puede utilizar para obtener información del navegador, como nombre de aplicación, nombre de código de aplicación, agente de usuario, etc.

El objeto del navegador es la propiedad de la ventana, por lo que se puede acceder a él mediante: **window.navigator** o **navigator**

# Propiedades del objeto Navigator js
```
|No.|	Propiedades	  |   Descripcion                                                                 |
|1  |	appName	      |   devuelve el nombre                                                          |
|2  |	appVersion	  |   devuelve la versión                                                         |
|3  |	appCodeName	  |   devuelve el nombre del código                                               |
|4  |	cookieEnabled |	  devuelve verdadero si la cookie está habilitada; de lo contrario, es falso  |
|5  |	userAgent	  |   devuelve el agente de usuario                                               |
|6  |	language	  |   devuelve el idioma. Sólo es compatible con Netscape y Firefox.              |
|7  |	userLanguage  |	  devuelve el idioma del usuario. Solo es compatible con IE.                  |
|8  |	plugins	      |   devuelve los complementos. Sólo es compatible con Netscape y Firefox.       |
|9  |	systemLanguage|	  devuelve el idioma del sistema. Solo es compatible con IE.                  |
|10 |	mimeTypes[]	  |   devuelve la matriz de tipo mime. Sólo es compatible con Netscape y Firefox. |
|11 |	platform	  |   devuelve la plataforma, por ejemplo, Win32.                                 |
|12 |	online	      |   devuelve verdadero si el navegador está en línea; de lo contrario, es falso.|
```

# Metodos del objeto navigator js

**javaEnabled()** comprueba si java está habilitado y **taintEnabled()** comprueba si la contaminación está habilitada. Está en desuso desde JavaScript 1.2.