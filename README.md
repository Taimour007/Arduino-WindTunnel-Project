

**Description:**  
This project integrates an **Arduino-based control system** with a **wind tunnel** to measure aerodynamic forces, specifically **drag** and **lift**, at different angles of attack. The primary goal is to create a system that allows for real-time force measurements and adjustments during wind tunnel testing to assess the aerodynamic performance of various objects.

### **Project Components & Features:**

- **Arduino Integration:**  
  The core of the project is an **Arduino microcontroller** that interfaces with multiple sensors and actuators. The Arduino controls and processes the data from sensors to calculate drag and lift forces acting on the object being tested.

- **Force Measurement:**  
  The system uses **load cells** connected to **HX711 amplifiers** to measure the forces in both the **x-axis** (drag) and **y-axis** (lift). The force values are calculated and transmitted in real-time to the Arduino, which then processes and displays the results.

- **Angle of Attack Control:**  
  The system incorporates **servo motors** controlled by Arduino to adjust the angle of attack of the test object. This adjustment allows for real-time data acquisition of forces at varying angles, helping to optimize aerodynamic performance and identify key factors that affect drag and lift.

- **Wind Speed Measurement:**  
  **Ultrasonic sensors** and a **speed sensor** are used to monitor the wind speed within the tunnel. The wind speed data is fed into the system to calculate the aerodynamic coefficients (drag coefficient, lift coefficient) based on the measured forces and wind velocity.

- **Real-time Data Display:**  
  The project includes a **real-time display system**, where the data is presented graphically or iteratively, allowing for immediate analysis of aerodynamic performance during testing. This could involve output to a **serial monitor**, a **LCD screen**, or a **PC interface**.

- **Flexibility:**  
  The system is designed for versatility and can be adapted to different test objects by adjusting the setup, such as changing the geometry of the object or altering wind tunnel conditions. The control system allows for easy modification and experimentation.

### **Applications & Outcomes:**
- **Educational Tool:**  
  This project serves as an educational tool for understanding aerodynamic principles in real-time and is suitable for both academic and practical applications in aerodynamics, automotive design, or aerospace engineering.
  
- **Practical Applications:**  
  The system can be used for testing various objects such as **bluff bodies**, **airfoils**, or **vehicles**, making it a valuable tool for performance analysis, design optimization, and understanding how design changes influence drag and lift forces.

- **Data Analysis & Optimization:**  
  Through detailed analysis of the **drag and lift coefficients** at various angles of attack, engineers can fine-tune designs for optimal aerodynamic performance, making it a useful tool for **product development** and **research**.

