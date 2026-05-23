<h1 align="center">Autolavado IoT — Sistema de Monitoreo de Fases de Autolavado en Tiempo Real</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Angular-17-DD0031?logo=angular&logoColor=white" alt="Angular">
  <img src="https://img.shields.io/badge/TypeScript-5.2-3178C6?logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Licencia-GPL_v3-0298c3?logo=gnu&logoColor=white" alt="GPL v3">
  <img src="https://img.shields.io/badge/Estado-Active-2ea44f" alt="Active">
</p>

<p align="center">
  <em>Interfaz web para monitorear las fases de un autolavado automático usando sensores ultrasónicos e indicadores LED.</em>
</p>

<p align="center">
  <a href="README.md">🇬🇧 English</a> · <a href="README.es.md">🇪🇸 Español</a>
</p>

---

## Acerca del Autolavado IoT

Dashboard de monitoreo en tiempo real para un sistema de autolavado automático. Tres sensores ultrasónicos detectan la posición del vehículo a través de las fases de lavado, enjuague y secado. Los indicadores LED se encienden para mostrar la fase activa, y las mediciones de distancia se visualizan mediante sliders interactivos.

### Ecosistema

| Componente | Repositorio | Stack |
|-----------|-----------|-------|
| Frontend | [chrisssp/iot-carwash](https://github.com/chrisssp/iot-carwash) | Angular 17, TypeScript |
| API Backend | [chrisssp/iot-carwash-api](https://github.com/chrisssp/iot-carwash-api) | Spring Boot 3, Java 17, MongoDB |

## Funcionalidades

- Monitoreo de distancia ultrasónica en tiempo real (3 sensores)
- Detección visual de fases: lavado (azul), enjuague (verde), secado (rojo)
- Sliders interactivos de distancia con indicadores de posición del vehículo
- Polling cada 1 segundo para actualizaciones en vivo
- Interfaz responsive con tema oscuro

## Inicio rápido

### Requisitos previos

- Node.js 18+
- Angular CLI 17+
- Microcontrolador compatible con Arduino con sensores ultrasónicos y LEDs

### Instalación

```bash
git clone https://github.com/chrisssp/iot-carwash.git
cd iot-carwash
npm install
ng serve
```

La aplicación corre en `http://localhost:4200` y espera la API en `http://localhost:8080`.

## Contribuciones

Lee [CONTRIBUTING.md](CONTRIBUTING.md) para conocer las convenciones de ramas, commits y PRs.

## Licencia

Este proyecto está bajo la licencia GPL v3 — ver [LICENSE](LICENSE) para más detalles.