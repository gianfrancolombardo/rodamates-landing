# Guía de Diseño Visual - ReNomada Landing Page para Flutter

## Filosofía Visual

La landing page de ReNomada transmite una sensación de **movimiento, comunidad y sostenibilidad** a través de un diseño que combina elementos modernos con una estética nómada. El diseño utiliza contrastes dramáticos entre fondos oscuros y secciones claras para crear ritmo visual y guiar la atención del usuario.

## Paleta de Colores Conceptual

### Colores Principales
- **Fondo Principal**: Azul muy oscuro (slate-900) que evoca la noche y el viaje
- **Fondo Secundario**: Azul oscuro (slate-800) para transiciones suaves
- **Fondo Terciario**: Gris azulado (slate-700) para elementos sutiles

### Colores de Acento
- **Azul Vibrante**: Para elementos principales y CTAs
- **Púrpura**: Para gradientes y elementos de comunidad
- **Rosa**: Para acentos finales en gradientes
- **Verde**: Para elementos de sostenibilidad
- **Naranja**: Para elementos de logística/paquetes

### Colores de Texto
- **Blanco**: Para títulos principales y texto sobre fondos oscuros
- **Gris Claro**: Para texto secundario sobre fondos oscuros
- **Gris Oscuro**: Para texto sobre fondos claros
- **Negro**: Para títulos sobre fondos blancos

### Fondos Alternativos
- **Blanco Puro**: Para secciones de contraste
- **Verde Muy Claro**: Para sección de impacto ambiental
- **Azul Muy Claro**: Para elementos sutiles

## Tipografía y Jerarquía Visual

### Jerarquía de Textos
- **Títulos XL**: Muy grandes, bold, para headlines principales
- **Títulos LG**: Grandes, bold, para secciones importantes  
- **Títulos MD**: Medianos, semibold, para subtítulos
- **Texto Body**: Regular, para contenido principal
- **Texto Body LG**: Ligeramente más grande para descripciones importantes

### Características Tipográficas
- **Fuente Principal**: Sans-serif moderna y limpia
- **Peso**: Desde regular hasta black (800-900) para títulos
- **Espaciado**: Letter-spacing negativo en títulos para mayor impacto
- **Altura de línea**: Compacta en títulos (1.1-1.2), cómoda en texto (1.5)

## Espaciado y Layout

### Sistema de Espaciado
- **Micro**: 4px - Para elementos muy pequeños
- **Pequeño**: 8px - Para espaciado interno de componentes
- **Mediano**: 16px - Para espaciado estándar entre elementos
- **Grande**: 24px - Para separación de secciones
- **Extra Grande**: 32px - Para separación importante
- **XXL**: 48px - Para separación entre secciones principales
- **XXXL**: 64px - Para separación máxima entre secciones

### Layout y Contenedores
- **Ancho máximo**: 1152px (max-w-6xl) para contenido principal
- **Padding horizontal**: 24px en móvil, más en desktop
- **Border radius**: 12px estándar, 16px para elementos grandes, 24px para elementos muy grandes

## Componentes Visuales Principales

### 1. Header/Navegación
**Características Visuales:**
- **Fondo**: Azul muy oscuro con transparencia y blur
- **Posición**: Fixed en la parte superior
- **Logo**: Icono púrpura + texto con gradiente blanco-azul
- **Navegación**: Enlaces en gris claro que se vuelven blancos al hover
- **Altura**: Compacta (80px aproximadamente)

### 2. Sección Hero
**Características Visuales:**
- **Fondo**: Gradiente diagonal de azul oscuro
- **Layout**: Dos columnas (contenido + mockup)
- **Badge**: Píldora azul con punto animado "Próximamente"
- **Título Principal**: 
  - Primera línea en blanco sólido
  - Segunda línea con gradiente azul-púrpura-rosa
- **Descripción**: Texto gris claro, tamaño mediano
- **Formulario CTA**: 
  - Input con borde gris, fondo semi-transparente
  - Botón principal con gradiente azul-púrpura y sombra
  - Botón secundario con borde gris
- **Mockup**: Teléfono con animación de swipe real

### 3. Sección Problema
**Características Visuales:**
- **Fondo**: Gradiente vertical de azul oscuro
- **Título**: Blanco, centrado, muy grande
- **Grid**: 2x2 de tarjetas
- **Tarjetas**:
  - Fondo azul oscuro semi-transparente
  - Borde gris sutil
  - Icono en contenedor con gradiente de color
  - Título blanco, descripción gris claro
  - Hover: escala sutil y cambio de borde

