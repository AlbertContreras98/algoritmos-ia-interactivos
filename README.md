# Algoritmos de IA interactivos

App web para practicar algoritmos de inteligencia artificial paso a paso. Genera ejercicios aleatorios (4 niveles de dificultad) o personalizados y corrige cada paso al momento. Cada ejercicio tiene un botón *Resolver* para ver la solución completa.

**Abrir la app:** https://albertcontreras98.github.io/algoritmos-ia-interactivos/

## Algoritmos incluidos

- Minimax con poda alfa‑beta (valores minimax, α/β por nodo y hojas podadas)
- Búsqueda de coste uniforme (UCS), voraz y A* (listas de abiertos y cerrados por paso; en voraz y A*, preguntas sobre admisibilidad y consistencia de la heurística)
- KNN (distancia euclídea o de Hamming, vecinos y clase por mayoría)
- K‑means (distancias a cada centroide y asignación por iteración hasta converger)
- Encadenamiento hacia delante (conjunto conflicto y resolución por especificidad, recencia y orden textual)
- Encadenamiento hacia atrás (metas, sub‑objetivos y vuelta atrás si una regla falla)
- Red neuronal simple (2 entradas, 3 neuronas ocultas, ReLU y Heaviside)
- Árbol de decisión (tablas de conteo, bondad de cada variable y división)

En modo personalizado se pueden introducir los datos propios (grafos por aristas `1-2-5, 2-3-1` o por matriz de adyacencia, reglas `A B -> C`, puntos `x-y`…). Los nodos y puntos se numeran desde 1.

## Uso

- **Navegador (PC o móvil):** abre el enlace de arriba.
- **Instalar en el móvil:** abre el enlace y elige *Añadir a pantalla de inicio* (Android: menú ⋮ → *Instalar app*; iPhone: Compartir → *Añadir a pantalla de inicio*). Después funciona sin conexión.
- **Sin internet:** descarga `index.html` y ábrelo con cualquier navegador.

## Tecnología

HTML, CSS y JavaScript sin dependencias, en un solo archivo (`index.html`). PWA con `manifest.json` y `sw.js` para instalación y uso sin conexión.
