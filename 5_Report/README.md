# **Vehicle Seat Temperature Controlling System**

## **Introduction:**

The seat temperature controlling system is basically used to control the temperature of the seat. The user gets access to turn on the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the activities of the control system are done on a microcontroller called Atmega328. The functionality of the heat control system is coded in embedded c and the working is demonstrated using simuation in a software called SimulIDE.

## Features
- The System will sense that driver or passenger seated or not.
- Driver or Passenger has the access to modify the temperature in the vehicle.
- As per Drivers request, Heater will generate the heat as per requirement.
- It is best for European Countries.
- Low cost and robust system.

## SWOT Analysis
### Strengths
- User Friendly
- Easy to adjust the temperature inside the vehicles.
- Modular Approach.
- Low cost and robust system.

### Weakness
- It can be applicable for those countries which are having low temperature.
### Opportunities
- It can be implemented by having both Heater and AC.
### Threats
- Not suitable for average or high temperature places.

## **4W and 1H:**

### **Why:**
To maintain the warm atmosphere in the vehicles in cold weather.

### **What:**
Temperature controlling system to measure,control and generate heat.

### **Where:**
Automotive Industry.

### **When:**
If temperature inside the vehicle is low.

### **How:**
By installing the system in vehicles.

## Detail requirements
### High Level Requirements
| High Level Requirements      | Description |
| ----------- | ----------- |
| HLR1      | Microcontroller   |
| HLR2   | Temperature Sensor|
| HLR3   | Heat Generation|
| HLR4   | Display|
| HLR5   | Software used|

### Low Level Requirements
| Low Level Requirements      | Description |
| ----------- | ----------- |
| HLR1_LLR1      | ATmega328     |
| HLR2_LLR1   | LM35 and ADC|
| HLR2_LLR2   | ADC with PWM-fast|
| HLR3_LLR1   | Thermoelectric module|
| HLR4_LLR1   |LCD and LED|
| HLR5_LLR1   | Code Blocks with AVR GCC compiler |
| HLR5_LLR2   | SimulIDE |

# Architecture
## Block Diagram
![](https://github.com/abhishekkanap/M2_VehicleSeatTemperatureControllingSystem/blob/862960bcad2a7888f4481df7a3ac0a4addff5358/2_Architecture/Block_Diagram.jpg)
## Flow chart
![](https://github.com/abhishekkanap/M2_VehicleSeatTemperatureControllingSystem/blob/862960bcad2a7888f4481df7a3ac0a4addff5358/2_Architecture/Flow_Chart.jpg)

# Images and Videos
## Simulation Diagram
![](https://github.com/abhishekkanap/M2_VehicleSeatTemperatureControllingSystem/blob/e5f9519f4530753fe126f34b62559c19980d9992/6_ImagesAndVideos/Simulation_Diagram.png)
## Simulation Video
https://user-images.githubusercontent.com/90414155/164933862-cb33fb13-7d7c-4836-8da8-c5394b176cb3.mp4


