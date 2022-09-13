<!-- hide -->
# Data Pre-processing Project Tutorial
<!-- endhide -->

- Descarga los datos de Airbnb de Nueva York de Kaggle.com (Encuentra el enlace directo a continuación)
- Realiza tantos análisis de datos exploratorios como puedas para encontrar patrones y obtener información de los datos.
- Usa tu cuaderno de exploración para probar diferentes métodos de limpieza.
- Una vez que tengas tu proceso de limpieza final, usa tu archivo app.py para crear una canalización que limpie tus datos.

## 🌱  Cómo iniciar este proyecto

Esta vez no se hará fork, tómate un tiempo para leer estas instrucciones:

1. Crea un nuevo repositorio basado en el [proyecto de Machine Learning](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) [haciendo clic aquí](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Abre el repositorio creado recientemente en Gitpod usando la [extensión del botón de Gitpod](https://www.gitpod.io/docs/browser-extension/).
3. Una vez que Gitpod VSCode haya terminado de abrir, comienza tu proyecto siguiendo las instrucciones a continuación.

## 🚛 Cómo entregar este proyecto

Una vez que hayas terminado de resolver los ejercicios, asegúrate de confirmar tus cambios, hazle "push" a el fork de tu repositorio y ve a 4Geeks.com para subir el enlace del repositorio.

## 📝 Instrucciones:

**New York City Airbnb data**:

Este es un conjunto de datos que contiene datos de Airbnb sobre la ciudad de Nueva York. Lo usarás para practicar tu nuevo EDA (análisis exploratorio de datos) y habilidades de limpieza de datos.

**Paso 1:**

Utiliza el siguiente conjunto de datos en línea:

```
https://raw.githubusercontent.com/4GeeksAcademy/data-preprocessing-project-tutorial/main/AB_NYC_2019.csv
```

¡Es hora de trabajar en ello!

**Paso 2:**

Usa notebook explore.ipynb para encontrar patrones e información valiosa tanto como puedas. Realiza gráficos que nos ayuden a comprender los patrones encontrados, obtén algunas estadísticas, crea nuevas variables si es necesario, etc.

- ¿Qué podemos aprender sobre diferentes anfitriones y áreas?

- ¿Qué anfitriones son los más ocupados y por qué?

- ¿Hay alguna diferencia notable de tráfico entre las diferentes áreas y cuál podría ser la razón?

No olvides escribir tus observaciones.

**Paso 3:**

Ahora que tienes un hermoso notebook EDA y tienes un mejor conocimiento de los datos, imaginemos que Airbnb te pide que entregues un pipeline de Machine Learning que limpie los datos, a fin de dárselos a su área de modelado para la predicción de precios futuros.

Usa app.py para crear tu pipeline de limpieza que prepara los datos para el modelado. Guarda tus datos limpios en la carpeta de datos 'Procesados'.

Solíamos agregar nuestro archivo .env en el archivo .gitignore para ocultar nuestras contraseñas y credenciales del control de versiones.

> Esta vez, asegúrate de agregar la carpeta de datos a tu archivo .gitignore. Especialmente para grandes conjuntos de datos, esto es muy importante.

En tu archivo README, escribe un breve resumen de tu proceso de limpieza y explica de dónde provienen los datos (Agrega el enlace), porque no cargarás ninguna de las carpetas de datos.
