# Documentacion e Instalación de JDK en el Ubuntu con sus respectivos pasos

## Alumno: Ricardo Adrian Medina Gómez

### INDICE

#### 1 actualización del sistema
#### 2 Instalación de Java 
#### 3 Java Instalado
#### 4 Versión específica 8 de Java
#### 5 Configuración de las variables de Entorno
#### 6 Modificación del fichero profile
#### 7 Java versión 8 Instalado

## 1 Actualización del sistema con el comando.

```
sudo apt-get update
```
![actualizado el sistema](https://user-images.githubusercontent.com/78496018/134310622-131e1fab-e323-4c20-b644-191c04cc7a6a.png)

## 2 Instalación de Java con el comando. (sudo apt-get install default-jdk)

```
sudo apt-get install default-jdk
```
![Instalacion Java](https://user-images.githubusercontent.com/78496018/134311297-97de8675-4e67-4f90-8a89-995555954c8a.png)

## 3 Instalado Java.
```
java -version
```
![java version](https://user-images.githubusercontent.com/78496018/134311558-c153a59e-683e-4837-84f9-19c8c0ff286f.png)

## 4 Versión específica de Java.

## OpenJDK8: sudo apt install openjdk-8-jdk
```
sudo apt install openjdk-8-jdk
```
![8](https://user-images.githubusercontent.com/78496018/134487621-87b8f241-0b2b-4067-9c69-920903055553.png)

# 5 Configuración de las variables de Entorno.

## Lista de las versiones de OpenJDK instaladas
```
ls /usr/lib/jvm
```
![diferentes versiones Java](https://user-images.githubusercontent.com/78496018/134488159-bb9e70b2-ff34-4b7b-b598-d87b1d67f229.png)


# 6 Modificación del fichero profile

## Realizamos los cambios seleccionando la versión 8 

![nano profile](https://user-images.githubusercontent.com/78496018/134489766-51f17cd9-211a-455d-b09f-42d95f49be5b.png)

![Nano completado](https://user-images.githubusercontent.com/78496018/134489870-73822486-7c2c-4529-a190-c279160e808b.png)

## Y ya estaría completado el cambio de la version 

![8](https://user-images.githubusercontent.com/78496018/134494947-8de67991-4680-47f6-a2fa-248c4cd199c9.png)


# 7 Java versión 1.8 Instalado.





