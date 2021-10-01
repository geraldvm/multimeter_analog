# Multímetro Análogo
Proyecto para el Curso de Taller Analógico de la carrera de Ingeniería en Computadores.

### Para el correcto funcionamiento de estas simulaciones lor archivos descargados deben ejecutarse en el programa
Multisim v14.0

# Medir resistencia

1. Descargue el archivo [ohmeter.ms14](https://github.com/geraldvm/multimeter_analog/blob/main/src/ohmeter.ms14) ubicado en la carpeta src.
2. Abra el archivo en el software de simulación Multisim.
3. Coloque la resistencia que desea medir entre las terminales _Rin_ y _GND_.
4. El Ohmetro posee auto escala, para conocer la escala empleada se puede observar los indicadores en la salidas [1-10],[10-100] y [100-1k].

| LED    | Descripción                                                      |
|--------|------------------------------------------------------------------|
| 1-10   | La resistencia medida se encuentra dentro del rango de 0Ω a 10Ω. |
| 10-100 | La resistencia se encuentra dentro del rango de 10Ω a 100Ω.      |
| 100-1k | La resistencia se encuentra dentro del rango de 100Ω a 1kΩ.      |

***

![Ohmeter](https://github.com/geraldvm/multimeter_analog/blob/main/img/ohmeter.PNG)

# Medir tensión DC

1. Descargue el archivo [voltmeter.ms14](https://github.com/geraldvm/multimeter_analog/blob/main/src/voltmeter.ms14) ubicado en la carpeta src.
2. Abra el archivo en el software de simulación Multisim.
3. Coloque la feunte de tensión o lo que desea medir en paralelo entre las terminales _Vin_ y _GND_.
4. Es importante recordar que el voltímetro mide tensiones en el rango de 5 V a 10 V.
5. El voltímetro posee dos modos de uso: _AC_ y _DC_. Para usar el modo DC debe colocar la entrada AC_Mode en 0 V.

![voltmeter](https://github.com/geraldvm/multimeter_analog/blob/main/img/voltmeter.PNG)

***

# Medir tensión AC

1. Descargue el archivo [voltmeter.ms14](https://github.com/geraldvm/multimeter_analog/blob/main/src/voltmeter.ms14) ubicado en la carpeta src.
2. Abra el archivo en el software de simulación Multisim.
3. Coloque la feunte de tensión o lo que desea medir en paralelo entre las terminales _Vin_ y _GND_.
4. Es importante recordar que el voltímetro mide tensiones en el rango de 5 V a 10 V.
5. El voltímetro posee dos modos de uso: _AC_ y _DC_. Para usar el modo DC debe colocar la entrada AC_Mode en 5 V.
 
![Ohmeter](https://github.com/geraldvm/multimeter_analog/blob/main/img/voltmeter_ac.PNG)

***

# Controlador PWM
![Ohmeter](https://github.com/geraldvm/multimeter_analog/blob/main/img/pwm.PNG)
***
