# Plantilla de prompt para presentaciones con IA

## Sistema de diseño Asimetrix

Usa esta plantilla para generar presentaciones HTML profesionales usando el sistema de diseño Asimetrix. El resultado será un archivo HTML único, visualmente impactante, listo para presentar.

---

## Parte 1: configuración del diseño

### paleta de colores Asimetrix

Copia y pega estos valores en tu prompt:


COLOR PRINCIPAL (Primario): #040939 (Azul profundo)
COLOR SECUNDARIO: #0E567B (Azul aqua)
COLOR DE FONDO: #FFFFFF (Blanco) o #F8F9FA (Gris claro)
COLOR DE TEXTO PRINCIPAL: #050B49
COLOR DE APOYO/ACENTO: #4BA2FF (Azul eléctrico)
COLOR AQUA ELÉCTRICO: #00E3FF
COLOR AQUA GRISÁSEO: #7EC6DE
COLOR DE ÉXITO: #4BA2FF
COLOR DE ERROR: #C0062B
COLOR DE ADVERTENCIA: #FFD600


### tipografía


fuente principal: Roboto (Google fonts)
- Headings: Roboto Bold (700)
- Body: Roboto Regular (400)
- Tamaños: H1=56px, H2=44px, H3=32px, Body=16px


### iconografía


Usa iconos estilo línea (stroke) con:
- Ancho de trazo: 2px
- Color: #040939 (default), #7EC6DE (hover)
- Categorías: Direccionales, Conexiones, Alertas, Archivos
- Logo de asimetrix: https://asimetrix.co/hs-fs/hubfs/logo-AX-Asimetrix-unlocking-the-power-of-data.webp?width=460&height=132&name=logo-AX-Asimetrix-unlocking-the-power-of-data.webp


---

## Parte 2: estructura del prompt

Copia y completa este prompt para usar con ChatGPT o Gemini:

---

*PROMPT:*


Eres un diseñador gráfico experto en presentaciones corporativas premium. Crea una presentación HTML completa usando el sistema de diseño Asimetrix.

## configuración visual

- Color primario: #040939
- Color secundario: #0E567B  
- Color de acento: #4BA2FF
- Color de fondo: [BLANCO/GRIS CLARO/OSCURO]
- Fuente: Roboto (Google fonts)
- Estilo: apple keyNote (siempre)

## contexto de la presentación

- Tema: [TEMA PRINCIPAL]
- Subtítulo: [SUBTÍTULO IMPACTANTE]
- Audiencia: [Junta directiva/Clientes/Inversionistas/Equipo/etc.]
- Objetivo: [Vender/Presentar resultados/Persuadir/Explicar]
- Tono: [Persuasivo/Ejecutivo/Técnico/Inspirador]
- Restricción: [No emojis]

## estructura narrativa

1. Portada: Título + subtítulo + fecha/presentador
2. Contexto: [Contexto del tema]
3. Cifras clave: [3-4 KPIs con valores]
4. Problema: [El desafío actual]
5. Limitación: [Lo que no podemos hacer hoy]
6. Oportunidad: [La oportunidad identificada]
7. Solución: [La propuesta de valor]
8. Cómo funciona: [Pasos o proceso]
9. Comparativa: [Nosotros vs. competencia]
10. Modelo económico: [Precios o costos]
11. Beneficios: [Resultados esperados]
12. Cierre: [Llamado a la acción]

## datos a incluir

[CIFRAS ESPECÍFICAS:]
- KPI 1: [valor] - [descripción]
- KPI 2: [valor] - [descripción]
- KPI 3: [valor] - [descripción]
- [Otros datos relevantes]

MENSAJES CLAVE:
- [Mensaje 1 importante]
- [Mensaje 2 importante]
- [Mensaje 3 importante]

## requisitos técnicos

1. Un único archivo HTML con CSS y JS embebidos
2. Cada slide = 100vh (pantalla completa)
3. Navegación con puntos laterales (bullets)
4. Avanzar con scroll y teclas ←↑↓→
5. Diseño responsive (16:9)
6. Animaciones suaves (fadeInUp con staggered delays)
7. KPI cards visuales y proporcionados
8. Comparativas claras en 3 segundos
9. No deformar tipografía ni imágenes
10. Tarjetas con hover effect
11. Barra de progreso superior (3px, color acento, ancho proporcional al avance)
12. Botón de pantalla completa (fullscreen) arriba a la derecha
13. Alternar fondos claros y oscuros entre diapositivas para romper monotonía
14. Logo Asimetrix adaptativo: en fondo oscuro se muestra blanco/original, en fondo claro se muestra negro (usar filter:brightness(0))
15. Colores en OKLCH preferiblemente (neutrales tintados hacia el hue del brand)
16. Textura de grano sutil (SVG noise) como overlay en body para premium
17. SVG sprites con <symbol>/<use> para iconos repetidos (no duplicar inline SVGs)
18. Transición especial entre portada y segunda diapositiva (opcional: zoom mascota + escaneo matrix + dissolve)

