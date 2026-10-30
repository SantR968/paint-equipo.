# Paint

Programa de dibujo desarrollado en Python con Turtle y Free Python Games, basado en el código original de Grant Jenks.

## Objetivo

Dibujar figuras geométricas mediante dos clics y seleccionar sus colores con el teclado.

## Requisitos

- Python 3.
- Turtle disponible en la instalación de Python.
- Biblioteca Free Python Games.

## Instalación y ejecución

Desde la carpeta del repositorio, crear y activar un ambiente virtual en Windows:

```bat
py -m venv .venv
.venv\Scripts\activate
python -m pip install freegames
python paint.py
```

## Controles

Hacer clic dentro de la ventana para que reciba las instrucciones del teclado.

### Figuras

- `l`: línea.
- `s`: cuadrado.
- `c`: círculo.
- `r`: rectángulo.
- `t`: triángulo.

### Colores

- `K`: negro.
- `W`: blanco.
- `G`: verde.
- `B`: azul.
- `R`: rojo.
- `p`: morado.

Las mayúsculas y minúsculas deben respetarse de acuerdo con las teclas registradas en el código.

Después de seleccionar una figura, hacer dos clics para definir su ubicación y dimensiones. Para el círculo, el primer clic establece el centro y el segundo determina el radio.

## Modificaciones

### Santiago Román Villalobos Bolaños

- Agregó el color morado mediante la tecla `p`.
- Implementó la función para dibujar círculos.
- Calculó el radio como la distancia entre los dos puntos seleccionados.
- Utilizó `turtle.circle()` para evitar confundir la función de Turtle con la función `circle()` del programa.
- Evitó dibujar círculos de radio cero.

### Compañera de equipo

- Completó la función para dibujar rectángulos.
- Completó la función para dibujar triángulos.

## Comprobación del funcionamiento

- Presionar `p` y comprobar que las figuras se dibujen en morado.
- Seleccionar el círculo y hacer dos clics separados para verificar su centro y radio.
- Probar el rectángulo y el triángulo con diferentes puntos.
- Comprobar que las líneas y los cuadrados originales sigan funcionando.

## Trabajo colaborativo

Se utilizó un repositorio principal y un fork, sin acceso de colaborador. El primer commit contiene el código original y las funcionalidades se registraron en commits separados. Los cambios del fork se integraron mediante pull requests.

## Código de referencia

Grant Jenks, Free Python Games:
https://grantjenks.com/docs/freegames/paint.html
