# Car
## Aplicación web que permita a los usuarios calcular el costo en combustible entre dos ciudades en Chile.
## La interacción con el usuario se desglosa en los siguientes pasos:
  ### PASO 1:

    Debe usar ambos selects para elegir dos ciudades distintas (requisito)
    ● El botón “ Buscar ” debe habilitarse sólo cuando el origen y el destino estén definidos
    ● Al presionar el botón Buscar
    ● se despliega el selector de vehículos del paso 2 .
    ● En el menú superior debe existir un tooltip con información acerca del
    funcionamiento del sitio
    ● (BONUS) Al momento de definir el origen y el destino se deben marcar ambos y la
    ruta que los une en el mapa usando el API de google maps.
    
 ### PASO 2:
   
    ● Se deben listar los 4 vehículos disponibles, pudiendo elegir uno de ellos
    ● Al lado del vehículo se debe indicar el costo total del viaje seleccionado basados en
      los kilómetros por litro de cada vehículo y la distancia que separa a las ciudades
      antes elegidas
    ● En la parte inferior del elemento recién desplegado se debe indicar en un campo de
      texto el número de pasajeros. Dicho valor debe ser numérico, positivo, y ser menor o
      igual al máximo de pasajeros del vehículo elegido (dependiendo de cada vehículo)
    ● El botón Compartir carro sólo se habilita cuando se elija un vehículo y el campo de
     número de pasajeros sea válidos
     
 ### ASPECTOS TÉCNICOS:
 
    ● Debe instalar todas las dependencias a usar (Bootstrap ó Materialize, jQuery) con
      NPM usando los flags correspondientes (--save ó --save-dev)
    ● Debe usar SASS de forma correcta, con los correspondientes usos de las variables ,
      mixins y estilos anidados . Todo esto de modo de evitar repetir código.
    ● Debe crear una tarea para compilar los estilos, otra para compilar los scripts, otra
      para mover las imágenes, y una tarea final que llame a las tareas anteriores. Todas
      estas tareas deben estar definidas en su gulpfile.
    ● Todas estas tareas además deben poder ser llamadas desde NPM.
    ● Todo su código realizado debe encontrarse en una carpeta src en la raíz de su
      proyecto.
    ● Todo el código compilado debe generarse en una carpeta dist en la raíz de su
      proyecto.
    ● Para las ciudades disponibles se exige que sean todas las Capitales Regionales de
      Chile (15 ciudades). Para esto se facilita una tabla con las distancias de cada ciudad al
      kilómetro 0 (en la plaza de armas de Santiago).
    ● Para el costo por litro de la bencina considere un costo fijo de CL$673 .
    ● Para los vehículos disponibles se facilita una tabla informativa con el rendimiento
      (Kms/Lt) y la capacidad máxima de pasajeros de estos.
      
###  ANEXOS:

    TIPOS DE VEHÍCULOS
    
    Vehículo Máximo de Pasajeros Consumo (Km/L)
    
     ● Auto 5 - 12
     ● Moto 2 - 21
     ● MiniVan 8 - 7
     ● Camión 3 - 6
    
    
    LISTA DE CAPITALES REGIONALES
    
    Ciudad Distancia a Km 0
    
    ● Arica - 2059
    ● Iquique - 1789
    ● Antofagasta - 1368
    ● Calama - 1567
    ● La Serena - 470
    ● Valparaiso - 116
    ● Santiago - 0
    ● Rancagua - 84
    ● Talca - 257
    ● Concepción - 500
    ● Temuco - 690
    ● Valdivia - 848
    ● Puerto - Montt 1032
    ● Coyhaique - 1888
    ● Punta Arenas - 3004
