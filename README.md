Source: Web Fetch
---
NoteDiscovery | Knowledge Base | Docker
 NoteDiscovery: Base de conocimiento autohospedada en Docker (alternativa Obsidian Sync, Notion, Apple Notes)
 Gestor de notas Markdown con grafo de conocimiento, búsqueda full-text, backlinks bidireccionales. MCP para IA. Temas customizables. Dark mode. Offline-capable. FastAPI + Alpine.js. MIT open source.

 ¿Qué es NoteDiscovery?
 NoteDiscovery es una herramienta moderna de toma de notas self-hosted que permite construir tu propia base de conocimiento con Markdown puro, sin dependencia de servicios cloud ni vendor lock-in. Es la alternativa open source a Obsidian Sync, Notion, Roam Research, diseñada para máxima privacidad y propiedad de datos.

 Propuesta clave: Tus notas viven como archivos .md plain text en una carpeta que controlas. Puedes usar git, grep, cualquier tool sobre ellas. Editor split-pane (Markdown + preview en vivo). Grafo de conocimiento dinámico (visualiza conexiones entre notas). Búsqueda instant full-text. Backlinks bidireccionales (wikilinks [[nota]]). Dark mode. MCP integration para IA (Claude, Cursor). Zero database, cero complejidad. Corre en 50MB RAM. Docker one-liner setup.

 Características principales: Editor Markdown split-pane (izquierda: source, derecha: live preview sin lag). Grafo de conocimiento dinámico con visualización. Búsqueda full-text instant. Backlinks bidireccionales (wikilinks [[nota]]). Outline panel (tabla de contenidos, click-to-jump). Favoritos (star notes). Temas customizables. Dark mode + light mode. Dibujo en-app (sketches PNG). Soporte LaTeX (MathJax) para ecuaciones. Syntax highlighting (100+ lenguajes). Mermaid diagrams. Archivos adjuntos (images, PDFs, etc). Table of contents automático. URI protocols (mailto, ssh, ftp, slack, discord, etc). Plantillas custom. Sistema plugin (extensible). Multi-idioma (15+, incluyendo español). MCP server integrado (interacción IA). Almacenamiento YAML config. FastAPI backend. Alpine.js frontend (sin heavy frameworks). Healthcheck Docker. MIT open source. Compatible Obsidian (importa bóvedas). Git-friendly (version control notas).

 Para knowledge workers: Segunda cerebro privada. Base de conocimiento sin suscripción. Datos tuyos. Forever.

 Características principales

 Editor Markdown split-pane
 Source + live preview sin lag. Sintaxis highlighting.

 Grafo de conocimiento dinámico
 Visualiza conexiones entre notas. Graph view 3D.

 Búsqueda full-text instant
 Encuentra notas rápidamente. Cached search.

 Backlinks bidireccionales
 Wikilinks [[nota]]. Descubre relaciones automáticamente.

 Outline panel (TOC)
 Tabla de contenidos. Click-to-jump headings.

 Temas customizables
 Dark mode, light mode, custom themes. YAML config.

 Dibujo integrado
 In-app sketches. PNG files next to markdown.

 LaTeX + MathJax
 Ecuaciones matemáticas. Mermaid diagrams.

 MCP para IA
 Claude, Cursor, Anthropic tools. IA lee tus notas.

 Multi-idioma
 15+ idiomas. Español incluido. Locales customizables.

 Almacenamiento plain text
 Markdown files. Sin BD. Git-friendly. Portabilidad.

 Ultra-ligero
 50MB RAM. FastAPI + Alpine.js. Sin heavy frameworks.

 Requisitos del sistema

 Docker & Docker Compose
 50-100 MB RAM mínimo (ultra-ligero)
 500 MB - 5 GB espacio disco (depende volumen notas)
 Puerto 8000 o custom (configurable)
 Navegador moderno: Chrome, Firefox, Safari, Edge
 Python 3.10+ (si ejecutas sin Docker)

 Setup ultra-rápido: Docker one-liner. 60 segundos a funcionar.

 Instalación con Docker Compose

 Opción 1: Docker Compose (recomendado)
 mkdir -p notediscovery/data && cd notediscovery

curl -O https://raw.githubusercontent.com/gamosoft/NoteDiscovery/main/docker-compose.ghcr.yml


docker compose -f docker-compose.ghcr.yml up -d

 Opción 2: Docker Compose custom

docker compose up -d

 Opción 3: Docker run simple
 mkdir -p ./notediscovery-data

