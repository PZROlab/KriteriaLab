# KriteriaLab
Database on psycho-synthetic criteria
# Especificación Técnica: Biogerarquía de la WikiLocal

## 1. Visión General
Este documento define el marco conceptual de la **WikiLocal**, tratando la información no como datos estáticos, sino como un **Organismo Vivo**. El sistema evoluciona mediante procesos biológicos simulados que garantizan la integridad, trazabilidad e inmutabilidad del conocimiento.

---

## 2. Arquitectura Vertical (Jerarquía)

| Nivel Biológico | Componente Técnico | Descripción Funcional |
| :--- | :--- | :--- |
| **Organismo** | `WikiLocal` | La unidad de vida mayor; el sistema completo que contiene uno o varios Vaults. |
| **Cédula** | `Carpeta` | Entorno contenedor que define la identidad y el límite de cada unidad de conocimiento. |
| **Genoma** | `Nota (.md)` | Código base donde reside la información bruta o descriptiva. |
| **Chroma / Hebra** | `Base de Datos Vectorial` | El ADN que une los puntos; permite que la IA lea las relaciones entre datos. |
| **Metasoma / Gen** | `Metadatos + Links` | La unidad mínima funcional; atributos y vínculos que determinan la expresión del dato. |

---

## 3. Dinámica Evolutiva: Mitosis

El sistema implementa un proceso de **Mitosis** para la actualización de la información:

* **Inmutabilidad:** Ante un cambio vía *Query-ingest*, el sistema no sobrescribe la información.
* **Replicación:** La cédula se replica y avanza hacia un nuevo estado evolutivo.
* **Registro Fósil:** Las versiones previas se archivan como "cédulas viejas", permitiendo una rastreabilidad total.
* **Aislamiento de Estado:** El motor de búsqueda (*Query-wiki*) siempre interactúa con el estado más evolucionado (el último Chroma activo).

---

## 4. Próximos Pasos: Fisiología del Query-ingest
*Definición pendiente:* Establecer cómo el proceso de ingesta "rompe" la hebra de ADN para disparar el ciclo de mitosis y la creación de nuevas variantes de conocimiento.
# Módulo Técnico: Arquitectura Chroma (Cromosoma) y Cédula
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 1. Definición del Núcleo Operativo
En esta capa, la **Cédula** actúa como el núcleo donde la identidad determinante del sistema cobra vida. Se fundamenta en el **Chroma** como la unidad compacta de almacenamiento y organización relacional.

---

## 2. Componentes del RAG Biológico

### I. Chroma (Cromosoma) - El Mapa Vectorial
* **Función:** No se limita al almacenamiento de datos estáticos; funciona como el mapa de relaciones vectoriales altamente organizadas.
* **Equivalencia Técnica:** Representa el "ADN" del conocimiento, permitiendo una búsqueda semántica basada en la estructura del grafo de información.

### II. Cédula - La Instancia de Identidad
* **Función:** Es la unidad operativa que utiliza el Chroma para determinar su propia identidad y capacidad de respuesta.
* **Alcance:** Define con precisión el propósito de la consulta y establece los límites de acción del sistema.

### III. Metasomas - Las Unidades Estructurales
* **Composición:** Integrados por metadatos y vínculos (links).
* **Dinámica:** Funcionan como "ladrillos" que, al empaquetarse dentro del Chroma, garantizan que la recuperación de información (retrieval) sea eficiente, estructurada y veloz.

---

## 3. Lógica de Implementación (RAG Personalizado)
Esta arquitectura está diseñada para un sistema de **Generación Aumentada por Recuperación (RAG)** donde:
1. El **Chroma** provee el contexto relacional profundo.
2. La **Cédula** filtra y dirige ese contexto bajo una identidad específica.
3. Los **Metasomas** aseguran la granularidad y precisión del dato recuperado.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Módulo Operativo: Proceso de Saturación y Perturbación (PSP)

