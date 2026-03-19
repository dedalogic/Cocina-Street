# 🍟 Cocina Street — App de Conteo de Inventario

App web mobile-first para el equipo de cocina de Street Flags. Permite hacer conteos de stock rápidos y enviar el resumen directamente al grupo de WhatsApp.

## ✨ Funcionalidades

- Selección de usuario (Ayerim, Bettys, Carmen, Miriam, Roxedy, Otra)
- Turno AM / PM con detección automática de día y fin de semana
- Conteo por 5 secciones: Carnes, Verduras, Lácteos, Abarrotes y Pan, Limpieza
- Semáforo automático: 🔴 Crítico (< 5 unidades) / 🟡 Stock bajo / ✅ OK
- Marcado manual de urgencia ⚠️ por producto
- Input numérico directo para productos de alto volumen (carnes, abarrotes)
- Resumen con vista previa del mensaje
- Envío directo a WhatsApp con fecha, turno y responsable
- Panel de administrador con clave para gestionar productos y usuarios
- Cada conteo parte siempre desde cero

## 🚀 Deploy en Netlify

1. Sube este repositorio a GitHub
2. Entra a [netlify.com](https://netlify.com) y conecta el repo
3. Build command: *(dejar vacío)*
4. Publish directory: `.`
5. ¡Listo!

## 🔒 Panel Admin

Accede desde el botón pequeño "Admin" en la pantalla de inicio.
- Contraseña por defecto: `cocina2024`
- Permite agregar/eliminar usuarios y productos por sección

> ⚠️ Para cambiar la contraseña, edita la variable `ADMIN_PASS` en `index.html`

## 🗂️ Estructura

```
cocina-street/
├── index.html       # App completa (una sola página)
├── README.md        # Este archivo
└── .gitignore
```

## 📱 Uso

La app es una PWA básica. Para instalarla en el celular:
- En iPhone: Safari → Compartir → "Agregar a pantalla de inicio"
- En Android: Chrome → Menú → "Agregar a pantalla de inicio"
