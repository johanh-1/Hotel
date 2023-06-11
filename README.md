# Hotel Gen1
Herramienta realizada para un hotel que facilita la asignación, reserva, supervisión y control de pagos de los huéspedes. El nombre de la empresa, logos y el resto de la información fueron cambiados para garantizar la privacidad del cliente.

## Contexto
Hotel Gen 1 es un hotel ubicado en Bogotá que anotaba a sus clientes en una libreta a mano. Por lo anterior, para este hotel era muy demorado y no se llevaba un control óptimo sobre los huéspedes del hotel ni sobre el dinero que les faltaba pagar. Además, era muy dificil obtener información de interés para el negocio como por ejemplo cuales eran las habitaciones más solicitadas, cuanto se había generado en un mes, cuántos clientes se habían ido sin pagar, cuales eran las habitaciones menos solicitadas, etc.

## Solución - Hojas
Con la idea de tener un mayor control sobre los huéspedes del hotel y sus respectivos pagos se creó una herramienta de Excel que consta de cuatro hojas:
1. Principal: Esta hoja sirve a modo de resumen y se puede observar; la cantidad de habitaciones disponibles; exactamente cuales habitaciones estan libres (color verde), cuales se desocupan este mismo día (color amarillo) y cuales estan ocupadas (color rojo); una lista con las habitaciones que se desocupan este mismo día (señalando de color azul las personas que ya han pagado totalmente su reserva y de color naranja aquellas personas que no han pagado la totalidad de su estadía); y una tabla con la información de los precios de cada habitación. <br> ![image](https://github.com/johanh-1/HotelGen1/assets/136139101/a464884d-77c6-40ac-a8c0-55978860edf0)
2. Calendario: Esta hoja permite observar un calendario dinámico de cada una de las habitaciones, la idea es que el operador pueda observar fácilmente cual es la disponibilidad de cada habitación cada uno de los días del mes. Por lo anterior, el operador puede cambiar de habitación, meses o años oprimiendo los botones correspondientes. También, esta hoja tiene el botón ***Crear Reserva*** que permite crear una reserva para la habitación que esté observando en ese momento. <br> ![image](https://github.com/johanh-1/HotelGen1/assets/136139101/c5db176a-b43d-4629-97da-d3f9180ff6e3)
3. Buscador: Esta hoja permite buscar reservas por identificador, cédula del titular, habitación o piso. <br> ![image](https://github.com/johanh-1/HotelGen1/assets/136139101/95bded17-7f30-4d7c-89de-0e9c9b4dcac7)
4. Dashboard: Esta hoja permite observar con gráficas y tablas información relevante del negocio como por ejemplo, ingreso bruto total por habitación y mes, cantidad de reservas realizadas por habitación y mes, habitaciones más solicitadas y una comparativa por mes del total que se ha abonado y lo que faltó por cancelar. <br> ![image](https://github.com/johanh-1/HotelGen1/assets/136139101/58bf334c-3890-42bd-87bf-2b8f024c742c)

## Solución - Formularios
Aparte de las hojas mostradas anteriormente, se crearon tres formularios con el fin de que fuera más fácil interactuar con la herramienta:

1. Crear reserva: Este formulario permite crear una reserva en el que los campos amarillos (Titular, Celular, Número de Documento, etc) son obligatorios mientras que los campos blancos (correo electrónico, total abonado, comentarios, etc) son opcionales. Este formulario permite seleccionar la fecha de ingreso y la fecha de salida y de forma dinámica va mostrando en pantalla el valor total de la reserva de acuerdo al número de noches seleccionadas. Finalmente, de forma totalmente opcional se puede llevar un registro de los acompañantes del titular. <br> ![image](https://github.com/johanh-1/HotelGen1/assets/136139101/d56e6a68-b3ea-49b7-8d60-d381e086ca32) <br> ![image](https://github.com/johanh-1/HotelGen1/assets/136139101/8490494c-b07b-4d6e-bb5b-f4caa2a8477d)
2. Detalles de la Reserva: Este formulario permite observar los detalles de una reserva determinada y, también, permite registrar un pago para esa reserva así como modificarla o eliminarla. <br> ![image](https://github.com/johanh-1/HotelGen1/assets/136139101/eef52697-ce78-4401-9d34-39cebae961ce)
3. Registrar Pago: Este formulario permite registrar el pago de una reserva. El nuevo saldo se modifica a medida que el usuario escribe el valor del pago realizado. <br> ![image](https://github.com/johanh-1/HotelGen1/assets/136139101/0332c668-f593-4bad-a6d6-8c4d4e33905d)

A continuación se muestra un video demostrativo.

### Video 
https://github.com/johanh-1/HotelGen1/assets/136139101/fb8de4f0-7583-4bac-b3f2-ac2b5e262da9

## Manual
Se creó un manual de usuario para que sea más fácil aprender a utilizar la herramienta y tener un punto de refencia para buscar información sobre los distintos procesos que se puede realizar.





Índice             |  Lista de Figuras
:-------------------------:|:-------------------------:
![image](https://github.com/johanh-1/HotelGen1/assets/136139101/c19e7973-d5ff-4409-81b9-8394cef3f39b)  |  ![image](https://github.com/johanh-1/HotelGen1/assets/136139101/7e6e7b2a-10be-4252-85f9-f33be92401ab)
