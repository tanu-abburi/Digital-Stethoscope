# Digital Stethoscope  
A **digital stethoscope** that amplifies, filters, and digitally processes heart sounds for enhanced diagnostics and remote monitoring.  
## Project Outline
We intend on developing a digital stethoscope system which includes an acoustic sensor that is attached to the processing unit, which will catch the signal, amplify it using an amplifier circuit using an op amp TL082.
The amplified signal is then sent to the ATMEGA328-P, which then converts the analog signal to a digital one ,which is then displayed as a waveform on the LCD TFT screen.  We intend to 3D printing an enclosure which will offer mechanical support and keep the enclosure compact.
## Working
The custom acoustic sensor is positioned on a pulse point of the body.
The sound is transmitted to an amplifier circuit via a condenser microphone. 
The amplified signal is then sent to the A0 ADC pin of the  ATmega328P microcontroller, where it is processed and displayed on the LCD screen.
On the LCD screen, we display to waveform as well as the calculated BPM rate .

## Simulation Results
![WhatsApp Image 2025-05-11 at 23 04 28](https://github.com/user-attachments/assets/676283ac-7c9b-4407-b349-a52547164ac3)

## Schematic
![Screenshot 2025-04-01 205124](https://github.com/user-attachments/assets/3de2b7ae-8619-4d17-8622-c52183fbfa94)
## PCB Layout and 3D view
![Screenshot 2025-04-01 205035](https://github.com/user-attachments/assets/310cc9ef-4899-44aa-a6ba-efcdcc17590b)
![Screenshot 2025-04-01 205024](https://github.com/user-attachments/assets/aa3de4de-1c26-4c6c-9281-6d6657d3f451)


##  Team Members  
- **Ashley Ann Benoy** - EE23BTECH11204  
- **Avani Chouhan** - EE23BTECH11205  
- **Abburi Tanusha** - EE23BTECH11201  
- **Manugunta Meghana Sai** - EE23BTECH11212  
- **Muthyala Nikhitha Sri** - EE23BTECH11213

## System

## References
https://circuitdigest.com/microcontroller-projects/diy-wireless-digital-stethoscope

https://people.ece.cornell.edu/land/courses/ece4760/FinalProjects/s2012/myw9_gdd9/myw9_gdd9/

https://circuitdigest.com/fullimage?i=circuitdiagram_mic/Wireless-Stethoscope-Circuit.png

https://www.youtube.com/watch?v=w6MbM_f_7Uo

https://www.youtube.com/watch?v=QSXJG3opua8&t=3s
