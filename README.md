# Apuntes-de-graficacion.
# 1.1 Historia y evolución de la graficación por computadora

La graficación por computadora es la disciplina que estudia la creación, manipulación y representación de imágenes digitales mediante el uso de computadoras. Su desarrollo ha evolucionado junto con el hardware y el software.

# Década de 1950 – Orígenes

Se desarrollan los primeros gráficos en pantallas de osciloscopio.

Uso principalmente científico y militar.

En 1963, Ivan Sutherland desarrolló el sistema Sketchpad en el MIT.

Sketchpad permitió dibujar directamente en pantalla con un lápiz óptico.

Se considera el inicio del Diseño Asistido por Computadora (CAD).

# Década de 1970 – Expansión industrial

Surgen los primeros sistemas CAD comerciales.

Se desarrollan algoritmos fundamentales como el algoritmo de Bresenham.

Se aplica en arquitectura e ingeniería.

# Década de 1980 – Gráficos 3D

Popularización de las computadoras personales.

Aparición de gráficos tridimensionales.

Técnicas de sombreado como Gouraud y Phong.

Comienzan los efectos digitales en cine.

# Década de 1990 – Revolución multimedia

Desarrollo de APIs gráficas como OpenGL y DirectX.

Videojuegos con gráficos 3D avanzados.

Integración de imágenes y animaciones en internet.

 # 2000 – Actualidad

Uso masivo de GPU.

Renderizado en tiempo real.

Realidad Virtual y Realidad Aumentada.

Motores gráficos como Unreal Engine y Unity.

# 1.2 Áreas de aplicación
# VIDEOJUEGOS

Creación de personajes y escenarios.

Renderizado en tiempo real.

# CINE Y ANIMACION 

Efectos especiales.

Animación 3D.

# DISEÑO ASISTIDO POR COMPUTADORA (CAD)

Arquitectura.

Ingeniería.

Diseño industrial.

# SIMULACIÓN

Simuladores de vuelo.

Simulación médica.

Modelado físico.

# VISUALIZACIÓN CIENTIFICA

Representación de datos estadísticos.

Modelos matemáticos.

# INTERFACES GRAFICAS (GUI)
Sistemas operativos.

Aplicaciones móviles.

# REALIDAD VIRTUAL AUMENTADA
Educación.

Entrenamiento profesional.

Entretenimiento.
# 1.3 Aspectos matemáticos de la graficación
La graficación por computadora se basa en matemáticas, especialmente en: 

Sistema cartesiano 2D:
```bash
(X, Y)
```
Sistema tridimensional:
```bash
(X, Y, Z)
```
Ecuación de la recta:
```bash
y = mx + b
```
# Álgebra Lineal

Permite transformar objetos mediante matrices y vectores.

Transformaciones básicas:

 Traslación

 Rotación

 Escalamiento

Reflexión

# Matriz de rotación 2D:
```bash

| cosθ  -senθ |
| senθ   cosθ |
```
# Transformaciones Geométricas

En 3D se utilizan matrices 4x4 con coordenadas homogéneas para mover, girar o escalar objetos.

# Trigonometría
Se usa para:

 Cálculo de ángulos.

 Movimiento circular.

 Dirección de vectores.
 # Cálculo Numérico
Se aplica en:

 Iluminación.

 Sombras.

 Renderizado.

 Interpolaciones.

 # 1.4 Modelos del color: RGB, CMY, HSV y HSL
 
 Los modelos de color son sistemas matemáticos que permiten representar colores en dispositivos digitales.
# Modelo RGB (Red, Green, Blue)

Modelo aditivo basado en luz.

Valores de 0 a 255.

# Ejemplos:
```bash

(255, 0, 0) = Rojo
(0, 255, 0) = Verde
(0, 0, 255) = Azul
(255, 255, 255) = Blanco
(0, 0, 0) = Negro
```
Se usa en pantallas y dispositivos electrónicos.

# Modelo CMY (Cyan, Magenta, Yellow)

Modelo sustractivo utilizado en impresión.

Relación con RGB (valores de 0 a 1):
```bash

C = 1 - R
M = 1 - G
```
# Modelo HSV (Hue, Saturation, Value)

COMPONENTES :
Hue (Matiz): 0° a 360°

Saturation (Saturación): 0% a 100%

Value (Brillo): 0% a 100%

Facilita la selección intuitiva de colores.

# Modelo HSL (Hue, Saturation, Lightness)

Componentes:

Hue (Matiz)

Saturation (Saturación)

Lightness (Luminosidad)