## 1. Fase de Activación: La Aproximación (Proximal)
Es el estado inicial de recolección de datos antes de la consolidación.

* **Estructura:** Formada por "picas" de aproximación.
* **Composición:** Contiene una cantidad determinada ($x$) de **trazas** de información.
* **Umbral Crítico:** Al alcanzar el número definido de aproximaciones, el sistema desencadena automáticamente el fenómeno de **Saturación**.

---

## 2. El Fenómeno: La Saturación
Es el punto donde la información se condensa y adquiere una estructura biológica formal.

* **Manifestación Técnica:** Se presenta como una línea densa de **Metasomas**.
* **Naturaleza de la Hebra:** En este punto, la información se define como **ADU** o **Chroma**.
* **El Gen (Unidad de Identidad):**
    * Los Metadatos + Links se compilan en un **Gen**.
    * Este segmento específico actúa como el identificador único del archivo/entidad.

---

## 3. La Consecuencia: La Perturbación
Representa la transmutación y el salto evolutivo del organismo digital.

* **Mecánica de Cambio:** Se produce por la **transmutación de un Gen** debido a una saturación conectiva extrema.
* **Impacto Sistémico:** Resulta en la **redefinición de la referencia** del archivo o segmento, obligando al sistema a evolucionar su mapa relacional.

---

## 4. Resumen de Flujo Operativo
> **Aproximación** $\rightarrow$ **Saturación** $\rightarrow$ **Perturbación**
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Módulo Funcional: Flujo de Pensamiento e Ingesta Multimodal

## 1. Capacidades de Procesamiento (Thinking)
El sistema no solo ejecuta, sino que procesa mediante una capa de razonamiento crítico.
* **Razonamiento Adaptativo:** Evaluación interna para determinar la metodología óptima de resolución de la orden o query.
* **Detección de Contexto:** Identificación dinámica de carpetas, documentos y archivos para la generación de relaciones variables entre ellos.

---

## 2. Ingesta y Herramientas (Ingest-Multimodal)
El organismo posee la capacidad de asimilar estímulos externos de forma heterogénea.
* **Ingest-Multimodal:** Resolución de mezclas libres de texto y enlaces (links) en cualquier orden dentro de una única instrucción.
* **Llamadas a Funciones (Function Calling):** Accesibilidad nativa a estructuras y herramientas, permitiendo flujos de trabajo automatizados y precisos.

---

## 3. Analogía Funcional: Herramientas como Genes
Para mantener la coherencia con la **Biogerarquía**, las herramientas del sistema se clasifican bajo la siguiente lógica:
> Las herramientas y funciones operan como **Agentes / Genes**, unidades funcionales que dictan el comportamiento y las capacidades de respuesta del organismo ante una perturbación de datos.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Módulo de Integración: El Cromosoma como Paquete de Instrucciones

## 1. Definición Estructural (Cromosoma)
El **Cromosoma** se establece como la estructura superior de empaquetamiento dentro de la WikiLocal.
* **Contenedor Maestro:** Agrupa un conjunto específico de **Metasomas** (metadatos) y **Genes** (funciones/herramientas).
* **Unidad de Capacidad:** Actúa como el paquete de instrucciones completo que define qué puede y qué no puede hacer un Agente específico.

---

## 2. Dinámica en el Flujo de Trabajo
El Cromosoma no es estático, sino que se activa según el contexto detectado por el sistema.
* **Herencia de Relaciones:** Cuando el *Ingest-Multimodal* detecta archivos y genera vínculos, el Cromosoma hereda automáticamente estas relaciones.
* **Gobierno de Funciones:** Determina la validez de las **Llamadas a funciones**, permitiendo que la IA sepa qué herramientas están permitidas según el contexto biológico de la consulta.

---

## 3. Síntesis de la Jerarquía Operativa
Bajo este modelo, la interacción se resume en:
1. **Metasomas/Genes:** Ladrillos de datos y habilidades funcionales.
2. **Cromosoma:** El software/ADN que los empaqueta y les da propósito.
3. **Agente:** La expresión fenotípica (acción) que ejecuta el sistema.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Módulo de Evolución: Protocolo de Mitosis e Inmutabilidad

