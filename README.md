# The-Head-of-the-Table
# 🎮 Proyecto Integrador con Unreal Engine 5  
## 🧠 Inteligencia Artificial • 🎨 Materiales • 🚇 Juego Final: *EL ANDÉN 7*

Este repositorio reúne todo el trabajo desarrollado en dos materias:  
**Motores Comerciales II** y **Programación de Materiales**, junto con el **proyecto integrador del cuatrimestre**: *EL ANDÉN 7*.  

El objetivo de este README es explicar de manera clara y profesional lo que se creó, cómo funciona y qué habilidades se demostraron.  
---

# 🧠 1. Motores Comerciales II — Inteligencia Artificial (IA)

En esta materia aprendí a crear comportamientos de **IA** usando las herramientas nativas de Unreal Engine 5.  
Todo está desarrollado con **Blueprints**.

### 🔧 Herramientas de IA utilizadas
- 🤖 **AIController:** cerebro del personaje controlado por IA  
- 🧩 **Behavior Trees:** flujo de decisiones de la IA  
- 📒 **Blackboards:** tabla donde la IA guarda información  
- 🛠️ **Tasks:** acciones concretas (caminar, esperar, buscar)  
- 🔍 **Decorators:** condiciones que determinan el comportamiento  
- 🔄 **Services:** actualizan datos constantemente  
- 📡 **EQS (Environment Query System):** IA busca lugares óptimos en el mapa  
- 🔷 **Blueprints:** lógica visual para crear comportamientos completos  

### 🎯 Resultados y habilidades demostradas
- Creación de **IA modular, reutilizable y escalable**  
- Manejo de percepciones, decisiones y estados  
- Integración de IA con el entorno y con eventos visuales  
- Organización lógica mediante Behavior Trees  

---

# 🎨 2. Programación de Materiales — Shaders

En esta materia desarrollé distintos **materiales visuales** usando el Material Editor de Unreal.  
Se trabajaron materiales base, instancias y efectos avanzados.

### 🧪 Materiales creados
- 🌊 **Agua:** movimiento, refracción, reflexión  
- ❄️ **Hielo:** transparencia, distorsión y microdetalles  
- ✨ **Partículas:** usando Niagara + materiales  
- 🎌 **Cel Shading:** estilo caricatura/anime  
- 🖨️ **Halftone Shader:** efecto de puntos tipo cómic  
- 🔮 **Warp/Distorsión:** ondulaciones usando ruido procedural  

### 🛠️ Técnicas utilizadas
- Material Editor (nodos visuales)  
- Material Functions (funciones reutilizables)  
- Material Instances (variaciones fáciles sin duplicar)  
- Material Parameter Collections (control global desde Blueprint)  
- Optimización del shader para buen rendimiento  

### 🎯 Habilidades demostradas
- Creación de materiales complejos y entendibles  
- Capacidad de combinar materiales con gameplay  
- Uso profesional del Material Editor  

---

# 🚇 3. Proyecto Integrador — *EL ANDÉN 7*

*EL ANDÉN 7* es un juego corto de **horror liminal**, diseñado para integrar IA, materiales y diseño de interacciones.  
Se inspira en *The Exit 8* y en espacios como los Backrooms.

### 🎮 Concepto general
El jugador camina por un pasillo de metro que se repite infinitamente.  
En cada repetición puede aparecer una **anomalía**.  
El jugador debe decidir:

- Si ve **algo fuera de lugar** → 🔙 **Retrocede**  
- Si todo está **normal** → ⏩ **Avanza**

Es un juego de **observación**, **memoria visual** y **tensión psicológica**.

---

# 🔁 Cómo funciona el juego (explicado simple)
1. 🚶 Entras al pasillo  
2. 👁️ Observas con atención  
3. ❓ Decides si hay anomalía o no  
4. ✔️ Acierto → avanzas  
5. ✖️ Error → reinicias el progreso  
6. 🔁 Repites hasta completar la meta de aciertos  

---

# 🧱 Organización del Proyecto (Estructura)

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

# 🔧 Tecnologías utilizadas

🎮 Unreal Engine 5  
🔷 Blueprints  
🤖 Behavior Trees  
📒 Blackboards  
📡 EQS  
✨ Niagara  
🎨 Material Editor  
🧩 Material Instances  
🗂️ Material Parameter Collections  
💡 Lumen  

# 📂 Estado actual del proyecto

📌 En desarrollo  
🚧 Añadiendo nuevas anomalías  
🎨 Mejorando materiales y efectos  
🎯 Integrando completamente IA + visuales + gameplay  

# 👤 Autor

**Kevin Chávez**  
Proyecto académico y de portafolio profesional  
Universidad Cuauhtémoc, Plantel Querétaro  


