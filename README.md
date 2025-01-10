# Lazy-Classifier-Traffic-Accidents-Madrid
## Analysis of Traffic Accidents in the City of Madrid

### DATASET STRUCTURE

**Dataset Name:** Traffic Accidents in the City of Madrid (since 2019)

**Description:** Traffic accidents in the City of Madrid recorded by the Municipal Police involving victims and/or property damage.

**Responsible Unit:** General Directorate of the Municipal Police

**Description of the SIGIT application file structure**

**IMPORTANT:**
- The file includes one record per person involved in the accident (drivers, passengers, pedestrians, witnesses, etc.).
- For 2019 and later:
  - The data structure differs from previous years. Details of these structures are available in the 'Associated Documentation' section.
  - Witness records are not included.
- Files from 2010 to 2018 only record accidents involving injuries or municipal property damage.
- The published data is provisional for up to six months after the end of the year.
- Neighborhood-level data is not currently available.

### TYPES OF ACCIDENTS:
- **Double collision:** Traffic accident involving two moving vehicles (head-on, side-front, side collisions).
- **Multiple collision:** Traffic accident involving more than two moving vehicles.
- **Rear-end collision:** Accident occurring when a vehicle in motion or stopped due to traffic circumstances is struck from behind by another vehicle.
- **Collision with obstacle or road element:** Accident involving a moving vehicle with a driver and a stationary object on the road or in an adjacent area (parked vehicle, tree, lamppost, etc.).
- **Pedestrian hit:** Accident involving a vehicle and a pedestrian on the road or walking on sidewalks, refuges, walkways, or other areas of the public road not intended for vehicle traffic.
- **Overturn:** Accident involving a vehicle with more than two wheels, where the tires lose contact with the road and the vehicle ends up on its side or roof.
- **Fall:** Includes all falls related to traffic circumstances (motorcycle, moped, bicycle, bus passenger, etc.).
- **Other causes:** Includes accidents caused by animal collisions, cliff falls, road departures, and other scenarios.

### SEVERITY:
- **01** Emergency care without subsequent admission - *MINOR*
- **02** Hospitalization of 24 hours or less - *MINOR*
- **03** Hospitalization of more than 24 hours - *SERIOUS*
- **04** Death within 24 hours - *FATAL*
- **05** Outpatient care after the accident - *MINOR*
- **06** Immediate medical care at a health center or mutual aid center - *MINOR*
- **07** Medical care only at the accident site - *MINOR*
- **14** No medical care
- **77** Unknown
- **Blank:** No medical care
