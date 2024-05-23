# Laboratorio-Sensores

Integrantes: Daniel Felipe Cantor Santana, Giovanni Obregon, Thomas Hernandez Ochoa, Andres Felipe Zuleta Romero


## Sensor Lidar
    


## Sensor de ultrasonido HS-SR04

Se realizó el montaje segun la guía,  inicialemente se verificó el puerto de conexión y que se visualizaran correctamente los datos en arduino, usando el archivo "[Usound3.ino](https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-Sensores/blob/main/Códigos/usound3.ino)", además se verificaron las distancias como se aprecia en las siguientes imagenes:

<img src="https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-Sensores/blob/main/Imagenes/Montaje.jpg" alt="Montaje" width="400"> <img src="https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-Sensores/blob/main/Imagenes/Sensor.jpg" alt="Sensor" width="400"> 

<img src="https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-Sensores/blob/main/Imagenes/conexión.jpg" alt="Conexión" width="400"> <img src="https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-Sensores/blob/main/Imagenes/verificacion.jpg" alt="Verificación" width="400">

Se verificó cada medida con un flexometro, ya que este se asumirá como el "valor real". Las distancias que seleccionamos fuero de 1m, 1,2m y 1,5 m:
![image](https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-Sensores/blob/main/Imagenes/Medidas.jpg)



Posteriormente se empleó el Script "¨[ultrasound3.m](https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-Sensores/blob/main/Códigos/ultrasound3.m)" de MatLab dicho código toma 100 muestras de médida y da una gráfica de comportamiento, como las que se muestra a continuación: 
![image](https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-Sensores/blob/main/Imagenes/Grafica_1m.jpg)
![image](https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-Sensores/blob/main/Imagenes/Grafica_1,2m.jpg)
![image](https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-Sensores/blob/main/Imagenes/Grafica_1,5m.jpg)

Para cada longitud se calculó la desviación estandar, la media ademas de sus errores absolutos y relativos:

...


## Sensores EV3
Para la toma de medidas de sensores EV3, se siguieron las instrucciones dadas en la guia del laboratorio con 2 particularidades, debido al guarda escobas de la habitación el sensor de ultrasonido del EV3 tomó como distancia inicial 4mm, sin embargo con el fin de reducir la incertidumbre, adicional a la cinta métrica se marcó con cinta los 100cm, como puede verse en las siguientes fotos:


