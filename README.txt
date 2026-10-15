PROYECTO INVERNADERO IOT - GUIA RAPIDA

1. Abre Docker Desktop.
2. Descomprime el ZIP y abre la carpeta en VS Code.
3. Terminal: docker compose up -d --build
4. Verifica: docker compose ps
5. Editor Node-RED: http://localhost:1880
6. Dashboard: http://localhost:1880/ui
7. Las lecturas se generan cada 5 segundos.
8. Para probar 1250 lux: en el editor haz clic en el botón del nodo RETO: 1250 lux.
9. En el editor, panel Debug (icono insecto) muestra publicación y recepción.
10. Los datos se guardan en datos/lecturas.csv.
11. Detener: docker compose down

Captura evidencias REALES de Docker, Debug, Dashboard y CSV.
El umbral de 1000 lux es solo para la práctica.
Mosquitto permite acceso anónimo solo para este laboratorio local.
