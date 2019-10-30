### *Analizando recorridos y distancias en la Ciudad*

<div class=text-justify>

A continuación vamos a ver un ejemplo de aplicación del servicio de ruteo de "OSRM" (http://project-osrm.org/), un paquete de uso libre, basado en datos de OpenStreetMap, que es muy útil a la hora de calcular distancias (km) y tiempos de viaje (min) entre 2 o más puntos georreferenciados.

El paquete se compone de 4 funciones que son:
- osrmTable(): matriz de tiempos de viaje entre puntos.
- osrmRoute(): camino más corto entre 2 puntos.
- osrmTrip(): viaje entre múltiples puntos.
- osrmIsochrone(): polígono de isocronas.

En este caso vamos a calcular el camino más corto entre 2 puntos con la función osrmRoute(). Para esto vamos a aprovechar los dataset disponibles en el Portal de Datos Abiertos de la Ciudad http://https://data.buenosaires.gob.ar/ utilizando la ubicación de hospitales públicos (formato CSV) y los polígonos de los barrios de la Ciudad (formato geoJSON). Como ambos archivos tienen información geográfica vamos a poder ubicarlos en el espacio y calcular las distancias entre ellos.

</div>
