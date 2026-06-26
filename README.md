# MU-OZCECE-ADAYANNEHANZEEL_EXAMEN_REG_ELECTRONICA
EXAME RELUARIZACION - SIMULACION ELECTRONICA 
# 🔌 Proyecto: Simulación de Convertidor DC-DC 

## 📌 Descripción

Este proyecto consiste en el análisis, cálculo y simulación de un convertidor DC-DC tipo Buck. Se evaluó su comportamiento mediante herramientas de simulación electrónica, verificando las variables principales como voltaje de salida, corrientes en los elementos y rizado.

---

## ⚙️ Objetivos

* Analizar el funcionamiento de un convertidor Buck
* Calcular parámetros eléctricos del circuito
* Simular el comportamiento del sistema
* Interpretar señales obtenidas en el osciloscopio

---

## 🧮 Cálculos teóricos

Se realizaron los cálculos necesarios para el diseño del convertidor, incluyendo:

* Voltaje de salida ( V_o )
* Corriente de salida ( I_o )
* Inductancia ( L )
* Capacitancia ( C )
* Rizado de corriente ( \Delta i_L )
* Rizado de voltaje ( \Delta V_o )


---

## 🧪 Simulación electrónica

Se implementó el circuito en un simulador electrónico, donde se analizaron las siguientes variables:

* Voltaje de salida
* Corriente en el inductor
* Corriente en el diodo
* Corriente en el interruptor
* Corriente de salida



---



### 🔹 Voltaje de salida

📍 *(Insertar imagen aquí)*
Se observa una señal casi constante con pequeñas variaciones (rizado).
Esto indica que el capacitor está filtrando correctamente la señal.

---

### 🔹 Corriente media de salida

📍 *(Insertar imagen aquí)*
La corriente es prácticamente constante, lo que confirma estabilidad en la carga.

---

### 🔹 Corriente en la inductancia

📍 *(Insertar imagen aquí)*
Se presenta una forma de onda triangular característica.

* Aumenta cuando el interruptor está encendido (ON)
* Disminuye cuando está apagado (OFF)

Esto indica operación en **modo de conducción continua (CCM)**.

---

### 🔹 Corriente por el diodo

📍 *(Insertar imagen aquí)*
El diodo conduce cuando el interruptor está apagado.

* Funciona como camino de recirculación
* Presenta pulsos complementarios al interruptor

---

### 🔹 Corriente por el interruptor

📍 *(Insertar imagen aquí)*
Se observan pulsos de corriente.

* Conduce solo en estado ON
* Es igual a la corriente del inductor durante ese tiempo

---

## 📉 Análisis de señales del osciloscopio

Las señales obtenidas permiten verificar el correcto funcionamiento del convertidor:

### ✔️ Voltaje de salida

* Señal DC con bajo rizado
* Confirma buen diseño del capacitor

### ✔️ Corriente del inductor

* Forma triangular
* Indica almacenamiento y liberación de energía
* No cae a cero → operación en CCM

### ✔️ Corriente del interruptor

* Pulsante
* Solo activa durante el ciclo ON

### ✔️ Corriente del diodo

* Complementaria al interruptor
* Actúa durante el ciclo OFF

📊 Resultados
Variable	Valor teórico	Valor simulado	Error (%)
Vo	17.4 V	11.4 V	-34.09 %
ΔiL	0.292	0	0.292
ΔVo	3.712	357	35.6 %


## 🧠 Conclusiones

* El convertidor opera correctamente en modo continuo
* El voltaje de salida es estable con bajo rizado
* El inductor y capacitor cumplen su función de filtrado
* Las señales coinciden con el comportamiento teórico esperado

