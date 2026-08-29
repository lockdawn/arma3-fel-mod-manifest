# Listas de Mods Arma 3 – Clan FEL

Este repositorio constituye el **compendio oficial de mods utilizados y autorizados por el Clan FEL para Arma 3**, organizado y documentado con el propósito de servir como referencia técnica para los editores de misiones y responsables de contenido.

Las listas aquí contenidas reúnen de manera estructurada los distintos paquetes de mods empleados en las operaciones del clan, incluyendo aquellos considerados obligatorios, recomendados o específicos para tareas de edición. Cada mod se acompaña de información relevante sobre su función, categoría, dependencias y uso habitual dentro del entorno FEL, permitiendo comprender no solo qué contenido se utiliza, sino también **por qué se utiliza** y en qué contexto resulta adecuado.

El objetivo principal es establecer una base común que garantice coherencia, compatibilidad y una identidad operativa uniforme entre todas las misiones desarrolladas por el clan. De esta forma, se evita la fragmentación de presets, la inclusión de contenido no autorizado o la dependencia de configuraciones personales que puedan afectar la experiencia multijugador o la estabilidad técnica.

Asimismo, este compendio permite a los nuevos editores integrarse rápidamente al flujo de trabajo del clan, conocer los estándares vigentes y disponer de una guía clara para seleccionar los recursos necesarios al diseñar escenarios. Para los editores experimentados, funciona como una referencia consolidada que facilita la planificación de misiones y la verificación de compatibilidad entre distintos módulos de contenido.

En síntesis, este repositorio no es únicamente una lista de mods, sino una **base documental que respalda la firma técnica, estética y funcional de las misiones en FEL**.

---

## 📌 Propósito

El propósito de estas listas es proporcionar una guía completa, confiable y estandarizada que permita a los editores:

- Identificar los mods mínimos requeridos para garantizar la compatibilidad con el entorno operativo del clan.  
- Conocer qué contenido está autorizado para su uso en misiones oficiales.  
- Diferenciar entre herramientas de edición, mejoras de jugabilidad, contenido opcional y dependencias técnicas.  
- Mantener una coherencia visual, sonora y mecánica entre las distintas operaciones.  
- Reducir errores derivados de configuraciones inconsistentes o de la falta de dependencias.  

Estas listas también cumplen una función de control y mantenimiento del ecosistema de mods del clan, evitando la proliferación de presets incompatibles o la inclusión de contenido que no haya sido evaluado previamente.

Al establecer una base común y claramente documentada, se facilita la colaboración entre editores, la continuidad de proyectos y la reproducibilidad de misiones a lo largo del tiempo. Cualquier editor puede desarrollar o modificar escenarios con la seguridad de que está trabajando dentro de un marco técnico conocido y aprobado.

En definitiva, este documento actúa como la referencia oficial para la construcción de misiones dentro del Clan FEL, asegurando que todas las operaciones compartan un mismo estándar de calidad, estabilidad y coherencia operativa.


## 📂 Contenido

