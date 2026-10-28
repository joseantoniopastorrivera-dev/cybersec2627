# cybersec2627 (Ciberseguridad CMO-314)

Sitio MkDocs con los materiales del módulo y proyectos en Python.

## Estructura
- `docs/ud1` … `docs/ud6` — teoría, actividades y retos por unidad (Markdown).
- `docs/proyectos/` — proyectos Python por unidad (plantilla con `TODO` + tests).
- `docs/recursos/`, `docs/retos/`, `docs/javascripts/`, `docs/stylesheets/`.
- `mkdocs.yml` — navegación y configuración; `hooks/pagina_completa.py` — hook de MkDocs.
- `.github/workflows/publicar.yml` — publica el sitio.

## Comandos
- `python -m venv .venv` y activarlo (`.venv\Scripts\activate` en Windows), luego `pip install -r requirements.txt`.
- `mkdocs serve` (http://127.0.0.1:8000) · `mkdocs build` (genera `site/`, no subirlo).
- Retos/proyectos: `pip install -r requirements-retos.txt`; los tests de cada proyecto están junto a su plantilla.

## Notas
- Una página nueva necesita entrada en `nav` de `mkdocs.yml`.
- Herramientas ofensivas solo contra el laboratorio propio, según el uso ético del módulo.
