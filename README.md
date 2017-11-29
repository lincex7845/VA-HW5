# VA-HW5
Tarea 5 - Visual Analytics - Ex-becarios Fulbright por regiones en Colombia

Dataset: [Cantidad de exbecarios por region](https://github.com/lincex7845/VA-HW5/blob/master/conteo_areas_regiones/conteo_areas_regiones.tsv)

Consideraciones:
- Se descartaron los datos de Bogota, Medellin y Cali debido a que estas ciudades
   concentran la mayor cantidad de exbecarios Fulbright
- Para esta visualizacion se tomaron en cuenta solamente los datos de exbecarios entre 2005 y 2015,
  ya que en este periodo se encuentra la mejor distribuida la cantidad de exbecarios en todo el pais.
- Se agruparon los exbecarios por regiones con similitudes culturales y geograficas:
  - Caribe (Atlantico, Cordoba, Sucre, Bolivar, Guajira, Cesar, San Andres y Providencia)
  - Pacifico (Costa pacifica de Nariño y Valle, Choco)
  - Santaderes (Norte Santander y Santander)
  - Llanos Orientales (Meta y Casanare)
  - Amazonia (Caqueta, Amazonas, Vaupes)
  - Sur-occidente (Valle, Cauca, Nariño)
  - Tolima Grande (Tolima y Huila)
  - Eje Cafetero (Risaralda, Quindio, Caldas)
  - Valle de Aburra: Municipios de Antioquia en la Cuenca del Rio Medellin (Bello, Envigado, La Estrella, Itagüi etc)
  
WHAT:

Datatable: 288 registros, 4 atributos
- Region: Categorico
- Cohorte: Cuantitativo secuencial
- Academic_Area: Categorico
- Total: Cuantitativo secuencial

WHY (Tareas):
- Presentar la distribucion de exbecarios por region y por area de estudio entre 2005 y 2015
- Identificar tendencias de crecimiento o decrecimiento por region y area de estudio entre 2005 y 2015
- Comparar la cantidad de exbecarios por area de estudios entre regiones durante 2005 y 2015  

HOW:
- Modismo: box plot
- Marcas:
  - Puntos: outliers o atipicos
  - Lineas: valores minimos y maximos
  - Area rectangular: cuartil
- Canales:
  - Posicion Horizontal: Regiones
  - Posicion Vertical: Exbecarios por area de estudio, por año
  - Color: Area de estudio
  - Longitud (vertical): Areas de estudio con mayor cantidad de exbecarios
  
Presione [aqui](https://lincex7845.github.io/VA-HW5/) para ir al demo