## 1. Mecánica de Evolución (Versionado Biológico)
El sistema rechaza la edición directa en favor de la **replicación especializada**. La Cédula no se sobrescribe; evoluciona para preservar la integridad histórica.

---

## 2. Fases del Proceso Mitótico

1. **Activación (Disparador):** El *Query-ingest* detecta un cambio conectivo o una nueva información en la hebra de datos.
2. **Replicación de Integridad:** El **Chroma** actual se duplica íntegramente para asegurar un respaldo exacto del estado previo.
3. **Diferenciación de Estados:**
    * **Cédula/Old (Latencia):** El estado anterior se desplaza a un "registro fósil". Es ignorado por el *Query-wiki* para eliminar redundancias, pero permanece accesible para auditoría.
    * **Cédula/Resultante (Activa):** La nueva instancia hereda la conexión y se convierte en el nodo operativo principal.

---

## 3. Nomenclatura de Linaje (Trazabilidad)
Para mapear la evolución del conocimiento, se aplica una estructura de nombres generacional:

* **Estado Inicial:** `Cedula_v1`
* **Primera Evolución:** `Cedula_v2_M1` (Mitosis 1)
* **Segunda Evolución:** `Cedula_v3_M2` (Mitosis 2)

> **Nota de Seguridad:** Este sistema de linaje permite el *rollback* inmediato a la "Cédula Madre" si la nueva configuración presenta inestabilidades.

---

## 4. Estructura de Metadatos de Linaje
*Propuesta de implementación:* Cada Chroma debe portar un encabezado de metadatos que registre su número de mitosis, timestamp de replicación y el hash de la Cédula antecesora.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
# Módulo de Inteligencia Adaptativa: Fisiología del Query-ingest

## 1. El Dato como Perturbación (Patógeno)
En la WikiLocal, la información entrante es un agente activo que desafía la homeostasis del sistema.
* **Tensión Semántica:** El dato nuevo genera una "deformación" al no encajar en las categorías preexistentes.
* **Motor Evolutivo:** La perturbación es necesaria; sin este "estrés" informativo, el Vault se estanca y deja de aprender.

---

## 2. Dinámica de Absorción y Especialización
Cuando la presión de la información supera la capacidad de la "membrana" de la Cédula, se activa la respuesta biológica.
* **División Lógica:** La Cédula se fragmenta en unidades funcionales más pequeñas y coherentes para gestionar la complejidad.
* **Secuenciación de la Hebra:** El patógeno se asimila y se convierte en una secuencia legítima del ADN (Nota), solidificando el conocimiento nuevo.

---

## 3. Ontología de la Operación (Las Cicatrices del Vault)
La verdadera inteligencia del sistema no reside en el estado final de las notas, sino en su historial de transformación.
* **La Traza como Estructura:** El valor reside en el registro de cómo una carpeta mutó, se dividió o absorbió datos.
* **Salud Sistémica:** Un Vault saludable se define por su actividad de mitosis y re-perfilado constante, no por un orden estático.

---

## 4. Interfaz de Consulta: Lectura de Linaje
El *Query-Wiki* evoluciona para leer las "cicatrices" de la mitosis. 
> **Ejemplo de Respuesta:** *"Esta nota existe porque absorbió el dato X, lo cual forzó la división de la carpeta original Y"*.
---------------------------------------------------------------------------------------------------------------------------------------------------------
# Módulo de Operaciones: Motores de Ingesta y Consulta (Query-System)

## 1. Arquitectura del Entorno (Vault)
El sistema se organiza en una jerarquía de contención que imita la especialización celular:
* **Célula (Carpeta):** La unidad funcional mínima de organización y límites operativos.
* **Genoma (Nota .md):** El código base o información descriptiva pura.
* **Hebras de ADN (Estructura):** La disposición lógica y sintáctica del contenido dentro de la nota.
* **Metasona (Metadatos + Links):** Elementos de conexión que definen el entorno y permiten el mapeo relacional sin procesar texto denso.