### 4. Sección Solución
**Características Visuales:**
- **Fondo**: Blanco puro (contraste dramático)
- **Badge**: Píldora azul con icono de rayo
- **Título**: Negro, muy grande, centrado
- **Descripción**: Gris oscuro, centrada
- **Grid**: 4 columnas de características
- **Tarjetas**:
  - Icono en contenedor con gradiente de color
  - Título negro, descripción gris
  - Centradas, sin fondo

### 5. Sección Cómo Funciona
**Características Visuales:**
- **Fondo**: Gradiente vertical de azul oscuro
- **Título**: Blanco, centrado
- **Subtítulo**: Gris claro, centrado
- **Grid**: 3 columnas de pasos
- **Pasos**:
  - Icono circular grande con gradiente de color
  - Número en círculo blanco superpuesto
  - Título blanco, descripción gris claro
  - Sombra de color en el icono

### 6. Sección Impacto Ambiental
**Características Visuales:**
- **Fondo**: Gradiente diagonal verde muy claro
- **Título**: Negro, muy grande
- **Descripción**: Gris oscuro
- **Grid**: 3 columnas de tarjetas
- **Tarjetas**:
  - Fondo blanco con sombra
  - Borde sutil del color del icono
  - Icono en contenedor con gradiente de color
  - Título negro, descripción gris

### 7. Sección Comunidad
**Características Visuales:**
- **Fondo**: Blanco puro
- **Badge**: Píldora púrpura con icono de usuarios
- **Título**: Negro, muy grande
- **Descripción**: Gris oscuro
- **Grid**: 3 columnas de valores
- **Tarjetas**: Centradas, sin fondo, solo iconos y texto

### 8. CTA Final
**Características Visuales:**
- **Fondo**: Gradiente diagonal de azul oscuro
- **Título**: Blanco, muy grande, centrado
- **Descripción**: Gris claro, centrada
- **Formulario**: Idéntico al hero pero centrado
- **Mensaje de agradecimiento**: Verde con icono de check

### 9. Footer
**Características Visuales:**
- **Fondo**: Azul muy oscuro
- **Logo**: Icono púrpura + texto blanco
- **Copyright**: Blanco con tagline gris
- **Redes**: Icono en contenedor gris oscuro

## Elementos de Interacción y Animación

### Efectos Hover
- **Escala Sutil**: 1.02x en tarjetas y botones
- **Cambio de Color**: Bordes y textos que se aclaran
- **Sombras**: Aparecen o se intensifican en hover
- **Transiciones**: Suaves, 300ms de duración

### Animaciones Principales
- **Punto Pulsante**: En el badge "Próximamente"
- **Swipe del Mockup**: Animación real de swipe en el teléfono
- **Escala de Iconos**: Los iconos crecen ligeramente en hover
- **Gradientes**: Efectos de gradiente en hover de inputs

### Estados de Formulario
- **Normal**: Borde gris, fondo semi-transparente
- **Focus**: Borde azul, fondo más opaco
- **Hover**: Borde más claro, gradiente sutil de fondo
- **Éxito**: Mensaje verde con icono de check

## Patrones de Diseño

### Alternancia de Fondos
- **Oscuro → Claro → Oscuro**: Crea ritmo visual
- **Secciones oscuras**: Hero, Problema, Cómo funciona, CTA final
- **Secciones claras**: Solución, Impacto ambiental, Comunidad
- **Transiciones**: Gradientes suaves entre secciones

### Jerarquía Visual
- **Títulos**: Muy grandes, bold, máximo contraste
- **Subtítulos**: Medianos, semibold
- **Texto**: Regular, contraste medio
- **Badges**: Pequeños, con color de acento

### Grid Systems
- **Hero**: 2 columnas (contenido + mockup)
- **Problema**: 2x2 grid
- **Solución**: 4 columnas
- **Cómo funciona**: 3 columnas
- **Impacto**: 3 columnas
- **Comunidad**: 3 columnas

### Espaciado Consistente
- **Entre secciones**: 64px (xxxl)
- **Entre elementos**: 24px (lg)
- **Padding interno**: 16px (md)
- **Padding de contenedor**: 24px (lg)

## Iconografía y Elementos Visuales

### Iconos por Sección
- **Problema**: Hoja (verde), Camión (azul), Ubicación (púrpura), Paquete (naranja)
- **Solución**: Globo (verde), Flecha (azul), Usuarios (púrpura), Chat (rosa)
- **Cómo funciona**: Cámara (azul), Ubicación (verde), Chat (púrpura)
- **Impacto**: Globo (verde), Hoja (teal), Corazón (verde)
- **Comunidad**: Hoja (verde), Corazón (azul), Chat (púrpura)

