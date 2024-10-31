# Practica_7
## Integrantes:  
- Francisco Javier Godinez Lopez
- Pablo Axel Silva Fuentes
- Eduardo David Salas Ayala
## Introducción:  

El objetivo de la práctica es aprender nuevos comandos para el manejo del robot Epson, con un obejtivo en la implementación de matrices. Esto permitirá explorar nuevas posibilidades en las diversas tareas que el robot puede realizar. En esta ocasión, la tarea asignada consistió en realizar un dibujo mediante el uso de matrices, lo que demuestra el potencial de esta técnica para automatizar y mejorar la precisión en trabajos complejos.

Los comando a aprender son los siguientes:

**Power High**
**Speed** 
**Jump3** 
**Here**
**Pallet**

## Instrucciones

El robot Epson debe realizar un dibujo designado.

1. Escoger el dibujo a realizar.
2. Configurar la matriz donde será dibujado limitando las esquinas de dicha matriz. 
3. Programar utilizando la matriz y los nuevos comandos.
4. Programar cada uno de los puntos de la matriz donde sera dibujado.
5. Ajustar la altura de robot epson para ahorrar tiempo entre punto y punto del dibujo.
6. Ejecutar la programación para que el robot realice la tarea asignada.

De tal manera que el codigo desarrollado quedo de la siguiente manera:

```
Function main
Power High
Speed 10

Pallet 0, Esq1, Esq2, Esq3, 10, 10
Go Pallet(0, 1, 1) +Z(15)
Go Pallet(0, 1, 1)
Jump3 Here +Z(15), Pallet(0, 1, 2) +Z(15), Pallet(0, 1, 2)
Jump3 Here +Z(15), Pallet(0, 1, 3) +Z(15), Pallet(0, 1, 3)
Jump3 Here +Z(15), Pallet(0, 1, 4) +Z(15), Pallet(0, 1, 4)
Jump3 Here +Z(15), Pallet(0, 1, 5) +Z(15), Pallet(0, 1, 5)

Jump3 Here +Z(15), Pallet(0, 2, 2) +Z(15), Pallet(0, 2, 2)
Jump3 Here +Z(15), Pallet(0, 2, 3) +Z(15), Pallet(0, 2, 3)
Jump3 Here +Z(15), Pallet(0, 2, 6) +Z(15), Pallet(0, 2, 6)

Jump3 Here +Z(15), Pallet(0, 3, 1) +Z(15), Pallet(0, 3, 1)
Jump3 Here +Z(15), Pallet(0, 3, 2) +Z(15), Pallet(0, 3, 2)
Jump3 Here +Z(15), Pallet(0, 3, 3) +Z(15), Pallet(0, 3, 3)
Jump3 Here +Z(15), Pallet(0, 3, 6) +Z(15), Pallet(0, 3, 6)
Jump3 Here +Z(15), Pallet(0, 3, 7) +Z(15), Pallet(0, 3, 7)

Jump3 Here +Z(15), Pallet(0, 4, 2) +Z(15), Pallet(0, 4, 2)
Jump3 Here +Z(15), Pallet(0, 4, 3) +Z(15), Pallet(0, 4, 3)
Jump3 Here +Z(15), Pallet(0, 4, 4) +Z(15), Pallet(0, 4, 4)
Jump3 Here +Z(15), Pallet(0, 4, 5) +Z(15), Pallet(0, 4, 5)
Jump3 Here +Z(15), Pallet(0, 4, 6) +Z(15), Pallet(0, 4, 6)
Jump3 Here +Z(15), Pallet(0, 4, 7) +Z(15), Pallet(0, 4, 7)

Jump3 Here +Z(15), Pallet(0, 5, 1) +Z(15), Pallet(0, 5, 1)
Jump3 Here +Z(15), Pallet(0, 5, 2) +Z(15), Pallet(0, 5, 2)
Jump3 Here +Z(15), Pallet(0, 5, 3) +Z(15), Pallet(0, 5, 3)
Jump3 Here +Z(15), Pallet(0, 5, 6) +Z(15), Pallet(0, 5, 6)
Jump3 Here +Z(15), Pallet(0, 5, 7) +Z(15), Pallet(0, 5, 7)

Jump3 Here +Z(15), Pallet(0, 6, 2) +Z(15), Pallet(0, 6, 2)
Jump3 Here +Z(15), Pallet(0, 6, 3) +Z(15), Pallet(0, 6, 3)
Jump3 Here +Z(15), Pallet(0, 6, 6) +Z(15), Pallet(0, 6, 6)

Jump3 Here +Z(15), Pallet(0, 7, 1) +Z(15), Pallet(0, 7, 1)
Jump3 Here +Z(15), Pallet(0, 7, 2) +Z(15), Pallet(0, 7, 2)
Jump3 Here +Z(15), Pallet(0, 7, 3) +Z(15), Pallet(0, 7, 3)
Jump3 Here +Z(15), Pallet(0, 7, 4) +Z(15), Pallet(0, 7, 4)
Jump3 Here +Z(15), Pallet(0, 7, 5) +Z(15), Pallet(0, 7, 5)

Home


Fend
```

