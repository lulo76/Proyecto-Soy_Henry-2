<p align=center><img src=https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png><p>

# <h1 align=center> **Lucas Wayar - PROYECTO INDIVIDUAL Nº2** </h1>

# <h1 align=center>**`Machine Learning`**</h1>

<p align="center">
<img src="https://blog.bismart.com/hubfs/20190903-MachineLearning.jpg"  height=300>
</p>
 

<hr>  

## **Introduccion**

Un importante Centro de Salud lo ha contratado con el fin de poder predecir si un paciente tendrá una estancia hospitalaria prolongada o no, para poder administrar la demanda de camas en el hospital según la condición de los pacientes recientemente ingresados.

## **Objetivos:**

Este es un proyecto individual para confeccionar en 4 dias, iniciando  con un proceso EDA (Análisis Exploratorio de Datos). Utilizando la información contenida en el dataset asociado, la cual recaba una muestra histórica de sus pacientes.
Estos corresponden a ciuerta informacion basica, como por ejemplo, Edad, Genero, Departamento de atencion entre otros.

## **Esquema**

<p align=center>
<img src = 'https://miro.medium.com/max/1400/1*GZwFvLQSgMjpmvLudTXVkA.png' height = 400></p>

## **Resultados**

He realizado dos pruebas de prediccion. En hambas he utilizado el mismo modelo de prediccion y las mismas variables.
La diferencia radica solamente en los atributos que he designado al modelo de regresion.
 *Utilizando los siguientes atributos me entrega el siguiente resultado:

        "lr = LogisticRegression(penalty='l2', 
                                class_weight='balanced'
                               )"

        * Accuracy del modelo de Reg. Logistica :    0.558
        * Recall del modelo de Reg. Logistica :      0.471


 *Utilizando los los atributos por defecto entrega los siguiente resultado:

        "lr = LogisticRegression()"

        * Accuracy del modelo de Reg. Logistica :    0.61
        * Recall del modelo de Reg. Logistica :      0.917
