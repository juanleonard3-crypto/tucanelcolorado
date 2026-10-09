# Tuco, el tucán guía de El Colorado 🦜

Avatar 3D (Three.js) que conversa por voz con un agente de ElevenLabs y responde solo sobre turismo de El Colorado, Formosa: Plaza San Martín, Camping Municipal y Parque Acuático.

## Uso
- Abrir la página en una pestaña propia, por `https` o `http://localhost`.
- Tocar el micrófono, permitir el acceso y hablar.
- Agregar `?debug` a la dirección para ver el chat y la consola de diagnóstico.

## Configuración
En `index.html`, la constante `AGENT_ID` tiene el identificador del agente de ElevenLabs.

## Probar en local
```
python3 -m http.server 8000
```
y abrir http://localhost:8000
