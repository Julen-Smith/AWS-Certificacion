# Capa gratuita
Existen tres tipos de productos gratuitos en amazon :
- Pruebas de ciertos productos.
- Ciertos productos durante el primer año.
- Productos gratuitos de por vida.

Ver un poco lo que incluye la capa gratuita -> https://aws.amazon.com/es/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all

# Creación de la cuenta

Es un registro normal, se pide tarjeta de crédito sí o sí.

A la hora de hacer login, también cabe destacar que tendremos dos opciones:
- Usuario Root (Cuenta con la que estamos registrados)
- Usuario IAM (Identity Access Manager) basicamente es un usuario con privilegios límitados. Supongo que lo investigaré más tarde.

# Infraestructura Global - Regiones
Los puntos azules corresponden a donde tiene alojados Amazon sus CPDs \
<img width="938" alt="Captura de pantalla 2022-08-18 a las 3 23 09" src="https://user-images.githubusercontent.com/55221433/185271540-ad05e346-463e-4f00-a608-f18d320906f9.png">

## ¿ Por qué seleccionar una región ?
- Motivos legales (Por ejemplo tema de protección de datos aquí en España/Europa)
- Precio (Amazon no mantiene el mismo precio en todas las regiones, tema impuestos y demás)
- Latencia (Hacia el usuario final)
- Disponibilidad de servicio

# IMPORTANTE
## Alarma de facturación
Todos los los datos de métricas de facturación se almacenan en la Región EE. UU. Este (Norte de Virginia). \
Estos datos incluyen los cargos estimados para todos los servicios de AWS que utilices, además del conjunto total estimado de los cargos de AWS. \
Por lo que es importante haber cambiado a Virginia antes de hacer la alarma de facturación. 

## Configuración

### Para empezar iremos a nuestro perfil > Panel de facturación

<img width="316" alt="Captura de pantalla 2022-08-18 a las 4 12 26" src="https://user-images.githubusercontent.com/55221433/185277908-d1422c15-70c2-4784-ae06-cf369b78e170.png"> 

### Perfil > Panel de facturación > Preferencias de facturación

<img width="1344" alt="Captura de pantalla 2022-08-18 a las 4 22 47" src="https://user-images.githubusercontent.com/55221433/185278950-c29a5ce3-84cb-4fff-bbc7-45c48b637bae.png">


### Marcar todas las casillas señaladas

<img width="1033" alt="Captura de pantalla 2022-08-18 a las 4 29 48" src="https://user-images.githubusercontent.com/55221433/185279896-9b0b0e36-f586-450f-9f43-84754c39d7f0.png">

### Guardar las preferencias si no saldrá la opción de Facturación mas tarde

<img width="219" alt="Captura de pantalla 2022-08-18 a las 4 50 43" src="https://user-images.githubusercontent.com/55221433/185282300-c4338838-1644-43ef-962a-7338691c3024.png">


### Perfil > Panel de facturación > Preferencias de facturación > Administre las alertas de facturación

<img width="1424" alt="Captura de pantalla 2022-08-18 a las 4 35 57" src="https://user-images.githubusercontent.com/55221433/185280624-d5d2684b-a5b3-49dc-aa1d-0bed2c86318b.png">

### Perfil > Panel de facturación > Preferencias de facturación > Administre las alertas de facturación > Crear Alarma > Seleccionar nueva métrica

<img width="785" alt="Captura de pantalla 2022-08-18 a las 4 45 47" src="https://user-images.githubusercontent.com/55221433/185281771-e45acfbc-d305-4495-ac82-a2e229706a76.png">

### Seleccionar nueva métrica > Facturación > Cargo total estimado > Click en usd y seleccionar métrica

![imagen](https://user-images.githubusercontent.com/55221433/185282789-17db17a3-cb7d-4ec8-bc94-dbbcfb776e9d.png)


### Configurar métrica en función a lo deseado

<img width="513" alt="Captura de pantalla 2022-08-18 a las 4 58 14" src="https://user-images.githubusercontent.com/55221433/185283574-8cb0827d-f943-4778-94a2-9343917de8f8.png">

### Configurar aviso en función a lo deseado

<img width="511" alt="Captura de pantalla 2022-08-18 a las 5 04 53" src="https://user-images.githubusercontent.com/55221433/185284275-10a9c892-21c9-47b8-a24c-4998bcfa4976.png">

### Cerrar la alarma

<img width="851" alt="Captura de pantalla 2022-08-18 a las 5 10 34" src="https://user-images.githubusercontent.com/55221433/185284727-2cb8d3c7-6608-449f-95dd-9eebac0a38bd.png">

### Una vez terminado nos saldrá este aviso por seguridad, unicamente hay que validar la suscripción desde el email



<img width="1160" alt="Captura de pantalla 2022-08-18 a las 5 12 18" src="https://user-images.githubusercontent.com/55221433/185284954-e8af1421-12a8-4759-a295-b760cce08e6f.png">
