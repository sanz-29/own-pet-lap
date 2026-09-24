                    VIRTUAL PET
                         │
                    Tauri 2 App
                         │
          ┌──────────────┴──────────────┐
          │                             │
     Frontend                       Rust Backend
 TypeScript + Three.js              Native Layer
          │                             │
     Pet Engine              ┌──────────┼──────────┐
          │                   │          │          │
     3D GLB Models         SQLite    Windows    System Tray
          │                           APIs
          │                              │
   ┌──────┼────────┐              Notifications
   │      │        │              Auto Startup
  Walk   Feed    Sleep
   │
 Grab → Drag → Throw
              │
          Physics Engine