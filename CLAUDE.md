# Herramientas para Claude Code

## Plugins recomendados (instalación manual)
```
/plugin marketplace add DietrichGebert/ponytail
/plugin install ponytail@ponytail
/plugin marketplace add addyosmani/agent-skills
/plugin install agent-skills@addy-agent-skills
```
- **Ponytail** (`DietrichGebert/ponytail`): prioriza la solución más simple (YAGNI, stdlib primero). No recorta validación, seguridad ni accesibilidad. Requiere Node en el PATH.
- **Agent Skills** (`addyosmani/agent-skills`): skills de ciclo de vida de ingeniería: `/spec`, `/plan`, `/build`, `/test`, `/review`, `/ship`.

Pendiente: habilitarlos por defecto en `.claude/settings.json` (`extraKnownMarketplaces` + `enabledPlugins`), para que se activen solos al abrir el repo.

## Instalación manual (no es un plugin de marketplace)
- **Graphify** (`safishamsi/graphify`, paquete PyPI `graphifyy`): grafo de conocimiento del código para reducir tokens al explorar.
  ```
  uv tool install graphifyy   # o pipx install graphifyy
  graphify install            # escribe skill, CLAUDE.md y hooks; revisar el diff antes de commitear
  ```
  Uso: `/graphify`.

## Deliberadamente NO incluido
- **OmniRoute** (`diegosouzapw/OmniRoute`): es un gateway/proxy de modelos, no un plugin. Aloja credenciales de proveedores y ve todos los prompts y respuestas. No usar con información corporativa sin revisión de seguridad.