---

## 2. Motor de Entrada: Query-Ingest
Es el proceso de metabolismo informativo del organismo.
* **Función:** Asimilación de datos externos hacia el sistema.
* **Canales de Captura:** Soporte multimodal para archivos, documentos, carpetas o enlaces.
* **Métodos de Entrada:**
    * **Ingreso Simple:** Carga manual o directa de datos.
    * **Solicitud Chat:** Ingesta asistida por IA para una integración automatizada y contextual.

---

## 3. Motor de Recuperación: Query-Wiki
Define la lógica de "Scoping" o alcance jerárquico para la recuperación selectiva de información.
1. **WikiLocal:** Búsqueda en el ecosistema general del organismo.
2. **Vault:** Localización en el almacén de datos específico.
3. **Carpeta $\rightarrow$ Nota:** Identificación del objetivo final dentro de la célula.
4. **Escalamiento:** Capacidad de salto sistémico hacia "otros Vaults" si la respuesta no reside en el entorno inmediato.

---

## 4. Análisis de Diseño: La Clave de la Metasona
La separación entre el **Genoma** (contenido) y la **Metasona** (relaciones) permite que el sistema de Chat mapee el grafo de conocimiento de forma eficiente, evitando la sobrecarga cognitiva al tratar con grandes volúmenes de texto.
----------------------------------------------------------------------------------------------------------------------------------------------------------
# Especificación Maestra: Arquitectura y Estructura de WikiLocal

## 1. Visión General del Sistema
La **WikiLocal** es un ecosistema adaptativo diseñado para transformar archivos estáticos en un **Organismo Vivo**. El sistema no almacena archivos de forma tradicional, sino que gestiona "asientos" de conocimiento vinculados a una red de origen.

## 2. Biogerarquía (Arquitectura Vertical)

| Nivel Biológico | Componente Técnico | Descripción Funcional |
| :--- | :--- | :--- |
| **Organismo** | `WikiLocal` | El sistema completo que integra uno o varios Vaults; la unidad de vida mayor. |
| **Cédula** | `Carpeta` | Entorno contenedor que define la identidad y los límites de cada unidad de conocimiento. |
| **Genoma** | `Nota (.md)` | Código base donde reside la información bruta o descriptiva. |
| **Chroma / Hebra** | `Base de Datos Vectorial` | El ADN del sistema; permite que la información sea legible y conectada para la IA. |
| **Metasoma / Gen** | `Metadatos + Links` | La unidad mínima funcional. Contiene la vinculación al archivo original y metadatos de identificación. |

## 3. Dinámica Operativa: Los Motores Query

El funcionamiento de la WikiLocal se rige por dos procesos metabólicos principales:

* **Query-Ingest (Motor de Entrada):**
    * **Función:** Crea el contenido de los Vaults mediante la generación de Metasomas.
    * **Mecánica:** Al detectar cambios, dispara el proceso de **Mitosis**, replicando la Cédula y archivando el estado anterior como "registro fósil".
* **Query-Wiki (Motor de Consulta):**
    * **Función:** Ejecuta búsquedas relacionales en toda la WikiLocal para devolver respuestas contextuales.
    * **Scoping:** Opera siempre sobre el estado más evolucionado (el último Chroma activo).

---

## 4. Principios de Integridad
1.  **Inmutabilidad:** El historial nunca se pierde; las versiones previas se preservan en "cédulas viejas".
2.  **Rastreabilidad:** El número de mitosis permite identificar el momento exacto de la evolución de una conexión.
3.  **Vínculo Externo (MFL):** Los Vaults almacenan accesos directos que mantienen la conexión con los archivos originales fuera del sistema.
-------------------------------------------------------------------------------------------------------------------------------------------------------------
