# Lazy-Classifier-Traffic-Accidents-Madrid
## Analysis of Traffic Accidents in the City of Madrid

### ESTRUCTURA DEL CONJUNTO DE DATOS

**Nombre del conjunto de datos:** Accidentes de tráfico de la Ciudad de Madrid (desde 2019)

**Descripción:** Accidentes de tráfico en la Ciudad de Madrid registrados por Policía Municipal con víctimas y/o daños al patrimonio.

**Unidad responsable:** Dirección General de la Policía Municipal

**Descripción de la estructura del fichero de la aplicación SIGIT**

**IMPORTANTE:**
- El fichero incluye un registro por persona implicada en el accidente (conductores, viajeros, peatones, testigos, etc.)
- En el año 2019 y posteriores:
  - La estructura de datos varía respecto a los años anteriores. El detalle de estas estructuras está disponible en el apartado 'Documentación Asociada'
  - No se incluyen registros de testigos.
- Los ficheros de 2010 a 2018 solo registran los accidentes con heridos o con daños al patrimonio municipal.
- Los datos publicados son provisionales hasta seis meses después del año vencido.
- Actualmente no se dispone de datos por barrio.

### TIPOS DE ACCIDENTES:
- **Colisión doble:** Accidente de tráfico ocurrido entre dos vehículos en movimiento (colisión frontal, fronto lateral, lateral).
- **Colisión múltiple:** Accidente de tráfico ocurrido entre más de dos vehículos en movimiento.
- **Alcance:** Accidente que se produce cuando un vehículo circulando o detenido por las circunstancias del tráfico es golpeado en su parte posterior por otro vehículo.
- **Choque contra obstáculo o elemento de la vía:** Accidente ocurrido entre un vehículo en movimiento con conductor y un objeto inmóvil que ocupa la vía o zona apartada de la misma (vehículo estacionado, árbol, farola, etc.).
- **Atropello a persona:** Accidente ocurrido entre un vehículo y un peatón que ocupa la calzada o que transita por aceras, refugios, paseos o zonas de la vía pública no destinada a la circulación de vehículos.
- **Vuelco:** Accidente sufrido por un vehículo con más de dos ruedas, en el que por alguna circunstancia los neumáticos pierden el contacto con la calzada, quedando apoyado sobre un costado o sobre el techo.
- **Caída:** Se agrupan todas las caídas relacionadas con el desarrollo y las circunstancias del tráfico (motocicleta, ciclomotor, bicicleta, viajero en bus, etc.).
- **Otras causas:** Recoge los accidentes por atropello a animal, despeñamiento, salida de la vía, y otros.

### LESIVIDAD:
- **01** Atención en urgencias sin posterior ingreso - *LEVE*
- **02** Ingreso inferior o igual a 24 horas - *LEVE*
- **03** Ingreso superior a 24 horas - *GRAVE*
- **04** Fallecido dentro de las 24 horas - *FALLECIDO*
- **05** Asistencia sanitaria ambulatoria con posterioridad - *LEVE*
- **06** Asistencia sanitaria inmediata en centro de salud o mutua - *LEVE*
- **07** Asistencia sanitaria sólo en el lugar del accidente - *LEVE*
- **14** Sin asistencia sanitaria
- **77** Se desconoce
- **En blanco:** Sin asistencia sanitaria
