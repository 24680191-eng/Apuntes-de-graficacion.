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
