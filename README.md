# 🛡️ HYDRA FORENSIC LENS // Auditoría Local de Metadatos y Seguridad de Enlaces

Herramienta web de privacidad y ciberseguridad defensiva que se ejecuta **100% en el navegador del usuario** (sin subir archivos ni enviar URLs privadas a servidores externos).

## 🔍 Capacidades Principales
1. **Auditoría Forense de Archivos y EXIF:**
   - Cálculo instantáneo de firmas criptográficas **SHA-256** y **SHA-1** mediante Web Crypto API.
   - Lectura de cabecera binaria (*Magic Bytes*) para verificar el formato real del archivo.
   - Extracción de metadatos EXIF/XMP/GPS ocultos en fotografías con enlace directo a OpenStreetMap.
   - **Purgador de Metadatos:** Permite descargar una copia limpia de la imagen sin coordenadas GPS ni datos del dispositivo.
2. **Escáner de Seguridad de Enlaces y DNS:**
   - Detección de acortadores, IPs directas, dominios Punycode (`xn--`), credenciales ocultas y parámetros de rastreo (`utm_*`, `fbclid`, `gclid`).
   - Consulta DNS en tiempo real (**A, MX, SPF**) mediante **Cloudflare DNS-over-HTTPS** sin visitar la página sospechosa.

## ⚖️ Aviso de Privacidad y Uso Responsable
Todo el procesamiento de archivos ocurre localmente en la memoria de tu navegador. Ningún documento o fotografía abandona tu equipo.
