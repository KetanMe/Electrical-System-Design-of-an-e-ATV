# Electrical-System-Design-of-an-e-ATV
![image](https://github.com/KetanMe/Electrical-System-Design-of-an-e-ATV/assets/121623546/cea2da10-91b2-4a8f-a4ee-67cd0cc9b70f)

Certainly! Here's a more detailed and refined version of the electrical system design for an e-ATV, divided into high voltage and low voltage systems:

### Electrical System Design of an e-ATV

The electrical system of the e-ATV is categorized into two main subsystems based on voltage levels: High Voltage (HV) and Low Voltage (LV).

#### High Voltage System
The High Voltage system operates at voltages greater than 15V and less than 60V. It comprises several critical components:

1. **Li-ion Battery:**
   - Provides the primary power source for the e-ATV.
   
2. **Battery Management System (BMS):**
   - Monitors and manages the battery pack to ensure safe operation and optimal performance.

3. **Motor:**
   - Drives the e-ATV and is responsible for propulsion.
   
4. **Motor Controller:**
   - Regulates the power from the battery to the motor, controlling speed and torque.
   
5. **Battery Charger:**
   - Charges the Li-ion battery pack when connected to an external power source.

#### Low Voltage System
The Low Voltage system operates below 15V and includes various auxiliary components essential for safety and functionality:

1. **Kill Switches:**
   - Two switches designed to quickly disable the vehicle in emergency situations.

2. **Reverse Light:**
   - Illuminates when the e-ATV is in reverse mode, enhancing visibility.

3. **Reverse Alarm:**
   - Provides an audible alert when the e-ATV is reversing, ensuring awareness.

4. **Ready to Drive Sound Buzzer:**
   - Indicates readiness of the e-ATV for operation after startup.

5. **Ignition Switch:**
   - Controls the main power to the vehicle's electronics.

6. **Start Button:**
   - Initiates the startup sequence for the e-ATV.

7. **Brake Light:**
   - Illuminates when brakes are applied, signaling deceleration to others.

8. **Indicator Lights:**
   - Provide visual signals for turn indications and operational statuses.

9. **TSAL (Tractive System Active Light):**
   - Flashes at a frequency of 3 to 5 Hz to indicate the status of the High Voltage system.

10. **Brake Switch:**
    - Detects when the brakes are applied and triggers corresponding lights and safety features.

#### Main Circuits in the Low Voltage System

1. **TSAL (Tractive System Active Light):**
   - Utilizes an IC555 timer circuit to flash the indicator light, indicating the operational status of the HV system.

2. **Ready to Drive Sound (RTDS):**
   - Uses an IC555 timer circuit to activate a buzzer briefly upon vehicle readiness, ensuring the user is informed.

3. **Brake to Tractive System:**
   - Employs an SCR switching circuit to ensure the e-ATV starts only when the correct startup sequence, including brake engagement, is followed. This circuit triggers the High Voltage Contactor (HVC) relay, allowing power to the vehicle.

This detailed breakdown outlines how the e-ATV's electrical system integrates both high and low voltage components to ensure safe, efficient, and reliable operation. Each subsystem and circuit plays a crucial role in enabling the vehicle's performance and safety features.
