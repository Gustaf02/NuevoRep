<h1 align="center">Equipo de trabajo en la UTN<h1/>

<p align="center">
<img src="https://user-images.githubusercontent.com/92409193/196237446-707e6016-bfde-4e8c-9fec-17e76289338a.png">
</p>

# Ejercicios según el mes 
<details>
    <sumary><b> Asistencia octubre: </b></sumary><br/>
    <ul>
    <li> Carlos Gustavo Ortiz - Laboratorio II - Clase 9 - “Clase aritmética: resta, multiplicación y división” </li>
<li></li>
    </ul>
</details>

# Información de contacto: 

<details>
    <sumary><b>Gustavo Ortiz</b></sumary><br/>
    <ul>
    <li>[linkedin](https://www.linkedin.com/feed/?midToken=AQFRMDW-2-iFPQ&midSig=1_DcMyS90Jaqc1&trk=eml-email_notification_single_search_appearance_01-header-14-home&trkEmail=eml-email_notification_single_search_appearance_01-header-14-home-null-evrdhn%7El16c7rij%7E7t-null-neptune%2Ffeed)</li>
<li></li>
    </ul>
</details>

<p align="center">
<img src="https://user-images.githubusercontent.com/92409193/196229657-22fea5ad-b235-4123-98de-68f40200b6af.gif">
</p>


## **1. Descripción**
    
> Palta, un delivery de comidas saludables, posee sucursales en todo el país. Nosotros somos Hola Mundo, alumnos de la UTN Regional San Rafael y los desarrolladores de este programa para esta empresa. 
    
> Para tareas administrativas el país se encuentra dividido en cinco zonas: Norte, Sur, Este, Oeste y Centro.  
    
> El programa diferencia dos tipos de usuarios: admin y user. Cada uno presenta características propias y funcionalidades, que se explicará en el apartado siguiente. 
    
> También se incluye un sistema de días, donde el programa sabe en cual estamos y cuál fue el anterior, para que el admin tenga información precisa con la cual trabajar. Esto simula una base de datos, la que presenta distintos parámetros y se los ordena para mostrar información, a través de matrices.
  
## **1.1. Tipos de usuarios: user y admin**
    
> Dentro de la opción de user, o usuario, tenemos la opción de rellenar la información de las ventas diarias. La venta muestra qué representante la realizó y en qué zona. 
    
> Dentro de la opción admin se puede apreciar las ventas del día actual y el anterior. Asimismo, el admin puede modificar cuantos representantes tiene por día. Si no lo define, el programa decide 2 opciones según el día. 
    
> Si es el dia 1 y el admin no cambia la cantidad de empleados, se define un valor predeterminado, en nuestro ejemplo ese valor es 8.
> En caso de que el admin cambie la cantidad de empleados, se mantendrá en esta cantidad hasta que el admin los cambie nuevamente, aunque solo se pueden cambiar 1 vez por día.
    
> Una vez ingresados los datos, o simplemente si no se quiere ver nada de lo que se realizó en el día, el admin puede avanzar de fecha y se reinician algunos parámetros para nuevamente, repetir el ciclo explicado.

## **1.2. Zonas y ventas**
    
> La empresa almacena sus datos y obtiene estadísticas sobre el comportamiento de sus representantes y de las ventas. Una vez cargada la información, a través de un menú, el programa puede mostrar:

> > * Total de ventas por zonas.
> > * Total de ventas en cada zona por todos los representantes
> > * Total de las ventas realizadas por un representante 
> > * Total de ventas de cada representante 
> > * Mayor venta, indicando el número de representante que la realizó y la zona.
> > * Datos de venta del día anterior.
> > * Limpiar pantalla
> > * Salir del menú.

## **1.3. Sistema de días**
    
> El sistema de días presenta una importancia relevante dentro del programa.  
> Si no avanza de día, simplemente podremos seguir trabajando como vimos en los ejemplos de los caminos. 
> En el caso de avanzar existen 2 opciones:
> La primera opción es que el usuario no subió los datos de las ventas, entonces se le preguntara al usuario si desea avanzar de todos modos, en caso de avanzar sin subir datos, avanza el día, y se invalida la matriz del día anterior.
> En caso de avanzar con datos subidos, se reinicia el ingreso del usuario, pero se registra que el dia anterior si se trabajó. En este mismo proceso, se registra la matriz anterior y se reinicia la nueva, para evitar errores del tipo “fuera de rango”.

## **1.4. Subprogramas:**
    
> Para terminar de explicar el programa existen cuatro subprogramas:

> > * Llenar matriz: se llama cuando el vendedor va a iniciar los datos.
> > * Reiniciar matriz: iguala los valores de los datos a 0. 
> > * Verificación avance día: revisa que no hayan quedado espacios en blanco. 
> > * Imprimir matriz: separa los datos por zona y representante para una visualización más gráfica y sencilla.
