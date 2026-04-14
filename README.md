# VALDRIS — El Juego de los 4 Reinos

Juego de tablero estratégico épico con estética inspirada en StarCraft / Dark Templar.

## Contenido

- `index.html` — Página principal con lore, reinos, héroes, bestiario, cartas y dados
- `game.html` — Tablero virtual interactivo con sistema de turnos, recursos y combate

## Cómo subir a GitHub Pages

1. Crea un repositorio en GitHub (ej: `valdris`)
2. Sube estos archivos a la raíz del repositorio
3. Ve a **Settings → Pages → Source → main branch → / (root)**
4. Tu juego estará en: `https://TU-USUARIO.github.io/valdris`

## Mecánicas implementadas

- Tablero 11×11 en rombo con 4 castillos, 4 minas, zona de jefes y Grial central
- Sistema de turnos para 4 jugadores (local)
- Dados interactivos (D6 movimiento, D8 combate)
- Economía de recursos y minerales por turno
- Reclutamiento de unidades y recolectores
- Compra de equipo con minerales
- Registro de acciones en tiempo real
- Estado de cada reino (recursos, HP castillo, unidades)

## Próximas versiones

- [ ] Movimiento real de unidades en el tablero
- [ ] Sistema de combate completo con animaciones
- [ ] Cartas visuales animadas
- [ ] Fichas de personaje individuales
- [ ] Modo multijugador online (Firebase)
- [ ] Bestiario interactivo
- [ ] Sistema de niveles para héroes
