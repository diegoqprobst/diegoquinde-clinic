# clinic.diegoquinde.com

Sitio personal de investigación de **Diego Andrés Quinde Probst** — la intersección de la
terapia breve estratégica/sistémica y la IA. Modelos interactivos + divulgación.

- `index.html` — homepage autocontenida (HTML/CSS/JS vanilla, sin build). Incluye un modelo
  interactivo del contrafactual de una intervención.
- `CNAME` — dominio personalizado: `clinic.diegoquinde.com`

## Despliegue (Vercel)

El sitio es estático y se sirve en Vercel, junto al dominio `diegoquinde.com`.

1. En Vercel: **New Project** → importa este repositorio.
2. **Framework Preset: Other.** Build Command vacío. Output Directory: `.` (raíz).
3. **Settings → Domains** → añade `clinic.diegoquinde.com`. Como `diegoquinde.com` ya está en
   la cuenta, Vercel configura el DNS y emite el certificado HTTPS automáticamente.

Cada push a `main` redespliega.

## Iterar

Es HTML/CSS/JS plano: edita `index.html`. Para añadir un modelo interactivo nuevo, duplica el
patrón de la sección `#modelo` (SVG + un poco de JS).

---

Material de investigación con datos 100% sintéticos. Las herramientas son apoyo para pensar y
formarse en clave sistémica; no predicen casos reales ni sustituyen el juicio clínico. No son
dispositivos médicos.
