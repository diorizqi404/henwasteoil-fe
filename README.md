# HEN Waste Oil Frontend

Frontend aplikasi HEN Waste Oil untuk pengelolaan setoran minyak jelantah, validasi pengepul, pemantauan distribusi, pengujian lab, dan dashboard stakeholder.

## Teknologi

- React 19
- Vite 8
- Tailwind CSS 4
- React Router DOM 7
- Axios
- Leaflet + React Leaflet
- Recharts
- Zustand
- Docker + Nginx

## Cara Menjalankan

### Lokal

```bash
npm install
npm run dev
```

Aplikasi berjalan di:

```txt
http://localhost:5173
```

### Build Production

```bash
npm run build
npm run preview
```

### Docker Compose

```bash
docker compose up -d --build
```

Default port aplikasi:

```txt
http://localhost:8080
```

Port dapat diubah dengan environment variable:

```bash
APP_PORT=8080 docker compose up -d --build
```

## Konfigurasi API

Base URL API default:

```txt
https://api.eepis.web.id/api/v1
```

Untuk mengganti API URL, set environment variable:

```bash
VITE_API_URL=https://api.example.com/api/v1
```