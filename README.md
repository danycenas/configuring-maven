La siguiente guia nos permite configurar Apache Maven en Windows 10.

# Requisitos

- Java SE Development Kit 8 [[Download]](https://www.oracle.com/technetwork/java/javaee/downloads/jdk8-downloads-2133151.html)
- Apache Maven [[Download]](https://maven.apache.org/download.cgi)

# Configurar JAVA_HOME

Instalar el JDK según se indica.

![picture](./img/1.png)

![picture](./img/2.png)

![picture](./img/3.png)

![picture](./img/4.png)

![picture](./img/5.png)

![picture](./img/6.png)

Una vez completada la instalación crear la variable de entorno de la siguiente manera.

![picture](./img/7.png)

![picture](./img/8.png)

![picture](./img/9.png)

![picture](./img/10.png)

![picture](./img/11.png)

Finalmente editar el PATH del sistema y añadir la variable creada.

![picture](./img/12.png)

![picture](./img/13.png)


Verificar el funcionamiento de la variable JAVA_HOME.
```bash
>java -version
java version "1.8.0_211"
Java(TM) SE Runtime Environment (build 1.8.0_211-b12)
Java HotSpot(TM) 64-Bit Server VM (build 25.211-b12, mixed mode)

>javac -version
javac 1.8.0_211
```

# Configurar M2_HOME

Descargar y descomprimir en la ruta específicada.

![picture](./img/15.png)

![picture](./img/16.png)

Luego crear la variable de entorno M2_HOME y añadirla al PATH del sistema.

![picture](./img/17.png)

![picture](./img/18.png)

Verificar el funcionamiento de la variable M2_HOME
```bash
>mvn -version
Apache Maven 3.6.1 (d66c9c0b3152b2e69ee9bac180bb8fcc8e6af555; 2019-04-04T12:00:29-07:00)
Maven home: C:\apache-maven-3.6.1\bin\..
Java version: 1.8.0_211, vendor: Oracle Corporation, runtime: C:\Program Files\Java\jdk1.8.0_211\jre
Default locale: es_PE, platform encoding: Cp1252
OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"
```
