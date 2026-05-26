# Jugadas Rugby 15

Aplicacion HTML para ver jugadas de rugby 15 en una cancha.

## Como usar

Abrir `index.html` en un navegador.

Tambien se puede levantar servidor local:

```powershell
python -m http.server 8057 --bind 127.0.0.1
```

Luego abrir:

```text
http://127.0.0.1:8057/index.html
```

## Jugadas incluidas

- Casita
- Jugada 25
- Jugada 27

## Que muestra

- Campo de rugby
- Jugadores por numero
- Preview tactico tipo pizarra
- Simulacion sin flechas
- Defensa rival
- Ruta de pelota editable por nodos
- Selector de jugada

## Colores

- Triangulos: jugadores
- Ovalo marron: pelota
- Puntos negros: defensa
- Lineas grises: ruta editable del preview

## Motor visual

- SVG con `viewBox` y `preserveAspectRatio`
- Jugadores estables
- Pelota animada por distancia real sobre ruta
- Trail visible solo en simulacion
- Nodos de ruta visibles solo en modo edicion

## Archivos

- `index.html`: aplicacion completa
- `vista-previa-jugada-27.png`: captura de ejemplo

## Nota

Las posiciones son esquematicas. Sirven para entender la secuencia y revisar la jugada.
