# TrabajoTeoriaDSD
## 🚀 Guía: Configuración de LaTeX en Ubuntu + VS Code

Esta guía detalla los pasos necesarios para compilar documentos con la clase `llncs`, manejar imágenes `.eps` y configurar **Visual Studio Code** como entorno de desarrollo.

### 1. Instalación del Motor LaTeX (Terminal)

Abre la terminal (`Ctrl + Alt + T`) y ejecuta el siguiente comando para instalar el núcleo de LaTeX, las fuentes europeas y las utilidades de conversión de imágenes:

```bash
sudo apt update && sudo apt install -y \
  texlive-latex-extra \
  texlive-fonts-recommended \
  texlive-font-utils \
  texlive-lang-spanish \
  cm-super

### 2. Instalación de pluggins VSCode
Instala desde VS Code los plugins:
- LaTeX
- LaTeX Workshop
