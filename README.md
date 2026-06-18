# Portafolio B2B Automático

Un portafolio web B2B diseñado para ser súper ligero, altamente profesional y sin fricciones de mantenimiento. En lugar de depender de grandes frameworks o constructores pesados, todo el sitio se genera estáticamente mediante un script de Python.

## Características Principales
- **Zero Config Maintenance:** Ejecutas el script y tu portafolio se construye al instante con tu información más reciente de GitHub.
- **Sincronización con GitHub:** El script `builder.py` consulta la API de GitHub para recuperar tus repositorios públicos, lenguajes de programación y "estrellas" y los inyecta dinámicamente como tarjetas de proyectos.
- **Soporte Multi-idioma:** Integrado de forma nativa con JavaScript ligero para alternar entre Español, Inglés y Portugués (ES / EN / PT) de forma instantánea.
- **SEO para Inteligencias Artificiales (AIO):** Contiene marcado semántico HTML5 y esquemas de datos estructurados (JSON-LD) para que rastreadores de IA (como ChatGPT, Gemini o Perplexity) entiendan perfectamente la información profesional del perfil.
- **Completamente Responsivo:** El diseño se adapta fluida y elegantemente desde pantallas ultra-anchas hasta los smartphones más pequeños, evitando el desbordamiento horizontal.
- **Estética Dark-Mode:** Un estilo pensado para transmitir profesionalismo tecnológico, combinando tonos oscuros con acentos vibrantes ("slime-blue").

## Cómo Usarlo

### 1. Requisitos
- Python 3.x
- Librería `requests` (`pip install requests`)

### 2. Generación del HTML
Simplemente corre el script en la raíz del proyecto:
```bash
python builder.py
```
Este comando generará o actualizará el archivo `index.html`.

### 3. Visualización y Despliegue
- Para verlo localmente: haz doble clic en `index.html` para abrirlo en cualquier navegador.
- Para publicarlo: haz un `git push` hacia la rama principal de tu repositorio configurado con **GitHub Pages**. Dado que el resultado es un HTML/CSS/JS estático puro, cargará al instante y de manera gratuita.

---
*Desarrollado y automatizado íntegramente en Python.*
