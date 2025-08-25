# **Documentación de la Landing Page de RdaMates**

## **1\. Contexto General e Ingeniería**

* **Objetivo Principal:** Esta es una landing page de prelanzamiento. Su único objetivo es validar el interés en la aplicación RodaMates y capturar correos electrónicos de usuarios potenciales para notificarles sobre el lanzamiento.  
* **Público Objetivo:** Nómadas digitales, personas que viven en furgonetas camperizadas ("van life"), caravanistas y viajeros que valoran la sostenibilidad, el minimalismo y la comunidad.  
* **Tono de Voz:** Cercano, auténtico, amigable y ligeramente ingenioso. Debe sonar como un compañero de ruta, no como una corporación. Se usa el "tú" informal.

## **2\. Sistema de Diseño (Design System)**

### **2.1. Paleta de Colores**

Se utiliza una paleta de colores suave y optimista llamada "Cielo del Amanecer".

* \--dark-slate-gray (Texto Principal): \#2F4F4F  
* \--alicia-blue (Fondo Secundario): \#EDF2FB  
* \--baby-blue-eyes (Acentos y Botones Primarios): \#ABC4FF  
* \--champagne-pink (Fondo de Sección): \#E8D1C5  
* \--dark-slate-gray (Fondo Principal \- Hero): \#2F4F4F  
* white (Texto sobre fondo oscuro): \#FFFFFF

### **2.2. Tipografía**

* **Titulares (h1, h2, h3):** 'Nunito', sans-serif. Grueso (700, 800).  
* **Cuerpo de Texto (p, li):** 'Lato', sans-serif. Normal (400).

## **3\. Desglose de Componentes por Sección**

### **Sección 1: Héroe**

* **Objetivo:** Captar la atención inmediatamente, comunicar la propuesta de valor única y presentar el mockup de la app junto a la llamada a la acción (CTA) principal.  
* **Estructura:** Ocupa toda la pantalla (100vh). Fondo de color sólido (--dark-slate-gray). Contenido centrado vertical y horizontalmente.  
* **Componentes:**  
  1. **Header:**  
     * **Contenido:** Logo/Texto "RodaMates 🚐".  
     * **Estilo:** Texto blanco, text-2xl, font-bold. Posición absoluta en la parte superior izquierda.  
  2. **Título (h1):**  
     * **Contenido:** "Lo que te sobra, es lo que otro nómada necesita. Justo aquí. Ahora mismo."  
     * **Estilo:** Texto blanco, text-4xl a text-6xl, font-extrabold.  
  3. **Subtítulo (p):**  
     * **Contenido:** "La app gratuita para la comunidad nómada. Regala lo que te sobra, encuentra lo que te falta y conecta con otros viajeros a tu alrededor."  
     * **Estilo:** Texto blanco, text-lg a text-xl.  
  4. **Mockup de la App:**  
     * **Descripción:** Una representación visual de un teléfono mostrando la interfaz principal de la app (el swipe de una tarjeta de objeto).  
     * **Activos:** Se requiere la imagen del objeto (silla de camping) y los iconos de los botones (❌, 🤝, 💚).  
     * **Estilo:** Centrado debajo del subtítulo. Ancho máximo de 300px.  
  5. **Formulario CTA:**  
     * **Texto introductorio:** "Estamos calentando motores. ¡Sé el primero en enterarte del lanzamiento\!"  
     * **Input:** Campo de tipo email, placeholder "Introduce tu correo electrónico".  
     * **Botón Primario:** Texto "¡Avísame\! 👋".  
     * **Botón Secundario:** Texto "Sí, ¡la idea me interesa\!". Estilo con borde blanco y fondo transparente.  
  6. **Mensaje de Agradecimiento (Oculto inicialmente):**  
     * **Contenido:** Título "¡Gracias por unirte\! ✨" y texto "Te avisaremos en cuanto RodaMates esté en la carretera. ¡Buena ruta\!".  
     * **Funcionalidad:** Reemplaza al formulario cuando el usuario envía su email o hace clic en el botón de interés.

### **Sección 2: El Problema ("¿Te suena familiar?")**

* **Objetivo:** Generar empatía listando los puntos de dolor comunes del público objetivo.  
* **Estructura:** Fondo claro (--alicia-blue). Título centrado y una cuadrícula de 2x2 con los problemas.  
* **Componentes:**  
  * **Título (h2):** "Te suena familiar?"  
  * **Grid de Problemas:** Cada elemento contiene:  
    1. **Icono (Emoji):** 🚐, ♻️, 📍, 📦.  
    2. **Título del Problema (h3):** "Espacio vital al límite", "Dilema sostenible", etc.  
    3. **Descripción (p):** Texto explicativo corto.

