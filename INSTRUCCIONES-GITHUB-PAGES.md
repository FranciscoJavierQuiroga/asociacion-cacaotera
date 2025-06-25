# 🚀 Instrucciones para Activar GitHub Pages

Esta guía te ayudará a activar GitHub Pages para el sitio web de la **Asociación de Mujeres y Familias Campesinas Cacaoteras de Guadalupe**.

## 📋 Pasos Previos

### 1. Preparar el repositorio
Asegúrate de tener todos los archivos del sitio listos:
- ✅ `index.md` (página principal)
- ✅ `_config.yml` (configuración)
- ✅ Carpeta `/docs/` con documentos PDF
- ✅ `README.md`

### 2. Subir archivos PDF
Coloca todos los documentos PDF en la carpeta `/docs/` con nombres descriptivos:
```
docs/
├── acta-constitucion-amfccg.pdf
├── estatutos-sociales-amfccg.pdf
├── personeria-juridica-amfccg.pdf
├── certificado-existencia-amfccg.pdf
├── rut-asociacion-amfccg.pdf
├── directorio-actual-amfccg.pdf
├── plan-estrategico-amfccg.pdf
├── memoria-anual-amfccg.pdf
├── proyecto-cacao-sostenible.pdf
└── informe-financiero-amfccg.pdf
```

## 🔧 Configuración en GitHub

### Paso 1: Crear/Configurar el repositorio
1. Ve a GitHub.com y crea un repositorio público
2. Nombra el repositorio (ej: `sitio-amfccg` o `asociacion-cacaotera`)
3. Asegúrate de que sea **público** (GitHub Pages gratis requiere repos públicos)

### Paso 2: Subir archivos al repositorio

#### Opción A: Interfaz web de GitHub
1. Arrastra y suelta todos los archivos a GitHub
2. Escribe un mensaje de commit: "Configuración inicial del sitio web AMFCCG"
3. Haz clic en "Commit changes"

#### Opción B: Línea de comandos
```bash
# Desde la carpeta del proyecto
git init
git add .
git commit -m "Configuración inicial del sitio web AMFCCG"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/NOMBRE-REPOSITORIO.git
git push -u origin main
```

### Paso 3: Activar GitHub Pages
1. Ve a tu repositorio en GitHub
2. Haz clic en **Settings** (Configuración)
3. Desplázate hacia abajo hasta la sección **Pages**
4. En "Source" selecciona: **Deploy from a branch**
5. En "Branch" selecciona: **main**
6. En "Folder" selecciona: **/ (root)**
7. Haz clic en **Save**

### Paso 4: Configurar la URL personalizada
1. En `_config.yml`, actualiza la línea:
   ```yaml
   url: "https://TU-USUARIO.github.io"
   baseurl: "/NOMBRE-REPOSITORIO"
   ```
2. Commit y push el cambio

## 🌐 Acceso al sitio

Una vez activado GitHub Pages:
- Tu sitio estará disponible en: `https://TU-USUARIO.github.io/NOMBRE-REPOSITORIO`
- La activación puede tomar 5-10 minutos
- Recibirás un email de confirmación cuando esté listo

## ✅ Verificación

Verifica que todo funcione correctamente:
- [ ] El sitio carga correctamente
- [ ] Los enlaces a PDFs funcionan
- [ ] El diseño se ve bien en móvil y desktop
- [ ] Los meta tags aparecen en el código fuente

## 🔄 Actualizaciones futuras

Para actualizar el sitio:
1. Edita los archivos necesarios
2. Haz commit y push a la rama `main`
3. GitHub Pages se actualizará automáticamente (5-10 minutos)

### Actualizar documentos:
1. Sube nuevos PDFs a `/docs/`
2. Actualiza los enlaces en `index.md`
3. Commit y push

### Cambiar información:
1. Edita `index.md` o `_config.yml`
2. Commit y push

## 🎨 Personalización adicional

### Cambiar tema:
En `_config.yml`, modifica:
```yaml
# Temas disponibles en GitHub Pages:
theme: minima                          # (actual)
theme: minimal-mistakes               # Alternativa
remote_theme: pages-themes/slate     # Tema remoto
```

### Agregar Google Analytics:
En `_config.yml`, agrega:
```yaml
google_analytics: UA-XXXXXXXX-X
```

### Agregar dominio personalizado:
1. Compra un dominio
2. En Settings → Pages → Custom domain
3. Agrega tu dominio (ej: `www.amfccg.org`)
4. Configura los DNS en tu proveedor

## 🆘 Solución de problemas

### El sitio no carga:
- Verifica que el repositorio sea público
- Revisa que GitHub Pages esté activado
- Espera 10-15 minutos después de la configuración

### Los PDFs no se cargan:
- Verifica que los archivos estén en `/docs/`
- Confirma que los nombres coincidan con los enlaces
- Asegúrate de que los PDFs sean menores a 25MB

### Errores de Jekyll:
- Revisa la sintaxis de `_config.yml`
- Verifica que `index.md` tenga el front-matter correcto
- Consulta los logs en Settings → Pages

## 📞 Soporte

Si necesitas ayuda:
1. Consulta la [documentación oficial de GitHub Pages](https://docs.github.com/pages)
2. Revisa los logs de construcción en el repositorio
3. Contacta al desarrollador del sitio

---

🎉 **¡Felicidades!** Una vez completados estos pasos, tendrás un sitio web profesional para la Asociación de Mujeres y Familias Campesinas Cacaoteras de Guadalupe funcionando en GitHub Pages.
