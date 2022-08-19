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
