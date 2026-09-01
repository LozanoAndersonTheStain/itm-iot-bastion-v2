# Casos de uso del mundo real

## 🔹 Caso A — Cadena de frío

Una empresa transporta medicamentos.

Cada vehículo transmite:

- temperatura;
- humedad;
- posición;
- estado de la puerta.

El sistema permite detectar si la temperatura supera un límite.

Relación con Bastión:

```
sensor de temperatura → MQTT → almacenamiento → dashboard
```

## Caso B — Monitoreo ambiental

Una red de estaciones mide:

- PM2.5;
- temperatura;
- humedad;
- presión;
- velocidad del viento.

Relación con Bastión:

```
estaciones → broker MQTT → Telegraf → InfluxDB → Grafana
```

## Caso C — Agricultura

Un cultivo puede medir:

- humedad del suelo;
- temperatura;
- radiación;
- nivel de un tanque.

Los datos pueden utilizarse para decidir cuándo irrigar.

## 🔹 Caso D — Industria

Una fábrica puede medir vibración y temperatura de motores.

El histórico permite encontrar cambios de comportamiento y programar mantenimiento.
