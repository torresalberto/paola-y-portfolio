# Yasbeth Paola Correa Castro — Portafolio Web (3 Diseños)

Tres sitios web de portafolio-currículum desarrollados a partir del CV en PDF de Yasbeth Paola Correa Castro, Ingeniera Civil.

---

## 📄 Fuente Original

**Archivo:** `Curriculum Vitae Profesional Mujer con Iconos Moderno Beige y Blanco.pdf`

**Datos extraídos:**
- **Nombre:** Yasbeth Paola Correa Castro
- **Profesión:** Ingeniera Civil
- **Experiencia:** 3+ años en presupuestos de obra
- **Educación:** Universidad Autónoma del Estado de Hidalgo — Lic. en Ingeniería Civil (Título y Cédula)
- **Experiencia:** Jefa de Contabilidad (Vandiere, Inc.), Analista Senior (Larana Inc.), Asistente Contable (Sociedad Martínez)
- **Investigación:** "Utilización de residuos mineros en concreto permeable como alternativa de construcción sostenible"
- **Software:** AutoCAD, Excel, OPUS, Prisma Master
- **Contacto:** yasbethcorrea@gmail.com | 775 253 2400 | Tulancingo de Bravo, Hidalgo

**Imágenes extraídas del PDF:**
- `img-000.png` — Página completa del CV (referencia de diseño)
- `img-001.png` — Fotografía de perfil de Paola

---

## 🌐 Los 3 Sitios Web

### 1. website-authority/ — "The Authority" (Ejecutivo Corporativo)

**Público objetivo:** Firmas de construcción, empresas de ingeniería, contratistas gubernamentales, RRHH corporativo

**Paleta:** Azul marino (#1a237e), carbón, dorado (#c9a227), blanco

**Tipografía:** Playfair Display (serif) + Inter (sans-serif)

**Características:**
- Hero con gradiente oscuro y estadísticas destacadas
- Línea de tiempo de experiencia profesional
- Tarjetas de habilidades con barras de progreso
- Sección de investigación con badge de publicación
- Formulario de contacto funcional
- Totalmente responsive

**Razonamiento psicológico:**
> El azul marino oscuro activa asociaciones subconscientes de confianza, profesionalismo y credibilidad institucional. El dorado señala logros sin ostentación. La tipografía serif activa el *Efecto Halo* — las fuentes clásicas se perciben como más competentes. El layout de cuadrícula imita planos arquitectónicos, generando familiaridad instantánea en gerentes de construcción. Los números cuantificados (25% reducción, 3+ años) crejan anclas de memoria más fuertes que el texto descriptivo.

---

### 2. website-innovator/ — "The Innovator" (Ingeniería Sustentable)

**Público objetivo:** Organizaciones de sustentabilidad, firmas de construcción verde, instituciones de investigación, consultorías ambientales

**Paleta:** Verde salvia (#8fbc8f), terracota (#e07a5f), arena (#f4f1ea), bosque (#2d4739)

**Tipografía:** Space Grotesk (sans geométrica) + Caveat (script orgánica)

**Características:**
- Hero con formas orgánicas animadas y foto con borde morphing
- Sección "Mi Historia" con tags flotantes animadas
- Tarjetas de trayectoria con gradientes
- Showcase de investigación en tarjeta destacada
- Nube de habilidades tipo tags interactivos
- Formas blob difuminadas como decoración

**Razonamiento psicológico:**
> Los tonos tierra (verdes, terracota, arena) activan respuestas *biófilicas* — los humanos confían instintivamente en los colores naturales. Para empleadores enfocados en sustentabilidad, esto crea *congruencia de valores* inmediata: "parece una de nosotros". Liderar con la investigación de residuos mineros (en lugar del título contable) es inesperado y memorable. El *Efecto Pratfall* muestra que el posicionamiento ligeramente contraintuitivo hace candidatos más distintivos y simpáticos. El layout narrativo (problema → investigación → solución) aprovecha el *sesgo de storytelling* — los humanos recordamos historias 22x más que hechos.

---

### 3. website-executive/ — "The Executive" (Lujo Minimalista)

**Público objetivo:** Reclutadores C-suite, clientes de consultoría privada, firmas de búsqueda ejecutiva, inversionistas de proyectos

**Paleta:** Beige cálido (#f5f5dc), crema (#fffdd0), taupe (#b8a89a), café espresso (#3e2723)

**Tipografía:** Cormorant Garamond (serif elegante) + Lora (serif body)

**Características:**
- Diseño de una sección por viewport con scroll suave
- Extremo minimalismo con whitespace generoso
- Fotos con filtro sepia que se revelan al hover
- Secciones numeradas (01, 02...)
- Destacados con subrayado en crema
- Meta de investigación con números grandes
- Totalmente editorial / estilo revista

**Razonamiento psicológico:**
> El minimalismo extremo señala confianza — "no necesito gritar porque mi trabajo habla". Este es el *Efecto Veblen* en diseño: la restricción implica alto valor. En reclutamiento ejecutivo, sobre-explicar se percibe como inseguridad. El whitespace = poder. El *Efecto Estético-Usabilidad* hace que las cosas bellas se perciban como más fáciles de usar y confiables. La paleta beige (que honra el CV original) crea *continuidad visual* — el espectador piensa subconscientemente "tiene gusto y consistencia". La *Regla Pico-Final* asegura que cada scroll entregue un "pico" memorable, terminando en una nota alta con contacto elegante.

---

## 🛠️ Tecnología

- **HTML5** semántico
- **CSS3** con variables, grid, flexbox, animaciones
- **JavaScript** vanilla (smooth scroll, navbar effects, mobile menu)
- **Google Fonts** cargadas vía CDN
- **100% Responsive** (mobile-first)
- **Zero dependencias** — cada sitio es un solo archivo HTML autocontenido

---

## 🚀 Cómo usar

Cada sitio es un archivo `index.html` autocontenido. Para visualizar:

```bash
# Opción 1: Abrir directamente en navegador
open website-authority/index.html
open website-innovator/index.html
open website-executive/index.html

# Opción 2: Servidor local
npx serve website-authority/
npx serve website-innovator/
npx serve website-executive/
```

Para publicar, simplemente sube la carpeta completa a cualquier hosting estático (Netlify, Vercel, GitHub Pages, etc.).

---

## 📁 Estructura

```
Paola Y/
├── Curriculum Vitae Profesional Mujer con Iconos Moderno Beige y Blanco.pdf
├── extracted_images/
│   ├── img-000.png          # Página completa del CV
│   └── img-001.png          # Foto de perfil
├── website-authority/
│   ├── index.html
│   └── assets/
│       ├── paola-photo.png
│       └── cv-reference.png
├── website-innovator/
│   ├── index.html
│   └── assets/
│       ├── paola-photo.png
│       └── cv-reference.png
├── website-executive/
│   ├── index.html
│   └── assets/
│       ├── paola-photo.png
│       └── cv-reference.png
└── README.md
```

---

## 📸 Uso de fotos

La foto de perfil de Paola (`img-001.png` extraída del PDF) se integra en:
- **Authority:** Hero con marco dorado + sección About
- **Innovator:** Hero con forma orgánica morphing + sección Contacto
- **Executive:** Hero con filtro sepia + sección Contacto

La página completa del CV (`img-000.png`) se usa como referencia de diseño y descargable.