Ejemplo en CSS:
```bash
color: hsl(240, 100%, 50%);
```
Muy utilizado en diseño web.

# CONCLUSIÓN

La graficación por computadora combina matemáticas, programación y tecnología para generar imágenes digitales.

Su evolución ha permitido avances en videojuegos, cine, ingeniería, simulación y realidad virtual.

Los modelos de color son esenciales para representar correctamente imágenes en pantallas y en impresión.

# REFERENCIAS BIBLIOGRÁFICAS

 Angel, E., & Shreiner, D. (2015). Interactive Computer Graphics: A Top-Down Approach with WebGL (7th ed.). Pearson.

 Foley, J. D., van Dam, A., Feiner, S. K., & Hughes, J. F. (1996). Computer Graphics: Principles and Practice (2nd ed.). Addison-Wesley.

 Hearn, D., & Baker, M. P. (2011). Computer Graphics with OpenGL (4th ed.). Pearson.

 Hill, F. S., & Kelley, S. M. (2014). Computer Graphics Using OpenGL (3rd ed.). Prentice Hall.

 Sutherland, I. E. (1963). Sketchpad: A Man-Machine Graphical Communication System. Massachusetts Institute of Technology.

 Shirley, P. (2016). Fundamentals of Computer Graphics (4th ed.). A K Peters/CRC Press.
# AHORA TE MOSTRARE COMO PINTAR UN CUBO CADA CARA DE COLOR 

PRIMERO NOS METEREMOS A BLENDER

<img width="2879" height="1825" alt="image" src="https://github.com/user-attachments/assets/6a8e8eb6-9c1b-4ee6-8ad2-a346c8bc0c4c" />
UNA VEZ AHÍ NOS IREMOS A (EDIT MODE) Y SELECCIONAREMOS ESE APARTADO 

DESPUES NOS IREMOS AL RECUADRO ESTE

<img width="398" height="122" alt="image" src="https://github.com/user-attachments/assets/c224fb17-4a55-40fa-ac3a-3c52cab06f70" />

SELECCIONAREMOS EL TERCER RECUADRO 
<img width="2879" height="1806" alt="image" src="https://github.com/user-attachments/assets/aeb6112c-75c0-4ade-af8b-5a14f8eed3c4" />

Y DESPUES SELECCIONAREMOS UNA CARA DEL CUBO 
DESPUES NOS IREMOS ALA PARTE DONDE DICE(MATERIAL)
<img width="898" height="880" alt="image" src="https://github.com/user-attachments/assets/41b212f6-4c3c-40db-b1eb-c7458122667b" />

NOS IREMOS AL SIGNO DE MAS Y DESPUES DE DAREEMOS A NEW

<img width="598" height="1284" alt="image" src="https://github.com/user-attachments/assets/58d8a05e-2ae5-4959-8be4-d672ff9e27eb" />

TENIENDO EL SIGNO DE MAS Y LA CARA SELECCIONADA

<img width="532" height="1012" alt="image" src="https://github.com/user-attachments/assets/44a8d170-b55e-49e7-8ef2-caf40d26bf7f" />

SELECCIONAMOS EN ESTE ORDEN 
1.ASSIGN
2.DESELECT
3.SELECT

HACIENDO ESO SELECCIONAMOS LA OARTE DONDE DICE NEW Y TE SALDRA ESTO

<img width="605" height="1373" alt="image" src="https://github.com/user-attachments/assets/63c17003-6dfb-497b-98bc-a014edeea156" />

PONES BASE DE COLOR Y PRECIONAS ASI Y TE SALDRA COLORES PARA QUE LOS ESCOJAS 

<img width="564" height="1455" alt="image" src="https://github.com/user-attachments/assets/6c8d4ee0-e3df-48c2-8efb-53bee107afa3" />

YA AHI ESCOGES EL COLOR QUE QUIERAS Y LE PRECIONAS EN CUALQUIER PARTE DEL FONDO NEGRO 
LUEGO TE IRAS EN LA PARTE DE ARRIBA Y PRECIONARAS EN ESTA PARTE LA TERCERA OPCION DEL RECUADRO

<img width="627" height="833" alt="image" src="https://github.com/user-attachments/assets/49bf8ab1-b54c-4822-8d2c-fb31e16189b3" />

ASI COMO VEZ LA IMAGEN 

UNA VEZ ECHO ESO SE PINTARA LA CARA QUE SELECCIONASTE

ASI TIENE QUE VERSE

<img width="2879" height="1815" alt="image" src="https://github.com/user-attachments/assets/26253cd1-d57b-43ae-a2d5-69440bd6b68b" />

