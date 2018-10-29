# Dataton Bancolombia

Este es el repositorio de la solución para el *_Dataton BC 2018_* desarrollada por el equipo *_The Plumbers_* conformado por:

1. [Edgar Leandro Jimenez Jaimes](https://github.com/eljimenezj)
2. [Oscar Nicolas Gomez Giraldo](https://github.com/nicolasggiraldo)
3. [Juan Camilo Fernandez Prato](https://github.com/jcfernandezp) 

La aplicación está dividida en 4 partes principales.

### 1. Controla tus gastos

En este apartado el usuario podrá observar cómo ha sido sus transacciones de manera histórica y encontrará algunos gráficos e indicadores estadísticos básicos que le permitirán entender como está frente a otros usuarios.

### 2. Capacidad de ahorro

La capacidad de ahorro se realiza utilizando, en primer lugar, un modelo de predicción de gastos a partir del histórico de transacciones de PSE para cada usuario, luego se estima sus ingresos con la información suministrada de la tabla de usuarios, de manera paralela el usuario puede ingresar un porcentaje de ahorro deseado a partir sus ingresos y una meta de ahorro y el aplicativo le genera un sistema de alerta miento visual (o semáforo ) que le indicará cómo está frente a sus metas de ahorro y su comportamiento de gastos. Por otra parte, se presentan gráficamente los comportamientos de ingresos y pronósticos de gastos.

### 3. Quieres un credito?

Para la asignación de créditos ágil se construyó un modelo de otorgamiento de crédito basado en el perfil del usuario, donde se cuenta con la información de la capacidad de ahorro del apartado anterior y la segmentación estructural que le definió el banco en la información suministrada. De manera que dependiendo el perfil integral del usuario el modelo le asigna o no el crédito, una vez que el usuario sea beneficiado con el crédito, el modelo le informa el monto máximo a prestar, la tasa de intereses asociada y el número de periodos dependiendo de la calificación que se le otorgue por el modelo.

### 4.Invierte tu dinero!

En este apartado se construyó un asistente virtual que a partir de la capacidad de ahorro y el segmento que tiene el cliente le recomienda opciones diferentes de inversión en los fondos con los que cuenta el banco, brindando información incluso de los montos mínimos necesarios para la apertura de estos.


<img src="https://www.grupobancolombia.com/wps/wcm/connect/050251d9-15cc-48a1-8b81-0b94a79b3282/logo-bancolombia.png?MOD=AJPERES&CACHEID=ROOTWORKSPACE-050251d9-15cc-48a1-8b81-0b94a79b3282-men-kU7" alt="Bancolombia" width="400" height="240"/> <img src="https://png2.kisspng.com/sh/3ba3ea652870af325905a191557adfc5/L0KzQYm3V8A0N6t0fpH0aYP2gLBuTfFlaZ9mReVALYTog7r6ggQueJ16hdRucj38grbwkr1mdl5Aed13LXnveX79gfxtbZt0ReJ1dX3ldcP6TcVjO5M3eaoBMUSzcYOATsUyOmQ1SKg9MUW2QIe3VME3PmE9SqM3cH7q/kisspng-adana-su-tesisat-plumber-yreir-en-yakn-ili-vallejo-plumbers-5b3b2a86140a27.5123006415306041660821.png" alt="Plumbers" width="300" height="240"/>
