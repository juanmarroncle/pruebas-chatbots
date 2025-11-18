# Widget Chatwoot - Pruebas Locales

Este proyecto contiene un widget de prueba para conectar con Chatwoot.

## 🚀 Cómo Usar

### Opción 1: Abrir Directamente (Más Simple)

Simplemente haz **doble clic** en el archivo `index.html` y se abrirá en tu navegador.

O arrastra el archivo `index.html` a tu navegador.

### Opción 2: Usando un Servidor HTTP Simple (Recomendado para evitar problemas de CORS)

Si tienes problemas de CORS al abrir directamente, puedes usar un servidor simple:

**Con Node.js:**
```bash
npx http-server -p 8000 -o
```

**Con Python (si lo tienes instalado):**
```bash
python -m http.server 8000
```
Luego abre: http://localhost:8000/index.html

## 📋 Configuración

### Variables Importantes en `index.html`:

```javascript
var BASE_URL = "http://31.97.243.241:3000";  // URL de tu servidor Chatwoot
var WEBSITE_TOKEN = "hsngErdhDU26QUUR2KQED9zE";  // Token del website
var IDENTITY_TOKEN = "FmxD7X6fBb94UC5fCsKLbFdb";  // Token de identidad (opcional)
```

## 🔍 Diagnóstico

1. Abre la consola del navegador (F12)
2. Revisa los mensajes de diagnóstico
3. Consulta `DIAGNOSTICO.md` para más información

## 📝 Notas

- El servidor local corre en el puerto **8000**
- Tu servidor Chatwoot está en **http://31.97.243.241:3000**
- Asegúrate de que el servidor Chatwoot sea accesible desde tu red

