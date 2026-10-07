# 📧 Firma de Correo Gmail — 33k (Andrés Darín)

Firma de correo profesional en HTML compatible con Gmail y clientes de correo modernos.

---

## 📁 Estructura del Proyecto

```text
sign_mail/
├── assets/
│   ├── signature-bg.png  # Fondo geométrico sutil (alta resolución / retina)
│   └── linkedin.png      # Icono oficial de LinkedIn
├── signature.html        # Plantilla HTML con diseño en tablas e inline styles
└── README.md             # Instrucciones de uso
```

---

## 🚀 Cómo instalar la firma en Gmail

### Paso 1: Abrir la plantilla
1. Haz doble clic en `signature.html` o ábrelo en tu navegador favorito (Chrome, Edge, Firefox, Brave).

### Paso 2: Copiar la firma
1. Selecciona visualmente la tarjeta de la firma con el cursor (o arrastra para sombrear todo el cuadro de la firma).
2. Presiona `Ctrl + C` (o `Cmd + C` en Mac) para copiar.

### Paso 3: Pegar en Gmail
1. Abre [Gmail](https://mail.google.com/) en tu navegador.
2. Haz clic en el icono de engranaje ⚙️ (**Configuración**) en la esquina superior derecha y selecciona **"Ver todos los ajustes"**.
3. En la pestaña **General**, baja hasta la sección **"Firma"**.
4. Haz clic en **"Crear nueva"** (o selecciona tu firma existente).
5. Pega la firma en el editor presionando `Ctrl + V` (o `Cmd + V`).
6. Configura los **Valores predeterminados de la firma** para nuevos correos y respuestas.
7. Ve al final de la página y haz clic en **"Guardar cambios"**.

---

## 🎨 Características de Diseño y Compatibilidad

- **Ancho:** ~430 px.
- **Layout en Tablas:** Máxima compatibilidad con motores de renderizado de correo (Gmail, Outlook, Apple Mail).
- **Estilos Inline:** Evita pérdida de formato por filtrado de etiquetas `<style>`.
- **Fondo Decorativo con Fallback:** Fondo geométrico sutil que en caso de no cargar o ser bloqueado mantiene contraste óptimo (100% legible sobre fondo blanco).
- **Elementos Interactivos:** Enlace directo y clickeable a LinkedIn.
