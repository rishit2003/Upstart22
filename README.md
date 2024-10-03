# Upstart22

# Lotus Eye Glasses

<img width="714" alt="Screenshot 2024-10-03 at 2 39 02 AM" src="https://github.com/user-attachments/assets/a303e698-144e-42ce-acff-a306cded058d">


## Overview
Lotus Eye Glasses aim to provide a cost-effective and efficient solution to assist blind and visually impaired individuals with mobility. The glasses utilize modern sensor technology and real-time processing to detect obstacles both at ground level and overhead, addressing limitations of traditional mobility aids like walking canes or guide dogs.

## Problem
- A study by the University of California reveals that 13% of blind individuals experience head-level accidents monthly, and 7% experience falls. 
- Current mobility solutions (walking cane, guide dogs, and partners) fail to protect users from above-ground obstacles (e.g., tree branches).
- According to Orbis, the number of blind individuals is expected to triple by 2050, increasing the need for accessible mobility aids.

## Solution
The Lotus Eye Glasses are designed to help individuals navigate their environment without requiring a walking cane or other aids. The product integrates:
- **Cameras and Ultrasonic Sensors** to detect the distance, height, and type of obstacles.
- **Mini-computer (Raspberry Pi Zero 2)** for real-time image processing and machine learning algorithms.
- **Vibration Motors and Earbuds** to alert the user via sensory feedback (vibration and sound).

## Competitive Advantage
Compared to similar products in the market:
- **Lotus Eye Glasses** retail at an accessible price of $300.
- Competitors such as **IrisVision** cost around $2950 and the **WeWalk Cane** costs $800.
- Lotus Eye Glasses provide obstacle detection at both ground and overhead levels, something other solutions lack.

## Components
- Dual **Cameras** for obstacle detection.
- **Ultrasonic Sensors** for proximity measurement.
- **Mini-computer** (Raspberry Pi Zero 2) to process data.
- **Vibration Motors** to provide tactile feedback.
- **Earbuds** for audio alerts.

## Key Features
- **Real-Time Obstacle Detection**: Identifies ground and overhead obstacles.
- **Affordable**: Priced significantly lower than other technological aids for the visually impaired.
- **Multi-Sensory Feedback**: Provides both auditory and tactile feedback to enhance user awareness and safety.
  
## How It Works
1. **Input**: The glasses capture environmental data through the cameras and ultrasonic sensors.
2. **Processing**: Data is processed by the onboard mini-computer using custom image processing and machine learning algorithms.
3. **Output**: Processed information is relayed to the user via earbuds (sound) or vibration motors for immediate awareness of their surroundings.

## Future Plans
- Continuous software updates for improved object detection accuracy.
- Expand to more markets with a focus on affordability and accessibility.

## References
1. [Watch Your Head Mind Your Step: Mobility-Related Accidents Experienced by People with Visual Impairment, University of California](https://engineering.ucsc.edu/sites/default/files/technical-reports/UCSC-SOE-10-24.pdf)
2. [World sight day 2022, The International Agency for the Prevention of Blindness](https://www.iapb.org/world-sight-day/)
3. [Number of blind people set to triple by 2050, Orbis](https://can.orbis.org/en/news/2017/number-of-blind-people-set-to-triple-by-2050-1#:~:text=253%20million%20people%20are%20visually1990%20to%203.38%25%20in%202015)
