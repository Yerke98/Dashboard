# Dashboard
At home dashboard
# 🚋 Tram Departure Dashboard

A simple, lightweight, and efficient dashboard that shows real-time tram departure times from your nearest tram stop using the open OVapi (KV78Turbo) API. Ideal for displaying on devices like an old e-reader, tablet, or desktop browser.

---

## 🌟 Features

- Real-time tram departure times (refreshes every minute).
- Easy to deploy and use.
- Optimized for readability and minimal power consumption, perfect for e-ink displays.

---

## 🛠️ Technology

- HTML, JavaScript, CSS
- Data source: [OVapi/KV78Turbo](https://github.com/skywave/KV78Turbo-OVAPI/wiki)
- Hosted on [GitHub Pages](https://pages.github.com/) for free.

---

## 🚀 Getting Started

### 1. Clone or Fork this Repository
```
git clone https://github.com/<your-username>/<repository-name>.git
```

### 2. Set your Tram Stop Code
- Find your tram stop code at the [OVapi stop finder](https://v0.ovapi.nl/haltes/).
- Replace the placeholder `jouw_halte_code` in `index.html` with your actual stop code.

Example:
```javascript
const halteCode = 'tramhalte:32002145';
```

### 3. Deploy with GitHub Pages
- Go to your repository's **Settings** → **Pages**.
- Select branch `main` and save.
- Your dashboard will be live shortly at:

```
https://<your-username>.github.io/<repository-name>/
```

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

