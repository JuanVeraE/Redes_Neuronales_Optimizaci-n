# Proyecto de Optimización Numérica y Combinatoria

## Descripción
Este proyecto aborda problemas de optimización numérica y combinatoria mediante diversos métodos, incluyendo descenso por gradiente, algoritmos evolutivos y optimización basada en heurísticas. El proyecto se divide en dos partes principales:

### Parte 1: Optimización Numérica
Se optimizan dos funciones de prueba entre las siguientes opciones:
- Función de Rosenbrock
- Función de Rastrigin

Las funciones seleccionadas se optimizan en dos y tres dimensiones utilizando:
1. **Método de descenso por gradiente** con condiciones iniciales aleatorias.
2. **Métodos heurísticos**, incluyendo algoritmos evolutivos, optimización de partículas y evolución diferencial.

El proceso de optimización será visualizado mediante un GIF animado o un video que muestre tanto el descenso por gradiente como el proceso heurístico. Además, se analizarán los resultados en términos del valor final de la función objetivo y el número de evaluaciones requeridas.

### Parte 2: Optimización Combinatoria
Se resuelve el problema del viajante de comercio en el contexto de un vendedor que debe recorrer las capitales de los 32 estados de México.

Para ello, se emplean dos métodos:
1. **Colonias de hormigas**
2. **Algoritmos genéticos**

El costo del recorrido se calcula considerando:
- El valor de la hora del vendedor (parámetro a estudiar).
- El costo de los peajes.
- El costo del combustible (según el vehículo elegido para el recorrido).

El mejor recorrido obtenido se representará gráficamente en un mapa de México y se animará mediante un GIF o un video.

---

## Instalación
Para ejecutar el proyecto, asegúrese de tener instalado Python y los paquetes necesarios. Puede instalar todas las dependencias ejecutando:

```bash
pip install -r requirements.txt
```

---

## Uso
1. **Optimización numérica:** Ejecute los scripts correspondientes a la optimización de las funciones seleccionadas.
2. **Optimización combinatoria:** Ejecute los algoritmos de colonias de hormigas o algoritmos genéticos para encontrar el mejor recorrido.
3. **Visualización:** Genere y analice las animaciones o videos producidos para observar los procesos de optimización.

---

## Autores
Este proyecto fue desarrollado como parte de una actividad académica por Daniel Daza Macias y Juan Manuel Vera Echeverri.