- ⚙️ [Lista de Mods Fundamentales](#️-lista-de-mods-fundamentales)
- ⚙️ [Mods para Edición](#️-mods-para-edición)
- ⚙️ [Mods de Optimización / Utilidades](#️-mods-de-optimizaciónutilidades)
- ⚙️ [Mods de Mapas](#️-mods-de-mapas)
- ⚙️ [Mods de Complementos, Equipamiento y Vehículos](#️-mods-de-complementos-equipamiento-y-vehículos)

<br />

# ⚙️ Lista de Mods Fundamentales

## Descripción

Esta lista de mods fundamentales corresponde al conjunto mínimo obligatorio para la creación de misiones dentro de FEL. Su objetivo es garantizar una base común de funcionalidades, realismo y herramientas que forman parte integral del rol, la experiencia de juego y los estándares operativos definidos por la comunidad.

Los mods incluidos en esta lista no son opcionales y deben ser considerados en todas las misiones, ya que habilitan mecánicas fundamentales como interacción avanzada, sistemas médicos, herramientas de edición, control Zeus, comunicaciones y mejoras estructurales que impactan directamente en la jugabilidad y en la coherencia de las operaciones.

Esta lista representa el mínimo técnico y funcional que todo editor debe asumir como presente en el entorno de juego. No deben ser eliminados ni sustituidos, ya que su ausencia compromete la experiencia esperada para los jugadores y rompe la compatibilidad con los lineamientos FEL.

A partir de esta lista, los editores pueden utilizar otros mods de las tablas que se presentan a continuación, las cuales se encuentran organizadas por función y describen extensiones opcionales que permiten enriquecer las misiones según sus objetivos, narrativa y nivel de complejidad.<br /><br />

## 📋 Lista de Mods – [arma_3-mods_fundamentales.html](https://github.com/lockdawn/arma3-fel-mod-manifest/blob/main/arma_3-mods_fundamentales.html)
<br />

| Nombre del Mod | Descripción | Utilidades | Categoría | Compatibilidad |
|----------------|-------------|------------|-----------|----------------|
| 3den Enhanced | Expande el editor 3DEN con herramientas avanzadas. | Edición de misiones, productividad. | Editor / Misiones | Independiente (recomendado con CBA_A3) |
| ACE | Sistema avanzado de realismo (médico, balística, interacción). | Realismo táctico, nuevas mecánicas de jugabilidad. | Jugabilidad / Médico | Requiere CBA_A3 |
| ACE3 Arsenal Extended - Core | Agrupa el arsenal por variantes para reducir la lista a la mitad de su tamaño original. | Realismo táctico, nuevas mecánicas de jugabilidad. | Jugabilidad / Médico | Requiere CBA_A3 |
| Advanced Combat Medicine | Extiende el sistema médico de ACE con mayor profundidad. | Medicina avanzada, procedimientos médicos. | Médico | Requiere ACE + CBA_A3 |
| Blastcore Edited | Mejora visual de explosiones, fuego y efectos de partículas. | Explosiones, humo, ambientación visual. | Gráficos / Efectos | Independiente |
| CBA_A3 | Librería base requerida por numerosos mods. | Framework, compatibilidad y funciones base. | Soporte | Base requerida por ACE, KAT/ACM, Zeus Enhanced, etc. |
| CH View Distance | Ajuste dinámico de distancias de visión. | Optimización de rendimiento y visibilidad. | Rendimiento | Independiente |
| Enhanced Movement | Permite trepar, saltar y moverse con mayor libertad. | Movilidad avanzada del jugador. | Movilidad | Independiente |
| Enhanced Movement Rework | Versión optimizada y más estable de Enhanced Movement. | Movimientos avanzados mejorados. | Movilidad | Independiente |
| Esenciales 2026 v2 | Compilado de utilidades básicas usadas en misiones FEL. | Funciones comunes, soporte general de misión. | Compilación | Puede requerir CBA_A3 y ACE |
| LAMBS_Danger.fsm | IA avanzada (Lambs) – módulo Danger. | IA dinámica de combate. | IA | Compatible con CBA_A3 (recomendado) |
| Task Force Arrowhead Radio (BETA!!!) | Sistema de comunicación por radio realista con frecuencias. | Comunicaciones tácticas por rol. | Comunicación | Compatible con CBA_A3 |
| Zeus Enhanced | Amplía significativamente las capacidades del Zeus. | Control avanzado de misiones en vivo. | Zeus / Administración | Requiere CBA_A3 |

<br /><br />

# ⚙️ Mods para Edición

## Descripción

Los **mods para edición** están pensados exclusivamente para los **creadores de misiones**. No añaden contenido jugable ni afectan al desarrollo de las partidas multijugador, sino que ofrecen **herramientas adicionales para diseñar, depurar y probar escenarios** en el editor de Arma 3.  

Dentro de este grupo se encuentran:  
- **3den Enhanced**: amplía el editor oficial con nuevas funciones, atajos, configuraciones avanzadas y utilidades para hacer más eficiente la construcción de misiones.  
- **A3U – Arma 3 Utilities**: aporta herramientas de depuración y pruebas rápidas, como reiniciar scripts, controlar el entorno, revisar rendimiento y teletransportar unidades durante la fase de testeo.  
- **Deformer**: permite modificar el terreno en vivo dentro de Zeus, útil para ajustar el entorno del campo de batalla de forma rápida y dinámica.
- **Modules Enhanced**: añade una amplia colección de módulos funcionales para Eden y Zeus que permiten implementar eventos, spawns, apoyo logístico, efectos ambientales y otras mecánicas.

En conjunto, estos mods facilitan el trabajo de los editores, reducen el tiempo de prueba y mejoran la flexibilidad a la hora de **crear misiones más realistas, dinámicas y pulidas**. Los jugadores **no necesitan** tenerlos cargados para unirse a partidas multijugador.<br /><br />

## 📋 Lista de Mods

<br />

| Nombre del Mod | Descripción | Funciones |
|----------------|-------------|------------|
| [3den Enhanced](https://steamcommunity.com/sharedfiles/filedetails/?id=623475643) | Mejora el editor 3DEN con más funciones. | Herramientas de creación, utilidades para misiones. |
| [A3U – Arma 3 Utilities](https://steamcommunity.com/sharedfiles/filedetails/?id=1560749177) | Herramientas para edición y depuración. | Utilidades técnicas, debug. |
| [Deformer](https://steamcommunity.com/sharedfiles/filedetails/?id=2822758266) | Herramienta para deformar terrenos en Zeus. | Edición de terreno en vivo. |
| [Modules Enhanced](https://steamcommunity.com/sharedfiles/filedetails/?id=3043987264) | Mejora/expande módulos del editor/Zeus. | Utilidades de misión. | Utilidad | N/D |

<br /><br />

# ⚙️ Mods de Optimización\Utilidades

## Descripción

Los **mods de optimización** en este preset no añaden nuevos uniformes, armas o mapas, sino que **mejoran y expanden la experiencia de juego** en Arma 3. Están diseñados para aumentar la **inmersión, el realismo y la jugabilidad**, ofreciendo ajustes técnicos, visuales y sonoros que elevan la calidad del simulador.  

Dentro de este grupo se encuentran:  
- **Mejoras gráficas y sonoras**: mods como *Blastcore Edited* y *JSRS Soundmod* transforman explosiones, humo, disparos y ambiente sonoro, logrando una experiencia mucho más realista.  
- **Extensiones de jugabilidad**: *ACE* y *KAT Advanced Medical*/*Advanced Combat Medicine* profundizan el realismo con sistemas médicos, balística avanzada y mecánicas adicionales.  
- **Movilidad y animaciones**: *Enhanced Movement* y su rework permiten escalar, trepar y moverse de formas más naturales en combate.
- **IA y dinámica de misión**: *Lambs AI* y *ALiVE* aportan inteligencia artificial mejorada y campañas dinámicas persistentes.  
- **Herramientas de control y soporte**: mods como *CBA_A3*, *CH View Distance*, *Simplex Support Services* y *TFAR* añaden frameworks, control de rendimiento, soporte táctico y comunicación realista por radio.  

En conjunto, estos mods **perfeccionan cómo se siente jugar**: la visión, el sonido, las animaciones, los efectos y la comunicación dentro del juego.<br />

## 📋 Lista de Mods

<br />

| Nombre del Mod | Descripción | Utilidades | Categoría | Compatibilidad |
|----------------|-------------|------------|-----------|----------------|
| [ACE](https://steamcommunity.com/sharedfiles/filedetails/?id=463939057) | Sistema avanzado de realismo (médico, balística, interacción). | Realismo, nuevas funciones de jugabilidad. | Jugabilidad / Médico | Requiere CBA_A3 |
| [ACRE2](https://steamcommunity.com/sharedfiles/filedetails/?id=751965892) | Comunicación por radio realista con frecuencias. | Utilidades de comunicación. | Comunicación | Compatible con CBA_A3 |
| [Advanced Combat Medicine](https://steamcommunity.com/sharedfiles/filedetails/?id=3235483358) | Extiende el sistema médico de ACE. | Jugabilidad médica avanzada. | Médico | Requiere ACE + CBA_A3 |
| [AI behavior modification](https://steamcommunity.com/sharedfiles/filedetails/?id=3641926249) | Ajustes/mejoras de comportamiento de IA. | IA más reactiva / tweaks de combate. | IA | N/D |
| [AIO Lambs Pack](https://steamcommunity.com/sharedfiles/filedetails/?id=2815713819) | IA mejorada con comportamientos más realistas. | IA dinámica y utilidades de combate. | IA | Compatible con CBA_A3 |
| [Airfield Logistics](https://steamcommunity.com/sharedfiles/filedetails/?id=3048131698) | Logística y utilidades para operación en aeródromos. | Reabastecimiento/soporte (según mod). | Utilidad | N/D |
| [ALiVE](https://steamcommunity.com/sharedfiles/filedetails/?id=620260972) | Sistema de guerra dinámica persistente. | Campañas dinámicas, utilidades de misión. | IA / Dinámica | Compatible con CBA_A3 |
| [Blastcore Edited](https://steamcommunity.com/sharedfiles/filedetails/?id=767380317) | Mejora de efectos visuales de explosiones y humo. | Mejores explosiones, partículas y efectos. | Gráficos / Efectos | Independiente |
| [CBA_A3](https://steamcommunity.com/sharedfiles/filedetails/?id=450814997) | Librería base requerida por muchos mods. | Framework y compatibilidad. | Soporte | Base requerida por ACE, KAT/ACM, ALiVE, etc. |
| [CH View Distance](https://steamcommunity.com/sharedfiles/filedetails/?id=837729515) | Ajuste dinámico de distancias de visión. | Rendimiento y visibilidad. | Rendimiento | Independiente |
| [DCO Soldier FSM](https://steamcommunity.com/sharedfiles/filedetails/?id=2825929474) | Ajustes FSM para comportamiento de soldados. | IA/animaciones/decisiones. | IA | N/D |
| [DCO UnitScanner](https://steamcommunity.com/sharedfiles/filedetails/?id=2811378998) | Herramienta/función de escaneo de unidades. | Utilidad táctica/diagnóstico. | Utilidad | N/D |
| [Dog](https://steamcommunity.com/sharedfiles/filedetails/?id=2912186689) | Sistema/perro K9 (contenido y mecánicas). | Reconocimiento/rol. | Jugabilidad | N/D |
| [Enhanced Movement](https://steamcommunity.com/sharedfiles/filedetails/?id=333310405) | Permite trepar y saltar obstáculos. | Movimientos nuevos. | Movilidad | Independiente |
| [Enhanced Movement Rework](https://steamcommunity.com/sharedfiles/filedetails/?id=2034363662) | Versión optimizada del mod anterior. | Movimientos nuevos, más estables. | Movilidad | Independiente |
| [Esenciales 2026 v2](https://steamcommunity.com/sharedfiles/filedetails/?id=3709556444) | Compilado de utilidades básicas usadas en misiones FEL. | Funciones comunes, soporte general de misión. | Compilación | Puede requerir CBA_A3 y ACE |
| [IEDD Notebook](https://steamcommunity.com/sharedfiles/filedetails/?id=3048818056) | Libreta interactiva para desactivación de IED. | Utilidad EOD (desactivación de explosivos). | Jugabilidad | Compatible con ACE |
| [JSRS Soundmod 2025](https://steamcommunity.com/sharedfiles/filedetails/?id=3407948300) | Mejora global de sonidos de armas y ambiente. | Sonidos realistas, ambiente. | Sonido | Independiente |
| [KAT – Advanced Medical](https://steamcommunity.com/sharedfiles/filedetails/?id=2020940806) | Extiende el sistema médico de ACE. | Jugabilidad médica avanzada. | Médico | Requiere ACE + CBA_A3 |
| [LAMBS_Danger.fsm](https://steamcommunity.com/sharedfiles/filedetails/?id=1858075458) | IA avanzada (Lambs) – módulo Danger. | IA dinámica de combate. | IA | Compatible con CBA_A3 (recomendado) |
| [Machinegun AI](https://steamcommunity.com/sharedfiles/filedetails/?id=3369853634) | Mejora comportamiento de IA con ametralladoras. | IA de supresión/uso de MG. | IA | N/D |
| [Real Flashlights](https://steamcommunity.com/sharedfiles/filedetails/?id=3366918628) | Linternas más realistas (haz/iluminación). | Inmersión/visibilidad. | Gráficos/Utilidad | N/D |
| [RHSTERRACORE](https://steamcommunity.com/sharedfiles/filedetails/?id=2288691268) | Librería de soporte para RHS. | Requerido para compatibilidad. | Soporte | Necesario para varios mods RHS |
| [Simplex Support Services](https://steamcommunity.com/sharedfiles/filedetails/?id=3029520419) | Sistema de apoyo (artillería, logística, etc.). | Soporte y funciones tácticas. | Jugabilidad / Soporte | Compatible con CBA_A3 |
| [Task Force Arrowhead Radio (TFAR)](https://steamcommunity.com/sharedfiles/filedetails/?id=894678801) | Comunicación por radio realista con frecuencias. | Utilidades de comunicación. | Comunicación | Compatible con CBA_A3 |
| [WebKnight Flashlights and Headlamps](https://steamcommunity.com/sharedfiles/filedetails/?id=2572487482) | Linternas y lámparas frontales (contenido). | Inmersión/visión nocturna. | Equipamiento | N/D |

<br /><br />

# ⚙️ Mods de Mapas

## Descripción

Esta tabla incluye todos los mapas del preset, con detalles de bioma, tamaño, realismo, dependencias y características principales.<br />

## 📋 Lista de Mods

<br />

| Nombre del Mapa | Descripción | Bioma | Tamaño aprox en km | Realismo | Dependencias | Características |
|-----------------|-------------|-------|---------------|----------|--------------|-----------------|
| [Al Salman 2.0](https://steamcommunity.com/sharedfiles/filedetails/?id=2857846877) | Terreno urbano y desértico inspirado en Irak. | Desierto / Urbano | 10x10 | Basado en Irak | Standalone | Poblados, bases militares, desierto |
| [Angola Maps v1.3](https://steamcommunity.com/sharedfiles/filedetails/?id=1446500688) | Terreno ambientado en Angola. | Selva / Sabana | N/D | Basado en Angola | Standalone | N/D |
| [Avdiivka Ukraine](https://steamcommunity.com/sharedfiles/filedetails/?id=3216037810) | Recrea la ciudad ucraniana de Avdiivka en guerra. | Urbano / Bélico | 8x8 | Basado en ciudad real | Standalone | Edificios destruidos, ambiente moderno |
| [CLA Clafghan](https://steamcommunity.com/sharedfiles/filedetails/?id=2523301491) | Terreno afgano clásico, muy usado en campañas. | Desierto / Montañoso | 20x20 | Basado en Afganistán | Standalone | Valles, aldeas, terreno montañoso |
| [CUP Terrains - Core](https://steamcommunity.com/sharedfiles/filedetails/?id=583496184) | Librería de objetos y texturas base para mapas CUP. | Varios | Varios | Varios | Requerido por mapas CUP | Sin jugabilidad directa, es dependencia |
| [Fallujah 2.0](https://steamcommunity.com/sharedfiles/filedetails/?id=2926828901) | Representación urbana de Fallujah, Irak. | Urbano / Desértico | 10x10 | Basado en ciudad real | Standalone | Ciudad densa, calles estrechas |
| [G.O.S Al Rayak](https://steamcommunity.com/sharedfiles/filedetails/?id=648172507) | Terreno G.O.S “Al Rayak”. | Boscoso / Oriente Medio | 20x20 | País de Oriente Medio | Standalone | N/D |
| [G.O.S Gunkizli](https://steamcommunity.com/sharedfiles/filedetails/?id=693153082) | Terreno desértico con pequeños poblados. | Desierto | 20x20 | Ficticio | Standalone | Poblados dispersos, grandes áreas abiertas |
| [G.O.S Leskovets](https://steamcommunity.com/sharedfiles/filedetails/?id=855464203) | Terreno europeo boscoso con pueblos. | Boscoso / Europeo | 20x20 | Ficticio (inspirado en Balcanes) | Standalone | Pueblos pequeños, bosques densos |
| [G.O.S N'Djenahoud](https://steamcommunity.com/sharedfiles/filedetails/?id=937515516) | Escenario africano desértico y árido. | Desierto / Africano | 20x20 | Ficticio | Standalone | Desierto abierto, aldeas africanas |
| [G.O.S. N'ziwasogo v2 APEX](https://steamcommunity.com/sharedfiles/filedetails/?id=2084904847) | Selva africana densa y húmeda. | Selva | 20x20 | Ficticio | Standalone | Vegetación densa, aldeas, jungla cerrada |
| [Green Sea Terrain](https://steamcommunity.com/sharedfiles/filedetails/?id=2645015212) | Región ficticia basada en el “universo Arma” (Green Sea). | Europeo / Costero | 20x20 | Ficticio | Standalone | Variado, con ciudades y áreas rurales |
| [Kingdom of Regero](https://steamcommunity.com/sharedfiles/filedetails/?id=2278254320) | Terreno “Kingdom of Regero”. | Desierto / Selva | 10x10 | Ficticio | Standalone | N/D |
| [Korsac](https://steamcommunity.com/sharedfiles/filedetails/?id=3043043427) | Terreno ficticio (datos limitados). | Boscoso / Europeo | 8x8 | Ficticio | Standalone | N/D |
| [Kujari](https://steamcommunity.com/sharedfiles/filedetails/?id=1726494027) | Terreno africano con pueblos dispersos. | Africano / Semiárido | 20x20 | Ficticio | Standalone | Pueblos pequeños, sabana |
| [Kunduz River](https://steamcommunity.com/sharedfiles/filedetails/?id=3078351739) | Terreno basado en Afganistán (Kunduz). | Desértico / Montañoso | 15x15 | Basado en Afganistán | Standalone | Río central, aldeas, terreno montañoso |
| [Lybor](https://steamcommunity.com/sharedfiles/filedetails/?id=3013515917) | Terreno ficticio con geografía variada. | Boscoso / Europeo | 6x6 | Ficticio | Standalone | N/D |
| [Mutambara](https://steamcommunity.com/sharedfiles/filedetails/?id=2814015609) | Terreno africano de sabana. | Africano / Sabana | 20x20 | Ficticio | Standalone | Aldeas africanas, terreno abierto |
| [Niakala](https://steamcommunity.com/sharedfiles/filedetails/?id=2801060088) | Terreno africano árido y seco. | Africano / Desierto | 10x10 | Ficticio | Standalone | Zonas áridas, pequeños poblados |
| [North Takistan](https://steamcommunity.com/sharedfiles/filedetails/?id=2829330653) | Terreno inspirado en Takistán (norte). | Desértico/Montañoso (aprox.) | 12x12 | Inspirado en región | Standalone | N/D |
| [Orglandes](https://steamcommunity.com/sharedfiles/filedetails/?id=2173146730) | Terreno “Orglandes”. | Bosque | 4x4 | Campiña Francesa WW2 | Standalone | N/D |
| [RHSTERRACORE](https://steamcommunity.com/sharedfiles/filedetails/?id=2288691268) | Base de terrenos RHS (objetos y texturas). | Varios | Varios | Varios | Requerido por mapas RHS | Sin jugabilidad directa, es dependencia |
| [Robotyne Ukraine](https://steamcommunity.com/sharedfiles/filedetails/?id=3118416433) | Terreno basado en zona de Ucrania (Robotyne). | Urbano/Rural (aprox.) | 12x12 | Basado en zona real | Standalone | N/D |
| [Svalbard](https://steamcommunity.com/sharedfiles/filedetails/?id=3401164850) | Terreno ártico/islas Svalbard. | Ártico/Nevado | 500x500 | Inspirado en región real | Standalone | N/D |
| [Tembelan Island](https://steamcommunity.com/sharedfiles/filedetails/?id=1252091296) | Terreno de isla (Tembelan). | Tropical/Isla (aprox.) | 10x10 | Ficticio | Standalone | N/D |
| [Šumava](https://steamcommunity.com/sharedfiles/filedetails/?id=2947655994) | Terreno europeo boscoso basado en la región de Šumava (Chequia). | Boscoso / Europeo | 10x10 | Basado en región real | Standalone | Bosques densos, pueblos rurales |

<br /><br />

# ⚙️ Mods de Complementos, Equipamiento y Vehículos

## Descripción

Esta sección incluye los mods que aportan uniformes, armas, vehículos, facciones, helicópteros, jets, portaaviones y otros complementos.  
Son la base para enriquecer la experiencia de juego y aportar variedad en misiones tanto de infantería como de aviación y operaciones especiales.<br />

## 📋 Lista de Mods

<br />

| Nombre del Mod | Descripción | Dependencias | Enfoque | Uso típico |
|----------------|-------------|--------------|---------|------------|
| [3CB Factions](https://steamcommunity.com/sharedfiles/filedetails/?id=1673456286) | Facciones de la Guerra Fría y modernas. | CBA_A3 | Infantería, vehículos, facciones | Escenarios británicos / africanos |
| [ACE and KAT Medical WWII Item Replacements](https://steamcommunity.com/sharedfiles/filedetails/?id=3168260137) | Reemplazos de ítems médicos WWII para ACE/KAT. | ACE, KAT, CBA_A3 | Médico | Misiones WWII/IFA |
| [Animate - Rewrite](https://steamcommunity.com/sharedfiles/filedetails/?id=3283612524) | Sistema/paquete de animaciones (Rewrite). | N/D | Animaciones | Inmersión/acciones |
| [Arma Realistic Map Assets V2](https://steamcommunity.com/sharedfiles/filedetails/?id=2982306133) | Assets realistas para mapas/escenarios. | N/D | Assets | Escenarios/ambientación |
| [B1 Centauro](https://steamcommunity.com/sharedfiles/filedetails/?id=3289269638) | Vehículo blindado Centauro. | N/D | Vehículos | Fuerzas terrestres |
| [Breach - Rewrite](https://steamcommunity.com/sharedfiles/filedetails/?id=3283645995) | Sistema de breaching/entradas (Rewrite). | N/D | Jugabilidad CQB | Asaltos urbanos |
| [BWMod](https://steamcommunity.com/sharedfiles/filedetails/?id=1200127537) | Contenido Bundeswehr (BW). | N/D | Facción/Equipamiento | Escenarios Alemania/NATO |
| [cTab](https://steamcommunity.com/sharedfiles/filedetails/?id=871504836) | Tablets/BFT/gestión táctica (cTab). | CBA_A3 (común) | C2/Interfaz | JTAC, líderes, tracking |
| [CUP Terrains - Maps](https://steamcommunity.com/sharedfiles/filedetails/?id=583544987) | Mapas CUP (paquete principal). | CUP Terrains - Core | Mapas | Terrenos CUP |
| [CUP Terrains - Maps 2.0](https://steamcommunity.com/sharedfiles/filedetails/?id=1981964169) | Mapas adicionales CUP. | CUP Terrains - Core | Mapas | Terrenos CUP extra |
| [CUP Units](https://steamcommunity.com/sharedfiles/filedetails/?id=497661914) | Unidades CUP (infantería/vehículos). | CBA_A3 (común) | Facciones | BLUFOR/OPFOR variados |
| [CUP Weapons](https://steamcommunity.com/sharedfiles/filedetails/?id=497660133) | Arsenal clásico y moderno. | CBA_A3 | Arsenal de armas | Complemento para cualquier facción |
| [Enhanced RHS Hind Mi-24VM & Mi-24PM](https://steamcommunity.com/sharedfiles/filedetails/?id=2826534435) | Variantes del Mi-24. | RHS AFRF | Helicópteros | Misiones con apoyo aéreo OPFOR |
| [FPV Drone Crocus](https://steamcommunity.com/sharedfiles/filedetails/?id=3045129955) | Drones FPV explosivos. | CBA_A3 | Drones suicidas | Escenarios urbanos y asimétricos |
| [French armour pack](https://steamcommunity.com/sharedfiles/filedetails/?id=3317407146) | Pack de blindados franceses. | N/D | Vehículos | Fuerzas terrestres |
| [FRXA's TFAR Extra Retextured Equipment](https://steamcommunity.com/sharedfiles/filedetails/?id=1606874412) | Equipo retexturizado TFAR. | TFAR | Comunicaciones | Inmersión visual para radio operadores |
| [Hendrix Russian and Ukraine Gear](https://steamcommunity.com/sharedfiles/filedetails/?id=3440614160) | Gear de Rusia y Ucrania. | CBA_A3 | Uniformes, chalecos | Misiones en contexto Ucrania-Rusia |
| [IFA3 AIO](https://steamcommunity.com/sharedfiles/filedetails/?id=2648308937) | Total conversion WWII (Iron Front AIO). | N/D | WWII | Campañas WWII |
| [Iron Front ArmA 3 : ACE 3 Compatibility patch](https://steamcommunity.com/sharedfiles/filedetails/?id=773759919) | Compatibilidad ACE para IFA/WWII. | ACE, IFA3 | Compat | WWII con ACE |
| [JCA - Infantry Arsenal](https://steamcommunity.com/sharedfiles/filedetails/?id=3333302397) | Arsenal de infantería. | CBA_A3 | Armas y uniformes | Escenarios multirrol |
| [JCA - Infantry Arsenal Compat Ace3](https://steamcommunity.com/sharedfiles/filedetails/?id=3337555434) | Compatibilidad con ACE3. | ACE3, JCA Arsenal | Ajustes médicos y balísticos | Misiones con ACE3 |
| [K9 Companion](https://steamcommunity.com/sharedfiles/filedetails/?id=3576759846) | Sistema/compañero K9. | N/D | Jugabilidad | Recon/rol |
| [Mx Mexico Drug War - Guerra de las Drogas México RHS](https://steamcommunity.com/sharedfiles/filedetails/?id=3514248400) | Contenido México (Drug War) basado en RHS. | RHS (varios), CBA_A3 | Facciones | Escenarios México |
| [MxHMMWV - Humvees Mexicanos RHS](https://steamcommunity.com/sharedfiles/filedetails/?id=3388240174) | Humvees mexicanos (RHS). | RHS, CBA_A3 | Vehículos | Escenarios México |
| [MxVehicles-Vehiculos Mexicanos RHS](https://steamcommunity.com/sharedfiles/filedetails/?id=3514192308) | Vehículos mexicanos (RHS). | RHS, CBA_A3 | Vehículos | Escenarios México |
| [NR6 PACK - HAL Evolved](https://steamcommunity.com/sharedfiles/filedetails/?id=1877858319) | HAL/funcionalidad extendida (NR6). | N/D | Jugabilidad/Utilidad | Misiones dinámicas |
| [Project OPFOR](https://steamcommunity.com/sharedfiles/filedetails/?id=735566597) | Facciones insurgentes. | CBA_A3 | OPFOR irregulares | Escenarios de contrainsurgencia |
| [RHS Additions - Rewrite](https://steamcommunity.com/sharedfiles/filedetails/?id=3553838240) | Extensiones para RHS. | RHS Mods | Expansión | Ampliar arsenal RHS |
| [RHS Plus](https://steamcommunity.com/sharedfiles/filedetails/?id=3299910335) | Extensión/compat para RHS (Plus). | RHS, CBA_A3 | Expansión | Complementar RHS |
| [RHSAFRF](https://steamcommunity.com/sharedfiles/filedetails/?id=843425103) | Ejército ruso. | CBA_A3 | Ejército regular | OPFOR principal |
| [RHSGREF](https://steamcommunity.com/sharedfiles/filedetails/?id=843593391) | Facciones extras. | CBA_A3 | Guerrillas, ejércitos menores | Escenarios secundarios |
| [RHSSAF](https://steamcommunity.com/sharedfiles/filedetails/?id=843632231) | Ejército serbio. | CBA_A3 | Ejército regular | Escenarios balcánicos |
| [RHSUSAF](https://steamcommunity.com/sharedfiles/filedetails/?id=843577117) | Ejército estadounidense. | CBA_A3 | Ejército regular | NATO / BLUFOR principal |
| [Russian Tank Series](https://steamcommunity.com/sharedfiles/filedetails/?id=3418145558) | Serie de tanques rusos (pack). | N/D | Vehículos | OPFOR blindado |
| [S & S](https://steamcommunity.com/sharedfiles/filedetails/?id=2183975396) | Equipamiento adicional. | CBA_A3 | Expansión | Complemento multirrol |
| [S & S: New Wave](https://steamcommunity.com/sharedfiles/filedetails/?id=2643518676) | Expansión de S&S. | CBA_A3, S&S | Expansión | Complemento multirrol |
| [Speshal Core](https://steamcommunity.com/sharedfiles/filedetails/?id=3283642267) | Librería/“core” para otros mods Speshal/Rewrite. | N/D | Framework | Dependencia de rewrite packs |
| [Tactical Balaclavas v1.4.3](https://steamcommunity.com/sharedfiles/filedetails/?id=3042884554) | Balaclavas tácticas (equipamiento). | N/D | Equipamiento | Inmersión/roles |
| [Tier One Fix](https://steamcommunity.com/sharedfiles/filedetails/?id=3595340620) | Fix/patch para Tier One. | Tier One Weapons | Fix | Correcciones |
| [Tier One Weapons](https://steamcommunity.com/sharedfiles/filedetails/?id=2268351256) | Pack de armas Tier One. | N/D | Armas | SOF/Operaciones especiales |
| [TR-85M1 Bizonul](https://steamcommunity.com/sharedfiles/filedetails/?id=3132242050) | Tanque TR-85M1. | N/D | Vehículos | Fuerzas terrestres |
| [TRYK Multiplay-Uniform Fix](https://steamcommunity.com/sharedfiles/filedetails/?id=741196544) | Fix para uniformes TRYK. | TRYK Uniforms | Corrección | Uso de uniformes TRYK |
| [Tryk's Multi-play Uniforms Pack 0.9.4b](https://steamcommunity.com/sharedfiles/filedetails/?id=684872545) | Pack de uniformes modernos. | CBA_A3 | Gear moderno | Operaciones especiales |
| [Tryk's Multi-play Uniforms Pack 0.9.4b](https://steamcommunity.com/sharedfiles/filedetails/?id=684872545) | Uniformes TRYK (pack). | N/D | Uniformes | SOF/varios |
| [USMC equipment](https://steamcommunity.com/sharedfiles/filedetails/?id=2951237069) | Equipamiento del USMC. | CBA_A3 | Infantería USMC | Misiones de Marines en Irak / Afganistán |
| [VME PLA Mod](https://steamcommunity.com/sharedfiles/filedetails/?id=1562282342) | Contenido PLA (China). | N/D | Facción | OPFOR/BLUFOR PLA |
| [XYI 75th & USMC Lite](https://steamcommunity.com/sharedfiles/filedetails/?id=3526739218) | Pack XYI 75th/USMC Lite. | N/D | Equipamiento/Facción | Misiones US |

# ⚙️ Mods Aeronavales

## Descripción

Esta categoría reúne todos los mods cuyo contenido está orientado exclusivamente a operaciones aéreas o aeronavales, incluyendo aeronaves de ala fija, helicópteros, buques portaaeronaves y sistemas directamente asociados a su empleo.

Se incluyen únicamente aquellos mods que aportan activos o funcionalidades propias del entorno aéreo. No se consideran mods mixtos que contengan uniformes, vehículos terrestres, armamento general u otros elementos no exclusivos de aviación.

Esta tabla sirve como referencia directa para los editores que deseen diseñar misiones centradas en pilotos, apoyo aéreo cercano, operaciones embarcadas o escenarios aeronavales completos.

## 📋 Lista de Mods

| Nombre del Mod | Tipo | Plataforma | Descripción | Uso típico |
|----------------|------|-----------|-------------|------------|
| [AH-1Z Viper](https://steamcommunity.com/sharedfiles/filedetails/?id=3546703780) | Helicóptero de ataque | USMC | Helicóptero de ataque moderno AH-1Z. | CAS, escolta, apoyo cercano desde bases o buques |
| [Boeing 737 and variants](https://steamcommunity.com/sharedfiles/filedetails/?id=1835744247) | Avión de transporte civil | Ala fija | Aeronaves tipo Boeing 737. | Transporte VIP, escenarios civiles, ambientación |
| [BWI - AT-6B + T-6A/C + PC-9A + PC-9 Pack](https://steamcommunity.com/sharedfiles/filedetails/?id=323854117) | Aviones ligeros | Ala fija | Pack de aeronaves de entrenamiento y ataque ligero. | COIN, patrullaje, entrenamiento |
| [C-130 Hercules Series (Hercules Upgrade Project)](https://steamcommunity.com/sharedfiles/filedetails/?id=3122396633) | Transporte pesado | Ala fija | Variantes del C-130 Hercules. | Logística aérea, paracaidismo, transporte estratégico |
| [F/A-18E/F Super Hornet 2020](https://steamcommunity.com/sharedfiles/filedetails/?id=2131302796) | Caza embarcado | Naval | Caza multirrol embarcado en portaaviones. | Superioridad aérea y ataque naval |
| [F-16 Fighting Falcon](https://steamcommunity.com/sharedfiles/filedetails/?id=366423278) | Caza multirrol | Ala fija | Caza F-16 moderno. | Dogfight, CAS, interdicción |
| [F-16V Fighting Falcon](https://steamcommunity.com/sharedfiles/filedetails/?id=3392051103) | Caza multirrol | Ala fija | Variante avanzada del F-16. | Superioridad aérea moderna |
| [F-35B Lightning](https://steamcommunity.com/sharedfiles/filedetails/?id=3517620967) | Caza STOVL | Naval | Variante de despegue corto/aterrizaje vertical. | Operaciones desde LHA o FOB |
| [F-35C Lightning](https://steamcommunity.com/sharedfiles/filedetails/?id=3083645332) | Caza embarcado | Naval | Variante naval del F-35. | Operaciones desde portaaviones CATOBAR |
| [FIR AWS (AirWeaponSystem)](https://steamcommunity.com/sharedfiles/filedetails/?id=366425329) | Sistema de armamento aéreo. | CBA_A3 | Bombas, misiles, pods | Soporte para jets y helicópteros |
| [Hatchet H-60 pack - Stable Version](https://steamcommunity.com/sharedfiles/filedetails/?id=1745501605) | Helicópteros utilitarios | Naval/Terrestre | Familia UH-60 con variantes navales. | Transporte, inserciones, MEDEVAC |
| [Hatchet Interaction Framework - Stable Version](https://steamcommunity.com/sharedfiles/filedetails/?id=2941986336) | Framework de interacción Hatchet. | CBA_A3 (común) | Framework | Soporte a mods Hatchet |
| [Improved RHS MiG-29SM + FIR support](https://steamcommunity.com/sharedfiles/filedetails/?id=2987850906) | Caza multirrol | Ala fija | Mejora del MiG-29. | Superioridad aérea OPFOR |
| [Lala Peral - Vehicle Interaction System](https://steamcommunity.com/sharedfiles/filedetails/?id=3083512801) | Interacción con vehículos (sistema). | N/D | Jugabilidad | Soporte/acciones en vehículos |
| [LHA](https://steamcommunity.com/sharedfiles/filedetails/?id=3596653038) | Buque anfibio portaaeronaves | Naval | Buque tipo LHA capaz de operar helicópteros y STOVL. | Operaciones anfibias y aeronavales |
| [Nimitz Experimental Build](https://steamcommunity.com/sharedfiles/filedetails/?id=1697731012) | Portaaviones | Naval | Portaaviones USS Nimitz funcional. | Operaciones embarcadas completas |
| [USAF Mod - Fighters](https://steamcommunity.com/sharedfiles/filedetails/?id=2397371875) | Aeronaves de combate | Ala fija | Pack de cazas USAF. | Operaciones aéreas modernas |
| [USAF_AC130_BETA](https://steamcommunity.com/sharedfiles/filedetails/?id=2226368165) | Gunship | Ala fija | AC-130 con armamento lateral. | Apoyo aéreo persistente |
| [USAF Mod - Main](https://steamcommunity.com/sharedfiles/filedetails/?id=2397360831) | USAF core (dependencia). | CBA_A3 (común) | Aviación | Base USAF mod |

---
