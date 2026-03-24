🍊 Calculadora de Torta de Naranja Pro

¡Bienvenido al repositorio de la Calculadora de Torta de Naranja! Esta herramienta ha sido desarrollada por Fernando Araujo para optimizar y profesionalizar el cálculo de ingredientes en la repostería, permitiendo un escalado preciso basado en las dimensiones reales de los moldes.

🚀 Enlace del Proyecto

Puedes ver la herramienta en funcionamiento aquí: GitHub Pages - Torta de Naranja

📸 Vista Previa

Interfaz Móvil

Selección de Molde

[Imagen de la interfaz de usuario en el celular]

[Imagen de los campos de dimensiones de la torta]

📋 Descripción

Esta aplicación web elimina las conjeturas al hornear. Utilizando el Método del Porcentaje Panadero, la calculadora ajusta automáticamente las cantidades de 8 ingredientes clave dependiendo de si usas un molde cuadrado/rectangular o redondo/cilíndrico.

Características Principales:

Cálculo por Volumen: Ajuste automático según altura, largo, profundidad o diámetro.

Números Enteros: Cantidades redondeadas a gramos para facilitar el pesado en balanzas de cocina.

Interfaz Móvil: Diseñada con Tailwind CSS para ser utilizada directamente en la cocina desde un celular.

Botón de Copiado: Genera una lista de ingredientes lista para compartir por WhatsApp o notas.

🧪 Especificaciones de la Receta (Excel vs App)

La base de esta calculadora se rige por los siguientes porcentajes extraídos de tu hoja de cálculo (con la Harina como el 100%):

Nº

INGREDIENTES

%

1

Harina

100,0%

2

Jugo de Naranja

39,2%

3

Azúcar

95,7%

4

Polvo de Hornear

3,4%

5

Aceite

32,6%

6

Sal

2,3%

7

Huevos

71,9%

8

Vainilla

3,0%

🛠️ Detalles Técnicos

El sistema utiliza factores de densidad calibrados para asegurar que el molde se llene correctamente basándose en tus pruebas:

Densidad Cuadrada: 0.4192 g/cm³ (Basado en molde 2.5 x 28 x 39 cm)

Densidad Redonda: 0.4195 g/cm³ (Basado en molde 14.5 x 9.5 cm)

Fórmulas utilizadas:

Volumen Cuadrado: $V = \text{Altura} \times \text{Profundidad} \times \text{Largo}$

Volumen Redondo: $V = \pi \times r^2 \times \text{Altura}$

💻 Instalación y Uso Local

Clona este repositorio:

git clone [https://github.com/loep1039/Torta_De_Naranja.git](https://github.com/loep1039/Torta_De_Naranja.git)


Abre el archivo index.html en cualquier navegador.

👤 Autor

Fernando Araujo
Desarrollo de herramientas para la eficiencia en producción de panadería y repostería.

Este proyecto fue documentado para asegurar la consistencia y calidad en cada horneada, replicando la precisión de las hojas de cálculo originales.
