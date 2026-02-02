# Tarea (c+d+e) · Edge, Fog, Mist y Cloud (DAW 1º)

## 🅲 Tarea C — Edge Computing y relación con Cloud

**Definición (3–5 líneas):**  
El *Edge Computing* es un modelo de computación donde el procesamiento de datos se realiza cerca del lugar donde se generan, como sensores, dispositivos IoT o equipos locales. Su objetivo principal es reducir la latencia, el uso de ancho de banda y la dependencia de servidores remotos. Permite respuestas más rápidas y mayor eficiencia en sistemas en tiempo real.

**Relación Edge ↔ Cloud (5–8 líneas):**  
Edge y Cloud Computing no se sustituyen, sino que se complementan. Edge se encarga del procesamiento inmediato y crítico cerca del usuario o dispositivo, mientras que la Cloud gestiona el almacenamiento masivo, análisis avanzado y aprendizaje automático. Los datos procesados en el Edge pueden enviarse a la Cloud para análisis histórico o centralizado. La Cloud también se usa para administrar, actualizar y coordinar múltiples nodos Edge. Juntas permiten sistemas escalables, rápidos y eficientes.

**Ejemplo real:**  
En vehículos autónomos, los sensores procesan datos en el Edge para tomar decisiones inmediatas (frenar, girar), mientras que la Cloud analiza grandes volúmenes de datos para mejorar algoritmos y mapas.

**Fuentes oficiales (mín. 2):**
- https://www.ibm.com/topics/edge-computing  
- https://aws.amazon.com/what-is/edge-computing/

---

## 🅳 Tarea D — Fog vs Mist (niveles y zonas de aplicación)

**Definición Fog (2–4 líneas):**  
Fog Computing es una capa intermedia entre el Edge y la Cloud que distribuye procesamiento, almacenamiento y control más cerca de los dispositivos finales. Reduce la carga de la Cloud y mejora la latencia en sistemas distribuidos.

**Definición Mist (2–4 líneas):**  
Mist Computing lleva el procesamiento directamente al dispositivo final, como sensores o microcontroladores. Se encarga de tareas muy simples y rápidas, con recursos extremadamente limitados.

**Esquema (ASCII o Mermaid recomendado):**

<img width="1024" height="1536" alt="ChatGPT Image 2 feb 2026, 12_24_33" src="https://github.com/user-attachments/assets/0502f419-fce9-4c3f-b6c2-0a847430478c" />


**Zonas de aplicación (qué hace cada capa):**
- **Mist** → Procesamiento mínimo en sensores (filtrado básico, detección simple).
- **Edge** → Análisis en tiempo real y decisiones inmediatas.
- **Fog** → Coordinación de varios nodos Edge y procesamiento intermedio.
- **Cloud** → Almacenamiento masivo, análisis avanzado y gestión global.

---

## 🅴 Tarea E — Ventajas de la Cloud en sistemas conectados

Incluye mínimo 3 ventajas (recomendado 5), con explicación + ejemplo.

1) **Ventaja:** Escalabilidad  
   **Explicación:** La Cloud permite aumentar o reducir recursos según la demanda sin cambiar infraestructura física.  
   **Ejemplo:** Una aplicación IoT puede gestionar más sensores durante horas punta sin interrupciones.

2) **Ventaja:** Almacenamiento masivo  
   **Explicación:** Ofrece gran capacidad para guardar datos históricos de forma segura y accesible.  
   **Ejemplo:** Guardar años de datos de sensores industriales para análisis.

3) **Ventaja:** Acceso global  
   **Explicación:** Los datos y servicios están disponibles desde cualquier lugar con conexión a Internet.  
   **Ejemplo:** Supervisar una fábrica desde otro país en tiempo real.

4) **Ventaja:** Alta disponibilidad  
   **Explicación:** Los proveedores Cloud ofrecen redundancia y tolerancia a fallos.  
   **Ejemplo:** Un sistema sigue funcionando aunque falle un servidor.

5) **Ventaja:** Actualizaciones centralizadas  
   **Explicación:** Permite gestionar y actualizar software de forma remota.  
   **Ejemplo:** Actualizar firmware de miles de dispositivos IoT desde un panel web.

**Fuente oficial (mín. 1):**
- https://cloud.google.com/learn/what-is-cloud-computing

---

## 📚 Fuentes (enlaces oficiales)

- https://www.ibm.com/topics/edge-computing  
- https://aws.amazon.com/what-is/edge-computing/  
- https://www.cisco.com/c/en/us/solutions/internet-of-things/what-is-fog-computing.html  
- https://cloud.google.com/learn/what-is-cloud-computing  


