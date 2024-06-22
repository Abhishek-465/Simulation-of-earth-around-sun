
# 1) Problem Statement

* Create a simulation to track the orbit of the Earth around the Sun for a period of 1 year.
* Use Euler and Runge - Kutta method of 4th order (RK4) for this task.
* Find the distance from Earth to Sun at Apogee using Euler and RK4 method and compare it with the original.

   ## 1.1) Given Equations

   * Accn of Earth due to Gravity of the Sun                    
       → $a = -\frac{GM}{|r|^3}\times\vec{r}$
   
   * ODE for Position                               
       → $\frac{dr}{dt} = v$ 
   
   * ODE for Velocity                  
      → $\frac{dv}{dt} = a$
   
   ## 1.2) Initial Condition
   * Earth is at its Perihelion (closest to Sun)

# 2) Simulation for Earth

![Logo](earth_orbit.png)

   
  

# 3) Simulate any planet of your choice
* Here is the [Planetary Fact Sheet](https://nssdc.gsfc.nasa.gov/planetary/factsheet/
) that you can refer.
