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
### Ultrasonido EV3
Para la toma de medidas del sensor de ultrasonido del EV3, se siguieron las instrucciones dadas en la guia del laboratorio con 2 particularidades, debido al guardaescobas de la habitación el sensor de ultrasonido del EV3 tomó como distancia inicial 4mm, sin embargo con el fin de reducir la incertidumbre, adicional a la cinta métrica se marcó con cinta los 100cm, como puede verse en las siguientes fotos:

<img src="https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-Sensores/blob/main/Imagenes/Ultrasonido_EV3.jpg" alt="Ultrasonido_EV3" width="400"> <img src="https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-Sensores/blob/main/Imagenes/Cinta_Ev3.jpg" alt="Cinta_Ev3" width="400">

![image](https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-Sensores/blob/main/Imagenes/Distancia_4mm.jpg)

Dicho experimento se realizó con el siguiente código:

Se realizaron 3 tomas de medias, dando los siguientes resultados:


### Encoder EV3
Para la medición del encoder de los motores se desmontó una de las llantas del robot y la guja plástica que tiene se tomó como indicardor. Alineando dicha aguja con el hueco de la parte superior, se realizaron giros de 35° y se midió con un transpotador el cambio del ángulo, (esta medicion se realizó 3 veces).

<img src="https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-Sensores/blob/main/Imagenes/Encoder_EV3.jpg" alt="Encoder_EV3" width="600">

El código usado fue el siguiente:




En este experimento pudo evidenciarse que el encoder del EV3 no permite giros menos a 45°. Como se ve en el código se le indicó realizar el desplazamiento cada 35°, sin embargo lo realizó cad 45°.

Con los datos tomados se realizaron los siguientes cálculos:



