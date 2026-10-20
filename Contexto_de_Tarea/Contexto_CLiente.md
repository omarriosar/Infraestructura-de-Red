## Diseño de infraestructura de red para *Traveler*

### Contexto del proyecto
A partir del croquis arquitectónico de distribución y los requerimientos operativos de la empresa *Traveler*, se definieron las especificaciones técnicas iniciales para el despliegue de la infraestructura de red y cableado estructurado. 

Durante el levantamiento de requerimientos con el área de arquitectura, se establecieron los siguientes tipos de nodos y dispositivos finales:

---

### Especificación de nodos y servicios

#### 1. Estaciones de trabajo fijas
Áreas asignadas al personal operativo para labores continuas.
* 1 nodo para computadora de escritorio.
* 1 nodo para teléfono IP (VoIP).

#### 2. Estaciones de trabajo fijas con impresora
Puestos asignados con necesidad de impresión.
* 1 nodo para computadora de escritorio.
* 1 nodo para teléfono IP (VoIP).
* 1 nodo para impresora de inyección de tinta en red.

#### 3. Estaciones de trabajo para equipos portátiles
Espacios temporales destinados a usuarios con computadoras portátiles que requieran conexión física a los servicios corporativos:
* 1 nodo de datos por estación para acceso alámbrico de alta disponibilidad.

#### 4. Sistema de videovigilancia IP (CCTV)
* Nodos de red dedicados para la instalación de cámaras IP en los puntos estratégicos señalados en el plano.
* El grabador de video en red (NVR) se concentrará directamente en el **Cuarto de Telecomunicaciones** (TR/MDF).

#### 5. Impresión de gran formato / Alto volumen
* 1 nodo de datos dedicado en el área de exhibición para una impresora corporativa de alta capacidad.
