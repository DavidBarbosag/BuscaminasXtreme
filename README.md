## BuscaMinas Xtreme

BuscaMinas Xtreme is an interactive and collaborative gaming platform inspired by the classic Minesweeper, designed for multiple players to play together in real time while communicating through chat.

This project is divided into independent modules that communicate with each other using WebSockets and REST APIs, and are integrated into this repository as Git submodules.

# Key Features
* Multiplayer Minesweeper-style game
* Real-time communication (chat)
* Board synchronization for all participants
* Room authentication and management
* Distributed architecture based on microservices



---

##  Estructura del Proyecto

```bash
dinamicboard-central/
├── servicios/
│   ├── juego/       # Game logic and state synchronization
│   ├── chat/         # Real-time messaging service
│   └── web/          # web
├── .gitmodules       
├── README.md        
└── wiki/     
