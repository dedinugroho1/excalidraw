# Excalidraw - Dedi's Fork

Virtual whiteboard untuk sketsa diagram dengan tampilan hand-drawn.

![Excalidraw](https://excalidraw.com/og-image-2.png)

## ✨ Fitur

- 🎨 Hand-drawn style yang natural
- 🌙 Dark mode support
- 🤝 Real-time collaboration
- 📱 Responsive (desktop & mobile)
- 💾 Export ke PNG, SVG, JSON
- 🔒 End-to-end encryption untuk collaboration
- 📚 Library shapes yang bisa di-reuse

## 🚀 Quick Start

```bash
# Install dependencies
yarn install

# Jalankan development server
yarn start
```

Buka [http://localhost:5173](http://localhost:5173) di browser.

## 🛠️ Scripts

| Command | Deskripsi |
|---------|-----------|
| `yarn start` | Jalankan dev server |
| `yarn build` | Build untuk production |
| `yarn test` | Jalankan tests |
| `yarn fix` | Auto-fix linting & formatting |

## 📁 Struktur Project

```
├── excalidraw-app/     # Main application
├── packages/
│   ├── excalidraw/     # Core library
│   ├── common/         # Shared utilities
│   ├── element/        # Element types & logic
│   └── math/           # Math utilities
├── examples/           # Example implementations
└── dev-docs/           # Documentation site
```

## 🔧 Tech Stack

- React 19
- TypeScript
- Vite
- Vitest
- Firebase (collaboration)

## 📝 License

MIT License - lihat file [LICENSE](LICENSE) untuk detail.

---

Fork dari [Excalidraw](https://github.com/excalidraw/excalidraw)
