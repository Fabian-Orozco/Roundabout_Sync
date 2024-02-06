# **Roundabout Sync**

## **Problem Description**

This project is a C++ traffic simulator for vehicles navigating a roundabout. It utilizes multithreading to model vehicles' movements.

The simulation initializes shared data and parses command-line arguments for settings like minimum and maximum driving times and verbose mode.

Vehicles enter and exit the roundabout following predetermined routes represented by separate threads.

Movement through the roundabout is simulated with random time delays. Semaphores manage access to the roundabout to prevent collisions. Once all vehicles complete their routes, the program prints their paths. 

This simulation aids in understanding traffic dynamics and can be useful for road network optimization and driver behavior analysis.

### **Program features:**

**Programming language:** C++  
**Concurrencia:** Threads de C++, Semáforos (semaphore.h)

### **Compilation:**

Execute the command: `make`  

### **Execution:**

Type the command to execute, followed by the minimum and maximum waiting time in milliseconds and `-v` if you want to know the path of each vehicle.

Example:
`bin/roundabout_sync 100 500 -v`

## **Credits**

**Author:** Fabián orozco chaves
**Contact:** <fabian7orozco@gmail.com>

---

Other paths: 
[Solution Design](./design/readme.md)