docker run -d \\
 --name notediscovery \\
 --restart unless-stopped \\
 -p 8000:8000 \\
 -v ./notediscovery-data:/app/data \\
 ghcr.io/gamosoft/notediscovery:latest

 Acceder (setup inicial)
 http://localhost:8000 - Dashboard NoteDiscovery

 Primer uso

 Abre http://localhost:8000
 Verás editor Markdown split-pane limpio
 Click \"New Note\" para crear primera nota
 Escribe título y contenido
 Auto-save cada 5 segundos (visto en UI)
 ¡Listo! Notas guardadas en ./data/

 Primeros pasos

 1. Crear primera nota

 Click \"+ New Note\"
 Nombre: \"Mi Primera Nota\"
 Contenido: escribe Markdown (# Título, **bold**, etc)
 Live preview aparece a la derecha en tiempo real
 Auto-saved

 2. Usar wikilinks (backlinks bidireccionales)

 En nota, escribe: [[Otra Nota]]
 Se crea automático link a esa nota
 En \"Otra Nota\", verás backlink a primera nota
 Graph view muestra conexión visualmente

 3. Ver grafo de conocimiento

 Menú → \"Graph View\"
 Visualiza notas como nodos, links como aristas
 Click nodo para navegar a nota
 Zoom, pan, interactivo

 4. Buscar notas (instant full-text)

 Search bar arriba (lupa icon)
 Escribe palabra clave
 Resultados instant en ambos: titulo + contenido
 Cached para velocidad

 5. Star favoritos

 Nota → click ⭐ icon
 Aparece en \"Favoritos\" panel
 Acceso rápido a notas importantes

 6. Usar LaTeX (ecuaciones matemáticas)
 $$E = mc^2$$

Inline: $E = mc^2$

 Powered by MathJax
 Renderiza automático en preview

 7. Insertar Mermaid diagrams
 ```mermaid
graph TD
 A[Start] --> B[Process]
 B --> C[End]
```

 8. Dibujar sketches (in-app drawing)

 Menu → \"+ New Drawing\"
 Editor de dibujo aparece (pencil, lines, shapes, color picker)
 Autosave como PNG next to nota
 Link en Markdown para embed

 9. Cambiar tema (Dark/Light mode)

 Settings (engranaje icon) → Theme
 Elige Dark, Light, o custom
 Preferencia guardada

 10. MCP para IA (Claude, Cursor)

 En Claude Desktop config (~/.claude-desktop/claude_desktop_config.json):

 {
 \"mcpServers\": {
 \"notediscovery\": {
 \"command\": \"docker\",
 \"args\": [
 \"run\", \"--rm\", \"-i\",
 \"-e\", \"NOTEDISCOVERY_URL=http://host.docker.internal:8000\",
 \"ghcr.io/gamosoft/notediscovery:latest\",
 \"python\", \"-m\", \"mcp_server\"
 ]
 }
 }
}

 Reinicia Claude Desktop
 Claude ahora puede leer tus notas, explorar grafo, encontrar backlinks

 11. Cambiar idioma

 Settings → Language
 Elige español (u otro)
 UI cambia al instante

 Casos de uso

 Segunda cerebro (Zettelkasten): Sistema de notas conectadas. Descubre patrones. Asimilación conocimiento.
 Researchers/scholars: Base de conocimiento de papers, artículos, ideas. Grafo de referencias.
 Developers: Wiki técnica personal. Documentación interna. Recipes, cheat sheets, tutoriales.
 Teams/pequeños equipos: Wiki compartida. Control vía git. Sin SaaS.
 Privacidad-first: Notas nunca leave your server. Cero telemetría. Zero tracking.

 HTTPS con Caddy (producción)

 Caddyfile simple
 notes.tudominio.com {
 reverse_proxy localhost:8000
}

 Acceso remoto seguro
 https://notes.tudominio.com con HTTPS automático

 IMPORTANTE: Proteger con autenticación
 Por defecto, NoteDiscovery NO tiene autenticación (default password: admin). CAMBIAR si expones a red

 Gestión y mantenimiento

 Ver logs
 docker logs -f notediscovery

 Backup de notas (IMPORTANTE)
 cp -r ./data ./data-backup-$(date +%Y%m%d-%H%M%S)

cd ./data && git add . && git commit -m \"Backup $(date)\" && cd ..

 Restore de backup
 docker stop notediscovery
rm -rf ./data
cp -r ./data-backup-YYYYMMDD-hhmmss ./data
docker start notediscovery

 Reiniciar container
 docker compose restart

 Actualizar a versión más reciente
 docker compose pull
docker compose up -d

 Monitorear consumo (ultra-ligero)
 docker stats notediscovery

 Explorar notas (CLI)
 ls -la ./data/

find ./data -name \"*.md\" | wc -l

grep -r \"palabra-clave\" ./data/

 Comparativa con alternativas

 vs Obsidian Sync (SaaS)
 NoteDiscovery gana: Gratis, self-hosted, web-based. Obsidian gana: Desktop app, plugins masivos, sincronización E2E.

 vs Notion
 NoteDiscovery gana: Markdown puro, privacidad, grafo. Notion gana: Databases, templates, UI polished, team features.

 vs Roam Research (SaaS)
 NoteDiscovery gana: Self-hosted, gratis, open source. Roam gana: Roam protocol, PKM features, community.

 vs Apple Notes/Google Keep
 NoteDiscovery gana: Backlinks, grafo, Markdown, datos tuyos. Cloud gana: Sync automático, simplicity.

 Mejor para: Knowledge workers que valoran privacidad, ownership, Markdown, y grafo. Segunda cerebro sin suscripción.