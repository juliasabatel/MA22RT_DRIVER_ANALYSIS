# MA22RT_DRIVER_ANALYSIS 🏎

**Driver analysis of the MART FS** team during the Formula Student Spain race, last race of the 2021/2022 season.

Endurance is one of the most outstanding **Formula Student** tests, it consists of a 22km timed race with a mandatory driver change in the middle, so there is an A and B driver.
The analysis of the driver consists of a study of speed, acceleration, brake and RPM through the telemetry obtained in the race. We have data from driver A and driver B.


<img width="834" alt="speed" src="https://user-images.githubusercontent.com/29893993/207564778-74184fa2-966c-4d73-8bdd-3feeb8f53830.png">





## TOOLS ⚙️

-	RaceStudio 3 (software)

-	Pandas, Numpy (Python)

-	Power BI

-	Ploty (library)

-	Matolip (library)


## WHAT CAN BE DONE 🔥

Printing of maps by longitude and latitude, aerial plane, dark, white... filtering by speed, acceleration, brake, RMP, longitudinal accelerations, lateral accelerations... 

Comparison of **drivers A and B** by filtering by maximum, minimum and average values.





https://user-images.githubusercontent.com/29893993/207554415-ea66182b-7f8b-46a7-8227-8d4e420ef24c.mov





The graph of the video above belongs to the acceleration of the driver A, the map is segmented by colors so that both the acceleration and other values such as speed etc. are ordered in red tones the highest values and in greenish tones the lowest values (Made with PowerBI). 

On this map an exact point is taken from the lower graph, so you can see exactly where you are. It can also be done in the opposite way, from an exact point on the map to obtain the speed, acceleration, braking and other values that have previously been collected by the telemetry of the car.

For a more accurate comparison, and to obtain conclusions, drivers A and B have been compared in the same [graph]() in which the green color corresponds to driver A and the purple color to driver B.
The upper graph belongs to the speed, the second to the acceleration and the third belongs to the longitudinal acceleration through which brake has been obtained.

<img width="834" alt="telemetry" src="https://user-images.githubusercontent.com/29893993/207556829-0600c475-8113-470e-bdb7-919ec7b09654.png">

## STEP BY STEP ⭐️

-  Obtaining the data in `.csv` format from RaceStudio 3 (software) and dividing the race by laps, having finally 16 `.csv` files of which the first 8 belong to driver A and the final 8 to driver B.


- Import into Python, where the cleaning of the different `.csv` files has been carried out, especially of the **fast lap** of the drivers A and B.


- Exploration of the different files, through which we have obtained the values to filter by lap, obtaining the fastest lap (in this case, it has been done by speed).


- Once the fast laps of each driver are determined (driver A is LAP5 and driver B is LAP8), and the clean values are obtained, the printing of different graphs that visually help the study of the driver's behavior is carried out.

- After visualizing the most relevant data, we proceed to export the clean `.csv` to power BI (microsoft tool) to make interactive graphs and easily select the values.

<img width="834" alt="speed_AB" src="https://user-images.githubusercontent.com/29893993/207568812-aa599a20-f2b6-44d6-8239-31c37eea9f82.png">



## CONCLUSION

The data obtained by driver A and driver B present an interesting behavior because while driver B has more speed and separates him from driver B by 2.22 km/h, driver B has a higher acceleration value and when braking, he has less braking than driver A, making driver A perfect for circuits with many curves while driver B will obtain better results in circuits with more straights.


<img width="805" alt="RESULTS" src="https://user-images.githubusercontent.com/29893993/207619134-97da8aad-e73d-45f7-8715-63898735edac.png">


