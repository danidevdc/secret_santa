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
- 🔗 **Enlaces Únicos** - Genera un enlace personalizado para cada participante
- 💬 **Integración WhatsApp** - Comparte enlaces directamente por WhatsApp
- 📊 **Tracking en Tiempo Real** - Monitorea quién ha abierto su enlace
- 🎁 **Animación Interactiva** - Cada participante ve una animación especial al revelar su asignación

## 🚀 Tecnologías

- **HTML5**
- **JavaScript Vanilla** (sin frameworks, rápido y ligero)
- **Tailwind CSS** (vía CDN)
- **Canvas Confetti** (animaciones)
- **LocalStorage** (persistencia)

## 💡 Cómo Usar

### Para el Organizador:
1. **Agregar Participantes**: Escribe los nombres de todos los participantes
2. **Configurar Exclusiones (Opcional)**: Define parejas o familiares que no deben intercambiar
3. **Generar Sorteo**: Haz clic en "Generar Sorteo" para crear las asignaciones
4. **Enviar Enlaces**: Haz clic en "Enviar Enlaces" y comparte cada enlace personalizado
5. **Compartir por WhatsApp**: Usa el botón de WhatsApp para enviar automáticamente
6. **Monitorear**: Ve en tiempo real quién ha abierto su enlace
7. **Exportar/Guardar**: Descarga los datos para conservarlos

### Para los Participantes:
1. **Recibir Enlace**: El organizador te enviará un enlace único por WhatsApp
2. **Abrir Enlace**: Haz clic en el enlace en tu dispositivo
3. **Ver Animación**: Disfruta de la animación del regalo
4. **Revelar Asignación**: Haz clic en el regalo para descubrir tu amigo secreto
5. **Mantener Secreto**: ¡No le digas a nadie!

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

### Sistema de Enlaces Únicos
- Cada participante recibe un enlace personalizado y seguro
- Los enlaces se generan con encriptación Base64
- Cada enlace solo funciona para la persona asignada
- Se puede compartir fácilmente por WhatsApp o copiar al portapapeles

### Tracking en Tiempo Real
- Monitorea quién ha abierto su enlace
- Indicadores visuales (✅ Abierto / ⏳ No abierto)
- Barra de progreso con porcentaje de participación
- Actualización automática cada 2 segundos
- Los datos se comparten mediante localStorage con sessionID único

### Integración WhatsApp
- Botón directo para compartir por WhatsApp
- Mensaje pre-formateado con instrucciones
- Personalizado para cada participante
- Compatible con WhatsApp Web y móvil

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

### Configuración
```
Participantes:
- Ana
- Carlos
- María
- Pedro

Exclusiones:
- Ana → NO → Carlos (son pareja)
- María → NO → Pedro (son hermanos)
```

### Generación de Enlaces
```
✅ Sorteo generado exitosamente!

📱 Enlaces para compartir:
- Ana: https://tu-url.github.io/secret_santa/reveal.html?s=...&g=...&r=...
  Estado: ⏳ No abierto → 💬 Enviar por WhatsApp

- Carlos: https://tu-url.github.io/secret_santa/reveal.html?s=...&g=...&r=...
  Estado: ✅ Abierto → 💬 Enviar por WhatsApp

- María: https://tu-url.github.io/secret_santa/reveal.html?s=...&g=...&r=...
  Estado: ⏳ No abierto → 💬 Enviar por WhatsApp

- Pedro: https://tu-url.github.io/secret_santa/reveal.html?s=...&g=...&r=...
  Estado: ✅ Abierto → 💬 Enviar por WhatsApp

📊 Progreso: 2 de 4 participantes han abierto su enlace (50%)
```

### Experiencia del Participante
```
1. Recibe mensaje por WhatsApp:
   "🎅 ¡Hola Ana! 🎁
    Has sido seleccionada para participar en el Amigo Secreto.
    Haz clic en este enlace para descubrir a quién le vas a regalar:
    [ENLACE]
    ¡No compartas este enlace con nadie! 🤫"

2. Abre el enlace y ve:
   - Pantalla de carga animada
   - Regalo flotando con animación
   - Instrucciones para hacer clic

3. Hace clic en el regalo:
   - Animación de apertura del regalo
   - Confeti explosivo
   - Revelación del nombre con animación especial
   - Consejos y recordatorios
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
