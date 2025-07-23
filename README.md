# BuscaMinas Xtreme

**BuscaMinas Xtreme** es una plataforma de juego interactivo y colaborativo inspirada en el clásico **Buscaminas**, diseñada para que múltiples jugadores puedan jugar juntos en tiempo real mientras se comunican por chat.

Este proyecto está dividido en módulos independientes que se comunican entre sí usando WebSockets y APIs REST, y están integrados en este repositorio como submódulos.

---

##  Características principales

- Juego tipo Buscaminas multijugador
- Comunicación en tiempo real (chat)
- Sincronización de tablero para todos los participantes
- Autenticación y control de salas
- Arquitectura distribuida basada en microservicios

---

##  Estructura del Proyecto

```bash
dinamicboard-central/
├── servicios/
│   ├── juego/        # Lógica del juego y sincronización de estado
│   ├── chat/         # Servicio de mensajería en tiempo real
│   └── voz/          # Comunicación por voz con WebRTC
├── .gitmodules       # Definición de los submódulos Git
├── README.md         # Este archivo
└── wiki/             # (O documentación en la pestaña Wiki de GitHub)
