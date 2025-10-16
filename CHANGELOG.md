# Changelog

Todas las versiones siguen el formato [SemVer].

## [v1.0.0] - 2025-10-16
### 🆕 Añadido
- **Prompt IA — Codificación de payload**: generador automático de variantes *codificadas* de payloads XSS para laboratorio, manteniendo ejecución y estructura.
- **x18_list (100 técnicas+)**: desde Base64, URL-encode y entidades HTML, hasta escapes JS, UTF-16/32, ROT, MIME, CSS, PDF, SQL, JSON, YAML, etc.
- **Scopes de aplicación**:
  - `special_only` → solo caracteres especiales (`< > / = ' " + ( ) { } [ ] . , ; : % # & ? \` ~ ^ | \`).
  - `all` → contenido completo (preservando tokens críticos).
  - `mixed` → segmentación inteligente (URL, texto, JS).
- **Flags combinables**:
  - `#*` reutiliza última codificación.
  - `#**` solo codifica no-reservados.
  - `#a` mezcla codificaciones por sección.
- **Reproducibilidad** con `seed` y control de `variants_per_payload`.
- **Validación estricta** (A–F): tokens críticos, balanceo de delimitadores, primitiva de ejecución, lista de codificaciones, scope respetado, sin BIDI/invisibles en tokens.
- **Salida mínima**: solo lista de payloads resultantes, uno por línea (sin metadatos).
- **Plantilla de uso**: bloque “AHORA, PEDIR INSUMOS” para ejecución guiada.

### ✨ Cambiado
- N/A — primera versión.

### 🐞 Corregido
- N/A — primera versión.

### 📌 Notas
- Orientado a **laboratorio** y programas con autorización.  
- “Codificá, mutá y evadí — tu payload nunca más será el mismo.”
