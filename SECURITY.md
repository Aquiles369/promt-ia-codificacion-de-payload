# Política de seguridad

## 🧠 Resumen
**Prompt IA — Codificación de payload** es un recurso educativo/ofensivo para **laboratorio**.  
No ejecuta código por sí mismo ni interactúa con sistemas externos; guía la generación de variantes codificadas de payloads con fines de prueba ética.

---

## 🔐 Principios de seguridad
- **Uso ético y legal**: solo en entornos con autorización explícita (labs, programas de bug bounty, auditorías).
- **Contenido seguro**: no incluye exploits activos ni automatiza ataques en sistemas reales.
- **Privacidad**: no recopila ni debe almacenar datos sensibles en ejemplos.
- **Sin backend**: es documentación/plantilla; la ejecución corre por cuenta del usuario en su entorno controlado.

---

## ✅ Buenas prácticas
- Validar y revisar cada variante en entornos aislados antes de cualquier uso real.
- Respetar el **alcance** de programas de bug bounty y normas locales.
- Mantener registro interno de pruebas (reproducibilidad con `seed`).
- No compartir públicamente payloads sensibles ni específicos de un target sin permiso.

---

## 🐛 Reporte de problemas
Si detectás inconsistencias o riesgos:
1) No publiques detalles sensibles en issues.  
2) Contactá al mantenedor (GitHub/Discord).  
3) Incluí contexto: payload(s), `x18_list`, `apply_scope`, flags y `seed`.

---

## 🛡️ Alcance

| Área                         | Estado                 |
|-----------------------------|------------------------|
| Backend / API               | ❌ No aplica           |
| Ejecución de código         | ❌ No incluida         |
| Payloads activos            | ❌ No incluidos        |
| Guía/plantilla de uso       | ✅ Incluida            |
| Datos sensibles             | ❌ No almacenar        |

---

## ⚠️ Descargo
Recurso con fines **educativos y de investigación**. El uso indebido puede ser ilegal.  
El autor no se hace responsable por acciones no autorizadas derivadas del uso de esta plantilla.

---

**“Codificá, mutá y evadí — tu payload nunca más será el mismo.”**
