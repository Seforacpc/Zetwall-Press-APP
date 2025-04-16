# 📱 Zétwal Press – Application Flutter

**Zétwal Press** est une application mobile et web d’actualités conçue pour offrir une expérience de lecture fluide, sans publicité, et respectueuse de l’utilisateur. Elle met en avant la sobriété visuelle, la rapidité d’accès à l’information, et l’accessibilité vocale.

---

## 🧩 Fonctionnalités principales

- 📰 Lecture d’actualités internationales (NewsAPI & RSS NYT)
- 🌍 News locales de Martinique via scraping Render
- ☀️ Météo actuelle & historique (OpenWeather + Visual Crossing)
- 🗣️ Chatbot vocal (recherche et lecture d’articles)
- 📝 Création et affichage d’articles personnalisés
- 💾 Cache local avec Hive (lecture offline partielle)

---

## 🛠️ Technologies utilisées

| Stack | Description |
|-------|-------------|
| Frontend | Flutter 3.19.0 |
| Backend | Python 3.11 + Flask (Render.com) |
| API vocale | ElevenLabs TTS |
| Base de données locale | Hive |
| Gestion d’état | Riverpod |
| Design | Google Fonts + Playfair Display |

---

## 🚀 Installation

1. Clonez le dépôt :

```bash
git clone https://github.com/seforacpc/zetwal-press.git
cd zetwal-press