### Estilo de Iconos
- **Tamaño**: 32px para contenedores grandes, 16px para pequeños
- **Contenedores**: Cuadrados redondeados con gradiente de color
- **Colores**: Cada icono tiene su color temático
- **Efectos**: Escala en hover, sombras sutiles

### Elementos Decorativos
- **Badges**: Píldoras con iconos y texto
- **Gradientes**: Diagonales y radiales para fondos
- **Sombras**: Sutiles, con color del elemento
- **Bordes**: Semi-transparentes, sutiles

## Responsive Design

### Breakpoints Conceptuales
- **Móvil**: < 640px - Una columna, espaciado reducido
- **Tablet**: 640px - 768px - Dos columnas máximo
- **Desktop**: 768px - 1024px - Layout completo
- **Large**: > 1024px - Espaciado ampliado

### Adaptaciones por Dispositivo
- **Móvil**: 
  - Hero en columna única
  - Grids en una columna
  - Espaciado reducido
  - Texto más pequeño
- **Tablet**: 
  - Hero mantiene dos columnas
  - Grids en 2 columnas máximo
  - Espaciado medio
- **Desktop**: 
  - Layout completo
  - Espaciado amplio
  - Hover effects activos

## Consideraciones para Flutter

### Widgets Principales
- **Container**: Para fondos y contenedores
- **Column/Row**: Para layouts
- **GridView**: Para grids de tarjetas
- **Card**: Para tarjetas con sombras
- **TextField**: Para inputs
- **ElevatedButton**: Para botones principales
- **OutlinedButton**: Para botones secundarios

### Animaciones en Flutter
- **AnimatedContainer**: Para cambios de escala
- **AnimatedOpacity**: Para transiciones
- **TweenAnimation**: Para animaciones personalizadas
- **Hero**: Para transiciones entre pantallas

### Gestión de Estado
- **Provider/Riverpod**: Para estado de formularios
- **AnimationController**: Para animaciones complejas
- **ScrollController**: Para scroll suave

### Performance
- **ListView.builder**: Para listas largas
- **CachedNetworkImage**: Para imágenes
- **const constructors**: Para widgets estáticos
- **RepaintBoundary**: Para optimización de pintado

## Resumen de la Experiencia Visual

### Flujo Visual Principal
1. **Entrada Dramática**: Hero con fondo oscuro y gradiente de texto llama la atención
2. **Problema Identificado**: Sección oscura con tarjetas que empatizan con el usuario
3. **Solución Clara**: Contraste blanco que presenta la solución de forma clara
4. **Proceso Simple**: Pasos numerados en fondo oscuro para facilidad
5. **Impacto Positivo**: Sección verde que refuerza los beneficios
6. **Comunidad**: Valores compartidos en fondo blanco
7. **Llamada Final**: CTA dramático que cierra el ciclo

### Elementos Clave para Replicar
- **Contraste Dramático**: Alternancia entre fondos oscuros y claros
- **Gradientes Sutiles**: En fondos, textos y elementos decorativos
- **Iconografía Consistente**: Cada sección tiene su paleta de colores
- **Espaciado Generoso**: Respiración visual entre elementos
- **Animaciones Sutiles**: Hover effects y transiciones suaves
- **Tipografía Jerárquica**: Tamaños y pesos bien definidos

### Sensación General
La landing page transmite **modernidad, confianza y movimiento**. El diseño oscuro con acentos de color crea una sensación premium, mientras que los elementos de comunidad y sostenibilidad añaden calidez humana. La alternancia de fondos mantiene el interés visual y guía naturalmente la atención del usuario a través de la historia de la marca.

Este diseño funciona porque:
- **Crea Contraste**: Los fondos oscuros hacen que el contenido blanco "pop"
- **Establece Ritmo**: La alternancia de secciones crea un flujo visual natural
- **Comunica Valores**: Los colores y iconos refuerzan los mensajes de sostenibilidad
- **Facilita la Navegación**: La jerarquía visual clara guía al usuario
- **Genera Confianza**: El diseño profesional transmite seriedad y calidad

---

**Esta guía de diseño visual te proporciona una base sólida para replicar la estética y sensación de la landing page de ReNomada en tu aplicación Flutter. El enfoque está en entender la filosofía visual, los patrones de diseño y los elementos clave que hacen que el diseño funcione, más que en código específico.**

**Recuerda que el éxito está en capturar la esencia del diseño: el contraste dramático, la alternancia de fondos, la iconografía consistente y las animaciones sutiles que crean una experiencia premium y moderna.**

