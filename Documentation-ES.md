# Cómo instalar "my-component" en Ubuntu.

###### En este artículo explicaremos cómo instalar el componente **my-component** a través de la terminal de [Ubuntu](https://ubuntu.com/), utilizando el comando *deb-get*.


| Índice | Tema |
| ----------- | ----------- |
| 1 | Actualización de repositorios |
| 2 | Instalación de deb-get |
| 3 | Instalación de componente |
| 4 | Fin de instalación |

### 1.	Abra una terminal[^1] y actualice su lista de repositorios de software.

Mediante este comando, permitimos a nuestra computadora instalar las versiones mas recientes del software dentro del repositorio. Ingrese el siguiente comando:

`$ sudo apt update`

> Aguarde a que el comando finalice para avanzar al siguiente paso.

### 2.	Instale “deb-get”

Dentro de la terminal, corra el siguiente comando, que instalará deb-get[^2], requisito para proceder con la instalación del componente requerido.

`$ curl -sL https://raw.githubusercontent.com/wimpysworld/deb-get/main/deb-get | sudo -E bash -s install deb-get` 


### 3.	Utilice deb-get para instalar el componente.

Con el siguiente comando, podremos descargar e instalar la versión más reciente de nuestro software:

`$ sudo deb-get install my-component`

### 4.	Finalice la instalación.

Aguarde a que el comando finalice. Una vez instalado, puede abrir el programa desde la terminal ingresando únicamente el nombre del mismo.

`$ my-component`

![](https://cdn.iconscout.com/icon/free/png-256/ubuntu-17-1175077.png)


[^1]: [Guia de uso de la terminal en Ubuntu](https://www.guia-ubuntu.com/index.php/Terminal)
[^2]: [deb-get en GitHub](https://github.com/wimpysworld/deb-get)
