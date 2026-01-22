# 💱 Conversor de Monedas - Challenge Alura Hotels

¡Bienvenido al Conversor de Monedas! Este proyecto es parte del Challenge del programa **Oracle Next Education (ONE)** en conjunto con **Alura**.

## 🚀 Funcionalidades
El programa permite realizar conversiones de moneda en tiempo real consultando la **ExchangeRate-API**. Las opciones incluyen:
- Dólar (USD) a Peso Argentino (ARS)
- Peso Argentino (ARS) a Dólar (USD)
- Dólar (USD) a Real Brasileño (BRL)
- Real Brasileño (BRL) a Dólar (USD)
- Dólar (USD) a Peso Colombiano (COP)
- Peso Colombiano (COP) a Dólar (USD)

## 🛠️ Tecnologías utilizadas
- **Java 17**
- **Biblioteca Gson**: Para la manipulación de datos JSON.
- **HttpClient**: Para realizar las solicitudes a la API.
- **Records**: Para modelar los datos de respuesta de forma limpia.

## 📦 Estructura del Proyecto
- `Principal.java`: Clase que contiene el menú interactivo y la lógica de usuario.
- `ConsultaMoneda.java`: Clase encargada de la conexión con la API y el filtrado de datos.
- `MonedaExchange.java`: Record que sirve como DTO para recibir la respuesta JSON.
