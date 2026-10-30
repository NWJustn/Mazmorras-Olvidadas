# 🏰 Mazmorra de bolsillo

Juego de mazmorras por turnos en pixel art, pensado para el celular. Hecho en un solo archivo HTML, sin dependencias ni instalación.

## Cómo jugar
- **Moverte / atacar:** botones ▲ ◀ ▼ ▶, deslizar el dedo sobre la mazmorra, o flechas del teclado.
- **Inventario:** toca una poción (cura 5 de vida) o un escudo (bloquea 2 de daño en 3 golpes). Usar un objeto gasta tu turno.
- **Objetivo:** llegar a la escalera en cada piso y sobrevivir hasta el piso 20.

## Héroes
| Héroe | Vida | Ataque | Alcance | Particularidad |
|---|---|---|---|---|
| Mago | 10 | 2 | 3 | Magia a distancia |
| Caballero | 14 | 3 | 1 | Muy resistente; tienda con armas de corto y medio alcance |
| Arquero | 9 | 2 | 4 | 25 % de golpe crítico (doble daño) |

## Pisos
- **Pisos 5, 10 y 15:** pisos seguros, sin enemigos, con comerciante.
- **Pisos 6, 11 y 16:** sala con un mini jefe. La escalera se abre al vencerlo.
- **Piso 20:** jefe final. Al vencerlo se desbloquea el **modo difícil ★**.

## Ejecutar en local
Abre `index.html` en cualquier navegador.

## Publicar con GitHub Pages
1. Sube estos archivos a un repositorio.
2. En el repositorio ve a **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. Guarda. En uno o dos minutos el juego estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Licencia
MIT. Ver `LICENSE`.
