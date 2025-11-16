# 🎅 Amigo Secreto / Secret Santa

Una aplicación web simple, elegante y completamente funcional para organizar intercambios de regalos de Amigo Secreto.

## 🌟 Características

- ✅ **100% en Español** - Toda la interfaz en español
- 🎨 **Diseño Moderno** - Interfaz hermosa y responsiva con Tailwind CSS
- 🎯 **Simple de Usar** - Intuitivo y fácil de navegar
- 🎲 **Sorteo Aleatorio** - Genera asignaciones aleatorias automáticamente
- 🚫 **Exclusiones Configurables** - Define quién no puede regalarle a quién
- 💾 **Persistencia Local** - Guarda los datos automáticamente
- 📥 **Exportar/Importar** - Guarda y comparte tus sorteos
- 🎊 **Animaciones Divertidas** - Efectos de confeti y transiciones suaves
- 📱 **Responsive** - Funciona en móviles, tablets y escritorio
- 🔒 **Revelación Privada** - Muestra las asignaciones una por una

## 🚀 Tecnologías

- **HTML5**
- **JavaScript Vanilla** (sin frameworks, rápido y ligero)
- **Tailwind CSS** (vía CDN)
- **Canvas Confetti** (animaciones)
- **LocalStorage** (persistencia)

## 💡 Cómo Usar

1. **Agregar Participantes**: Escribe los nombres de todos los participantes
2. **Configurar Exclusiones (Opcional)**: Define parejas o familiares que no deben intercambiar
3. **Generar Sorteo**: Haz clic en "Generar Sorteo" para crear las asignaciones
4. **Revelar Asignaciones**: Muestra quién le regala a quién, uno por uno
5. **Exportar/Guardar**: Descarga los datos para conservarlos

## 🎯 Características Destacadas

### Gestión de Participantes
- Agregar y eliminar participantes fácilmente
- Validación automática de nombres duplicados

### Sistema de Exclusiones
- Evita que ciertas personas se regalen entre sí
- Perfecto para parejas, familiares directos, etc.
- El algoritmo garantiza asignaciones válidas

### Algoritmo Inteligente
- Genera asignaciones aleatorias respetando todas las exclusiones
- Reintentos automáticos hasta encontrar una configuración válida
- Notifica si no es posible con las exclusiones actuales

### Persistencia de Datos
- Guarda automáticamente en LocalStorage
- Los datos persisten entre sesiones
- Función de exportación a JSON

### Experiencia de Usuario
- Animaciones suaves y atractivas
- Confeti al generar sorteos y revelar asignaciones
- Diseño responsive para cualquier dispositivo
- Interfaz intuitiva y amigable

## 🌐 Demo

Visita la página en GitHub Pages: [Tu URL aquí]

## 📦 Instalación

### Opción 1: GitHub Pages (Recomendado)
1. Haz fork de este repositorio
2. Activa GitHub Pages en Settings → Pages
3. Selecciona la rama `main` como fuente
4. ¡Listo! Tu página estará disponible en pocos minutos

### Opción 2: Local
1. Clona el repositorio
2. Abre `index.html` en tu navegador
3. ¡No requiere servidor!

## 🎁 Ejemplo de Uso

```
Participantes:
- Ana
- Carlos
- María
- Pedro

Exclusiones:
- Ana → NO → Carlos (son pareja)
- María → NO → Pedro (son hermanos)

Resultado del sorteo:
- Ana le regala a → María
- Carlos le regala a → Pedro
- María le regala a → Carlos
- Pedro le regala a → Ana
```

## 🔧 Personalización

El código es simple y está bien comentado. Puedes personalizar:
- Colores en las clases de Tailwind
- Animaciones en la sección `<style>`
- Lógica del sorteo en la función `generateAssignments()`

## 📄 Licencia

Libre para usar, modificar y distribuir.

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Siéntete libre de abrir issues o pull requests.

---

Hecho con ❤️ para hacer más fácil organizar intercambios de regalos
