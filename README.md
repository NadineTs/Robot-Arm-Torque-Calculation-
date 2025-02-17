# Robot-Arm-Torque-Calculation


## 1. Problem Statement  
To ensure the robotic arm can lift 1 kg, we need to calculate the required torque for each joint and select an appropriate servo motor for each.

---

## 2. Given Data  
- Load weight: \( m = 1 \) kg  
- Gravitational acceleration: \( g = 9.80 \) m/s²  
- Arm segment lengths:
  - Joint 3 (End Effector): 4 cm from the load  
  - Joint 2: 10 + 4 = 14 cm from the load  
  - Joint 1 (Base): 15 + 14 = 29 cm from the load  

- Force due to weight:
  \[
  F = m \times g = 1 \times 9.80 = 9.80 \text{ N}
  \]

---

## 3. Torque Calculation  

### Joint 3 (End Effector)
- Lifting only the 1 kg load  
- Distance: 4 cm  
- Required torque:  
  \[
  \tau_3 = 9.81 \times 4 = 39.2 \text{ N·cm}
  \]

#### Selected Servo Motor:
- **MG996R Servo**  
  - Torque: 13 kg·cm (≈ 127.53 N·cm)  
  - Voltage: 4.8-7.2V  
  - Purchase Link: [Amazon](https://www.amazon.com/TowerPro-MG996R-Digital-Torque-Helicopter/dp/B0081XIKTY)  

---

### Joint 2
- Lifting Joint 3 + Arm + 1 kg load  
- Distance: 14 cm  
- Required torque:  
  \[
  \tau_2 = 9.80 \times 14 = 137.2 \text{ N·cm}
  \]

#### Selected Servo Motor:
- **DS3218 Servo**  
  - Torque: 20 kg·cm (≈ 196 N·cm)  
  - Voltage: 6.8-8.4V  
  - Purchase Link: [Amazon] 

---

### Joint 1 (Base)
- Lifting entire arm + all joints + 1 kg load  
- Distance: 29 cm  
- Required torque:  
  \[
  \tau_1 = 9.80 \times 29 = 284.2 \text{ N·cm}
  \]

#### Selected Servo Motor:
- **JX Servo PDI-HV2060MG**  
  - Torque: 60 kg·cm (≈ 588 N·cm)  
  - Voltage: 6.6-8.4V  
  - Purchase Link: [Amazon]  
