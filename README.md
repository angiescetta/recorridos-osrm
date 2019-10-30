### *Analizando recorridos y distancias en la Ciudad*

<div class=text-justify>

A continuación vamos a ver un ejemplo de aplicación del servicio de ruteo de "OSRM" (http://project-osrm.org/), un paquete de uso libre, basado en datos de OpenStreetMap, que es muy útil a la hora de calcular distancias (km) y tiempos de viaje (min) entre 2 o más puntos georreferenciados.

El paquete se compone de 4 funciones que son:
- osrmTable(): matriz de tiempos de viaje entre puntos.
- osrmRoute(): camino más corto entre 2 puntos.
- osrmTrip(): viaje entre múltiples puntos.
- osrmIsochrone(): polígono de isocronas.

En este caso vamos a calcular el camino más corto entre 2 puntos con la función osrmRoute().

</div>
