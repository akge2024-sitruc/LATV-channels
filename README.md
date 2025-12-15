# LATV-channels
# 📺 LATV – Application de Streaming IPTV

**LATV** est une application de lecture de streaming IPTV permettant de regarder des chaînes TV en direct via des flux **HLS / M3U8**.  
Elle est conçue pour offrir un accès simple, rapide et organisé aux chaînes **africaines**, **françaises** et **internationales**.

---

## 🚀 Fonctionnalités

- ▶️ Lecture de chaînes TV en direct (Live Streaming)
- 🌍 Chaînes africaines, françaises et internationales
- 📰 Catégories : Général, News, Sports, Divertissement
- ⚡ Chargement dynamique des chaînes via fichier **JSON distant**
- 🔄 Mise à jour des chaînes sans mise à jour de l’application
- 🧠 Système de cache pour de meilleures performances
- 📱 Interface optimisée mobile (Android)

---

## 🛠️ Technologies utilisées

- **Flutter / Dart**
- **HTTP**
- **Flux HLS (M3U8)**
- **GitHub Raw JSON**
- Lecteur vidéo compatible streaming live

---

## 📂 Structure des données

Les chaînes sont chargées depuis un fichier `channels.json` hébergé sur GitHub.

### Exemple de structure :
```json
{
  "channels": [
    {
      "id": "africa24",
      "name": "Africa 24",
      "logo": "https://example.com/logo.png",
      "url": "https://example.com/stream.m3u8",
      "country": "Afrique",
      "category": "News",
      "status": "active"
    }
  ]
}
