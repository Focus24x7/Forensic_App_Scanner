# Forensic_App_Scanner
Forensic App Scanner v5.0 – Total Índex HTML Scanner Forensic es una mini aplicación forense desarrollada en HTML + JavaScript puro, diseñada para ejecutarse directamente en un navegador moderno.

🕵️‍♂️ 
# Forensic App Scanner v5.0

📌 
# Descripción general
HTML Scanner Forensic es una mini aplicación forense desarrollada en HTML + JavaScript puro, diseñada para ejecutarse directamente en un navegador moderno.

Su objetivo es localizar, analizar, clasificar y documentar aplicaciones web basadas en archivos index.html o *.html dentro de unidades de almacenamiento locales (discos duros, particiones o dispositivos USB).

La herramienta está pensada para análisis forense digital, inventariado técnico, auditorías de software, OSINT y control de activos web locales, sin necesidad de servidores, instalaciones ni dependencias backend.
________________________________________

🎯
# Objetivo principal
•	Detectar aplicaciones web HTML reales, no solo archivos sueltos.
•	Extraer metadatos semánticos (título, etiquetas, descripciones implícitas).
•	Clasificar automáticamente cada aplicación por categoría funcional.
•	Generar un inventario estructurado y exportable (Excel / PDF).

________________________________________

⚙️
# Funcionamiento
1. Ejecución
•	Se abre el archivo HTML en un navegador compatible (Chrome, Edge).
•	No requiere instalación ni permisos de administrador.

2. Selección de origen
•	El usuario puede:
o	Seleccionar una carpeta específica
o	O iniciar el análisis desde el nivel donde se encuentra la app
•	Puede analizar:
o	Disco local (ej. C:\, D:\)
o	Carpetas raíz
o	Unidades externas (USB, discos forenses)

3. Escaneo recursivo
La aplicación realiza un escaneo recursivo en profundidad:
•	Nivel raíz
•	Carpetas del mismo nivel
•	Subcarpetas internas
•	Continúa hasta que no existen más directorios por analizar
________________________________________

🔍
# Análisis de archivos
Para cada archivo index.html o *.html detectado, la app:

1.	Lee el contenido completo del archivo

2.	Intenta identificar:
o	<title>
o	Metadatos
o	Etiquetas semánticas
o	Palabras clave funcionales

3.	Si no existen etiquetas claras:
o	Analiza todo el código HTML/JS/CSS embebido
o	Deduce la funcionalidad por patrones y keywords

4.	Consolida la información, aunque la app esté compuesta por:
o	HTML
o	JavaScript
o	CSS
o	JSON u otros recursos locales
________________________________________


🧠
# Clasificación automática
La aplicación incorpora un diccionario de categorías forenses y técnicas, entre ellas:

•	Forense
•	OSINT
•	Malware
•	Criptografía
•	Red / Networking
•	Desarrollo
•	Marketing
•	Administrativa
•	Email Tracing
•	IP Geolocator
•	Hash Analyzer
•	Port Scanner
•	Metadata Extractor
•	Social Analyzer
•	General / Otros
•	
Cada app detectada se clasifica según coincidencias semánticas y se le asignan #tags automáticos.

________________________________________
📊
# Resultados mostrados
La interfaz presenta:
•	Nombre del archivo / aplicación
•	Categoría principal detectada
•	Etiquetas (#tags)
•	Ruta completa en disco
•	Vista previa del código fuente (truncado por seguridad)
•	Estadísticas globales:
o	Total, de apps encontradas
o	Tamaño total analizado
o	Promedio por aplicación
o	Estado del sistema
________________________________________
📤
# Exportación de evidencias
✔ Exportar a Excel (XLSX)
•	Inventario profesional estructurado
•	Columnas:
o	Aplicación
o	Categoría
o	Etiquetas
o	Ruta en disco
o	Tamaño
•	Útil para:
o	Informes periciales
o	Auditorías
o	Entregables legales

✔ Exportar a PDF
•	Mediante impresión del navegador (Ctrl + P)
•	Ideal para:
o	Evidencia documental
o	Anexos de carpetas de investigación
________________________________________

🛠️
# Tecnologías utilizadas
•	HTML5
•	JavaScript (Vanilla)
•	File System Access API
•	ExcelJS
•	Bootstrap 5
•	CSS personalizado (UI forense / cyber)
________________________________________

🔐
# Consideraciones forenses
•	No modifica archivos analizados
•	Lectura en modo usuario
•	No requiere conexión a internet
•	No ejecuta código encontrado
•	El código fuente se muestra solo parcialmente por seguridad
________________________________________

📁
# Estructura
/HTML-Scanner-Forensic
│
├── forensic_app_scanner_v5.html
├── Inventario_CyberApps_V5_*.xlsx
└── README.md
________________________________________


👤
# Autor / Desarrollo
# Lic. Al Azua
# © Focus24x7		
# Powered by AI – 2026

🌐 https://www.abogadosforenses.org
________________________________________

⚠️ 
# Nota legal
## Esta herramienta está diseñada para uso legítimo, análisis propio, auditoría autorizada o investigación forense. La versión que se comparte anuncia la utilidad de la herramienta, pero se limita su accesibilidad y funciones por obvias razones.

# El uso sobre sistemas sin autorización expresa es responsabilidad exclusiva del usuario.

