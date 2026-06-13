# Andrea IA — PWA Chat

Interfaz de chat agentica para el Superagent **Andrea** en Base44.

## Características
- 🌙 Dark mode con tema verde neón
- 📱 PWA instalable (Android/iOS/Desktop)
- 🎤 Transcripción de voz a texto (Web Speech API)
- 💬 Conexión en tiempo real con Base44 Superagent API
- 💾 Historial de conversación persistente (localStorage)
- ⚡ Service Worker para uso offline parcial

## Setup

1. Clona este repo
2. Abre `index.html`
3. Configura tu API Key en la sección `CONFIG`:
   ```js
   const CONFIG = {
     apiKey: 'TU_API_KEY_AQUI',
     ...
   }
   ```
4. Deploy en GitHub Pages (automático vía Actions)

## API Key

Ve a tu Superagent → Customize → Developer → API Reference → copia tu API Key.

## Estructura
```
/
├── index.html      # App principal + lógica
├── manifest.json   # PWA manifest
├── sw.js           # Service Worker
├── icon-192.png    # Ícono PWA (192px)
└── icon-512.png    # Ícono PWA (512px)
```
