NoteDiscovery: Base de conocimiento autohospedada en Docker (alternativa Obsidian Sync, Notion, Apple Notes)
    Gestor de notas Markdown con grafo de conocimiento, búsqueda full-text, backlinks bidireccionales. MCP para IA. Temas customizables. Dark mode. Offline-capable. FastAPI + Alpine.js. MIT open source.

    &#191;Qué es NoteDiscovery?

NoteDiscovery es una herramienta moderna de toma de notas self-hosted que permite construir tu propia base de conocimiento con Markdown puro, sin dependencia de servicios cloud ni vendor lock-in. Es la alternativa open source a Obsidian Sync, Notion, Roam Research, diseñada para máxima privacidad y propiedad de datos.

      Propuesta clave: Tus notas viven como archivos .md plain text en una carpeta que controlas. Puedes usar git, grep, cualquier tool sobre ellas. Editor split-pane (Markdown + preview en vivo). Grafo de conocimiento dinámico (visualiza conexiones entre notas). Búsqueda instant full-text. Backlinks bidireccionales (wikilinks). Dark mode. MCP integration para IA (Claude, Cursor). Zero database, cero complejidad. Corre en 50MB RAM. Docker one-liner setup.

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

      Docker &amp; Docker Compose
      50-100 MB RAM mínimo (ultra-ligero)
      500 MB - 5 GB espacio disco (depende volumen notas)
      Puerto 8000 o custom (configurable)
      Navegador moderno: Chrome, Firefox, Safari, Edge
      Python 3.10+ (si ejecutas sin Docker)

      Setup ultra-rápido: Docker one-liner. 60 segundos a funcionar.

    Instalación con Docker Compose

    Opción 1: Docker Compose (recomendado)
    mkdir -p notediscovery/data &amp;&amp; cd notediscovery

curl -O https://raw.githubusercontent.com/gamosoft/NoteDiscovery/main/docker-compose.ghcr.yml

docker compose -f docker-compose.ghcr.yml up -d

    Opción 2: Docker Compose custom
    cat &gt; docker-compose.yml &lt;&lt; 'EOF'
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
      # Opcional: customiza temas, plugins, idiomas
      # - ./themes:/app/themes
      # - ./locales:/app/locales
    environment:
      - TZ=Europe/Madrid
    healthcheck:
      test: ["CMD", "python", "-c", "import urllib.request; urllib.request.urlopen('http://localhost:8000/health')"]
      interval: 60s
      timeout: 3s
      retries: 3
EOF

docker compose up -d

    Opción 3: Docker run simple
    mkdir -p ./notediscovery-data

