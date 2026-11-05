# 🐟 Pecera Inteligente IoT

> **Prototipo de sistema IoT basado en el microcontrolador ESP32 y una arquitectura de software híbrida para el monitoreo continuo de parámetros ambientales y la automatización local y remota de actuadores en un acuario doméstico, integrando supervisión en tiempo real a través de una aplicación móvil cliente.**

### 🛠️ Arquitectura y Tecnologías Principales
* **Hardware IoT:** Procesamiento en el borde con ESP32, sensores telemétricos (temperatura, nivel, luz ambiental), módulo RTC y control de actuadores (relés, servomotor dispensador).
* **Comunicación:** Transmisión de telemetría y comandos mediante protocolo MQTT sobre redes Wi-Fi.
* **Backend:** Servidor en Node.js para la gestión de la base de datos y eventos remotos.
* **Cliente Móvil:** Supervisión y control en tiempo real mediante una aplicación móvil desarrollada en React Native.
