Referencia y Créditos Este proyecto fue desarrollado tomando como base y referencia el tutorial oficial de Flet: Flet Calculator Tutorial

l. ADN de la Aplicación (Configuración e Importación)
Aquí definimos las herramientas y el estado inicial. La variable resultado es el corazón de la visualización, ya que es el único elemento que cambiará dinámicamente. 
<img width="720" height="192" alt="image" src="https://github.com/user-attachments/assets/0cd4c7ff-b148-4d51-afa3-4820710113d7" />


2. Los Planos de Construcción (Clases Personalizadas)
En lugar de repetir el código de estilo para cada uno de los 19 botones, creamos "moldes". Usamos herencia para que todos compartan la propiedad de expandirse, pero tengan colores 
<img width="806" height="431" alt="image" src="https://github.com/user-attachments/assets/9088e517-de13-4a21-8eb3-f3112b908de3" />


3. El Cuerpo de la Calculadora (Contenedor y Columnas)
dist:
Aquí definimos el aspecto físico. El Container es el "chasis" y la Column es la columna vertebral que apila las filas de botones de arriba hacia abajo.
<img ancho="850" alto="271" alt="imagen" src="https://github.com/user-attachments/assets/f5de9afe-bc6d-4487-ac86-0c8fd2f9f020" />

4. La Distribución de Teclas (Filas y Proporciones)
Cada ft.Row organiza los botones horizontalmente. Flet calcula automáticamente el ancho de cada botón gracias a la propiedad
<img ancho="707" alto="405" alt="imagen" src="https://github.com/user-attachments/assets/6c6917e0-f44a-436f-9b88-3043a5d27836" />

6. Resultado Final (Visualización Completa)
Al ejecutar el código completo, el motor de Flet interpreta estas jerarquías y renderiza una interfaz profesional:

Fondo: Un bloque negro sólido de 350px de ancho.

Pantalla: Texto blanco moderno en la parte superior derecha.

Teclado: Una cuadrícula perfecta de colores:

Gris claro arriba (limpieza y signos).


Gris oscuro en el centro (números).

Naranja en la columna derecha (operadores).

<img ancho="446" alto="361" alt="imagen" src="https://github.com/user-attachments/assets/95620b38-c911-4346-9199-d16b43573bba" />
