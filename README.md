# Automatic Fire Fighting Robot using Arduino

An autonomous safety and disaster-management robot engineered to detect localized fire hazards and instantly suppress them. The system operates completely independently of the internet or external networks, making it a reliable choice for standalone emergency safety systems.

---

## 📸 Project Showcase

(./<img width="960" height="1280" alt="WhatsApp Image 2026-06-15 at 3 58 27 PM" src="https://github.com/user-attachments/assets/64f68e4e-777e-493a-acb7-3c2f2336f701" />)

*Figure 1: Completed hardware assembly and sensor orientation.*

---

## 🛠️ How It Works

* **Hazard Detection:** An array of onboard **Flame Sensors** continuously monitors the environment for specific infrared wavelengths emitted by open flames.
* **Intelligent Navigation:** Upon identifying a fire source, the **Arduino Uno** processes the orientation data and sends directional commands to the **L293D Motor Driver**. The dual-shaft gear motors align and navigate the chassis toward the hazard.
* **Active Suppression:** Once the robot reaches an optimal target distance, the Arduino activates a digital output channel, triggering the **5V Water Pump** to stream water directly onto the source until the flame sensor clears.

---

## 🔋 Hardware Components Used

* **Microcontroller:** Arduino Uno (Central Processing Brain)
* **Actuators & Drive:** Dual-Shaft DC Gear Motors (2x) & Robot Wheels
* **Motor Controller:** L293D Motor Driver Module/Shield
* **Sensors:** Infrared Flame Sensor Modules
* **Fire Suppressor:** 5V Mini Submersible Water Pump & Flexible Tubing
* **Chassis & Power:** Robot Car Base Frame & Portable Power Supply Pack
