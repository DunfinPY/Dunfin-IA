# DunFin-IA — Virtual Assistant

Asistente virtual inteligente de DunFin con mascota digital animada (V-Pet).

## Deploy en Vercel

1. Subí este repo a GitHub
2. Importá en vercel.com → Add New Project
3. En **Environment Variables** agregá:
   - `GROQ_API_KEY` = tu API key de Groq (console.groq.com)
4. Deploy

## Para activar el selector de color/criatura

En `src/App.jsx`, buscá esta línea y cambiá `false` a `true`:
```js
const [showPicker,setShowPicker]=useState(false);
```

## Desarrollo local

```bash
npm install
echo "GROQ_API_KEY=tu_key" > .env
npm run dev
```
.
