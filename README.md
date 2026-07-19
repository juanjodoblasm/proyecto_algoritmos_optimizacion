# Proyecto Algoritmos de Optimización — Sesiones de doblaje

Trabajo práctico de la asignatura **Algoritmos de Optimización**, Máster Universitario en Inteligencia Artificial (VIU).

## Autores

- Juan José Doblas Martínez
- Christian Dario Barahona Pesantes

## Problema elegido

**Problema 1: Organizar sesiones de doblaje.**

Se precisa coordinar el doblaje de una película. Los actores deben coincidir en el estudio en las tomas en las que sus personajes aparecen juntos. Todos los actores cobran lo mismo por cada día que se desplazan al estudio, independientemente del número de tomas grabadas ese día, y no se pueden grabar más de 6 tomas por día. El objetivo es planificar las sesiones por día minimizando el gasto total en servicios de actores (es decir, minimizando el número de días de grabación necesarios).

**Datos de partida:**
- 10 actores
- 30 tomas
- Matriz binaria actor/toma (1 = el actor participa en la toma, 0 = no participa)

## Estructura del repositorio

```
├── README.md
├── LICENSE
├── .gitignore
└── SEMINARIO/
    ├── seminario.ipynb        # Notebook final con la resolución completa
    └── data_doblaje.csv       # Matriz de actores/tomas usada como entrada
```

El notebook final se sube a la carpeta `SEMINARIO/` al terminar el trabajo, siguiendo la estructura pedida en el enunciado del trabajo práctico.

## Cómo trabajar con el notebook

El notebook sigue el formato de la plantilla oficial de la asignatura (pregunta + respuesta en Markdown + código Python), y puede abrirse directamente en Google Colab para ejecutarlo y editarlo de forma colaborativa.

## Licencia

Este proyecto está bajo licencia MIT — ver el archivo [LICENSE](LICENSE) para más detalles.
