# Tipos de kernel

## Kernel monolitico
<p> Es un tipo de de kernel que consiste en el que todas las funcionalidades principales del sistema operativo corren solamente en el espacio del kernel, los controladores de los dispositivos y servicios estan incluidos directamente en el. Se toma con enfoque simple y eficiente pero no modular. </p>

## Kernek microkernel
<p> Este tipo de kernel solamente implementa las funciones escenciales en el espacio kernel, asi mismo los servicios y los controladores de los dispositivos se ejecutan como procesos dentro del espacio del usuario. Es de tipo modular, una ventaja es que es menos propenso a fallos, pero la desventaja es que puede ser menos eficiente dibido a la comunicacion entre procesos. </p>

## Kernel hibrido

<p> Es el cual combina caracteristicas del kernel monolitico y del microkernel. Algunos de sus servicios y controladores corren en el espacio kernel, mientras que otros estan en el espacio de usuario. Lo cual busca obtener un equilibrio entre rendimiento y modularidad. </p>

## Kernel exokernel 

<p> Tiene un enfoque donde el kernel proporciona una abstraccion minima sobre el hardware, permitiendo a las aplicaiciones tener un control mas directo sobre los recursos del sistema. Las aplicaciones pueden implementar sus propias reglas de gestion de recursos. </p>

## Kernel nanokernel

<p> Es un tipo de kernel extremadamente ligero que proporciona solo las funcionalidades mas basicas, asi como la administracion de procesos y la comunicacion entre ellos. La mayoria de las demas funcionalidades se implementan como servicios externos. </p>