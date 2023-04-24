# taxi-service
it's a car park and it's drivers management application. you can see tables with all the information about your cars, drivers, car manufacturer and you can add drivers to one certain car that you wish. You can create and delete any car and it's manufacturer and driver. Used to have control about what cars you have in your taxi park and what the driver is driving a certain car and the quantity of your cars and its drivers.

🎯Functions:
  links:
  - /drivers/add (create new driver)
  - /drivers (show all the drivers)
  - /cars/add (create new car)
  - /cars (show all the cars)
  - /manufacturer/add (create new manufacturer for the car)
  - /manufacturers (show all the manufacturers)
  - /cars/drivers/add (add driver to car)
  - /login/logout (logging feature)

⚙️Project structure:
- models
- dao
- controllers
- services
- filter

Imports:
<img width="494" alt="Captura de pantalla 2023-04-23 a las 19 49 05" src="https://user-images.githubusercontent.com/112902418/233856233-f75e555b-aabd-4bdd-a93a-4e4942b31084.png">


👀How to start it:
- in the resources file you can find an database
structure to copy, so you can create it and connect it to this project (i used an MySQL).
- install TomCat server (9th version recommended) and connect this project to it.
- after all just run it, and it will redirect you to the page,
so you can navigate it (directions described in functions earlier).
