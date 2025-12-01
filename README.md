# CV - Estilo Instagram

Curriculum Vitae con diseño inspirado en la interfaz de Instagram. Todos los espacios están listos para que completes con tu información personal.

## 🎨 Características

- ✨ Diseño estilo Instagram (colores, tipografía, tarjetas)
- 📱 Totalmente responsive
- 🎯 Espacios en blanco listos para completar
- 💼 Secciones completas de CV
- 🔗 Enlaces de contacto integrados

## 📝 Cómo completar tu CV

### 1. Información Personal (Sección Perfil)

**Ubicación en `index.html`:** Líneas 30-60

- **Foto de perfil**: 
  - Agrega tu foto en la carpeta del proyecto
  - En la línea 31, cambia `src=""` por `src="ruta-a-tu-foto.jpg"`
  - O elimina la línea 32-36 del placeholder si usas tu foto

- **Nombre completo** (línea 38): Reemplaza `Tu Nombre Completo`
- **Título profesional** (línea 39): Reemplaza `Tu Título Profesional`
- **Ubicación** (línea 40): Reemplaza `Ciudad, País`
- **Estadísticas** (líneas 42-50): Actualiza los números y etiquetas
- **Biografía** (líneas 54-56): Escribe tu descripción profesional

### 2. Enlaces de Contacto

**Ubicación:** Líneas 58-88

- **Email** (línea 59): Cambia `tu-email@ejemplo.com`
- **LinkedIn** (línea 66): Cambia `tu-perfil` por tu usuario
- **GitHub** (línea 73): Cambia `tu-usuario` por tu usuario
- **Teléfono** (línea 80): Cambia `+1234567890` por tu número

### 3. Experiencia Laboral

**Ubicación:** Líneas 95-130

Para cada trabajo:
- **Nombre del Puesto** (línea 102): Reemplaza con tu puesto
- **Nombre de la Empresa** (línea 103): Reemplaza con el nombre de la empresa
- **Período** (línea 104): Formato "Mes Año - Mes Año" (ej: "Enero 2020 - Diciembre 2022")
- **Descripción** (líneas 107-109): Lista tus responsabilidades y logros

**Para agregar más trabajos:** Copia el bloque completo de `<div class="instagram-card experience-card">` (líneas 97-115) y pégalo antes del comentario en la línea 117.

### 4. Educación

**Ubicación:** Líneas 135-170

Para cada título:
- **Nombre del Título** (línea 142): Reemplaza con tu grado/título
- **Institución** (línea 143): Nombre de la universidad/escuela
- **Período** (línea 144): Años de estudio
- **Detalles** (línea 147): Información adicional (promedio, especialización, etc.)

**Para agregar más educación:** Copia el bloque de educación (líneas 137-150) y pégalo antes del comentario en la línea 152.

### 5. Habilidades

**Ubicación:** Líneas 175-205

- **Habilidades Técnicas** (líneas 180-186): Reemplaza los textos `Habilidad 1`, `Habilidad 2`, etc.
- **Herramientas** (líneas 188-194): Reemplaza `Herramienta 1`, `Herramienta 2`, etc.
- **Habilidades Blandas** (líneas 196-202): Reemplaza con tus habilidades blandas

**Para agregar más habilidades:** Simplemente agrega más `<span class="skill-badge">` dentro de cada categoría.

### 6. Proyectos

**Ubicación:** Líneas 210-260

Para cada proyecto:
- **Imagen del proyecto** (línea 216): 
  - Agrega una imagen y cambia el placeholder
  - O reemplaza `<div class="image-placeholder">📸</div>` por `<img src="ruta-imagen.jpg" alt="Proyecto">`
- **Nombre del Proyecto** (línea 220): Reemplaza `Nombre del Proyecto`
- **Descripción** (línea 221): Describe tu proyecto
- **Tecnologías** (líneas 224-225): Reemplaza `Tecnología 1`, `Tecnología 2`
- **Enlaces** (líneas 227-228): Actualiza las URLs de "Ver proyecto" y "Código"

**Para agregar más proyectos:** Copia el bloque completo del proyecto (líneas 213-232) y pégalo dentro de `.projects-grid`.

### 7. Idiomas y Certificaciones

**Ubicación:** Líneas 240-280

**Idiomas:**
- Reemplaza `Idioma 1`, `Idioma 2` (líneas 247, 251, 255)
- Reemplaza `Nivel` con el nivel correspondiente (Básico, Intermedio, Avanzado, Nativo)

**Certificaciones:**
- **Nombre** (líneas 262, 268): Reemplaza `Nombre de la Certificación`
- **Institución** (líneas 263, 269): Reemplaza `Institución emisora`
- **Fecha** (líneas 264, 270): Formato "Mes Año"

**Para agregar más:** Copia los bloques `<div class="language-item">` o `<div class="cert-item">` según corresponda.

## 🎨 Personalización de Colores

Si quieres cambiar los colores estilo Instagram, edita las variables en `style.css` (líneas 8-16):

```css
:root {
    --instagram-blue: #0095f6;        /* Color azul principal */
    --instagram-blue-hover: #1877f2;   /* Color azul al pasar el mouse */
    --bg-primary: #ffffff;             /* Fondo principal */
    --bg-secondary: #fafafa;          /* Fondo secundario */
    --text-primary: #262626;          /* Texto principal */
    --text-secondary: #8e8e8e;        /* Texto secundario */
}
```

## 🚀 Despliegue en GitHub Pages

1. **Completa tu información** siguiendo las instrucciones arriba

2. **Haz commit y push:**
   ```bash
   git add .
   git commit -m "Agregar CV estilo Instagram"
   git push origin main
   ```

3. **Activa GitHub Pages:**
   - Ve a tu repositorio en GitHub
   - Settings → Pages
   - Source: selecciona `main` branch
   - Save

4. **Tu CV estará disponible en:** `https://tu-usuario.github.io`

## 📱 Responsive

El diseño es completamente responsive y se adapta a:
- 📱 Móviles (320px+)
- 📱 Tablets (768px+)
- 💻 Desktop (1024px+)

## 📄 Estructura del Proyecto

```
ekab-hub.github.io/
├── index.html      # CV principal (completa aquí tu información)
├── style.css       # Estilos estilo Instagram
└── README.md       # Este archivo
```

## 💡 Tips

- **Foto de perfil**: Usa una imagen cuadrada (1:1) para mejor resultado
- **Imágenes de proyectos**: Tamaño recomendado 800x600px
- **Biografía**: Máximo 3-4 párrafos para mejor legibilidad
- **Experiencia**: Enfócate en logros y resultados, no solo responsabilidades
- **Proyectos**: Incluye enlaces a demos en vivo y repositorios

---

¡Listo para completar con tu información! 🎉
