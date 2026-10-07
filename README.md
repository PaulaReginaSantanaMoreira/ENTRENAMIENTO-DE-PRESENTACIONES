# 🎙️ ENTRENAMIENTO DE PRESENTACIONES

> **Aplicación Web Interactiva de Entrenamiento de Oratoria, Pronunciación y Control de Ansiedad para Presentaciones Académicas y Defensa de TFM ante Tribunal de la Unión Europea.**

🌐 **Despliegue GitHub Pages:** [https://PaulaReginaSantanaMoreira.github.io/ENTRENAMIENTO-DE-PRESENTACIONES/](https://PaulaReginaSantanaMoreira.github.io/ENTRENAMIENTO-DE-PRESENTACIONES/)

---

## 📱 Diseñado para Móviles, Tabletas y Ordenadores

Esta aplicación cuenta con arquitectura web adaptativa (*Mobile-First Responsive*) y soporte para **PWA (Progressive Web App)**:
- **📱 Teléfonos Móviles (Smartphones):** Interfaz vertical optimizada, botones táctiles de 48px+, selector de **cámara frontal / trasera** y gestos de deslizamiento (*Swipe*) con el dedo para avanzar diapositiva.
- **📟 Tabletas & iPads:** Distribución en estudio virtual con cámara web en directo al lado de la diapositiva y notas de apertura.
- **💻 Ordenadores & Portátiles:** Monitor dual con atajos de teclado (`Espacio`/`→` para avanzar, `P` para pausar) y visor de oratoria a pantalla completa.

---

## 🌟 Características Principales

### 1. 📹 Grabación de Vídeo y Voz en cada Tentativa
- Elección previa entre **Vídeo + Audio (Cámara Web)** o **Solo Voz (Audio Micrófono)**.
- Monitor en directo con efecto espejo regulable y control de contacto visual.
- Reproductor integrado con **navegación por diapositivas mediante marcas de tiempo** instantáneas.
- Descarga directa de la grabación en formato `.webm` / `.mp4`.

### 2. 🎤 Análisis Acústico en Vivo: Entonación y Volumen
- **Web Audio API:** Monitoreo dinámico del centroide espectral y pitch.
- **Detección de Monotonía:** Alerta si la voz se mantiene monótona o plana por más de 20 segundos.
- **Vúmetro de Volumen:** Indicadores de proyección vocal (*Suave*, *Óptimo*, *Fuerte*).
- **Detección de Silencios/Bloqueos:** Identificación de pausas incómodas superiores a 4.5 segundos.

### 3. 🗣️ Reconocimiento de Voz & Detección de Muletillas
- Transcripción en tiempo real en español (`es-ES`).
- Filtro acústico y semántico de muletillas académicas (*"eh"*, *"em"*, *"este..."*, *"o sea"*, *"bueno"*, *"digamos"*, *"básicamente"*, etc.).
- Medidor de velocidad de habla en **Palabras por Minuto (WPM)** con alertas de aceleración por ansiedad (>165 WPM).

### 4. 🔍 Auditoría Detallada de Fallos Observados
- Tarjetas individuales para cada incidencia observada con su **minuto y segundo exacto** (`📍 Slide 3 · [02:15]`).
- **Botón `▶ Ver/Oír este Fallo`:** Salta automáticamente en la grabación para escuchar cómo pronunciaste o entonaste en ese instante exacto.
- Explicación del **impacto ante el Tribunal de la UE** y **pauta de corrección inmediata**.
- Registro para añadir observaciones manuales del estudiante o tutor.

### 5. 🏆 Puntuación Global (0 a 10)
Fórmula de valoración ponderada en 6 dimensiones:
1. **Entonación & Modulación Vocal** (20%)
2. **Pronunciación & Dicción** (20%)
3. **Ritmo, Pausas & WPM** (20%)
4. **Control del Cronómetro (15:00 min)** (20%)
5. **Foco y Rigor Académico del TFM** (10%)
6. **Control Emocional & Ansiedad** (10%)

### 6. 📊 Historial y Exportación
- Histórico persistente en `localStorage`.
- Exportación en formato **CSV**.
- Vista de impresión formateada a **PDF**.

---

## 🚀 Cómo usar en el Teléfono o Tableta

1. Abre el enlace en **Safari (iOS)** o **Chrome (Android)**.
2. En Safari: Pulsa el botón **Compartir** → **"Añadir a pantalla de inicio"**.
3. En Chrome: Pulsa los tres puntos `⋮` → **"Instalar aplicación"** o **"Añadir a pantalla de inicio"**.
4. ¡Listo! La aplicación se abrirá a pantalla completa sin barra de navegación, como una app nativa.

---

## 👩‍🎓 Autoría
- **Autora:** Paula Regina Santana Moreira
- **Máster:** Gestión de la Seguridad Alimentaria en la Unión Europea
- **TFM:** Rúbrica y Aplicativo de Auditoría Higiénico-Sanitaria
