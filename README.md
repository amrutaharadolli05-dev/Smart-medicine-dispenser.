# Smart-medicine-dispenser.
A smart medicine dispenser that automates pill scheduling using sensors, a microcontroller, buzzer alerts, and real-time reminders. It ensures accurate dosage, prevents missed medicines, and improves patient safety by providing a reliable and user-friendly medication management system

Overview  
This is a Smart Medicine Dispenser system that automates the process of dispensing medicines at scheduled times. The goal is to help patients take the correct dosage at the right time and reduce medication errors.  

Problem Statement  
- Patients often forget to take their medicines at the correct time.  
- Manual dispensing can lead to wrong dosage or missed medicines.  
- In care facilities, it’s difficult for caregivers to monitor if patients have taken their medicines correctly.  

Objectives  
1. Automate medicine dispensing based on a predefined schedule.  
2. Provide reminders or alerts when it’s time to take medicines.  
3. Ensure secure access to the dispenser.  
4. Maintain a log of dispensed medicines for monitoring.  

Components / Technologies Used  
- Microcontroller (Arduino)   
- Real Time Clock (RTC) module  
- Push button / Switch  
- Buzzer / LED for alarms  
- Power supply / Battery  
- (Optional) Display (LCD / OLED)  
- Wires, PCB / Breadboard  


Working Principle
1. The RTC module keeps track of the current time.  
2. Based on a predefined schedule, the microcontroller activates a servo motor to dispense medicine from a compartment.  
3. A buzzer or LED alerts the patient or caregiver.  
4. The system maintains a log (in memory or external storage) of each dispense event.  
5. (Optional) If a compartment is empty, raise an alert / indication.  


Features  
- Scheduled dispensing  
- Reminder with buzzer or LED  
- Multiple compartments for different medicines  
- Simple user interface (button / switch)  
- Secure dispensing  
- Event logging  


