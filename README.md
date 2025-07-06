#  Fire Fighting Robot

An autonomous fire-fighting robot built using Arduino technology. This bot is designed to detect and extinguish fires efficiently using flame and smoke sensors, combined with a servo-operated water pump mechanism.

##  Abstract

The Fire Fighting Robot offers a compact and intelligent solution to detect and suppress small-scale fires. Using an **Arduino Uno** as the control hub, the robot processes data from multiple flame sensors and an MQ2 smoke sensor for 360° fire detection. A servo motor aims the water pump, which is triggered via a relay module to extinguish detected flames. The bot's movement is powered by **DC motors** controlled through an **L293D motor driver**, and it is energized by **18650 batteries**, making it portable and suitable for fire-prone zones and hazardous environments.


##  Key Features

- **Flame & Smoke Detection**  
  - Four flame sensors for directional accuracy  
  - MQ2 gas sensor for early smoke detection  

- **Fire Suppression Mechanism**  
  - Servo-mounted water pump  
  - Relay control for pump actuation

- **Agile Movement**  
  - Dual DC motors with L293D motor driver  
  - Capable of navigating to fire sources

- **Portable Power**  
  - Powered by two 18650 Li-ion batteries in series  
  - Ensures reliable and long runtime operation


## Components Required

| Component              | Quantity |
|------------------------|----------|
| Arduino Uno            | 1        |
| Relay Module           | 1        |
| Water Pump             | 1        |
| Flame Sensors          | 4        |
| MQ2 Smoke Sensor       | 1        |
| Servo Motor            | 1        |
| L293D Motor Driver     | 1        |
| DC Motors              | 2        |
| 18650 Batteries        | 2        |
| LM2956 Power Module    | 1        |

## Design

![image](https://github.com/user-attachments/assets/1e935512-923d-4b87-a8ce-baf9f32ca469)


##  Output

The robot successfully detects flame and smoke sources, activates its pump mechanism, and extinguishes the fire autonomously. This proves the robot's potential in indoor safety systems, laboratories, and educational demonstrations.



## 📽️ Demo Preview 
![image](https://github.com/user-attachments/assets/2faa6cda-5941-4dcb-8795-22beeeac4034)


##  Future Enhancements
- Add temperature sensors for enhanced fire detection
- Integrate wireless control or app-based override
- Add obstacle avoidance for fully autonomous pathfinding