Para el desarrollo de la práctica, se seleccionó el dibujo de un fantasma del videojuego Pac-Man, con el propósito de realizar pixel art. Esta técnica, que se basa en la creación de imágenes mediante puntos, facilita la ubicación precisa de cada uno dentro de una matriz, permitiendo así completar la tarea asignada de manera eficiente.

por lo que se consigui el siguiente resultado:

![WhatsApp Image 2024-10-24 at 1 51 17 PM](https://github.com/user-attachments/assets/e425b601-a1e4-42b7-9d42-0e0460a3b43a)

En el siguiente video se muestra el proceso que se llevó a cabo para completar la tarea.

https://github.com/user-attachments/assets/0f6ea516-3a81-4a85-8389-ec3e777dda23

## Conclusiones:  
### Francisco Javier Godinez Lopez:
La práctica realizada evidenció la importancia de las matrices como elemento clave en la programación avanzada de robots. Este enfoque nos permitió no solo afianzar conocimientos previos, sino también explorar nuevas posibilidades de optimización en procesos complejos. La integración de comandos adicionales para el manejo de matrices abre caminos hacia soluciones más versátiles y adaptables a los requerimientos específicos de cada tarea. A pesar de algunos desafíos iniciales en la comprensión de ciertos códigos, la tarea de realizar un dibujo facilitó el entendimiento del funcionamiento del robot Epson con matrices, permitiendo cumplir con éxito los objetivos planteados en la práctica.


### Pablo Axel Silva Fuentes: 
El desarrollo de esta práctica permitió adquirir conocimientos valiosos, especialmente sobre la implementación de matrices en la programación robótica. La incorporación de matrices amplía las opciones para resolver tareas asignadas y complementa el dominio de comandos previamente aprendidos. Los nuevos comandos empleados ayudan a optimizar las soluciones de acuerdo con los requisitos específicos. Aunque no surgieron obstáculos mayores, se presentaron algunas dificultades para comprender ciertos comandos nuevos. No obstante, la creación de un dibujo fue de gran ayuda para entender cómo el robot Epson maneja las matrices, logrando cumplir satisfactoriamente con el objetivo inicial de la práctica.


### Eduardo David Salas Ayala:
El desarrollo de esta práctica nos permitió adquirir nuevos conocimientos, en particular sobre el uso de matrices. La aplicación de matrices facilita diversas soluciones en las tareas asignadas y complementa el uso de comandos aprendidos en prácticas anteriores. Los nuevos comandos nos permiten optimizar soluciones según los requerimientos específicos. Durante la práctica no se presentaron obstáculos adversos, aunque hubo pequeñas dificultades al comprender algunos comandos nuevos. Sin embargo, el diseño de un dibujo ayudó a entender cómo el robot Epson trabaja con matrices, logrando así cumplir satisfactoriamente con el objetivo incial de la práctica.

## Referencias bibliográficas
- Epson (2020). EPSON RC+ 7.0 Manual del usuario Administración y desarrollo de proyectos (Ver.7.3). https://files.support.epson.com/far/docs/epson_rc_pl_70_users_guide_spanish_(v73r2).pdf


