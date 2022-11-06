Beschreibung des Roboters:

  - Entwickelt wurde 2022 im Labor für Mechatronik der Jade Hochschule. 
  
  - Antrieb
      Differentieller Antrieb mit Getriebemotoren und einem Stützrad
  
  - Sensorik
      - Nativ sind vorne am Roboter zwei CNY70 Reflexlichtschranken im Abstand von ca. 3cm verbaut.
      - weitere Reflexlichtschranken sind jeweils auf der Platine im Bereich der Räder angebracht. Diese dienen ausschließlich dem Erfassen der Raddrehzahl.
      -  Temp / Hall / Touch-Sensor  
      
  - Mikrocontoller
    - ESP32 Wroom 32 mit: Dual-Core 32bit LX6 Mikroprozessoren 
                          448KByte ROM
                          520 Kbyte SRAM
                          RTC
                          12-bit ADC 
                          8-bit D/A converters                         
                         
  - Schnitstellen
    - USB-C zu Programmieren des Roboters
    - UART --> Über stiftleiste
    - I²C --> über Stiftleiste
    - Bluetooth
    - Wifi
   
  - Spannungsversorgung
    - 4x AAA Batterien/Akkus
    - USB-C
    Temp / Hall / Touch-Sensor  
  
  - Programmierung
    Am Einfachsten lässt sich der ESP32 in der Arduino IDE programmieren. Videos und Anleitungen findet ihr im Bereich "Videos"
    Der Roboter kann einfach per USB-C Kabel mit einem Laptop verbunden werden. Alternativ mit einem FTDI-Programmer und der UART Schnittstelle.
    
