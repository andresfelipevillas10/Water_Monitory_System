---
description: >-
  WMSV3: monitoreo hídrico de bajo costo para apoyar la gestión del riesgo
  durante El Niño.
icon: hand-wave
---

# WMS

## Water Monitoring System — WMSV3

WMSV3 es la versión definitiva de nuestro sistema IoT de monitoreo hídrico. Mide condiciones ambientales y niveles de agua para apoyar la detección temprana de escenarios de riesgo asociados al Fenómeno de El Niño.

### Características

<table data-card-size="large" data-view="cards"><thead><tr><th></th><th>Característica</th><th>Descripción</th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td><h4>💰</h4></td><td><h4>Bajo costo</h4></td><td>Componentes accesibles para facilitar su reproducción y despliegue.</td><td></td></tr><tr><td><h4>🧩</h4></td><td><h4>Fácil de usar</h4></td><td>Visualización local y consulta remota en una arquitectura clara.</td><td></td></tr><tr><td><h4>💡</h4></td><td><h4>Innovador</h4></td><td>Variables ambientales, nivel de agua y análisis de datos.</td><td></td></tr><tr><td><h4>📡</h4></td><td><h4>Conectado</h4></td><td>Mediciones por MQTT para almacenamiento y visualización en la nube.</td><td></td></tr></tbody></table>

### Datos, alertas e inteligencia

El ESP32 publica las lecturas mediante MQTT hacia el gateway. La Raspberry Pi ejecuta Mosquitto, conserva los datos en SQLite y sincroniza las métricas con Ubidots.

El software usa interrupciones para medir el pulso `ECHO` del sensor ultrasónico sin bloquear el ciclo principal. Los datos históricos permiten identificar tendencias y apoyar el análisis de anomalías.

{% hint style="warning" %}
Las alertas indican condiciones que requieren revisión. No sustituyen mediciones oficiales ni decisiones de las autoridades competentes.
{% endhint %}

### Equipo

<table data-card-size="large" data-view="cards"><thead><tr><th></th><th>Integrante</th><th>Rol</th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td><h4>📷</h4></td><td><h4>Nombre del integrante</h4></td><td>Rol y responsabilidad principal.</td><td></td></tr><tr><td><h4>📷</h4></td><td><h4>Nombre del integrante</h4></td><td>Rol y responsabilidad principal.</td><td></td></tr><tr><td><h4>📷</h4></td><td><h4>Nombre del integrante</h4></td><td>Rol y responsabilidad principal.</td><td></td></tr></tbody></table>

> Reemplaza cada espacio con una foto, el nombre y el rol correspondiente.

### Mapa de la documentación

<table data-card-size="large" data-view="cards"><thead><tr><th></th><th>Sección</th><th>Contenido</th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td><h4>00</h4></td><td><h4>Presentación</h4></td><td>Contexto, equipo y navegación del proyecto.</td><td></td></tr><tr><td><h4>01</h4></td><td><h4>Contexto y requisitos</h4></td><td>Problema hídrico, alcance y criterios de diseño.</td><td></td></tr><tr><td><h4>02</h4></td><td><h4>Diseño de la solución</h4></td><td>Arquitectura, modelo de negocio y restricciones.</td><td></td></tr><tr><td><h4>03</h4></td><td><h4>Implementación de hardware</h4></td><td>Esquemáticos, sensores e integración física.</td><td></td></tr><tr><td><h4>04</h4></td><td><h4>Implementación de software</h4></td><td>Diagramas, firmware y comunicación MQTT.</td><td></td></tr><tr><td><h4>05</h4></td><td><h4>Configuración y pruebas</h4></td><td>Protocolo experimental y validación del sistema.</td><td></td></tr><tr><td><h4>06</h4></td><td><h4>Resultados y análisis</h4></td><td>Visualización de datos y demostración del proyecto.</td><td></td></tr><tr><td><h4>07</h4></td><td><h4>Retos y conclusiones</h4></td><td>Aprendizajes, limitaciones y trabajo futuro.</td><td></td></tr><tr><td><h4>08</h4></td><td><h4>Inteligencia artificial</h4></td><td>Metodología, análisis y validación de la IA.</td><td></td></tr><tr><td><h4>09</h4></td><td><h4>Referencias y anexos</h4></td><td>Código fuente, referencias y recursos complementarios.</td><td></td></tr></tbody></table>

> Añade el enlace interno de cada tarjeta cuando su página esté creada.