### **Sección 3: La Solución**

* **Objetivo:** Presentar la app como la solución directa a los problemas mencionados.  
* **Estructura:** Fondo blanco para crear contraste. Contenido centrado.  
* **Componentes:**  
  * **Título (h2):** "La "caja de cosas gratis" de los campings, ahora en tu bolsillo."  
  * **Párrafo (p):** Descripción general de la app.  
  * **Lista de Características (ul):** Lista vertical con 4 puntos clave. Cada punto tiene:  
    1. **Icono (Emoji):** 🌍, 👉, 🤝, 💬.  
    2. **Texto:** Característica destacada en negrita seguida de una breve explicación.

### **Sección 4: Cómo Funciona**

* **Objetivo:** Demostrar la simplicidad y facilidad de uso de la app en 3 pasos.  
* **Estructura:** Fondo claro (--alicia-blue). Título centrado y una disposición de 3 columnas para los pasos.  
* **Componentes:**  
  * **Título (h2):** "Así de simple, así de rápido"  
  * **Columnas de Pasos (x3):** Cada columna contiene:  
    1. **Icono (Emoji):** 📸, 🗺️, 💬, dentro de un círculo de color.  
    2. **Título del Paso (h3):** "1. Publica lo que no usas", etc.  
    3. **Descripción (p):** Explicación breve del paso.

### **Sección 5: Impacto Ambiental**

* **Objetivo:** Conectar con los valores de sostenibilidad de la comunidad.  
* **Estructura:** Fondo de color distintivo (--champagne-pink). Título, párrafo introductorio y 3 cajas de beneficios.  
* **Componentes:**  
  * **Título (h2):** "Un pequeño gesto, un gran respiro para el planeta"  
  * **Párrafo (p):** Texto que explica el beneficio ecológico de reutilizar.  
  * **Cajas de Beneficios (x3):** Cada caja contiene:  
    1. **Icono (Emoji):** 🌍, 💧, ♻️.  
    2. **Título del Beneficio (h3):** "Menos CO2", "Ahorro de Agua", "Menos Residuos".  
    3. **Descripción (p):** Explicación del beneficio.

### **Sección 6: La Comunidad**

* **Objetivo:** Reforzar el pilar comunitario de la aplicación.  
* **Estructura:** Fondo blanco. Título, párrafo y 3 cajas de valores.  
* **Componentes:**  
  * **Título (h2):** "Más que una app, somos una tribu rodante"  
  * **Párrafo (p):** Texto que enfatiza la conexión social.  
  * **Cajas de Valores (x3):** Cada caja contiene:  
    1. **Título del Valor (h3):** "Sostenibilidad Real ♻️", "Apoyo Mutuo 🙏", "Conexiones Auténticas 🤝".  
    2. **Descripción (p):** Breve texto sobre el valor.

### **Sección 7: CTA Final**

* **Objetivo:** Realizar una última llamada a la acción clara y directa para maximizar la conversión.  
* **Estructura:** Fondo claro (--alicia-blue). Contenido centrado. Es una versión simplificada del CTA del Héroe.  
* **Componentes:**  
  * **Título (h2):** "¿Listo para aligerar la furgo y conectar con la tribu?"  
  * **Párrafo (p):** Texto de refuerzo.  
  * **Formulario CTA:** Idéntico en funcionalidad al del Héroe.  
  * **Mensaje de Agradecimiento:** Idéntico en funcionalidad al del Héroe.

### **Sección 8: Footer**

* **Objetivo:** Proporcionar información de copyright y un enlace a redes sociales.  
* **Estructura:** Fondo blanco. Contenido simple y centrado.  
* **Componentes:**  
  * **Nombre de la marca y año:** "RodaMates © 2025"  
  * **Slogan:** "Una herramienta para la tribu rodante."  
  * **Icono de Red Social:** Icono de Instagram enlazado al perfil de la app.

## **4\. Stack Tecnológico Recomendado**

Para construir esta landing page de manera eficiente y con un resultado de alto rendimiento, se recomienda el siguiente stack tecnológico:

* **Framework:** **Astro**. Es ideal para sitios web rápidos y centrados en el contenido como esta landing page. Su arquitectura de "cero JavaScript por defecto" garantiza tiempos de carga mínimos.  
* **Estilos CSS:** **Tailwind CSS**. Un framework de CSS "utility-first" que permite construir diseños complejos directamente en el HTML de forma rápida y consistente, sin necesidad de escribir CSS personalizado.  
* **Iconos:** **Lucide Icons**. Una librería de iconos SVG limpia, ligera y muy completa. Se integra fácilmente en proyectos de Astro para proporcionar iconografía nítida y coherente.