# 1.5. Representación y trazo de líneas y polígonos.
```bash

import bpy
import math

# Limpiar la escena antes de empezar
bpy.ops.object.select_all(action='SELECT')
bpy.ops.object.delete()

def crear_poligono_2d(nombre, lados, radio):
    # Crear una nueva malla y un nuevo objeto
    malla = bpy.data.meshes.new(nombre)
    objeto = bpy.data.objects.new(nombre, malla)

    # Vincular el objeto a la escena actual
    bpy.context.collection.objects.link(objeto)

    vertices = []
    aristas = []

    # Cálculo de vértices usando coordenadas polares a cartesianas
    for i in range(lados):
        angulo = 2 * math.pi * i / lados
        x = radio * math.cos(angulo)
        y = radio * math.sin(angulo)
        vertices.append((x, y, 0))  # Z = 0 para mantenerlo en 2D

    # Definir las conexiones (aristas) entre los vértices
    for i in range(lados):
        aristas.append((i, (i + 1) % lados))

    # Definir la cara del polígono
    caras = [list(range(lados))]

    # Cargar los datos en la malla
    malla.from_pydata(vertices, aristas, caras)
    malla.update()

# Llamada a la función: Un hexágono de radio 5
crear_poligono_2d("Poligono2D", lados=6, radio=5)
```
# ¿Qué hace este código en general?

Este código crea una figura geométrica regular (por ejemplo un triángulo, cuadrado, pentágono, hexágono, etc.) dentro de Blender usando matemáticas.

En este caso específico, crea un hexágono porque se le indican 6 lados.

# Importaciones
```bash
import bpy
import math
```
# Aquí estamos trayendo dos herramientas:

bpy → Es el módulo que permite controlar Blender con código. Sin esto no podríamos crear objetos.

math → Nos da funciones matemáticas como:

pi (π)

cos() (coseno)

sin() (seno)

Estas funciones son necesarias para calcular los puntos del polígono.
# Limpiar la escena
```bash

bpy.ops.object.select_all(action='SELECT')
bpy.ops.object.delete()
```

Esto hace dos cosas:

Selecciona todos los objetos que estén en la escena.
Los elimina.
¿Por qué se hace esto?
Para empezar desde cero y que no haya otros objetos molestando.

# La función principal
```bash

def crear_poligono_2d(nombre, lados, radio):
```
# Aquí estamos creando una función.

Una función es un bloque de código que hace algo específico cuando lo llamamos.

Esta función necesita tres cosas:

nombre → Cómo se llamará el objeto en Blender.

lados → Cuántos lados tendrá la figura.

radio → Qué tan grande será (distancia del centro a cada esquina).

# Crear la malla y el objeto
```bash

malla = bpy.data.meshes.new(nombre)
objeto = bpy.data.objects.new(nombre, malla)
bpy.context.collection.objects.link(objeto)
```
# En Blender, todo objeto 3D necesita una malla.

Primero se crea la malla (estructura vacía).
Luego se crea el objeto que usa esa malla.
Finalmente se agrega a la escena para que sea visible.

Si no lo enlazamos a la colección, no aparecería.

# Crear listas para guardar datos
```bash

vertices = []
aristas = []
```
#Aquí estamos creando dos listas vacías.

vertices guardará los puntos (esquinas).

aristas guardará las líneas que conectan esos puntos.

Piensa en los vértices como clavos y en las aristas como hilos que los conectan.

 # Calcular los vértices (la parte matemática)
```bash

 for i in range(lados):
    angulo = 2 * math.pi * i / lados
    x = radio * math.cos(angulo)
    y = radio * math.sin(angulo)
    vertices.append((x, y, 0))
```

Aquí está lo más importante.

¿Qué está pasando?
Queremos que los puntos estén perfectamente distribuidos en un círculo.

Entonces:
Dividimos el círculo completo (360° o 2π radianes) entre el número de lados.

Así cada punto queda separado uniformemente.

La fórmula:

angulo = 2πi / lados

Después usamos:

x = radio * cos(angulo)
y = radio * sin(angulo)

Eso convierte coordenadas circulares en coordenadas normales (X, Y).

El 0 al final significa que todos los puntos estarán en el plano horizontal (2D).

# Crear las aristas (conectar puntos)
```bash

for i in range(lados):
    aristas.append((i, (i + 1) % lados))
```
Aquí conectamos cada punto con el siguiente.

El símbolo % (módulo) es importante.

Sirve para que cuando llegue al último punto, lo conecte de nuevo con el primero y así cerrar la figura.

Si no hicieras eso, quedaría abierta.

