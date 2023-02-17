1- Three-phase energy monitoring with ESPHome
 
  3 x voltage transformers – one for each phase  (2000/100mA)
  3x 220Ω als burden resistor. Es wird bis maximum 28A reichen.

2- Gas pulse counter
  A gas meter is usually very easy to read. A simple reed contact is sufficient for most gas meters.
  Reed-Kontakt
    
3- Umgebungstemperatur
  NTC z.B. 10kΩ with 10kΩ resistence
  2x 10kΩ für Spannungsteiler + 10µf

4- RF-Receiver and Buzzer
  433MHz TX RX Receiver Superhet RF Modules

All together with an ESP32 z.B. S2 Mini v1.0.0

ESPHome is used for programming and creating the *.yaml file.
