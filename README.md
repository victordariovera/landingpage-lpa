# LPA Automatizaciones - Landing Page

Landing page estática para LPA Automatizaciones, servicio profesional de portones automáticos.

## 🚀 Despliegue en GitHub Pages

Este sitio está configurado para desplegarse automáticamente en GitHub Pages desde la rama `main`.

### Configuración del Dominio Personalizado

Para usar el dominio `automatizacioneslpa.com.ar`:

1. **En GitHub:**
   - Ve a Settings → Pages
   - En "Custom domain", ingresa: `automatizacioneslpa.com.ar`
   - Marca "Enforce HTTPS"

2. **En tu proveedor de DNS:**
   - Crea un registro CNAME apuntando a: `tu-usuario.github.io` (o `tu-organizacion.github.io`)
   - O crea un registro A apuntando a las IPs de GitHub Pages:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153

3. **Espera la propagación DNS** (puede tardar hasta 48 horas)

## 📁 Estructura del Proyecto

```
├── index.html          # Página principal
├── styles.css          # Estilos CSS
└── README.md          # Este archivo
```

## 🎨 Características

- ✅ Diseño responsive (mobile-first)
- ✅ Animaciones en botones de WhatsApp
- ✅ Enfoque en guardia 24/7 los 365 días
- ✅ Optimizado para edificios residenciales, galpones y empresas
- ✅ Sin dependencias externas (HTML + CSS puro)
- ✅ Smooth scroll opcional

## 📝 Próximos Pasos

1. Reemplazar el logo placeholder en `index.html` (línea 16)
2. Reemplazar la imagen principal placeholder en `index.html` (línea 53)
3. Actualizar el número de WhatsApp si es necesario (ya configurado: +54 9 11 3292-9892)

## 🔧 Desarrollo Local

Simplemente abre `index.html` en tu navegador o usa un servidor local:

```bash
# Con Python 3
python3 -m http.server 8000

# Con Node.js (http-server)
npx http-server
```

Luego visita: `http://localhost:8000`

## 📞 Contacto

- WhatsApp: +54 9 11 3292-9892
- Email: info@lpaautomatizaciones.com
