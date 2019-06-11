# Puerta automática con Arduino
El sistema responde cuando un objeto es detectado a menos de 10cm de distancia del sensor ultras&oacute;nico, cuando est&aacute; dentro del rango abre las puertas accionadas por los servomotores, si el objeto se mueve mayor a 10cm entonces comienza una cuenta de aproximadamente 3 segundos y se cierran las puertas. Podrás encontrar este proyecto con más detalles aquí [Puerta automática con Arduino](https://www.proyecto-teos.com/puerta-automatica-con-arduino).
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

Si requieres más información de este y otros proyectos, puedes ir a nuestra [página web](https://www.proyecto-teos.com) y dar clic en la parte de proyectos en donde encontraras los códigos, diagramas, hojas de datos, librerías, recursos y una documentación más extensa.