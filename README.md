# Embedded Systems Journey

A project and lab journal by Vivek Chaudhary, an ICT engineering student at Pandit Deendayal Energy University. The portfolio traces how signals enter a system, how the controller processes them, and how to observe the output in hardware or simulation.

## Project portfolio

| Project | Engineering focus | What to look for |
| --- | --- | --- |
| [ESP32 Air Quality Monitoring System](https://github.com/vivekar217220-del/AQI_Monitoring_System-) | ADC sensor input, I²C display, status alerts, and Wi-Fi telemetry experiments | Pin assignments, local monitoring firmware, and HTTP and MQTT recordings. The AQI uses simulated PM2.5. |
| [Arduino Smart Robotic Car](https://github.com/vivekar217220-del/Ultrasonic-and-Bluetooth-Controlled-Obstacle-Avoiding-Robotic-Car-using-Arduino-and-Motor-Shield) | Ultrasonic obstacle detection, Bluetooth commands, and motor control | Demo recording and build notes about driver and wiring iterations. |
| [RevAlert](https://github.com/vivekar217220-del/PWM-Based-DC-Motor-Speed-Controller-with-RPM-Display-and-Safety-Indication-System) | ATmega2560 ADC, Timer1 PWM, display, and threshold alarms | How a potentiometer input controls the motor duty cycle and produces a displayed RPM estimate. |
| [AVR Interrupt Demo](https://github.com/vivekar217220-del/Embedded_Interrupts) | External interrupts, reset behavior, and GPIO | LED and buzzer indications that make the interrupt and reset events observable. |
| [IR Home Automation](https://github.com/vivekar217220-del/Remote-Control-Based-Home-Automation-for-Smart-Home-.) | NEC IR decoding and command dispatch | How timed pulses become appliance output commands in an Arduino and Tinkercad project. |
| [8-Bit CPU in Logisim](https://github.com/vivekar217220-del/Simple-8-Bit-CPU-Design-using-Logisim) | Digital logic and instruction execution | How the program counter, instruction register, control logic, and ALU contribute to the fetch–decode–execute cycle. |
| [Dual-Output Power Supply](https://github.com/vivekar217220-del/Dual-Output-Regulated-Power-Supply-230V-AC-to-12V-9V-DC-) | AC-to-DC conversion and linear regulation | Proteus schematic for reviewing the transformer, bridge, filter, and regulator stages. |

## Hands-on build notes

### Water-level indicator

An academic breadboard project built with Raj Patel. A common probe and three level probes feed BC547 transistor stages. The stages activate colored LEDs as water reaches each level, and the highest level triggers a buzzer. The journal records the probe connections and the decision to move the prototype to a breadboard during assembly.

![Breadboard water-level indicator with probes, LEDs, and buzzer](<Screenshot 2026-02-16 200353.png>)

### Arduino robotic car

A group build combining an Arduino, HC-SR04 distance sensor, HC-05 Bluetooth module, motor driver, and geared motors. The journal documents driver experiments, signal and power connections, and serial wiring issues encountered during setup. The team received guidance from Dr. Ravi Kant and Dr. Ankur Changela.

![Robotic car chassis with geared motors, controller, and wiring](<Screenshot 2026-02-16 200416.png>)

### CPU design and microcontroller exercises

The individual CPU project traces instruction data from memory through control logic, registers, and the ALU. The ATmega2560 exercises document GPIO output with a blinking LED, displaying digits 0–9 on a seven-segment display, and driving a geared motor through an L293D.

## How to use this journal

- Start with the [project journal](What_I_Done) for component tables, build notes, and wiring decisions.
- Open the linked project repository for any available firmware, schematic, screenshot, or recording.
- Compare the artifact with its description. Physical build photos capture assembly, while screenshots capture the corresponding design or simulation state.
