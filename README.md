# Puerta automática con Arduino
Este es un proyecto de una puerta automática con Arduino.

### Empezando
Este proyecto se basa en los sensores que hemos usado anteriormente, si no tienes mucha experiencia en el manejo de dichos sensores puedes consultar nuestros repositorios.

- Sensor de distancia https://github.com/proyectoTEOS/Sensor-de-distancia-HC-SR04-con-Arduino
- Servomotor https://github.com/proyectoTEOS/Servomotor-con-Arduino

### Requisitos
- Tener el IDE de [Arduino](https://www.arduino.cc/en/Main/Software) (o el de tu preferencia) con la versión más actual
- Contar con las librerías [Ultrasonic](https://github.com/JRodrigoTech/Ultrasonic-HC-SR04) y [Servo](https://github.com/arduino-libraries/Servo)
- Tener el material para hacer el proyecto (claro)

### Materiales
Enlistaremos los materiales que se necesitan para realizar el proyecto, pero puedes conseguir componentes similares.
- 1 Arduino UNO R3
- 2 Servomotores Futaba S3003
- 1 Ultrasónico HC-SR04
- 1 Led de color rojo y otro verde (o del color que prefieras)
- 2 resistencias de 330ohms
- 1 Protoboard (opcional)
- **Fuente de poder de 5 volts a 1 Amper (indispensable para suministrar voltaje a los servos, por ningún motivo alimentes los servomotores con Arduino)**

### Código
**[Aqui](https://github.com/proyectoTEOS/Puerta-automatica-con-Arduino/blob/master/Puerta-automatica-con-Arduino.ino)** podrás obtener el link del código, esta comentado de tal forma que puedas entender su estructura y función.

### Diagrama
El siguiente esquemático muestra como se debe conectar todos los componentes con la placa.
![](/resources/diagrama-puerta-automatica.jpg)

Toma en cuenta estas consideraciones:
- Conecta los servomotores a una fuente externa de voltaje (de 5 volts y 1 Amper como mínimo)
- Puentear GND de la fuente externa con GND del Arduino
- Si vas a utilizar otro tipo de servomotores, considera la carga que pueden soportar

### Prototipo
Aquí dejaremos imágenes de nuestro prototipo, pronto subiremos los pasos para que puedas realizar un prototipo similar.
![](/resources/prototipo-puerta-automatica-1.jpg)
![](/resources/prototipo-puerta-automatica-2.jpg)
![](https://www.proyecto-teos.com/git/puerta/demo-puerta.gif)