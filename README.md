# VL53LOX
> En lugar de calcular la distancia midiendo la cantidad de luz reflejada desde el objeto (en lo que influye significativamente el color y tipo de superficie). Mide con precisión el tiempo que tarda la luz en viajar desde el objeto más cercano y volver reflejada hasta el sensor (un proceso llamado Time-of-Fly, o Tiempo de vuelo).

![image](https://github.com/Martinslafer/VL53LOX/assets/156008489/e54dabe9-404d-4c2e-b7a9-be201a84c79d)

- Caracteristicas
  - Emisor infrarrojo: 940 nm
  - Distancia: hasta 2000 mm
  - Dirección I2C: Programable
  - Fuente de luz VCSEL (Vertical-cavity surface-emitting laser = Láser de emisión de superficie de cavidad vertical)
  - Sensor de rango con avanzado microcontrolador
  - El chip mide sólo 4,4 x 2,4 x 1,0 mm
  - Medición de distancia rápida y precisa
  - Mide rango absoluto hasta 2 m.
  - El rango reportado es independiente de la reflectividad del objetivo
  - Compensación óptica cruzada integrada avanzada para simplificar la selección del vidrio de cobertura
  - Seguro para el ojo humano
  - Dispositivo láser de clase 1 que cumple con la última norma IEC 60825-1: 2014 – 3ª edición
  - Fácil integración por el sistema de montaje de soldadura del chip
  - No tiene óptica adicional
  - Fuente de alimentación individual
  - Regulador de voltaje integrado en la plaqueta
  - Interfaz I2C para control de dispositivos y transferencia de datos
  - Pines de entrada salida de uso general Xshutdown (para reinicio) e Interrupt (interrupción)
  - Dirección I2C programable

## Arduino Pinout
<img src="https://github.com/Martinslafer/VL53LOX/assets/156008489/8ee939d1-2a42-4d8b-92a5-c38a56f64d1a" width="400" />


| Arduino Pin | VL53LOX Board | Function   |
|-------------|-----------------|------------|
| None        | GPIO1              | Ready       |
| GND         | GND             | Ground     |
| 5v         | VCC             | Power      |
| SDA         | SDA             | I2C Data   |
| SCL         | SCL             | I2C Clock  |
| None      | XSHUT             | Restart/Off  |


## Libreria
- **Name:** Adafruit_VL53L0X
- **Version:** 1.2.4
- **Author:** Adafruit
- **Maintainer:** adafruit <support@adafruit.com>
- **Sentence:** Sensor driver for VL53L0X Time of Flight sensor
- **Paragraph:** Sensor driver for VL53L0X Time of Flight sensor
- **Category:** Sensors
- **Url:** https://github.com/adafruit/Adafruit_VL53L0X
- **Architectures:** *
- **Depends:** Adafruit SSD1306, Adafruit GFX Library
