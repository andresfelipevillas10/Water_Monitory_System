---
description: >-
  Solución IoT de bajo costo para el monitoreo hídrico ante el Fenómeno de El
  Niño.
---

# Water Monitoring System (WMSV3)

<p align="center"><strong>💧 MONITOREO HÍDRICO INTELIGENTE</strong></p>

## Water Monitoring System (WMSV3)

> _Una solución IoT de bajo costo para anticipar y observar el estrés hídrico._
>
> Monitoreo ambiental conectado para la Sabana de Bogotá y Cundinamarca.

WMSV3 reúne sensores, procesamiento embebido y visualización de datos. El sistema convierte mediciones de campo en información clara para actuar a tiempo.

{% hint style="info" %}
**Visión general.** Esta página presenta el propósito y las capacidades del proyecto. Los módulos de la wiki desarrollan los detalles técnicos.
{% endhint %}

***

### El reto hídrico

{% hint style="warning" %}
#### 💧 Fenómeno de El Niño

La reducción de reservas y el aumento de evaporación requieren información local y continua. WMSV3 busca acortar el camino entre medir, interpretar y responder.
{% endhint %}

{% columns %}
{% column %}
#### Qué observamos

* Nivel y comportamiento del agua
* Radiación, temperatura y humedad
* Señales que anticipan estrés hídrico
{% endcolumn %}

{% column %}
#### Qué habilitamos

* Lecturas desde el nodo de monitoreo
* Alertas locales ante umbrales definidos
* Datos disponibles para análisis y decisiones
{% endcolumn %}
{% endcolumns %}

***

### Una solución conectada

La plataforma integra instrumentación de campo, firmware embebido y consulta de datos. Cada capa aporta una parte esencial del sistema.

{% columns %}
{% column %}
#### 📡 Sensores y percepción

Capturamos las variables del entorno con instrumentación de bajo consumo. Las lecturas construyen una visión más completa de cada punto de monitoreo.

**Variables clave:** nivel del agua, radiación solar y condiciones climáticas.
{% endcolumn %}

{% column %}
#### ⚡ Acción y despliegue

Transformamos las mediciones en información visible. El nodo puede comunicar alertas en sitio y habilitar consultas remotas.

**Capacidades:** señalización, pantalla local y panel de telemetría.
{% endcolumn %}
{% endcolumns %}

***

### Arquitectura en breve

{% stepper %}
{% step %}
#### Medir

Los sensores registran el estado hídrico y atmosférico del entorno.
{% endstep %}

{% step %}
#### Procesar

El microcontrolador organiza las lecturas y evalúa las condiciones configuradas.
{% endstep %}

{% step %}
#### Comunicar

El nodo presenta la información localmente y la prepara para la consulta remota.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
**Diseñado para crecer.** El proyecto puede evolucionar de un prototipo de campo a una red de nodos con análisis histórico.
{% endhint %}

***

### Explora el proyecto

La wiki se organiza en módulos. Cada uno amplía la visión presentada aquí.

<table data-view="cards"><thead><tr><th>Módulo</th><th>Contenido</th></tr></thead><tbody><tr><td><strong>Contexto y requisitos</strong></td><td>Problema hídrico, alcance y necesidades del sistema.</td></tr><tr><td><strong>Diseño de la solución</strong></td><td>Arquitectura, flujo de datos y propuesta de valor.</td></tr><tr><td><strong>Hardware</strong></td><td>Sensores, conexiones y componentes del nodo.</td></tr><tr><td><strong>Software</strong></td><td>Firmware, lógica de monitoreo e integración.</td></tr><tr><td><strong>Validación y resultados</strong></td><td>Pruebas, evidencias y aprendizajes del proyecto.</td></tr></tbody></table>

***

> **WMSV3** combina monitoreo ambiental, electrónica y software para cuidar un recurso esencial.

<p align="center"><strong>Sabana de Bogotá · Cundinamarca · Monitoreo con propósito</strong></p>