# Crear la cara (relleno)
```bash

caras = [list(range(lados))]
```
Esto le dice a Blender:

"Une todos estos puntos en una sola superficie".

# Cargar todo en la malla 
```bash

malla.from_pydata(vertices, aristas, caras)
malla.update()
```
Aquí finalmente se le pasa toda la información a Blender:

Los puntos

Las líneas

La superficie

Y se actualiza la malla para que aparezca.

# Llamar a la función
```bash

crear_poligono_2d("Poligono2D", lados=6, radio=5)
```
Esto ejecuta todo lo anterior.

Le estamos diciendo:

Nombre: "Poligono2D"

Lados: 6

Radio: 5

Resultado: se crea un hexágono regular centrado en el origen.

# te dejo una imagen
<img width="2879" height="1827" alt="image" src="https://github.com/user-attachments/assets/7866215d-7525-4241-9329-d02aa9787701" />


# FLOR DE VIDA
```bash

import bpy
import math

# Limpiar escena
bpy.ops.object.select_all(action='SELECT')
bpy.ops.object.delete()

# Parámetros de la figura
radio = 3
angulo_actual = 0
paso_angular = 20

# 1. Círculo central
bpy.ops.mesh.primitive_circle_add(radius=radio, location=(0, 0, 0), vertices=64)


while angulo_actual < 360:
    
    x = radio * math.cos(math.radians(angulo_actual))
    y = radio * math.sin(math.radians(angulo_actual))
    
    bpy.ops.mesh.primitive_circle_add(radius=radio, location=(x, y, 0), vertices=64)
    
    # Actualización de estado
    angulo_actual += paso_angular
```

Este código está escrito en Python usando la API bpy de Blender, y sirve para generar varios círculos distribuidos alrededor de un círculo central formando un patrón circular.

# 1. Importación de librerías
```bash

import bpy
import math
```

bpy → Es la librería de Blender que permite crear y manipular objetos dentro de la escena.

math → Se usa para realizar cálculos matemáticos, especialmente funciones trigonométricas como seno y coseno.

# 2. Limpiar la escena
```bash

bpy.ops.object.select_all(action='SELECT')
bpy.ops.object.delete()
```

Primero se seleccionan todos los objetos de la escena y luego se eliminan.

Esto asegura que la escena esté vacía antes de crear las nuevas figuras.

# 3. Parámetros de la figura
radio = 3
angulo_actual = 0
paso_angular = 20

radio = 3 → Define el tamaño del círculo.

angulo_actual = 0 → Ángulo inicial desde donde empieza el patrón.

paso_angular = 20 → Cantidad de grados que avanzará en cada repetición del ciclo.

Esto significa que se creará un círculo cada 20 grados hasta completar los 360°.

# 4. Círculo central
```bash

bpy.ops.mesh.primitive_circle_add(radius=radio, location=(0, 0, 0), vertices=64)
```

Se crea un círculo en el centro de la escena:

radius=radio → Tamaño del círculo.

location=(0, 0, 0) → Posición en el origen.

vertices=64 → Cantidad de vértices (más vértices = círculo más suave).

# 5. Ciclo while (Generación del patrón circular)
```bash

while angulo_actual < 360:
```

Este ciclo se repetirá mientras el ángulo sea menor a 360 grados.

Eso garantiza que se complete toda la circunferencia.

# 6. Cálculo de coordenadas
x = radio * math.cos(math.radians(angulo_actual))
y = radio * math.sin(math.radians(angulo_actual))

Aquí se aplica trigonometría:

math.radians() convierte grados a radianes (porque Python trabaja en radianes).

cos() calcula la coordenada en X.

sin() calcula la coordenada en Y.

Fórmula usada:

x = r cos(θ)
y = r sen(θ)

Esto permite posicionar cada nuevo círculo exactamente sobre la circunferencia del círculo central.

# 7. Crear círculo en la nueva posición
```bash

bpy.ops.mesh.primitive_circle_add(radius=radio, location=(x, y, 0), vertices=64)
```

Se crea un nuevo círculo:

Con el mismo radio.

En la posición calculada.

En el plano Z = 0.

# 8. Actualización del ángulo
angulo_actual += paso_angular

Aquí se aumenta el ángulo en 20 grados en cada iteración.

Si el paso es 20°:
```bash

360 / 20 = 18 círculos
```

Por lo tanto, se crearán 18 círculos alrededor del central.

# TE DEJO UNA PEQUEÑA DEMOSTRACION


https://github.com/user-attachments/assets/ee69d78f-10f3-46fc-99df-ce6d098ceb44



