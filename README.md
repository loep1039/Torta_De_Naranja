🍊 Calculadora de Torta de Naranja Pro

¡Bienvenido al repositorio de la Calculadora de Torta de Naranja! Esta herramienta ha sido desarrollada por Fernando Araujo para optimizar y profesionalizar el cálculo de ingredientes en la repostería, permitiendo un escalado preciso basado en las dimensiones reales de los moldes.

🚀 Enlace del Proyecto

Puedes acceder a la herramienta directamente aquí: https://loep1039.github.io/Torta_De_Naranja/

📸 Vista Previa

Interfaz y Uso:
En la versión móvil, el usuario puede seleccionar rápidamente el tipo de molde. Una vez introducidas las dimensiones (altura, largo, profundidad o diámetro), la aplicación muestra automáticamente la lista de ingredientes optimizada para la producción inmediata.

📋 Descripción

Esta aplicación web elimina las conjeturas al hornear. Utilizando el Método del Porcentaje Panadero, la calculadora ajusta las cantidades de los ingredientes clave dependiendo de si usas un molde cuadrado/rectangular o redondo/cilíndrico, garantizando que nunca sobre ni falte mezcla.

Características Principales:

Cálculo por Volumen: Ajuste automático de masa según las medidas exactas del molde en centímetros.

Números Enteros: Todas las cantidades se redondean a gramos para facilitar el trabajo con balanzas digitales de cocina.

Interfaz Móvil: Diseño adaptativo (Responsive) optimizado para ser consultado desde un smartphone en el área de trabajo.

Botón de Copiado: Función integrada para copiar la lista de ingredientes y enviarla por WhatsApp o guardarla en notas.

🧪 Especificaciones de la Receta (Excel vs App)

La base de esta calculadora se rige por los porcentajes exactos de la receta original de Fernando Araujo, tomando la Harina como el 100%. Los ingredientes incluidos en el cálculo automático son: Harina (100.0%), Jugo de Naranja (39.2%), Azúcar (95.7%), Polvo de Hornear (3.4%), Aceite (32.6%), Sal (2.3%), Huevos (71.9%) y Vainilla (3.0%).

🛠️ Detalles Técnicos

El sistema utiliza factores de densidad calibrados tras pruebas reales de horneado para asegurar un llenado perfecto. Para moldes cuadrados, se aplica una densidad de 0.4192 g/cm³. Para moldes redondos, la densidad utilizada es de 0.4195 g/cm³.

Fórmulas Matemáticas:

La aplicación determina el volumen ($V$) multiplicando las dimensiones según la geometría del molde. En moldes cuadrados se calcula como $V = \text{Altura} \times \text{Profundidad} \times \text{Largo}$. En moldes redondos, se utiliza la fórmula de cilindro $V = \pi \times r^2 \times \text{Altura}$.

💻 Uso Local

Si deseas ejecutar este proyecto localmente, puedes clonar el repositorio y abrir el archivo index.html en cualquier navegador web moderno:
git clone https://github.com/loep1039/Torta_De_Naranja.git

👤 Autor

Fernando Araujo
Especialista en desarrollo de herramientas digitales para la eficiencia en producción de repostería.

Este proyecto documenta y automatiza la precisión de las hojas de cálculo originales para asegurar la calidad en cada horneada.