## salida esperada

- Archivo HTML completo
- Listo para guardar como .html
- Sin explicaciones innecesarias
- Contenido completo construido
- Diseño profesional terminado


---

## parte 3: ejemplo de prompt completado

---

*Prompt de ejemplo para usar:*


Eres un diseñador gráfico experto en presentaciones corporativas premium. Crea una presentación HTML completa usando el sistema de diseño Asimetrix.

## configuración visual

- Color primario: #040939
- Color secundario: #0E567B  
- Color de acento: #4BA2FF
- Color de fondo: Blanco (#FFFFFF)
- Fuente: Roboto (Google fonts)
- Estilo: corporativo premium, estilo Apple keynote
- Logo: Usa el logo asimetrix en la esquina inferior derecha de cada diapositiva y muestralo grande en la primera, si el fondo de la diapositva es blanco o color claro, muestra el logo en negro, si es de color dejalo como esta.

## contexto de la presentación

- Tema: Propuesta de Transformación Digital
- Subtítulo: Optimización de procesos para el sector industrial
- Audiencia: Junta directiva de empresa manufacturera
- Objetivo: Obtener aprobación para presupuesto de transformación digital
- Tono: Persuasivo y ejecutivo

## estructura narrativa

1. Portada: "Transformación Digital 2025" + "Eficiencia operativa +40%"
2. Contexto: Tendencias de digitalización en manufacturing
3. Cifras clave: 67% empresas digitalizadas, $2.3M mercado, 18 meses ROI
4. Problema: Procesos manuales, errores humanos, costos elevados
5. Limitación: sistemas legacy, resistencia al cambio, falta de talento tech
6. Oportunidad: Capturar 15% del mercado en 18 meses
7. Solución: Plataforma integrada de automatización
8. Cómo funciona: Diagnóstico → Implementación → Optimización → Escalamiento
9. Comparativa: Proceso actual vs. solución propuesta
10. Modelo económico: $1,499/mes por usuario, 30% margen
11. Beneficios: +40% eficiencia, -35% costos, NPS 85+
12. Cierre: "Comencemos la transformación"

## datos a incluir

CIFRAS:
- 67% de empresas del sector ya están en proceso de transformación digital
- $2.3 millones de mercado potencial
- 40% de incremento en eficiencia operativa
- 35% de reducción en costos de operación
- 18 meses para recuperar inversión
- ROI de 3x en primer año

MENSAJES CLAVE:
- La digitalización no es opcional, es supervivencia
- El momento de actuar es ahora
- tenemos la experiencia y el equipo para hacerlo

## requisitos técnicos

1. Un único archivo HTML con CSS y JS embebidos
2. Cada slide = 100vh (pantalla completa)
3. Navegación con puntos laterales (bullets)
4. Avanzar con scroll y teclas
5. Diseño responsive
6. Animaciones suaves (fadeInUp con staggered delays)
7. KPI cards con iconos
8. Gráficos de progreso visual
9. Comparativas claras: "Antes vs. Después"
10. Estilo premium tipo Apple/consultoría
11. Barra de progreso superior azul claro (3px, proporcional al avance entre slides)
12. Botón de fullscreen arriba a la derecha (se adapta al tema claro/oscuro)
13. Alternar fondos: intercalar slides oscuras (#040939) con slides claras (blanco/gris) para no ser plano
14. Logo adaptativo: en slides oscuras mostrar el logo original (claro), en slides claras usar filter:brightness(0) para mostrarlo negro
15. Preferir OKLCH para colores, tintando neutrales hacia el hue del brand
16. Textura de grano premium (SVG feTurbulence noise) como overlay sutil (opacity 0.02-0.03)
17. Usar <svg><symbol> sprites para iconos repetidos, referenciados con <use href="#id"/>

## salida esperada

Archivo HTML completo, listo para presentar, diseño profesional premium.


---

## parte 4: instrucciones de uso

### para chatgpt:
 1.⁠ ⁠Copia la parte 3 completa
 2.⁠ ⁠Pega en el chat
 3.⁠ ⁠Espera el código HTML
 4.⁠ ⁠Guarda el archivo como ⁠ presentacion.html ⁠
 5.⁠ ⁠Abre en tu navegador

### para gemini:
 1.⁠ ⁠Usa el mismo prompt de la parte 3
 2.⁠ ⁠Solicita el código en un solo bloque
 3.⁠ ⁠Descarga el archivo HTML

### personalización adicional:
•⁠  ⁠*Para cambiar colores:* Modifica los valores CSS en ⁠ :root ⁠
•⁠  ⁠*Para agregar imágenes:* Usa bloques con ⁠ background-image ⁠ o etiquetas ⁠ <img> ⁠
•⁠  ⁠*Para más slides:* Copia la estructura de un slide existente y cambia el contenido
•⁠  ⁠*Para diferente número de puntos de navegación:* El JS genera automáticamente según slides

---

## notas importantes

 1.⁠ ⁠*Capitalización en español:* sigue estas reglas estrictamente
   - Usa SIEMPRE Sentence Case (solo mayúscula inicial de cada oración)
   - Evita Title Case (donde cada palabra inicia con mayúscula)
   - Ejemplo correcto: "Resultados del cuarto trimestre 2024"
   - Ejemplo incorrecto: "Resultados Del Cuarto Trimestre 2024"
   - Mayúscula solo al inicio de texto, después de punto, y después de ¡! o ¿?
   - Nombres propios: personas, lugares, instituciones, marcas (María, Madrid, Universidad Nacional, Coca-Cola)
   - Primera palabra de títulos de obras (Cien años de soledad)
   - NO usan mayúscula: días (lunes), meses (abril), estaciones (verano), gentilicios (mexicano), cargos (rey, presidente)
   - Siglas: todo en mayúsculas (ONU, RAE)

 2.⁠ ⁠*Revisión obligatoria:* Antes de generar el contenido, revisa 3 veces cada palabra para evitar errores de capitalización. Asegúrate de que:
   - Todos los títulos usen Sentence Case
   - No haya Title Case en ningún encabezado
   - Los nombres propios estén correctamente capitalizados
   - Los acrónimos estén en mayúsculas (si corresponde)

 3.⁠ ⁠*KPI cards:* Usar valores proportionados, no exaggerar tamaños
 4.⁠ ⁠*Imágenes:* Si no tienes, usar placeholders con gradientes o iconos SVG
 5.⁠ ⁠*Animaciones:* Incluir ⁠ animate ⁠ y ⁠ animate-delay-1 ⁠, ⁠ animate-delay-2 ⁠, etc.
 6.⁠ ⁠*Navegación:* Puntos laterales + teclado + scroll funcionan automáticamente

---

## parte 5: mejoras visuales premium (aplicar siempre)

Estas mejoras adicionales elevan la calidad visual de las presentaciones:

### barra de progreso superior
- Barra fija en `top:0`, 3px de alto, color acento (`#4BA2FF`)
- Width proporcional: `((slideActual + 1) / totalSlides) * 100%`
- Transición suave con `cubic-bezier(0.16, 1, 0.3, 1)`
- Box-shadow sutil para glow

### botón de pantalla completa
- Posición `fixed top:16px right:16px`, z-index alto
- Icono SVG de 4 esquinas de expansión
- Adaptar estilos al tema del slide activo (claro/oscuro)
- Al hacer click: `document.documentElement.requestFullscreen()`

### fondos alternados (no plano)
- Intercalar slides con fondo oscuro (`oklch(10% 0.042 258)`) y fondo claro (blanco o `oklch(97% 0.005 258)`)
- Patrón recomendado: Portada oscura → slide 2 clara → slide 3 oscura → slide 4 clara...
- Cada slide debe tener `data-theme="dark"` o `data-theme="light"` para que el JS adapte navegación

### logo adaptativo
- En slides oscuras: logo original (colores claros, sin filtro)
- En slides claras: `filter:brightness(0)` para mostrar logo en negro
- Posición: esquina inferior derecha, `height:28px`

### colores OKLCH
- Usar `oklch()` para todos los colores de fondo, texto y bordes
- Tintear neutrales hacia el hue 258 (brand Asimetrix): `oklch(98% 0.005 258)` en vez de `#fff`
- Reducir chroma cerca de extremos de lightness (0% y 100%)
- Nunca usar `#000` o `#fff` puros

### textura de grano (premium)
```css
body::after {
  content: '';
  position: fixed;
  inset: 0;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='1'/%3E%3C/svg%3E");
  background-size: 256px 256px;
  opacity: 0.028;
  pointer-events: none;
  z-index: 1000;
  mix-blend-mode: overlay;
}
```

### SVG sprites (optimización)
- Definir iconos repetidos como `<symbol>` dentro de un SVG oculto al inicio del body
- Referenciar con `<svg width="16" height="16"><use href="#icon-name"/></svg>`
- Reduce tamaño HTML significativamente

### transición 3D matrix (portada → segunda diapositiva)

Efecto especial para la transición entre la portada y la segunda slide. Secuencia:

1. **Overlay oscuro** se activa (`opacity:1`, fondo `oklch(6% 0.03 258)`)
2. **Mascota/imagen** aparece centrada, escala de `0.6` a `1.1` con `cubic-bezier(0.16, 1, 0.3, 1)` (650ms)
3. **Escaneo matrix** (650ms–1350ms): líneas horizontales verdes barren de arriba a abajo + glow láser + lluvia de caracteres katakana/hex
4. **Dissolve** (1350ms–1900ms): mascota escala a `1.6` con `opacity:0`, overlay se desvanece revelando la slide 2

```css
/* Scan lines */
#scan-lines::before {
  background: repeating-linear-gradient(180deg,
    oklch(75% 0.22 145 / 0.0) 0px,
    oklch(75% 0.22 145 / 0.12) 1px,
    oklch(75% 0.22 145 / 0.0) 3px,
    oklch(75% 0.22 145 / 0.0) 6px);
  animation: scanSweep 0.8s cubic-bezier(0.25, 0, 0.3, 1) forwards;
}

@keyframes scanSweep { from { top: -100%; } to { top: 100%; } }

/* Glow bar */
#scan-glow {
  background: oklch(80% 0.25 145);
  box-shadow: 0 0 30px 10px oklch(70% 0.22 145 / 0.5),
              0 0 80px 20px oklch(60% 0.18 145 / 0.25);
  animation: glowSweep 0.8s cubic-bezier(0.25, 0, 0.3, 1) forwards;
}

/* Matrix rain columns */
.matrix-col {
  font-family: 'Courier New', monospace;
  font-size: 12px;
  color: oklch(75% 0.22 145);
  text-shadow: 0 0 8px oklch(65% 0.2 145 / 0.8);
  writing-mode: vertical-lr;
  text-orientation: upright;
}
```

```javascript
// Spawn columns with random katakana + hex characters
function spawnMatrixRain() {
  const cols = Math.floor(window.innerWidth / 18);
  const chars = 'アイウエオカキクケコサシスセソタチツテト0123456789ABCDEF';
  for (let i = 0; i < cols; i++) {
    const col = document.createElement('div');
    col.className = 'matrix-col';
    col.style.left = (i * 18) + 'px';
    col.style.opacity = (0.15 + Math.random() * 0.35).toString();
    let text = '';
    for (let j = 0; j < 60; j++) text += chars[Math.floor(Math.random() * chars.length)];
    col.textContent = text;
    overlay.appendChild(col);
  }
}
```

- Imagen de mascota: `https://asimetrix.co/hubfs/AX%20-%20Pv%20con%20cerdo.png`
- Solo se activa en transición slide 0 ↔ 1 (portada ↔ segunda)
- Resto de slides usa transición normal (translateY + opacity)
- Limpiar columnas matrix con `.remove()` en fase de cleanup

### prohibiciones de diseño
- **NO** usar `background-clip: text` con gradientes (gradient text)
- **NO** usar `border-left` o `border-right` > 1px como acento decorativo
- **NO** usar glassmorphism como default (solo si es muy justificado)
- **NO** repetir el mismo tamaño de card en cuadrícula (variar contenido y tamaños)
- **NO** usar bounce o elastic en easings (usar ease-out exponencial)

---

## parte 6: ejemplo en vivo

Esta presentación fue generada siguiendo exactamente las instrucciones de esta plantilla. Úsala como referencia visual del resultado esperado.

<div style="position:relative;width:100%;padding-bottom:56.25%;border-radius:16px;overflow:hidden;border:1px solid oklch(0% 0 0 / 0.1);box-shadow:0 8px 32px oklch(0% 0 0 / 0.12);margin:24px 0;">
  <iframe
    src="md/presentacion-maneja-tu-ia.html"
    style="position:absolute;top:0;left:0;width:100%;height:100%;border:none;"
    title="Ejemplo de presentación generada con la plantilla Asimetrix"
    loading="lazy"
  ></iframe>
</div>

> Navega con las teclas ←↑↓→, scroll, o los puntos laterales. Presiona el ícono de pantalla completa para la experiencia completa.

---

Plantilla creada para el sistema de diseño Asimetrix