docker run -d \
  --name notediscovery \
  --restart unless-stopped \
  -p 8000:8000 \
  -v ./notediscovery-data:/app/data \
  ghcr.io/gamosoft/notediscovery:latest

    Acceder (setup inicial)
    http://localhost:8000 - Dashboard NoteDiscovery

    Primer uso

      Abre http://localhost:8000
      Verás editor Markdown split-pane limpio
      Click "New Note" para crear primera nota
      Escribe título y contenido
      Auto-save cada 5 segundos (visto en UI)
      &#161;Listo! Notas guardadas en ./data/

    Primeros pasos

    1. Crear primera nota

      Click "+ New Note"
      Nombre: "Mi Primera Nota"
      Contenido: escribe Markdown (# Título, **bold**, etc)
      Live preview aparece a la derecha en tiempo real
      Auto-saved

    2. Usar wikilinks (backlinks bidireccionales)

      En nota, escribe: [[Otra Nota]]
      Se crea automático link a esa nota
      En "Otra Nota", verás backlink a primera nota
      Graph view muestra conexión visualmente

    3. Ver grafo de conocimiento

      Menú &#8594; "Graph View"
      Visualiza notas como nodos, links como aristas
      Click nodo para navegar a nota
      Zoom, pan, interactivo

    4. Buscar notas (instant full-text)

      Search bar arriba (lupa icon)
      Escribe palabra clave
      Resultados instant en ambos: titulo + contenido
      Cached para velocidad

    5. Star favoritos

      Nota &#8594; click &#11088; icon
      Aparece en "Favoritos" panel
      Acceso rápido a notas importantes

    6. Usar LaTeX (ecuaciones matemáticas)
    $$E = mc^2$$

Inline: $E = mc^2$

      Powered by MathJax
      Renderiza automático en preview

    7. Insertar Mermaid diagrams
    ```mermaid
graph TD
  A[Start] --&gt; B[Process]
  B --&gt; C[End]
```

    8. Dibujar sketches (in-app drawing)

      Menu &#8594; "+ New Drawing"
      Editor de dibujo aparece (pencil, lines, shapes, color picker)
      Autosave como PNG next to nota
      Link en Markdown para embed

    9. Cambiar tema (Dark/Light mode)

      Settings (engranaje icon) &#8594; Theme
      Elige Dark, Light, o custom
      Preferencia guardada

    10. MCP para IA (Claude, Cursor)

      En Claude Desktop config (~/.claude-desktop/claude_desktop_config.json):

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

      Reinicia Claude Desktop
      Claude ahora puede leer tus notas, explorar grafo, encontrar backlinks

    11. Cambiar idioma

      Settings &#8594; Language
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

# O con git (repo tu data folder)
cd ./data &amp;&amp; git add . &amp;&amp; git commit -m "Backup $(date)" &amp;&amp; cd ..

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

# Típicamente: 

    Explorar notas (CLI)
    ls -la ./data/

# Ver todas las notas .md
find ./data -name "*.md" | wc -l

# Grep en todas tus notas
grep -r "palabra-clave" ./data/

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

    Referencias oficiales

      GitHub Repository - gamosoft/NoteDiscovery
      Official Website - notediscovery.com
      Docker Hub - gamosoft/notediscovery
      Live Demo
      Features Documentation
      MCP Integration Guide

    Apoya el canal GENBYTE
    Suscríbete al canal de YouTube
    Suscríbete a la newsletter semanal
    Invítame a un Ko-fi
    genbyte@proton.me

    Sígueme en mis redes sociales

      Telegram
      Discord
      YouTube
      GitHub
      Blog
      Twitter

Obtener enlace

Facebook

X

Pinterest

Correo electrónico

Otras aplicaciones

Comentarios

Publicar un comentario

      BLOG_CMT_createIframe('https://www.blogger.com/rpc_relay.html');

   (adsbygoogle = window.adsbygoogle || []).push({});

    .post-body a.b-tooltip-container {
      position: relative;
      display: inline-block;
    }

    .post-body a.b-tooltip-container .b-tooltip {
      display: block !important;
      position: absolute;
      top: 100%;
      left: 50%;
      transform: translate(-20%, 1px);
      visibility: hidden;
      opacity: 0;
      z-index: 1;
      transition: opacity 0.2s ease-in-out;
    }

    .post-body a.b-tooltip-container .b-tooltip iframe {
      width: 200px;
      height: 198px;
      max-width: none;
      border: none;
      border-radius: 20px;
      box-shadow: 1px 1px 3px 1px rgba(0, 0, 0, 0.2);
    }

    @media (hover: hover) {
      .post-body a.b-tooltip-container:hover .b-tooltip {
        visibility: visible;
        opacity: 1;
      }
    }

Entradas populares de este blog

Cómo Instalar y configurar SERVIDOR VPN WIREGUARD en MIKROTIK 🔐 #VPN #Wireguard #Mikrotik #RouterOS

Wireguard en Mikrotik Breve Explicación de Wireguard &#191;Qué es WireGuard VPN? WireGuard es un nuevo protocolo de VPN. No se trata de un software, sino de un conjunto de instrucciones que permite crear VPNs de forma muy sencilla. Ha sido desarrollada como una alternativa a IPsec, OpenVPN y similares VPNs, pero más rápida y sencilla de usar. En esencia, WireGuard está basado en ideas del protocolo IPsec. WireGuard es una VPN extremadamente simple, pero rápida y moderna que utiliza criptografía de última generación. Su objetivo es ser más rápido, más simple, y más versátil que IPSec, evitando al mismo tiempo el enorme dolor de cabeza (sobre todo en redes con NAT). Pretende ser considerablemente más eficaz que OpenVPN. WireGuard está diseñado como una VPN de propósito general para ejecutarse en interfaces embebidas, apto para muchas circunstancias diferentes. Se ejecuta sobre el protocolo UDP, por lo tanto es considerado un túnel de capa 3. &#191;Cómo funciona Wireguard VPN? WireGuard es un proto...

Read more &#187;

Cómo instalar y configurar DSM SYNOLOGY 7.2.2 en PC | Guía completa, instalación, RAID 1, SMB

Instalación y puesta en marcha de Synology DSM 7.2.2 en PC Vídeo ACTUALIZADO, NUEVA VERSIÓN DEL ARC LOADER:&#160; https://youtu.be/LgghogL-UCA https://genbyte.blogspot.com/2025/08/como-convertir-pc-en-synlogy-con-6-tb.html ----- Proceso de instalación y puesta en marcha de sistema operativo DSM Synology versión 7.2.2 en un PC, concretamente un HP 800 G1 EliteDesk. El PC tendrá 3 discos SSD, uno de 120 GB para el S.O. DSM, y otros dos de 240GB cada en RAID 1 para los Datos. Los 3 dicos duros conectados al PC mediante cables SATA. Lo primero que necesitamos es descargar la imagen bootloader ARC, desde el siguiente repositorio de Gothub, también necesitamos Rufus, en este momento, es la versión 4.6. Imagen ARC:&#160; https://github.com/AuxXxilium/arc Imagen usado en el vídeo 1.1.29:&#160; https://github.com/AuxXxilium/arc/releases/tag/1.1.29 Rufus:&#160; https://rufus.ie/es/ Después de descargar la imagen ARC.img, conectamos nuestro primer disco SSD de 120GB por cable o conector SATA-USB y...

Read more &#187;

Cómo INSTALAR y CONFIGURAR OpenVPN en MIKROTIK. Guía completa paso a paso.

Cómo INSTALAR y CONFIGURAR OpenVPN en MIKROTIK. Guía completa paso a paso. Vídeo tutorial paso a paso en Youtube Desarrollo Ilustración: Diagrama RED Creación de Redes (Address) ----------------------------------------------- WAN 192.168.1.0/24 LAN 192.168.88.0/24 VPN 192.168.100.0/24 Creación del Rango VPN ------------------------ 192.168.100.1 - 192.168.100.100 Creación de los Certificados ------------------------------- Los certificados que vamos a crear a continuación tendrán una validez de 10 años; days-valid=3650 Crear certificado CA ---------------------- /certificate add name=CA-tpl country=&quot;&quot; state=&quot;&quot; locality=&quot;&quot; organization=&quot;&quot; unit=&quot;&quot; common-name=&quot;CA&quot; key-size=4096 days-valid=3650 key-usage=crl-sign,key-cert-sign /certificate sign CA-tpl ca-crl-host=127.0.0.1 name=&quot;CA&quot; Crear certificado Server -------------------------- /certificate add name=SERVER-tpl country=&quot;&quot; state=&quot;&quot; locality=...

Read more &#187;

Con la tecnología de Blogger

Genbyte &#169; 2026 | Blogger Google

Aprende casi todo sobre Linux:

Libro Administración de Linux: de 0 a 100

    🚀 La newsletter de Genbyte

    Recibe contenido sobre tecnología, automatizaciones, IA y tendencias digitales directamente en tu bandeja de entrada.

  Suscribirme gratis

Invítame a un Ko-fi

kofiwidget2.init('Support Me on Ko-fi', '#29abe0', 'W7W79Z4P');kofiwidget2.draw();

Mis Links

.lp-social-container {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  justify-content: center;
  margin: 15px 0;
}

.lp-social-pill {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  padding: 10px 16px;
  border-radius: 999px;
  text-decoration: none;
  font-family: system-ui, sans-serif;
  font-size: 14px;
  font-weight: 500;
  color: #fff;
  transition: all 0.25s ease;
}

/* 🎨 Colores optimizados */
.lp-social-pill:nth-child(1) { background: #229ED9; }   /* Telegram */
.lp-social-pill:nth-child(2) { background: #5865F2; }   /* Discord */
.lp-social-pill:nth-child(3) { background: #FF0033; color:#ffffff; }   /* YouTube */
.lp-social-pill:nth-child(4) { background: #24292F; }   /* GitHub */
.lp-social-pill:nth-child(5) { background: #34A853; color:#ffffff; }   /* Blog */
.lp-social-pill:nth-child(6) { background: #1D9BF0; }   /* Twitter */

/* &#10024; Hover moderno */
.lp-social-pill:hover {
  transform: translateY(-3px) scale(1.03);
  box-shadow: 0 6px 14px rgba(0,0,0,0.25);
  filter: brightness(1.05);
}

    &#9993; Telegram

    💬 Discord

    📽 YouTube

    💻 GitHub

    📄 Blog

    🐦 Twitter

Archivo

julio 20268

junio 202626

mayo 202672

abril 202618

marzo 20267

febrero 20264

enero 20265

diciembre 202516

noviembre 20256

octubre 202510

septiembre 20257

agosto 20256

julio 20252

diciembre 20247

noviembre 20245

octubre 20245

septiembre 20249

agosto 20242

julio 20246

junio 20243

mayo 20243

abril 20245

marzo 20241

febrero 202413

enero 202411

diciembre 20234

agosto 20232

julio 20231

mayo 20232

abril 20234

marzo 20235

febrero 20233

enero 20238

diciembre 20224

agosto 20221

mayo 202211

febrero 20222

enero 20221

agosto 20211

julio 20211

junio 20211

mayo 20211

enero 20213

noviembre 20203

octubre 20201

septiembre 20201

agosto 20202

julio 20202

junio 20202

mayo 20203

abril 20202

marzo 20202

febrero 20202

noviembre 20192

octubre 20193

septiembre 20192

noviembre 20182

octubre 20185

enero 20182

mayo 20171

enero 20172

diciembre 20162

agosto 20161

diciembre 20153

noviembre 20156

octubre 20152

septiembre 20151

enero 20152

diciembre 20141

septiembre 20141

agosto 20142

mayo 20142

marzo 20141

febrero 20141

diciembre 20131

noviembre 20133

octubre 20135

Mostrar más
Mostrar menos

Etiquetas

#AppFest2012
#Bilal #Joomla #CMS #Página #Personal #Blog #Analytics #Google
#CPD
#NAS #SAN #Backup #Backup4all #duplicity #Linux #WindowsServer
#RaspberrPi
#SAI
#Seguridad
#SuperComupter
0x80070643
2fa

acceso red
actualizacion coronavirus
actualización windows
adinistracion
alix
almacenamiento
amazon
amd
android
Antivirus
app web
apps
apu
Arabic
archivos
arranque
autenticación
autenticación segura
backup
backup sd
balanceo
Blogger
bloquea ads
boards
borrar
bot
cam
casos
cctv
certbot
certificado digital
certifidado
Chema Alonso
chrome
ciberdilencuente
cifs
clean
clonezilla
cloudflare
Cloudflare WARP
cmd
cola
comand
comandos
comaprtir
conexion
contagios
container
contenedores
copia
copias seguridad
coronavirus
covid
datos
dd
debian
desintalar docker
desktop
dhcp
diseño
disk
diskpart
disney
Diun
dns
doble factor
docker
docker compose
Dockhand
domain
dominio seguro
Dozzel
elimina
English
equipo
error
error windows
escritorio
escritorio remoto
españa
espia
esxi
exportar
ext
extension
facebook
fallecidos
firewall
format
fotos
French
ghost
gmail
google
grabar pantalla
gratis
Hacker
hamachi
HBO
homelab
http://youtu.be/yRGn63y7bP4
https
IFTTT
impresión
imprimir
Instagram
instalar
inventario
inventory
iptv
iptv legal
iso
Jackett
Joomla
KB5034441
lan
letscrypt
lineageos
Linux
local
mac
malware
maquinasvirtuales
microfono
mikrotik
monitoreo
monitorizar
motioneye
móviles
Multilanguage
multiplataforna.
multisesion
multiusuario
nas
net
netflix
netuse
ng
nmap
no exportable
ntfs
nube
ocs
oidc
onedrive
openmediavault
opensource
openvpn
owncloud
p2p
pantallazo
partition
passkeys
password
pendrive
pfsense
pfsesne
phishing
pi
pihole
plex
pocket id
port
portainer
portal cautivo
prescindir windows
prime
privada
Prowlarr
Proxy
prunemate
Radarr
raid
rakuten
RaspberrPi
raspberry
raspberry pi
raspbian
raspeberry
rdp
reagentc /enable
recuperados
red
remota
robocpy
root
rpi
rpimonitor
screenrecord
sd
security
Seguridad
Seguridad Informática
server
servidor casero
servidor dns
share
sistema
sistema operativo
sistemas
smarttv
smb
smtp
so
Sonarr
Spanish
ssh
ssl
storage
superuser
system
tailscale
tdt
telegram
terminal
tls
torrents
Truecrypt
tv
tv box
tv gratis
tv legal
typosquatting
ubuntu
update
usb
usb booteable
use
user
usuario
usuarios
vbox
vigilancia
vincular
virus
vlan
vmware
vpn
vpn segura
wan
web
webcam
windows
windows 10
Windows7
wordpress
xiaomi

Mostrar más
Mostrar menos

Denunciar abuso

    document.addEventListener('DOMContentLoaded', function(event) {
      window.cookieChoices && cookieChoices.showCookieConsentBar && cookieChoices.showCookieConsentBar(
          (window.cookieOptions && cookieOptions.msg) || 'Este sitio utiliza cookies de Google para prestar sus servicios y para analizar su tr\xe1fico. Tu direcci\xf3n IP y user-agent se comparten con Google, junto con las m\xe9tricas de rendimiento y de seguridad, para garantizar la calidad del servicio, generar estad\xedsticas de uso y detectar y solucionar abusos.',
          (window.cookieOptions && cookieOptions.close) || 'Entendido',
          (window.cookieOptions && cookieOptions.learn) || 'M\xe1s informaci\xf3n',
          (window.cookieOptions && cookieOptions.link) || 'https://www.blogger.com/go/blogspot-cookies');
    });

window['__wavt'] = 'AEUoTZqGnLwAnT8lq7Efygzq_IlR:1783519417575';_WidgetManager._Init('//www.blogger.com/rearrange?blogID\x3d8219365441889466865','//genbyte.blogspot.com/2026/07/como-instalar-notediscovery-en-docker.html','8219365441889466865');
_WidgetManager._SetDataContext([{'name': 'blog', 'data': {'blogId': '8219365441889466865', 'title': 'Genbyte', 'url': 'https://genbyte.blogspot.com/2026/07/como-instalar-notediscovery-en-docker.html', 'canonicalUrl': 'https://genbyte.blogspot.com/2026/07/como-instalar-notediscovery-en-docker.html', 'homepageUrl': 'https://genbyte.blogspot.com/', 'searchUrl': 'https://genbyte.blogspot.com/search', 'canonicalHomepageUrl': 'https://genbyte.blogspot.com/', 'blogspotFaviconUrl': 'https://genbyte.blogspot.com/favicon.ico', 'bloggerUrl': 'https://www.blogger.com', 'hasCustomDomain': false, 'httpsEnabled': true, 'enabledCommentProfileImages': true, 'gPlusViewType': 'FILTERED_POSTMOD', 'adultContent': false, 'analyticsAccountNumber': '', 'encoding': 'UTF-8', 'locale': 'es', 'localeUnderscoreDelimited': 'es', 'languageDirection': 'ltr', 'isPrivate': false, 'isMobile': false, 'isMobileRequest': false, 'mobileClass': '', 'isPrivateBlog': false, 'isDynamicViewsAvailable': true, 'feedLinks': '\x3clink rel\x3d\x22alternate\x22 type\x3d\x22application/atom+xml\x22 title\x3d\x22Genbyte - Atom\x22 href\x3d\x22https://genbyte.blogspot.com/feeds/posts/default\x22 /\x3e\n\x3clink rel\x3d\x22alternate\x22 type\x3d\x22application/rss+xml\x22 title\x3d\x22Genbyte - RSS\x22 href\x3d\x22https://genbyte.blogspot.com/feeds/posts/default?alt\x3drss\x22 /\x3e\n\x3clink rel\x3d\x22service.post\x22 type\x3d\x22application/atom+xml\x22 title\x3d\x22Genbyte - Atom\x22 href\x3d\x22https://www.blogger.com/feeds/8219365441889466865/posts/default\x22 /\x3e\n\n\x3clink rel\x3d\x22alternate\x22 type\x3d\x22application/atom+xml\x22 title\x3d\x22Genbyte - Atom\x22 href\x3d\x22https://genbyte.blogspot.com/feeds/5369295723767392150/comments/default\x22 /\x3e\n', 'meTag': '', 'adsenseClientId': 'ca-pub-5584594928588539', 'adsenseHostId': 'ca-host-pub-1556223355139109', 'adsenseHasAds': true, 'adsenseAutoAds': true, 'boqCommentIframeForm': true, 'loginRedirectParam': '', 'isGoogleEverywhereLinkTooltipEnabled': true, 'view': '', 'dynamicViewsCommentsSrc': '//www.blogblog.com/dynamicviews/4224c15c4e7c9321/js/comments.js', 'dynamicViewsScriptSrc': '//www.blogblog.com/dynamicviews/a8c62dcffd0094e0', 'plusOneApiSrc': 'https://apis.google.com/js/platform.js', 'disableGComments': true, 'interstitialAccepted': false, 'sharing': {'platforms': [{'name': 'Obtener enlace', 'key': 'link', 'shareMessage': 'Obtener enlace', 'target': ''}, {'name': 'Facebook', 'key': 'facebook', 'shareMessage': 'Compartir en Facebook', 'target': 'facebook'}, {'name': 'Escribe un blog', 'key': 'blogThis', 'shareMessage': 'Escribe un blog', 'target': 'blog'}, {'name': 'X', 'key': 'twitter', 'shareMessage': 'Compartir en X', 'target': 'twitter'}, {'name': 'Pinterest', 'key': 'pinterest', 'shareMessage': 'Compartir en Pinterest', 'target': 'pinterest'}, {'name': 'Correo electr\xf3nico', 'key': 'email', 'shareMessage': 'Correo electr\xf3nico', 'target': 'email'}], 'disableGooglePlus': true, 'googlePlusShareButtonWidth': 0, 'googlePlusBootstrap': '\x3cscript type\x3d\x22text/javascript\x22\x3ewindow.___gcfg \x3d {\x27lang\x27: \x27es\x27};\x3c/script\x3e'}, 'hasCustomJumpLinkMessage': true, 'jumpLinkMessage': 'Read more \xbb', 'pageType': 'item', 'postId': '5369295723767392150', 'postImageThumbnailUrl': 'https://blogger.googleusercontent.com/img/a/AVvXsEhbPGv8wgBFqzoNHIseXbVQ4I-2eHUlCCRYJcGhhEHNC-b3O51a-fKenAjngZ1LV1YbAbw0aJyTLIKZhmX8AJQCqvV6a_Qzi-l0OrTZr2Pr8SkOD6O034-WJCbotpAJPaVT0h2f1kSu6julIJHqR5eZqUiLPM0rO0SSZnCosqL-O0oWy4zGZHOTyFNOjjU\x3ds72-c', 'postImageUrl': 'https://blogger.googleusercontent.com/img/a/AVvXsEhbPGv8wgBFqzoNHIseXbVQ4I-2eHUlCCRYJcGhhEHNC-b3O51a-fKenAjngZ1LV1YbAbw0aJyTLIKZhmX8AJQCqvV6a_Qzi-l0OrTZr2Pr8SkOD6O034-WJCbotpAJPaVT0h2f1kSu6julIJHqR5eZqUiLPM0rO0SSZnCosqL-O0oWy4zGZHOTyFNOjjU', 'pageName': 'C\xf3mo instalar NoteDiscovery en Docker - Base de conocimiento autohospedada en Docker', 'pageTitle': 'Genbyte: C\xf3mo instalar NoteDiscovery en Docker - Base de conocimiento autohospedada en Docker'}}, {'name': 'features', 'data': {}}, {'name': 'messages', 'data': {'edit': 'Editar', 'linkCopiedToClipboard': 'El enlace se ha copiado en el Portapapeles.', 'ok': 'Aceptar', 'postLink': 'Enlace de la entrada'}}, {'name': 'template', 'data': {'name': 'custom', 'localizedName': 'Personalizado', 'isResponsive': true, 'isAlternateRendering': false, 'isCustom': true}}, {'name': 'view', 'data': {'classic': {'name': 'classic', 'url': '?view\x3dclassic'}, 'flipcard': {'name': 'flipcard', 'url': '?view\x3dflipcard'}, 'magazine': {'name': 'magazine', 'url': '?view\x3dmagazine'}, 'mosaic': {'name': 'mosaic', 'url': '?view\x3dmosaic'}, 'sidebar': {'name': 'sidebar', 'url': '?view\x3dsidebar'}, 'snapshot': {'name': 'snapshot', 'url': '?view\x3dsnapshot'}, 'timeslide': {'name': 'timeslide', 'url': '?view\x3dtimeslide'}, 'isMobile': false, 'title': 'C\xf3mo instalar NoteDiscovery en Docker - Base de conocimiento autohospedada en Docker', 'description': '              NoteDiscovery | Knowledge Base | Docker      NoteDiscovery: Base de conocimiento autohospedada en Docker (alternativa Obsidian...', 'featuredImage': 'https://blogger.googleusercontent.com/img/a/AVvXsEhbPGv8wgBFqzoNHIseXbVQ4I-2eHUlCCRYJcGhhEHNC-b3O51a-fKenAjngZ1LV1YbAbw0aJyTLIKZhmX8AJQCqvV6a_Qzi-l0OrTZr2Pr8SkOD6O034-WJCbotpAJPaVT0h2f1kSu6julIJHqR5eZqUiLPM0rO0SSZnCosqL-O0oWy4zGZHOTyFNOjjU', 'url': 'https://genbyte.blogspot.com/2026/07/como-instalar-notediscovery-en-docker.html', 'type': 'item', 'isSingleItem': true, 'isMultipleItems': false, 'isError': false, 'isPage': false, 'isPost': true, 'isHomepage': false, 'isArchive': false, 'isLabelSearch': false, 'postId': 5369295723767392150}}, {'name': 'widgets', 'data': [{'title': 'Buscar este blog', 'type': 'BlogSearch', 'sectionId': 'search_top', 'id': 'BlogSearch1'}, {'title': 'Genbyte (cabecera)', 'type': 'Header', 'sectionId': 'header', 'id': 'Header1'}, {'title': '', 'type': 'PageList', 'sectionId': 'page_list_top', 'id': 'PageList1'}, {'type': 'AdSense', 'sectionId': 'ads', 'id': 'AdSense1'}, {'type': 'AdSense', 'sectionId': 'ads', 'id': 'AdSense2'}, {'title': 'Entradas del blog', 'type': 'Blog', 'sectionId': 'page_body', 'id': 'Blog1', 'posts': [{'id': '5369295723767392150', 'title': 'C\xf3mo instalar NoteDiscovery en Docker - Base de conocimiento autohospedada en Docker', 'featuredImage': 'https://blogger.googleusercontent.com/img/a/AVvXsEhbPGv8wgBFqzoNHIseXbVQ4I-2eHUlCCRYJcGhhEHNC-b3O51a-fKenAjngZ1LV1YbAbw0aJyTLIKZhmX8AJQCqvV6a_Qzi-l0OrTZr2Pr8SkOD6O034-WJCbotpAJPaVT0h2f1kSu6julIJHqR5eZqUiLPM0rO0SSZnCosqL-O0oWy4zGZHOTyFNOjjU', 'showInlineAds': true}], 'headerByline': {'regionName': 'header1', 'items': [{'name': 'share', 'label': ''}]}, 'footerBylines': [{'regionName': 'footer1', 'items': [{'name': 'comments', 'label': 'comments'}, {'name': 'icons', 'label': ''}]}, {'regionName': 'footer2', 'items': [{'name': 'labels', 'label': ''}]}, {'regionName': 'footer3', 'items': [{'name': 'location', 'label': 'Location:'}]}], 'allBylineItems': [{'name': 'share', 'label': ''}, {'name': 'comments', 'label': 'comments'}, {'name': 'icons', 'label': ''}, {'name': 'labels', 'label': ''}, {'name': 'location', 'label': 'Location:'}]}, {'title': '', 'type': 'PopularPosts', 'sectionId': 'page_body', 'id': 'PopularPosts1', 'posts': [{'title': 'C\xf3mo Instalar y configurar SERVIDOR VPN WIREGUARD en MIKROTIK \ud83d\udd10 #VPN #Wireguard #Mikrotik #RouterOS', 'id': 7806756629556397861}, {'title': 'C\xf3mo instalar y configurar DSM SYNOLOGY 7.2.2 en PC | Gu\xeda completa, instalaci\xf3n, RAID 1, SMB', 'id': 6323457506488490841}, {'title': 'C\xf3mo INSTALAR y CONFIGURAR OpenVPN en MIKROTIK. Gu\xeda completa paso a paso.', 'id': 3276948939221682320}]}, {'type': 'Attribution', 'sectionId': 'footer', 'id': 'Attribution1'}, {'title': 'Aprende casi todo sobre Linux:', 'type': 'HTML', 'sectionId': 'sidebar_bottom', 'id': 'HTML4'}, {'title': '', 'type': 'HTML', 'sectionId': 'sidebar_bottom', 'id': 'HTML3'}, {'title': 'Inv\xedtame a un Ko-fi', 'type': 'HTML', 'sectionId': 'sidebar_bottom', 'id': 'HTML1'}, {'title': 'Mis Links', 'type': 'HTML', 'sectionId': 'sidebar_bottom', 'id': 'HTML2'}, {'title': '', 'type': 'BlogArchive', 'sectionId': 'sidebar_bottom', 'id': 'BlogArchive1'}, {'title': 'Etiquetas', 'type': 'Label', 'sectionId': 'sidebar_bottom', 'id': 'Label1'}, {'title': '', 'type': 'ReportAbuse', 'sectionId': 'sidebar_bottom', 'id': 'ReportAbuse1'}]}]);
_WidgetManager._RegisterWidget('_BlogSearchView', new _WidgetInfo('BlogSearch1', 'search_top', document.getElementById('BlogSearch1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_HeaderView', new _WidgetInfo('Header1', 'header', document.getElementById('Header1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_PageListView', new _WidgetInfo('PageList1', 'page_list_top', document.getElementById('PageList1'), {'title': '', 'links': [{'isCurrentPage': false, 'href': 'http://genbyte.blogspot.com/', 'title': 'Inicio'}, {'isCurrentPage': false, 'href': 'https://www.youtube.com/@genbyte', 'title': 'Mi canal Youtube'}, {'isCurrentPage': false, 'href': 'https://genbyte.blogspot.com/p/newsletter.html', 'id': '2370245159635941192', 'title': 'Newsletter'}], 'mobile': false, 'showPlaceholder': true, 'hasCurrentPage': false}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_AdSenseView', new _WidgetInfo('AdSense1', 'ads', document.getElementById('AdSense1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_AdSenseView', new _WidgetInfo('AdSense2', 'ads', document.getElementById('AdSense2'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_BlogView', new _WidgetInfo('Blog1', 'page_body', document.getElementById('Blog1'), {'cmtInteractionsEnabled': false, 'lightboxEnabled': true, 'lightboxModuleUrl': 'https://www.blogger.com/static/v1/jsbin/3745941268-lbx__es.js', 'lightboxCssUrl': 'https://www.blogger.com/static/v1/v-css/828616780-lightbox_bundle.css'}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_PopularPostsView', new _WidgetInfo('PopularPosts1', 'page_body', document.getElementById('PopularPosts1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_AttributionView', new _WidgetInfo('Attribution1', 'footer', document.getElementById('Attribution1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_HTMLView', new _WidgetInfo('HTML4', 'sidebar_bottom', document.getElementById('HTML4'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_HTMLView', new _WidgetInfo('HTML3', 'sidebar_bottom', document.getElementById('HTML3'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_HTMLView', new _WidgetInfo('HTML1', 'sidebar_bottom', document.getElementById('HTML1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_HTMLView', new _WidgetInfo('HTML2', 'sidebar_bottom', document.getElementById('HTML2'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_BlogArchiveView', new _WidgetInfo('BlogArchive1', 'sidebar_bottom', document.getElementById('BlogArchive1'), {'languageDirection': 'ltr', 'loadingMessage': 'Cargando\x26hellip;'}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_LabelView', new _WidgetInfo('Label1', 'sidebar_bottom', document.getElementById('Label1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_ReportAbuseView', new _WidgetInfo('ReportAbuse1', 'sidebar_bottom', document.getElementById('ReportAbuse1'), {}, 'displayModeFull'));