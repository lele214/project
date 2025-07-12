tetris/
│
├── main.lua            → point d'entrée du projet
├── conf.lua            → configuration de la fenêtre Love2D
│
├── src/                → logique principale du jeu
│   ├── game.lua        → logique du Tetris (grille, pièces, règles)
│   ├── player.lua      → gestion du joueur (score, état)
│   ├── input.lua       → gestion des touches
│   ├── ui.lua          → affichage (score, menu, etc.)
│   └── states.lua      → états du jeu (menu, jeu, pause...)
│
├── libs/               → bibliothèques tierces (SQLite, HTTP, JSON)
│
├── assets/             → ressources visuelles/sonores
│   ├── images/
│   ├── fonts/
│   └── sounds/
│
├── data/               → fichiers de données
│   └── tetris.db       → base de données locale
│
└── api/                → appel et traitement d'API externe
    └── external_api.lua
