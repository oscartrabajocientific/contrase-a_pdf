# 🔐 PDF Password Protector

Este repositorio contiene un script en Python que permite proteger con contraseña todos los archivos PDF ubicados en una carpeta específica. Es ideal para tareas de automatización documental como la generación y envío de certificados, informes u otros documentos sensibles.

## 🚀 Características

- 🔒 Establece una contraseña para abrir cada archivo PDF (misma contraseña para todos).
- 📁 Funciona en lotes: protege todos los PDF en una carpeta.
- 🛠️ Opción segura usando archivos temporales (comentada en el código).
- 📢 Mensajes informativos para seguimiento del proceso.

## 📂 Estructura esperada

Coloca todos tus archivos `.pdf` en una carpeta definida por la variable `pdf_folder`, por ejemplo:


## 🧰 Requisitos

- Python 3.x  
- Biblioteca `pikepdf`  
- Google Drive montado (si se usa en Google Colab)

### Instalación de dependencias

```bash
pip install pikepdf

git clone https://github.com/tu-usuario/pdf-password-protector.git

python proteger_pdfs.py
