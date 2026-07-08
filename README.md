# 📓 NoteDiscovery - Base de conocimiento autohospedada en Docker

![NotaDescubierta Logo](https://via.placeholder.com/150x50/0066CC/FFFFFF?text=NoteDiscovery) <!-- Placeholder for actual logo if available -->

> **NoteDiscovery** es una herramienta moderna de toma de notas self-hosted que permite construir tu propia base de conocimiento con Markdown puro, sin dependencia de servicios cloud ni vendor lock-in. Es la alternativa open source a Obsidian Sync, Notion, Roam Research, diseñada para máxima privacidad y propiedad de datos.

## 📖 Descripción

NotaDiscovery es una herramienta moderna de toma de notas self-hosted que permite construir tu propia base de conocimiento con Markdown puro, sin dependencia de servicios cloud ni vendor lock-in. Es la alternativa open source a Obsidian Sync, Notion, Roam Research, diseñada para máxima privacidad y propiedad de datos.

Tu notas viven como archivos .md plain text en una carpeta que controlas. Puedes usar git, grep, cualquier herramienta sobre ellas. Editor split-pane (Markdown + preview en vivo). Grafo de conocimiento dinámico (visualiza conexiones entre notas). Búsqueda instant full-text. Backlinks bidireccionales (wikilinks [[nota]]). Modo oscuro. MCP para IA (Claude, Cursor). Cero base de datos, cero complejidad. Corre en 50MB RAM. Docker one-liner setup.

## 🚀 Características

- ✅ **Editor Markdown split-pane**: Vista previa en vivo sin retraso
- ✅ **Grafo de conocimiento dinámico**: Visualiza conexiones entre notas en 3D
- ✅ **Búsqueda full-text instantánea**: Encuentra notas rápidamente con caché
- ✅ **Backlinks bidireccionales**: Wikilinks [[nota]] y descubrimiento automático de relaciones
- ✅ **Panel de esquema (TOC)**: Tabla de contenidos con salto a encabezados
- ✅ **Favoritos (estrellas)**: Acceso rápido a notas importantes
- ✅ **Temas personalizables**: Modo oscuro, modo claro, temas custom vía YAML
- ✅ **Dibujo integrado**: Bocetos en-app guardados como PNG junto al markdown
- ✅ **LaTeX + MathJax**: Ecuaciones matemáticas y diagramas Mermaid
- ✅ **MCP para IA**: Integración con Claude, Cursor y otras herramientas de IA
- ✅ **Multi-idioma**: 15+ idiomas incluyendo español
- ✅ **Almacenamiento en texto plano**: Archivos Markdown, sin base de datos, amigable con Git
- ✅ **Ultra-ligero**: 50MB RAM, FastAPI + Alpine.js, sin frameworks pesados

## 📋 Requisitos del Sistema

- Docker & Docker Compose
- 50-100 MB RAM mínimo (ultra-ligero)
- 500 MB - 5 GB de espacio en disco (dependiendo del volumen de notas)
- Puerto 8000 o personalizable (configurable)
- Navegador moderno: Chrome, Firefox, Safari, Edge
- Python 3.10+ (si ejecutas sin Docker)

## 🛠️ Instalación

### Opción 1: Docker Compose (recomendado)

```bash
mkdir -p notediscovery/data && cd notediscovery

curl -O https://raw.githubusercontent.com/gamosoft/NoteDiscovery/main/docker-compose.ghcr.yml

docker compose -f docker-compose.ghcr.yml up -d
```

### Opción 2: Docker Compose personalizado

```bash
mkdir -p notediscovery/data && cd notediscovery

cat > docker-compose.yml << 'EOF'
version: '3.8'

services:
  notediscovery:
    image: ghcr.io/gamosoft/notediscovery:latest
    container_name: notediscovery
    restart: unless-stopped
    ports:
      - "8000:8000"
    volumes:
      - ./data:/app/data

    environment:
      - TZ=Europe/Madrid
    healthcheck:
      test: ["CMD", "python", "-c", "import urllib.request; urllib.request.urlopen('http://localhost:8000/health')"]
      interval: 60s
      timeout: 3s
      retries: 3
EOF

docker compose up -d
```

### Opción 3: Docker run simple

```bash
mkdir -p ./notediscovery-data

docker run -d \
  --name notediscovery \
  --restart unless-stopped \
  -p 8000:8000 \
  -v ./notediscovery-data:/app/data \
  ghcr.io/gamosoft/notediscovery:latest
```

## 🖥️ Uso básico

1. Accede a `http://localhost:8000` en tu navegador
2. Verás el editor Markdown split-pane vacío
3. Haz clic en **"New Note"** para crear tu primera nota
4. Escribe el título y el contenido
5. El auto-guardado ocurre cada 5 segundos (visible en la UI)
6. ¡Listo! Tus notas se guardarán en `./data/`

### Primeros pasos

1. **Crear primera nota**
   - Haz clic en `"+ New Note"`
   - Nombre: `"Mi Primera Nota"`
   - Contenido: escribe Markdown (`# Título`, **negrita**, etc.)
   - La vista previa en vivo aparece a la derecha en tiempo real
   - Guardado automático

2. **Usar wikilinks (backlinks bidireccionales)**
   - En una nota, escribe: `[[Otra Nota]]`
   - Se crea automáticamente un enlace a esa nota
   - En la nota "Otra Nota", verás un backlink a la primera nota
   - La vista de grafo muestra la conexión visualmente

3. **Ver el grafo de conocimiento**
   - Menú → `"Graph View"`
   - Visualiza nodos como notas y enlaces como aristas
   - Haz clic en un nodo para navegar a esa nota
   - Hacer zoom, pan, interactivo

4. **Buscar notas (full-text instantáneo)**
   - Barra de búsqueda arriba (icono de lupa)
   - Escribe una palabra clave
   - Resultados instantáneos en título y contenido
   - Caché para velocidad

5. **Marcar favoritos**
   - Nota → click en el icono ⭐
   - Aparece en el panel "Favoritos"
   - Acceso rápido a notas importantes

6. **Usar LaTeX (ecuaciones matemáticas)**
   ```markdown
   $$E = mc^2$$
   ```
   Inline: `$E = mc^2$`
   - Funciona con MathJax
   - Se renderiza automáticamente en la vista previa

7. **Insertar diagramas Mermaid**
   ```markdown
   ```mermaid
   graph TD
     A[Inicio] --> B[Proceso]
     B --> C[Fin]
   ```
   ```

8. **Dibujar bocetos (dibujo en-app)**
   - Menú → `"+ New Drawing"`
   - Aparece el editor de dibujo (lápiz, líneas, formas, selector de color)
   - Se guarda automáticamente como PNG junto a la nota
   - Un enlace en Markdown permite incrustarlo

9. **Cambiar tema (Modo Claro/Oscuro)**
   - Configuración (icono de engranaje) → Tema
   - Elige Oscuro, Claro, o personalizado
   - La preferencia se guarda

10. **MCP para IA (Claude, Cursor)**
    - En la configuración de Claude Desktop (`~/.claude-desktop/claude_desktop_config.json`):
    ```json
    {
      "mcpServers": {
        "notediscovery": {
          "command": "docker",
          "args": [
            "run", "--rm", "-i",
            "-e", "NOTEDISCOVERY_URL=http://host.docker.internal:8000",
            "ghcr.io/gamosoft/notediscovery:latest",
            "python", "-m", "mcp_server"
          ]
        }
      }
    }
    ```
    - Reinicia Claude Desktop
    - Claude ahora puede leer tus notas, explorar el grafo, encontrar backlinks

11. **Cambiar idioma**
    - Configuración → Idioma
    - Elige español (u otro)
    - La interfaz cambia al instante

## 🧹 Mantenimiento

### Ver los logs

```bash
docker logs -f notediscovery
```

### Copia de seguridad de las notas (IMPORTANTE)

```bash
cp -r ./data ./data-backup-$(date +%Y%m%d-%H%M%S)
```

O usando Git dentro del directorio de datos:

```bash
cd ./data && git add . && git commit -m "Backup $(date)" && cd ..
```

### Restaurar desde una copia de seguridad

```bash
docker stop notediscovery
rm -rf ./data
cp -r ./data-backup-YYYYMMDD-HHMMSS ./data
docker start notediscovery
```

### Reiniciar el contenedor

```bash
docker compose restart
```

### Actualizar a la última versión

```bash
docker compose pull
docker compose up -d
```

### Monitorear el consumo (ultra-ligero)

```bash
docker stats notediscovery
```

### Explorar las notas (CLI)

```bash
ls -la ./data/

find ./data -name "*.md" | wc -l

grep -r "palabra-clave" ./data/
```

## 🔒 Seguridad

> ⚠️ **Importante**: Por defecto, NoteDiscovery **no tiene autenticación** (contraseña predeterminada: admin). **CAMBIA LA CONTRASEÑA** si lo expones a una red externa.

## 🎯 Casos de uso

- **Segundo cerebro (Zettelkasten)**: Sistema de notas interconectadas. Descubre patrones. Asimila conocimiento.
- **Investigadores/académicos**: Base de conocimiento de papers, artículos, ideas. Grafo de referencias.
- **Desarrolladores**: Wiki técnica personal. Documentación interna. Recetas, cheat sheets, tutoriales.
- **Equipos pequeños**: Wiki compartida. Control mediante Git. Sin dependencia de SaaS.
- **Privacidad primero**: Nunca tus notas salen de tu servidor. Cero telemetría. Cero rastreo.

## 🆚 Comparativa con alternativas

| Característica          | NoteDiscovery         | Obsidian Sync (SaaS)       | Notion                  | Roam Research (SaaS)      | Apple Notes / Google Keep |
|-------------------------|-----------------------|----------------------------|-------------------------|---------------------------|---------------------------|
| Costo                   | Gratis (open source)  | Pago (sincronización)      | Freemium                | Pago                      | Gratis (con cuenta)       |
| Auto-hospedado          | ✅ Sí                 | ❌ No                      | ❌ No                   | ❌ No                     | ❌ No                     |
| Formato de archivo      | Markdown plano        | Markdown (vault)           | Propietario             | Propietario               | Propietario               |
| Grafo de conocimiento   | ✅ Sí                 | ✅ Sí (con plugin)         | ❌ Limitado             | ✅ Sí (nucleo)            | ❌ No                     |
| Privacidad / control de datos | ✅ Total            | ❌ Depende del servicio    | ❌ Bajo                 | ❌ Bajo                   | ❌ Bajo (empresa)         |
| Personalización         | ✅ Alta (temas, plugins) | ✅ Alta (CSS, plugins)   | ❌ Limitada             | ✅ Media                  | ❌ Baja                   |
| Rendimiento             | ✅ Ultra-ligero       | ⚠️ Puede ser pesado        | ⚠️ Pesado               | ⚠️ Pesado                 | ✅ Ligero                 |

> **Nota**: La tabla anterior es una comparación general basada en características típicas.

## 👏 Créditos

- Este `docker-compose.yml` y `README.md` fueron generados a partir del tutorial del blog de Genbyte: [Cómo instalar NoteDiscovery en Docker](https://genbyte.blogspot.com/2026/07/como-instalar-notediscovery-en-docker.html)
- Desarrollado por la comunidad de NoteDiscovery
- Inspirado en la necesidad de una herramienta de notas privada y autohospedada

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

---

🚀 ¡Disfruta de tu base de conocimiento privada y autohospedada con NoteDiscovery!
