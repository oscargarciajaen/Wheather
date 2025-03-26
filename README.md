# Weather App

Esta es una aplicación web que permite a los usuarios buscar el clima de una ciudad. Utiliza la API de OpenWeather para obtener datos meteorológicos en tiempo real basados en el nombre de la ciudad ingresada por el usuario.

## Descripción

La aplicación solicita al usuario que ingrese el nombre de una ciudad en un campo de búsqueda. Al hacer clic en el botón "Search", la aplicación obtiene las coordenadas geográficas de la ciudad y, a continuación, consulta los datos meteorológicos de esa ubicación. Los datos obtenidos incluyen la temperatura, la descripción del clima y el ícono correspondiente. La información se muestra en la misma página web.

## Características

- Búsqueda de clima por ciudad.
- Muestra la temperatura en grados Celsius.
- Muestra una breve descripción del clima (por ejemplo, "despejado", "lluvioso", etc.).
- Muestra un ícono representativo del clima actual.

## Tecnologías utilizadas

- **HTML5**: Estructura de la página.
- **CSS3**: Diseño y estilo de la interfaz de usuario.
- **JavaScript (ES6)**: Lógica de la aplicación y manejo de eventos.
- **OpenWeather API**: API externa para obtener datos meteorológicos.

## Instrucciones de uso

### 1. Clonar el repositorio

Primero, clona el repositorio en tu máquina local:

```bash
git clone https://github.com/tu_usuario/weather-app.git
```

## 2. Obtención de la clave API de OpenWeather

Para utilizar esta aplicación, necesitarás una clave API de OpenWeather. Sigue estos pasos:

1. Ve a [OpenWeather](https://openweathermap.org/).
2. Regístrate o inicia sesión en tu cuenta.
3. Ve a "My API keys" y genera una nueva clave.
4. Copia la clave API generada.

## 3. Configurar la clave API

En el archivo `script.js`, reemplaza `REPLACE_WITH_YOUR_API_KEY` con la clave API que obtuviste en el paso anterior.

```javascript
const apiKey = "REPLACE_WITH_YOUR_API_KEY"; // Coloca tu clave API aquí
```

## 4. Ejecutar la aplicación

Una vez que hayas configurado la clave API, abre el archivo `index.html` en tu navegador para ver la aplicación en acción.

## 5. Uso de la aplicación

1. Ingresa el nombre de la ciudad en el campo de texto.
2. Haz clic en el botón "Search".
3. La aplicación mostrará la temperatura, la descripción del clima y un ícono representativo del clima.

## Estructura del proyecto

El proyecto tiene la siguiente estructura de archivos:

weather-app/ 

│ 

├── index.html # Página principal de la aplicación 

├── styles.css # Estilos CSS para la interfaz de usuario 

├── script.js # Lógica JavaScript que maneja la búsqueda y la visualización del clima 

└── README.md # Documentación del proyecto