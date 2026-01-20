# The Head of the Table

## 🎮 Proyecto Integrador con Unreal Engine 5  
🧠 Inteligencia Artificial • 🎨 Materiales • 🚇 Juego Final: _EL ANDÉN 7_

Este repositorio reúne el trabajo desarrollado en las materias  
**Motores Comerciales II** y **Programación de Materiales**, integradas en el
proyecto final del cuatrimestre: **_EL ANDÉN 7_**.

El objetivo de este proyecto es demostrar la integración de **Inteligencia Artificial,
programación de materiales y diseño de gameplay** dentro de Unreal Engine 5,
utilizando flujos y herramientas profesionales.

---

## 🧠 1. Motores Comerciales II — Inteligencia Artificial

En esta materia se desarrollaron sistemas de **IA** utilizando las herramientas
nativas de Unreal Engine 5, implementadas completamente con **Blueprints**.

### 🔧 Herramientas de IA utilizadas
- **AIController:** control central del comportamiento del agente  
- **Behavior Trees:** estructura de toma de decisiones  
- **Blackboards:** almacenamiento de datos para la IA  
- **Tasks:** ejecución de acciones específicas  
- **Decorators:** condiciones para el flujo de comportamiento  
- **Services:** actualización constante de información  
- **EQS (Environment Query System):** selección de posiciones óptimas en el entorno  

### 🎯 Resultados y habilidades demostradas
- Diseño de **IA modular, reutilizable y escalable**  
- Manejo de estados, decisiones y percepción  
- Integración de IA con el entorno y eventos del juego  
- Organización lógica mediante Behavior Trees  

---

## 🎨 2. Programación de Materiales — Shaders

Se desarrollaron distintos **materiales visuales** utilizando el **Material Editor**
de Unreal Engine, trabajando con materiales base, instancias y efectos avanzados.

### 🧪 Materiales desarrollados
- **Agua:** movimiento, refracción y reflexión  
- **Hielo:** transparencia, distorsión y detalle superficial  
- **Partículas:** integración con Niagara  
- **Cel Shading:** estilo visual tipo caricatura/anime  
- **Halftone Shader:** efecto tipo cómic  
- **Warp / Distorsión:** efectos mediante ruido procedural  

### 🛠 Técnicas utilizadas
- Material Editor (sistema de nodos)  
- Material Functions  
- Material Instances  
- Material Parameter Collections  
- Optimización de shaders para rendimiento  

### 🎯 Habilidades demostradas
- Creación de materiales complejos y organizados  
- Integración visual con gameplay  
- Uso avanzado del sistema de materiales de Unreal  

---

## 🚇 3. Proyecto Integrador — _EL ANDÉN 7_

**_EL ANDÉN 7_** es un juego corto de **horror liminal**, diseñado para integrar
IA, materiales y diseño de interacciones.

El proyecto se inspira en **_The Exit 8_** y en conceptos de espacios liminales
como los Backrooms.

### 🎮 Concepto de juego
El jugador recorre un pasillo de metro que se repite continuamente.
En cada ciclo puede aparecer una **anomalía**.

La mecánica principal se basa en la observación:

- Si el jugador detecta una anomalía → **retroceder**
- Si todo parece normal → **avanzar**

El juego pone a prueba la **memoria visual, la atención al detalle
y la tensión psicológica**.

---

## 🔁 Funcionamiento general del juego
1. El jugador entra al pasillo  
2. Observa el entorno cuidadosamente  
3. Decide si existe una anomalía  
4. Una decisión correcta permite avanzar  
5. Un error reinicia el progreso  
6. El ciclo se repite hasta alcanzar el objetivo  

---

## 🧱 Organización del Proyecto

```text
/AI
  /BehaviorTrees
  /Blackboards
  /Tasks
  /Decorators
  /AIControllers

/Materials
  /BaseMaterials
  /Instances
  /Effects
  /Functions

/Anden7
  /Blueprints
  /Anomalies
  /UI
  /Maps
```

---

## 🔧 Tecnologías utilizadas
- Unreal Engine 5  
- Blueprints  
- Behavior Trees  
- Blackboards  
- EQS  
- Niagara  
- Material Editor  
- Material Instances  
- Material Parameter Collections  
- Lumen  

---

## 📂 Estado actual del proyecto
- Proyecto en desarrollo  
- Expansión del sistema de anomalías  
- Mejora visual de materiales y efectos  
- Integración completa de IA, visuales y gameplay  

---

## 👤 Autor
**Kevin Jair Chávez Castro**  
Proyecto académico y de portafolio profesional  
Universidad Cuauhtémoc, Plantel Querétaro
