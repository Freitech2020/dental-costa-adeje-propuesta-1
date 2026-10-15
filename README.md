# Dental Costa Adeje — Propuesta 1: Swiss High-Tech & Implantology Precision

> **Modalidad Estratégica 1:** Minimalismo lumínico suizo, fondo claro quirúrgico, tipografía *Plus Jakarta Sans*, acento Turquesa Joya (`#00A896`), micro-animaciones SVG con `stroke-dashoffset` y foco en cirugía guiada 3D y tecnología Straumann®.

---

## 🔬 Especificaciones de Diseño y UX

- **Identidad Visual:** Quirúrgico lumínico (`#FFFFFF` / `#F8FAFC`), pizarra profunda (`#0F172A`), acento Turquesa Joya (`#00A896`) y verde confianza médica (`#166534` sobre `#F0FDF4`).
- **Accesibilidad WCAG 2.1 AA:** Ratios de contraste certificados superiores a 4.5:1 en todos los textos de párrafo y 5.90:1 en botones de acción.
- **Tipografía (Ley 8):** Plus Jakarta Sans (Google Fonts), H1 único en Hero (1.18em), párrafos desktop >= 18px (1.65em), móvil >= 16px (1.5em).
- **Micro-interacciones:** Retícula quirúrgica animada sobre visual clínico con trazado vectorial dinámico SVG (`stroke-dashoffset`).
- **Conversión Directa:** Enlace telefónico canónico `tel:+34683101030` visible en cabecera y barra móvil fija; botón radar de WhatsApp con mensaje contextualizado y predefinido.
- **Internacionalización:** Selector interactivo de 4 idiomas (`ES`, `EN`, `DE`, `IT`) con previsualización dinámica.
- **Autoridad Médica (E-E-A-T):** Cuadro médico acreditado con Dr. Facundo Mateo Ríos (Director Médico, COEST Nº 38000921), Dra. Ana Isabel Martín Fuster (COEST Nº 38001140) y Dra. Maryuri de Castro (COEST Nº 38001215).

---

## 📁 Estructura del Entregable

```
propuesta-1-swiss-hightech/
├── index.html                  # Prototipo interactivo HTML5/CSS/JS (1440px / 390px)
├── elementor-template.json     # Plantilla Elementor Pro 100% Flexbox Containers (v0.4)
├── README.md                   # Documentación técnica de la propuesta
├── .gitignore                  # Exclusiones de control de versiones
└── assets/                     # Activos WebP (<90 KB) y spritesheet SVG
    ├── logo_costa_adeje_dental.webp
    ├── hero_fondo_clinica.webp
    ├── implant_3d_scan.webp
    ├── doctor_facundo_mateo.webp
    ├── clinica_doctora_consulta.webp
    ├── doctora_maryuri_castro.webp
    ├── transporte_vip_shuttle.webp
    ├── marca_straumann.webp
    ├── marca_nobel_biocare.webp
    ├── marca_ticare.webp
    ├── marca_invisalign.webp
    ├── marca_spark.webp
    └── spritesheet_dental_icons.svg
```

---

## 🚀 Despliegue e Importación

### Prototipo Navegable
Abrir directamente `index.html` en cualquier navegador moderno o servir mediante servidor local:
```bash
python -m http.server 8000
```

### Importación en WordPress / Elementor Pro
1. Acceder al panel de administración de WordPress en Staging.
2. Ir a **Plantillas > Plantillas Guardadas > Importar Plantillas**.
3. Seleccionar y subir el archivo `elementor-template.json`.
4. Insertar la plantilla en la página de inicio como contenedor de ancho completo.

---

## 🐙 Repositorio Git Oficial

- **Remoto configurado:** `https://github.com/Freitech2020/dental-costa-adeje-propuesta-1.git`
- **Rama principal:** `main`
- **Comando de subida:**
```powershell
git -C "propuestas/propuesta-1-swiss-hightech" push -u origin main
```
