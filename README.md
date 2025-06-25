# 🌱 Sitio Web - ASOCIACIÓN DE MUJERES Y FAMILIAS CAMPESINAS CACAOTERAS DE GUADALUPE

Este repositorio contiene el sitio web oficial de la **Asociación de Mujeres y Familias Campesinas Cacaoteras de Guadalupe (AMFCCG)**, desarrollado con Jekyll y alojado en GitHub Pages.

## 🚀 Sitio Web

Visita nuestro sitio web: [https://[tu-usuario].github.io/[nombre-repositorio]](https://[tu-usuario].github.io/[nombre-repositorio])

## 📁 Estructura del Proyecto

```
.
├── index.md              # Página principal
├── _config.yml          # Configuración de Jekyll
├── docs/                # Documentos PDF
│   ├── README.md
│   └── [archivos-pdf]
├── README.md            # Este archivo
└── _layouts/            # (opcional) Layouts personalizados
```

## 🛠️ Tecnologías Utilizadas

- **Jekyll** - Generador de sitios estáticos
- **GitHub Pages** - Hosting gratuito
- **Markdown** - Formato de contenido
- **Tema Minima** - Tema limpio y responsivo

## 📋 Documentos Disponibles

El sitio proporciona acceso a los siguientes documentos oficiales:

### Documentos Fundacionales
- Acta de Constitución
- Estatutos Sociales

### Documentos Legales
- Personería Jurídica
- Certificado de Existencia
- RUT de la Asociación

### Documentos Administrativos
- Directorio Actual
- Plan Estratégico
- Memoria Anual

## 🔧 Configuración y Despliegue

### Prerrequisitos
- Cuenta de GitHub
- Repositorio público (para GitHub Pages gratuito)

### Pasos para activar GitHub Pages:

1. **Clonar/Fork este repositorio**
2. **Subir documentos PDF** a la carpeta `/docs/`
3. **Configurar GitHub Pages**:
   - Ve a Settings → Pages
   - Selecciona "Deploy from a branch"
   - Branch: `main`
   - Folder: `/ (root)`
4. **Personalizar configuración**:
   - Edita `_config.yml` con tu información
   - Actualiza la URL en `_config.yml`
5. **Commit y Push**

### Comandos Git:

```bash
# Clonar el repositorio
git clone https://github.com/[tu-usuario]/[nombre-repositorio].git
cd [nombre-repositorio]

# Agregar archivos
git add .
git commit -m "Configuración inicial del sitio web AMFCCG"
git push origin main
```

## ✏️ Personalización

### Actualizar información de contacto:
Edita `index.md` en la sección "Información de Contacto"

### Cambiar tema:
Modifica `theme` en `_config.yml`:
```yaml
# Opciones disponibles en GitHub Pages:
theme: minima           # (por defecto)
theme: minimal-mistakes
remote_theme: pages-themes/minimal@v0.2.0
```

### Agregar nuevos documentos:
1. Sube el PDF a `/docs/`
2. Agrega el enlace en `index.md`
3. Commit y push los cambios

## 📱 Características

- ✅ **Diseño responsivo** - Se adapta a móviles y tablets
- ✅ **SEO optimizado** - Meta tags y sitemap incluidos
- ✅ **Carga rápida** - Sitio estático optimizado
- ✅ **Accesible** - Cumple estándares de accesibilidad
- ✅ **SSL incluido** - Certificado HTTPS automático

## 🤝 Contribuciones

Para actualizar el sitio web:

1. Fork el repositorio
2. Crea una rama para tus cambios
3. Realiza los cambios necesarios
4. Crea un Pull Request

## 📞 Contacto

- **Organización**: ASOCIACIÓN DE MUJERES Y FAMILIAS CAMPESINAS CACAOTERAS DE GUADALUPE
- **Email**: [contacto@amfccg.org]
- **Sitio Web**: [URL del sitio]

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

---

*Desarrollado con ❤️ para la comunidad campesina cacaotera de Guadalupe*
