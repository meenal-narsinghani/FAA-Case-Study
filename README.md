# FAA Case Sutdy - Part 1
### Model flight landing distance
---

#### View the R Notebook [here](https://meenal-narsinghani.github.io/FAA-Case-Study/FAADataAnalysis%20-%20Part1.html)

---
#### Background:
Landing Distance is the horizontal distance traversed by the aeroplane from a point on the approach path at a selected height above the landing surface to the point on the landing surface at which the aeroplane comes to a complete stop. Landing an aircraft is a difficult process requiring considerable manual dexterity. 
Here we implement a statiscal method that will help in determining landing distance for safe touchdown. Parameters important to the determination of landing distance, such as approach airspeed, touchdown distance, and stopping distance, are evaluated in terms
of probabilities. 

#### Motivation: 
To reduce the risk of landing overrun

#### Goal: 
To study what factors and how they would impact the landing distance of a commercial flight

#### Data Source: 
Landing data (simulated) from 950 commerical flights
See the 2 excel files: **[FAA-1.xls](FAA1.xls)** (800 flights) and **[FAA-2.xls](FAA2.xls)** (150 flights)

#### Variable dictionary:

- ***Aircraft:*** The make of an aircraft (Boeing or Airbus).
Duration (in minutes): Flight duration between taking off and landing. The duration of a normal flight should always be greater than 40min.
- ***No_pasg:*** The number of passengers in a flight.
- ***Speed_ground(in miles per hour):*** The ground speed of an aircraft when passing over the threshold of the runway. If its value is less than 30MPH or greater than 140MPH, then the landing would be considered as abnormal.
- ***Speed_air (in miles per hour):*** The air speed of an aircraft when passing over the threshold of the runway. If its value is less than 30MPH or greater than 140MPH, then the landing would be considered as abnormal.
- ***Height (in meters):*** The height of an aircraft when it is passing over the threshold of the runway. The landing aircraft is required to be at least 6 meters high at the threshold of the runway.
- ***Pitch (in degrees):*** Pitch angle of an aircraft when it is passing over the threshold of the runway.
2
- ***Distance (in feet):*** The landing distance of an aircraft. More specifically, it refers to the distance between the threshold of the runway and the point where the aircraft can be fully stopped. The length of the airport runway is typically less than 6000 feet.

#### Analytical Approach:

A structred analytical approach comprising of the steps mentioned below was followed to model the ***flight landing distance***

1. Initial Setup & Analytical Dataset creation
2. Exploratory Data Analysis
3. Factor Analysis
4. Variable Selection & Model Implementation
  * Simple Linear Regression
  * Multiple Linear Regression
  * Forward StepAIC Regression









