# Requirements

## Introduction
Now-days everyone is looking for automation and advancements in all the sectors. The Vehicle Seat Heat Monitoring System is capable of maintaining of heat in the vehicles seats. In European countries, the temperature is very low and any electronic designer should make sure that his equipment should work efficiently in that whether. 
In our project, the sensor will sense is the driver has been seated or not and if the driver seated then he need to set the temperature accordingly. Based on that our controller will set the heater to required temperature. The Heater will generate the heat and a LCD display will show requested the temperature. In our project we have used ATmega328 microcontroller along with temperature sensor, Push button, Heat generator, LED and LCD diplay,etc.

## Features
- The System will sense is driver or passenger seated or not.
- Driver or Passenger has the access to modify the temperature in the vehicle.
- As per Drivers request, Heater will generate the heat accordingly.
- It is best for European Countries.
- Low cost and robust system.
- Modular Approach.

## SWOT- Strengths, and Weakness, Opportunities Threats
### Strengths
- User Friendly
- Easy to alter the temperature inside the vehicles.
- Modular Approach
- Low cost and Robust system.

### Weakness
- Its only applicable for those countries which are having low temperature.
### Opportunities
- It can be implemented by having both Heater and AC.
### Threats
- Not suitable for average or high temperature places.

## 4W's and 1'H
### What : 
* Vehicle seat Temparature Monitoring System
### Where :
*  Used in Automotive Industries
### When:
*  At low or high Temperature


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
| HLR5_LLR1   | VS code with AVR GCC compiler |
| HLR5_LLR2   | SimulIDE |


# Architecture
## Block Diagram

![BlockDiagram](https://user-images.githubusercontent.com/94158848/144252353-b59a1418-ab91-470d-8abe-8768d463ff76.png)


## Flow Chart
![Flow_chart](https://user-images.githubusercontent.com/94158848/144252562-c0065241-7c9d-4bcc-b261-9cc929136fb9.png)


# Test Plans

|  Test ID | Description  | Input  | Output  | Status |
|---|---|---|---|---|
| TID_01  | Is person seated  | push button=1| push button=1| PASS  |
| TID_02  | Is person not seated  | push button=0| push button=0 | PASS  |
| TID_03  | Temperature Request | Temp=0| heater=Off | PASS  |
| TID_04  | Temperature Request | Temp=20| heater=20 degree generation | PASS  |
| TID_05  | Temperature Request | Temp=25| heater=25 degree generation | PASS  |
| TID_06  | Temperature Request | Temp=29| heater=29 degree generation | PASS  |
| TID_07  | Temperature Request | Temp=33| heater=33 degree generation | PASS  |
| TID_08  | LED ON | Button=1 && Heater=1| LED=1 | PASS  |
| TID_09  | LED OFF | Button=0 && Heater=0| LED=0 | PASS  |
| TID_10  | LCD Display | Temperature :)<br />20 deg Cel| Temperature :)<br />20 deg Cel| PASS  |

# Images And Videos
## Simulation Images
![simulIDE](https://user-images.githubusercontent.com/94158848/144254210-aaa70728-a119-4f53-a499-2c0c43f388d1.png)


![Temparature](https://user-images.githubusercontent.com/94158848/144263954-d493e215-1778-4548-a565-ea3d48f58327.png)

![Temparature_change](https://user-images.githubusercontent.com/94158848/144264124-d4691efe-2c71-4638-95ad-b1bc6d5ac377.png)




## Contributors List and Summary
|PS no. |  Name   |    Project Title    |
|-------|---------|----------------|
| `40020879` | Vikas Vengaldas |  Temperature Monitoring System |  


