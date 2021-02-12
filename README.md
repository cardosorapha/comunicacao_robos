# Comunicação_Robôs

Interface de comunicação USB com rádio para testes do Lambe Sujo, com as seguintes funcionalidades
* Envio de velocidades para até cinco robôs simultaneamente;
* Customização de velocidades para roda direita e esquerda a partir de sliders;
* Recebimento de velocidades de um robô escolhido;
* Plot das velocidades enviadas e recebidas do robô selecionado.

# Instalação e uso

Pré requisitos
* Linux
* QT Creator

As dependências necessárias são relacionadas à comunicação USB (bibliotecas padrão linux)

```c++
#include <fcntl.h> // Contains file controls like O_RDWR
#include <errno.h> // Error integer and strerror() function
#include <termios.h> // Contains POSIX terminal control definitions
#include <unistd.h> // write(), read(), close()
```

A outra dependência é o QcustomPlot, que está presente neste repositório.

# Contato

Raphael Cardoso - cardosodeoliveir@gmail.com

# Desenvolvido na 

![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSJUcp7vYZRgwicMF9AaetSQfGM64N9bouygR3l-a8tDz7XUipSKP3BhaND1EhU407AWziJzVAeV30tfvnKl9Y&usqp=CAU&ec=45774424)
