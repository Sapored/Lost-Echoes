# <a name="_6piwrd92xav3"></a>**Game Design Document – Lost Echoes**
## <a name="_vzxzpz74bs67"></a>**1. Información General**
- **Título del juego**: *Lost Echoes*
- **Género**: Aventura narrativa con elementos RPG y mecánicas de gestión de cordura.
- **Plataforma(s)**: PC (futuro: posible port a consolas).
- **Audiencia objetivo**: Jugadores interesados en narrativa ramificada, rol clásico y decisiones con consecuencias (ej. fans de Baldur’s Gate, Disco Elysium, Life is Strange).
- **Estilo visual**: Fantasía oscura, con un ambiente inmersivo inspirado en mitología y estética medieval.
## <a name="_47lv0x5q7q22"></a>**2. Concepto del Juego**
- *Lost Echoes* es una aventura narrativa donde el jugador interpreta a un joven aprendiz en un campamento de héroes.
- El foco está en:
  - Construir **relaciones** con tres compañeros (guerrero, maga, druida).
  - Mantener la **cordura** frente a la influencia de la “Canción de la Hidra Falsa”.
  - Tomar **decisiones** que afectarán las ramas narrativas y finales.
- El juego mezcla **diálogo ramificado** (+amistad/0/-amistad), **minijuegos de memoria** (para la cordura) y una progresión narrativa que culmina en un enfrentamiento con la Hidra.
## <a name="_ign3j15dhld7"></a>**3. Mecánicas Principales**
### <a name="_fpf16klvd71h"></a>**3.1. Sistema de Amistad**
- Cada interacción con un compañero puede dar: **+1, 0 o -1**.
- Escalas de amistad:
  - **10–8** → relación fuerte.
  - **7–5** → relación media.
  - **4–0** → relación baja.
  - **-1 – -2** → relación crítica. 
  - **-3** → relación rota. 
### <a name="_whhvvptmo42s"></a>**3.2. Cordura**
- Representada con un **valor numérico (0–10)**.
- Cada noche, el jugador juega un minijuego de memoria:
  - Recordar una secuencia de **símbolos** (ej. ⚔️ → 🌿 → 🔮 → 🐉).
  - Fallar reduce la cordura hasta **-2 por noche**.
  - Si la cordura llega a **0 → Game Over** (devorado por la Hidra).
- Dificultad aumenta con los días (menos tiempo para memorizar secuencia).
### <a name="_91u6xx44j0me"></a>**3.3. Decisiones Narrativas**
- Conversaciones con compañeros determinan:
  - **Afinidad** (amistad).
  - **Consecuencias futuras** (aliados en batalla, sacrificios, muertes).
- El tono de la narrativa cambia según la **cordura** (más baja = mundo más distorsionado/aterrador).
## <a name="_p2j266zhxrto"></a>**4. Personajes**
- **Jugador**: Aprendiz anónimo, hijo de una clériga y un monje respetados.
- **Kael (Guerrero)**: Orgulloso, busca perfección. Rivalidad/respeto.
- **Ember (Maga)**: Analítica, persigue la verdad de la magia. Busca profundidad.
- **Halsin (Druida)**: Conectado con la naturaleza. Empático, pero puede decepcionarse.
- **Maestro Garrick**: Mentor inicial, guía en el campamento.
- **Hidra Falsa**: Antagonista principal. Su canto pone en riesgo la cordura.
## <a name="_hz29ezhy8sp"></a>**5. Progresión del Juego**
1. **Introducción**: llegada al campamento, despedida de los padres.
1. **Primeras interacciones**: elección de con quién hablar (guerrero, maga, druida).
1. **Ciclo de juego**:
   1. Día → interacciones con compañeros (amistad).
   1. Noche → minijuego de cordura.
1. **Clímax**: confrontación con la Hidra.
1. **Resolución**: uno de los **6 finales principales** + **Game Over por cordura**.
## <a name="_fo825t3uvj6w"></a>**6. Finales**
1. **Amistad alta (8–10), Cordura ≥7** → Final bueno: todos sobreviven.
1. **Amistad alta (8–10), Cordura <7** → Derrotan a la Hidra, pero el amigo muere.
1. **Amistad media (7–5), Cordura ≥7** → Hidra derrotada, ambos heridos (pérdida permanente).
1. **Amistad media (7–5), Cordura <7** → Hidra escapa, amigo herido de gravedad.
1. **Amistad baja (4–0), Cordura ≥7** → Amigo te abandona, mueres.
1. **Amistad baja (4–0), Cordura <7** → Tú abandonas al amigo, condenas a todos.
1. **Cordura 0** → Game Over inmediato.


## <a name="_o6c972hjplou"></a>**7. Controles y UI (versión inicial)**
- **PC/Teclado + Mouse**
  - Selección de diálogos → clic izquierdo.
  - Confirmar símbolos → teclas 1–4 o clic sobre iconos.
- **UI propuesta**:
  - Indicador de **Amistad** (barra o número oculto).
  - Indicador de **Cordura** (visible en todo momento).
  - Ventana de diálogos con retrato del personaje.
## <a name="_c1dkak90s5uw"></a>**8. Estilo Narrativo y Atmosférico**
- **Tono**: fantasía oscura con toques melancólicos.
- **Inspiración**: *Baldur’s Gate*, *Disco Elysium*, *Darkest Dungeon*.
- **Narrativa**: Texto ramificado con ilustraciones estáticas o estilo VN (novela visual).
- **Atmósfera**: Música ambiental mística, efectos sonoros para resaltar tensión en minijuegos y distorsiones visuales al bajar la cordura.
## <a name="_1b4aqrp0xj34"></a>**9. Iteraciones Futuras**
- Sistema de combate ligero (por turnos o cinemático).
- Más compañeros/antagonistas secundarios.
- Profundización en el lore del mundo y la Hidra.
- Variación en los minijuegos de cordura (no solo memoria visual, sino auditiva o lógica).
- Ilustraciones y retratos de personajes.

