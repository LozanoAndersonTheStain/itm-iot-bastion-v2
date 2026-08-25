# Registro de cambios (Changelog)

Todas las modificaciones importantes de este proyecto serán documentadas en este archivo.

El formato está basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.0.0/),
y este proyecto se adhiere a [Versionado Semántico](https://semver.org/lang/es/).

---

## [0.1.0] - 2026-08-24

**Contribuidores de esta versión:**
| Nombre | Correo |
| :--- | :--- |
| Tookkeen | andersonlozano1123343@correo.itm.edu.co |

---

**Semana de trabajo actual:**
| Semana |
| :--- |
| 2 |

### 🚀 Añadido (Added)
*(Funcionalidades nuevas y estructura inicial)*

- Estructura inicial del proyecto y directorios base.
- Archivo `compose.yaml` para orquestar los servicios con Docker (Mosquitto, Telegraf, InfluxDB, Grafana).
- Configuración base de **Mosquitto** (`mosquitto/config/mosquitto.conf`) y lista de control de acceso (`acl`).
- Configuración de **Telegraf** (`telegraf/telegraf.conf`) para la ingesta de datos.
- Configuración de **Grafana** para el aprovisionamiento automático del datasource de InfluxDB.
- Script simulador de sensores (`simulator/sensor-simulator.sh`) para generar datos IoT de prueba.
- Scripts de utilidad:
  - `scripts/bootstrap-mosquitto.sh`: Configuración inicial del broker.
  - `scripts/publish-test.sh`: Publicación de mensajes de prueba.
  - `scripts/verify-stack.sh`: Verificación del estado de los servicios.
- Documentación inicial:
  - `README.md`: Visión general y guía rápida de inicio.
  - `docs/architecture.md`: Diagrama y explicación de la arquitectura del sistema.
  - `docs/entorno.md`: Especificaciones del entorno de desarrollo (WSL 2, RAM, CPU, etc.).
  - `docs/validation.md`: Criterios de validación del proyecto.
- Archivo de ejemplo de variables de entorno (`.env.example`).
- Archivo `.gitignore` para excluir archivos innecesarios del control de versiones.

---

## 📌 Próximos pasos / Pendientes
*Seran definidos segun los lineamientos que el profesor a dado a conocer en la plataforma de notion*
