# Maven-Doxygen
Herramientas de Calidad del Producto Software y Documentación. SonarQube, Maven y Doxygen

## 0.- Instalación manual de Maven
#### Antes de comenzar

Antes de instalar Maven se requiere que previamente tener instalado JDK y tenerlo añadido en las variables de entorno. 

### Descargar Maven

El enlace para descargar Maven es el siguiente http://maven.apache.org/download.cgi#Installation en el apartado files aparecen los enlaces de de descarga elige el comprensor que prefieras.

### Instalar Maven

Primero se debe descomprimir el archivo y se recomienda copiar la carpeta en el directorio `C:\Program Files` o donde el usuario prefiera.
Ahora, se debe añadir a las variables de entorno el directorio `Maven\bin`. Se procede a comprobar la versión actual de `Maven` con el comando `mvn -v`.

![Version de Maven](./img/maven-version.png)

## 1.-Construcción del proyecto en Eclipse

El proyecto descargado ha de ser integrado en nuestro IDE, para ello, y para evitar ciertos errores de compilación, se creará un nuevo `Maven simple project` en Eclipse que contendrá la estructura básica del futuro proyecto.

![pom.xml básico generado automáticamente](./img/basic-pom.png)

Como se puede apreciar, el `pom.xml` no es el final, sino el básico deseado para modificar.


# Bibliografía

[Instalación de Maven](https://dev.to/vanessa_corredor/instalar-manualmente-maven-en-windows-10-50pb)
[]()
[]()
[]()
[]()
