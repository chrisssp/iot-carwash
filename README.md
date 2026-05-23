<h1 align="center">IoT Car Wash — Real-Time Car Wash Phase Monitoring System</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Angular-17-DD0031?logo=angular&logoColor=white" alt="Angular">
  <img src="https://img.shields.io/badge/TypeScript-5.2-3178C6?logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/License-GPL_v3-0298c3?logo=gnu&logoColor=white" alt="GPL v3">
  <img src="https://img.shields.io/badge/Status-Active-2ea44f" alt="Active">
</p>

<p align="center">
  <em>Web interface for monitoring automatic car wash phases using ultrasonic sensors and LED indicators.</em>
</p>

<p align="center">
  <a href="README.md">🇬🇧 English</a> · <a href="README.es.md">🇪🇸 Español</a>
</p>

---

## About IoT Car Wash

A real-time monitoring dashboard for an automatic car wash system. Three ultrasonic sensors detect vehicle position across wash, rinse, and dry phases. LED indicators light up to show the active phase, and distance measurements are visualized through interactive sliders.

### Ecosystem

| Component | Repository | Stack |
|-----------|-----------|-------|
| Frontend | [chrisssp/iot-carwash](https://github.com/chrisssp/iot-carwash) | Angular 17, TypeScript |
| Backend API | [chrisssp/iot-carwash-api](https://github.com/chrisssp/iot-carwash-api) | Spring Boot 3, Java 17, MongoDB |

## Features

- Real-time ultrasonic distance monitoring (3 sensors)
- Visual phase detection: washing (blue), rinsing (green), drying (red)
- Interactive distance sliders with car position indicators
- 1-second polling for live updates
- Dark-themed responsive UI

## Quick Start

### Prerequisites

- Node.js 18+
- Angular CLI 17+
- Arduino-compatible microcontroller with ultrasonic sensors and LEDs

### Setup

```bash
git clone https://github.com/chrisssp/iot-carwash.git
cd iot-carwash
npm install
ng serve
```

The application runs on `http://localhost:4200` and expects the API at `http://localhost:8080`.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for branch naming, commit conventions, and PR workflow.

## License

This project is licensed under the GPL v3 — see the [LICENSE](LICENSE) file for details.