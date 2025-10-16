# Release Notes — v1.0.0 (2025-10-16)

## 🧠 Resumen
**Prompt IA — Codificación de payload**: fábrica automática de variantes XSS codificadas que mantiene el payload funcional y ayuda a romper filtros (WAF, sanitizadores, parsers) sin alterar la ejecución.  
Permite elegir técnicas (x18_list), alcance (`special_only | all | mixed`), banderas (#*, #**, #a), `seed` y `variants_per_payload`.  
📺 Demo: “lista codificaciones” en YouTube.

---

## 🧪 Problema que resuelve
WAF/filtros detectan payloads conocidos y bloquean PoCs. Este prompt:
- **Automatiza** miles de variantes.
- **Mantiene** sintaxis y ejecución.
- **Permite** evaluar impacto de cada codificación en detección/ejecución.

---

## ⚙️ Qué aporta
- **Automatización total**: input (payload/ lista) → N variantes listas.
- **Evasión multiplicada**: base64, URL doble, entidades mixtas, escapes JS/Unicode, ROT, MIME, etc.
- **Investigación sólida**: compara qué codificaciones pasan, cuáles fallan y por qué.
- **Laboratorio seguro**: pensado para entornos controlados.

---

## 🧰 Inputs principales
- `payloads`: uno o lista (uno por línea).
- `seed`: entero opcional (reproducibilidad).
- `variants_per_payload`: cuántas variantes por payload.
- `x18_list`: IDs de codificaciones a aplicar (ver catálogo 1–100).
- `apply_scope`: `special_only` | `all` | `mixed`.
- `combo_flags`: `#*`, `#**`, `#a` (opcional).
- `modo_validación`: `estricto` (default) | `relajado`.

---

## 🛡️ Reglas duras (extracto)
1) **No tocar tokens críticos ASCII** (`< > = + ( ) { } [ ] . , ; : ' " / ? ! & # % * \` ~ ^ | \`).  
2) **No cambiar nombres** de etiquetas/eventos (`script`, `img`, `onerror`, etc.).  
3) `special_only` → toca **solo** especiales.  
4) `all` → codifica texto/IDs/URLs preservando tokens.  
5) `mixed` → segmentación por contexto (URL/Texto/JS).  
6) Balanceo de delimitadores y **sin BIDI/invisibles** en tokens.  
7) Conservar **primitiva de ejecución** (alert/confirm/onerror/…); si rompe, **regenerar** (máx. 3 intentos).  

---

## ✅ Validación (modo estricto)
A) Tokens críticos preservados.  
B) Balanceo ()[]{}''"".  
C) Primitiva de ejecución presente.  
D) Codificaciones ∈ `x18_list`.  
E) Scope respetado.  
F) Sin BIDI/invisibles en tokens.

---

## 📤 Formato de salida
**Solo** los payloads generados, uno por línea. **Sin** títulos ni metadatos.

---

## 🛣️ Roadmap
- ✅ v1: 100 técnicas de codificación + scopes + flags + validación estricta.  
- ⏭️ v1.1: perfiles prearmados (WAF/CSP/DOM sinks) y ejemplos por contexto (HTML/atributo/JS/URL).

---

**“Una fábrica automática de variantes XSS codificadas que mantiene el payload funcional y rompe filtros como si fueran papel.”**
