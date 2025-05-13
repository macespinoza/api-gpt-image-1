# 🧠 API GPT-Image-1 – Ejemplos Prácticos de Generación y Edición de Imágenes

Este repositorio muestra ejemplos funcionales y comentados para trabajar con la API de OpenAI usando el modelo `gpt-image-1`. Se cubren casos de uso para:

- ✅ Generación de imágenes desde cero a partir de texto
- ✅ Edición de imágenes sin necesidad de máscara
- ✅ Edición localizada usando máscaras (zonas transparentes)
- ✅ Composición visual con múltiples imágenes
- ✅ Creación de sprites o recursos visuales con fondo transparente

---

## 📦 Requisitos

- Python 3.8+
- `openai` ≥ 1.13.3
- API Key válida de OpenAI
- Librerías auxiliares: `Pillow`, `IPython`

Instalación rápida:

```bash
pip install openai pillow
```

---

## 🚀 ¿Qué contiene este repositorio?

### 📘 Notebooks

| Archivo | Descripción |
|--------|-------------|
| `api_gpt_image_1_ejemplos_edicion_generacion.ipynb` | ✅ Versión actualizada con ejemplos comentados y funcionales |
| `api-gpt-image-1.ipynb` | ⚠️ Versión anterior compartida públicamente (no actualizada) |

---

## ✅ Ejemplos incluidos en el notebook actualizado

| Nº | Ejemplo | Descripción |
|----|---------|-------------|
| 0 | Generación desde cero | Crea una imagen nueva a partir de un prompt |
| 1 | Edición sin máscara | Modifica toda una imagen según una nueva descripción |
| 2 | Edición con máscara | Modifica zonas específicas usando un PNG con transparencia |
| 3 | Composición visual | Usa múltiples imágenes como entrada + prompt |
| 4 | Generación transparente | Genera sprites con fondo transparente (ej. para videojuegos) |

---

## 📂 Archivos de imagen de entrada

- `playa.jpg` – Imagen de fondo base
- `perro.jpg`, `gato.jpg` – Elementos para composición
- `mascara.png` – Imagen de máscara para edición localizada
- `sprite_gatito.png` – Resultado generado como imagen transparente

---

## 📌 Notas importantes

- El modelo `gpt-image-1` **devuelve imágenes en base64**, que deben decodificarse para visualizar o guardar.
- Las máscaras deben ser:
  - PNG
  - del mismo tamaño que la imagen base
  - tener fondo transparente (alpha = 0) donde se desea modificar
- Para sprites o stickers se recomienda usar `background="transparent"` y formato `png`.

---

## 🌐 Recursos oficiales

- [📚 Documentación OpenAI – GPT-Image-1](https://platform.openai.com/docs/guides/images)
- [💻 SDK OpenAI Python](https://github.com/openai/openai-python)

---

## 🤝 Conecta conmigo

Gracias por revisar este repositorio.  
Si te interesa colaborar, aprender más o invitarme a dar una charla, puedes escribirme o seguirme en LinkedIn:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Miguel%20Cotrina-blue?logo=linkedin&style=flat-square)](https://www.linkedin.com/in/mcotrina/)

> IA & Data con propósito
