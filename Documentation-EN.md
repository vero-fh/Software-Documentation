# How to install "my-component" in Ubuntu.

###### In this article we will review how to install the component **my-component** using the terminal in [Ubuntu](https://ubuntu.com/), through the *deb-get* command.


| Index | Topic |
| ----------- | ----------- |
| 1 | Updating the Repositories |
| 2 | Installing deb-get |
| 3 | Installing the Component |
| 4 | Finishing the Installation |

### 1.	Open a terminal[^1] and update your list of software repositories.

Using this command, we allow our computer to install the latest versions of the software within the repository. Enter the following command:

`$ sudo apt update`

> Please allow the command to finish before moving to the next step.

### 2.	Install “deb-get”

In the terminal, run the following command, which will install deb-get[^2], a requirement to continue with the installation of the required component.

`$ curl -sL https://raw.githubusercontent.com/wimpysworld/deb-get/main/deb-get | sudo -E bash -s install deb-get` 


### 3.	Use deb-get to install the component.

With this command, we can download and install the latest version of the component:

`$ sudo deb-get install my-component`

### 4.	Finish the installation.

Wait for the command to finish. Once it is installed, you can open the program from the terminal, entering only the software's name.

`$ my-component`

![](https://cdn.iconscout.com/icon/free/png-256/ubuntu-17-1175077.png)


[^1]: [Guia de uso de la terminal en Ubuntu](https://www.guia-ubuntu.com/index.php/Terminal)
[^2]: [deb-get en GitHub](https://github.com/wimpysworld/deb-get)
