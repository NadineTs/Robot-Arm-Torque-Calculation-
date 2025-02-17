# Robot-Arm-Torque-Calculation
The primary goal of this project is to design a robotic arm capable of lifting a weight of 1 kg. To achieve this, we need to calculate the required torque at each joint of the arm and select suitable servo motors that can provide the necessary torque to efficiently lift and maneuver the load.

![Image](https://github.com/user-attachments/assets/40b341c3-6028-4d4c-8c38-ef70a6eed8ea)



---

## 1. Given Data  
- Load weight: \( m = 1 \) kg  
- Gravitational acceleration: \( g = 9.80 \) m/s²  
- Arm segment lengths:
  - Joint 3 (End Effector): 4 cm from the load  
  - Joint 2: 10 + 4 = 14 cm from the load  
  - Joint 1 (Base): 15 + 14 = 29 cm from the load  

- Force (F):F = m × g = 1 × 9.80 = 9.80 N

## 2. Torque Calculation Formula:
Torque \( T \) is calculated using the formula:
T = F × d



## 3. Torque Calculation  

### Joint 3 (End Effector)
- Lifting only the 1 kg load  
- Distance: 4 cm  
- Required torque:  
  T3 = 9.80 \times 4 = 39.2  N·cm
 

#### Selected Servo Motor:
- **MG996R Servo**  
  - Torque: 13 kg·cm (≈ 127.53 N·cm)  
  - Voltage: 4.8-7.2V  
  - Purchase Link: [Amazon](https://www.amazon.sa/-/en/Beffkkip-2-Pack-MG996R-Digital-Helicopter/dp/B09JWK494C/ref=sr_1_1?crid=2HPDGCZWUKZXD&dib=eyJ2IjoiMSJ9.JoMfcBv4DDewnJ5kHuLRukhZQGPlxpxgKxCMGeeUEv6I1FNMye3uDdcLfDIPq9QM4gwz5DSKTroYtCgIp-MKzFzC2i3UyUg423yx4V1l9jQamDJqdJu1aVAHdy05bD-70UGkV-VTandu0ujCMqIX1ieBhb8T_i5ZHNFVIf3hnOQCA7smtEixkc_wzX1OJPS6ekZoQdGsunWEZjxgrIZOfNIa6l0OZiGFcQVGQ1SdPtEd9rHI5ighJW4_HPnFa6qRga2RniQ9L8MFwyIoQ9i2pY34ZOvfFjztSw7Z_8zFQSB3vbTQ4U1ChVevGy5pDgL8xD2rbzkrmBR2nCxrAX9oMV0b8FlA2hcvsHcjFTSdSqDUQOFp2DN9l84sdRLMzEuXYE5FqF40NtX-gAr6Gi6QArmhXF4LtbGHA_SEi27iVBcJPstsPCtPEZRgsl58Sl2u.0ikKBkeprgLeDxFhN7zlh6J8jPAWAeKmQD0ZU3iAkSI&dib_tag=se&keywords=MG996R+Servo&qid=1739791402&sprefix=mg996r+servo%2Caps%2C306&sr=8-1) 

---

### Joint 2
- Lifting Joint 3 + Arm + 1 kg load  
- Distance: 14 cm  
- Required torque:  
  T2 = 9.80 \times 14 = 137.2  N·cm
  

#### Selected Servo Motor:
- **DS3218 Servo**  
  - Torque: 20 kg·cm (≈ 196 N·cm)  
  - Voltage: 6.8-8.4V  
  - Purchase Link: [Amazon](https://www.amazon.sa/-/en/Digital-Waterproof-Mechanical-Fittings-Control/dp/B0CP3N4DWW)

---

### Joint 1 (Base)
- Lifting entire arm + all joints + 1 kg load  
- Distance: 29 cm  
- Required torque:  
  T1 = 9.80 \times 29 = 284.2 N·cm
 

#### Selected Servo Motor:
- **JX Servo PDI-HV2060MG**  
  - Torque: 60 kg·cm (≈ 588 N·cm)  
  - Voltage: 6.6-8.4V  
  - Purchase Link: [Amazon](https://www.amazon.sa/-/en/JX-PDI-HV2060MG-Voltage-Helicopter-Airplane/dp/B07PSLD9P9) 
