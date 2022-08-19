###  NETWORKING VPC

## Virtual Private Cloud
En amazon trabajaremos por regiones, es decir todo lo que haga en una región se queda en esa región.
Lo primero que tendriamos que hacer entonces, sería crear mi propia VPC, es decir mi propia red virtual privada en la que desplegar todos los componentes que quiera utilizar.
Nuestra vpc estará compuesta por lo siguiente.

Bloque CIDR:
Basicamente es donde iran almacenadas las direcciones de nuestros recursos en :
- IPV4
- IPV6
- Ambos
### Es el conjunto de direcciones ip que se le asignan a esta VPC
Nos facilitaran cierta máscara, en la que podremos asignar nuestros recursos.
Cada VPC puede tener de A a N zonas de disponibilidad.
En estas zonas de disponibilidad es donde se van a generar las subredes.

<img width="562" alt="Captura de pantalla 2022-08-19 a las 12 31 31" src="https://user-images.githubusercontent.com/55221433/185600236-9fbb0934-9892-4330-a701-ae4d841afab4.png">

## Parte Práctica - Crear una VPC

En todos los servicios vamos al apartado Networking & Content Delivery > VPC

<img width="380" alt="Captura de pantalla 2022-08-19 a las 12 41 57" src="https://user-images.githubusercontent.com/55221433/185601794-7fe7594d-a6d2-4dfb-a330-69e182208e40.png">

Por defecto vamos a poder ver que amazon nos crea una vpc por cada región en la que puedo trabajar.

<img width="290" alt="Captura de pantalla 2022-08-19 a las 12 52 35" src="https://user-images.githubusercontent.com/55221433/185603465-b257fb1b-57ea-4c73-8acd-921703c20a07.png">

Creamos una nueva VPC

![Aug-19-2022 13-09-20](https://user-images.githubusercontent.com/55221433/185606131-a5b4d3cb-4faa-40c0-979f-1eaab956fa6d.gif)

Le damos nombre y una ip por defecto

![Aug-19-2022 13-34-19](https://user-images.githubusercontent.com/55221433/185609772-d7e3be67-0892-4b92-b08f-232acbeb3e66.gif)

Listo tenemos una VPC creada.

## Propiedades de una VPC


