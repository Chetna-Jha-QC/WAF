# WAF
Web Application Firewall (Prototype) | Node.js, Express, React, MongoDB
waf-prototype/
├─ backend/
│  ├─ package.json
│  ├─ .env
│  ├─ src/
│  │  ├─ server.js          (start)
│  │  ├─ app.js             (express app)
│  │  ├─ middleware/
│  │  │  └─ waf.js
│  │  ├─ utils/
│  │  │  └─ detectors.js
│  │  ├─ models/
│  │  │  └─ Log.js
│  │  └─ routes/
│  │     ├─ logs.js
│  │     └─ health.js
│  └─ Dockerfile
├─ frontend/
│  ├─ package.json
│  ├─ index.html
│  └─ src/
│     └─ App.jsx
└─ README.md
