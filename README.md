# Trabajo-parqueadero-udea
Gestión de Parqueadero Parking Express.

Integrantes del grupo: 
- Tatiana Carvajal Carvajal; Soy de la carrera ingenieria industrial sede Turbo modalidad virtual, me considero una persona con buena capacidad de escucha, trabajo en equipo y disposicion para el aprendinzaje continuo.
- Luis Eduar León Bernal ; Soy de la carrera de ingenieria industrial sede Sonson en entorno virtual, me considero una persona muy neurtra, reactivo y exhibir rigor intelectual al abordar y comprender problemas. 
- Elizabeth Escobar Volkmar: Soy de la carrera de ingenieria industrial sede Medellin en modalidad virtual, me considero una persona con comunicación efectiva, proactiva y con buena capacidad de analisis 

Descripción del Problema.

<img src="logo trabajo final.jfif" alt="Logo" width="200"/> 
El parqueadero Parking Express brinda servicio exclusivamente para carros a la Universidad de Antioquia. Actualmente, el registro de entrada y salida de vehículos se realiza manualmente, lo que puede generar errores y lentitud en el servicio.
Se busca automatizar este proceso a través de un programa, que permita:

- Registrar usuarios y vehículos.
- Ingresar y retirar vehículos.
- Generar recibos de ingreso y cobros.
- Crear reportes administrativos.

## Objetivo del proyecto.
- Automatizar la gestión de Parking Express, permitiendo registrar usuarios, controlar el ingreso y salida de vehículos, calcular pagos y generar reportes básicos, todo a través de una interfaz sencilla y amigable para el usuario.
- Gestionar la información de forma organizada, reduciendo errores humanos y mejorando la eficiencia del parqueadero.
- Suplir las necesidades de cada uno de los roles (administrador, conductores y encargados) donde el software sea fácil de usar, ingreso rápido de datos y el registro de información y registro de pagos sea confiable
  
### 3. Funcionalidades y requisitos.

**Funcionalidades:**

-Control de acceso y salida.
-Registro de vehículos.
-Gestión de tarifas y pagos.

**Requisitos:**

-Sistema de facturación electrónica.
-Sensores de presencia o detectores de ocupación.
-Barreras automáticas o torniquetes.
-Conectividad a internet estable.

### 3.1 Funcionalidades obligatorias.

-Informes de ingresos, salidas y recaudo.
-Captura de hora de entrada y salida.
-Visualización en pantalla de espacios disponibles.
-Cámaras integradas al sistema.

#### Registro de Usuarios: Permite registrar los datos personales del usuario y su vehículo.
Nombre (mínimo 3 letras, sin números).
Apellido (mínimo 3 letras, sin números).
Documento de identidad (3 a 15 dígitos, solo números).
Placa del vehículo (exactamente 6 caracteres: 3 letras seguidas de 3 números).
Validaciones:
Comprobación del formato y contenido de cada dato.
Mostrar mensajes de error claro si los datos no cumplen las condiciones.

#### Ingreso de Vehículo: Permite registrar el ingreso de un vehículo al parqueadero.
Solo vehículos de usuarios registrados pueden ingresar.
Se debe registrar la hora y minuto exacto de entrada.
Se genera un recibo de ingreso que se muestra en pantalla.

#### Retiro de Vehículo: Permite registrar la salida del vehículo y calcular el cobro.
Solo usuarios registrados pueden retirar vehículos.
Se calcula el tiempo de permanencia exacto (horas y cuartos de hora).
Cálculo del cobro:
7000 pesos por cada hora completa.
1500 pesos por cada cuarto de hora adicional.
Pago mínimo: Si el total es menor de 7000 pesos, se cobra 7000 pesos.
#### Gestión Administrativa: Permite acceder a reportes de gestión mediante autenticación (usuario y contraseña).
Reportes que debe generar:
Total de vehículos registrados.
Total de vehículos retirados.
Total de vehículos actualmente parqueados.
Total de dinero recaudado por concepto de pagos.
Tiempo promedio de permanencia de los vehículos.
Listado de usuarios registrados.
Identificación del vehículo con mayor y menor tiempo de permanencia.
Exportación de Datos: Permite exportar toda la información relevante a archivos planos CSV.
Datos exportables:
Usuarios registrados.
Ingresos y retiros de vehículos.
Resúmenes de reportes administrativos.

### 3.2 Requisitos tecnicos
- Lenguaje de programación: Python
- Entorno de desarrollo: Visual Studio Code o Google Collab
- Bibliotecas: csv (para manejo de archivos CSV) y datetime (para manejo de fechas y horas).

### 3.3 Requisitos Funcionales
Manejo de datos básico
Validaciones de entradas
Organización en funciones para la estructura del código.
Exportación e importación de datos en CSV.

### 3.4 Requisitos No Funcionales
- Interfaz simple e intuitiva.
- Mensajes de error comprensibles para el usuario
- Código documentado internamente.
- El sistema debe de tener una respuesta rapida
- El sistema administrativo debe estar seguro, para ello debe ser funcional la autentico con usuario y cntraseña
- Asegurar que la información registrada sea correcta

### 4. Prioridades y alcances,

- **Alcance del proyecto actual:** Cubrir las funcionalidades críticas para operar un parqueadero de forma básica y confiable desde la consola.

- **Priorización:** Primero asegurar registro, control de vehículos y cobros; luego reportes y exportación de datos.

- **Roadmap futuro:** Mejoras opcionales orientadas a optimizar la experiencia de usuario y escalabilidad del sistema.

### 5. Limitaciones y Restricciones

- el manejo de exportes solo se manejará en formato CSV
- Solo se usará el lenguaje de Python y no tendra una interfaz grafica
- Al no tener un presupuesto para el proyecto solo se usaran herramientas gratuitas y que permitan realizan trabajo colaborativo

### 6. Interfaz y experiencia de usuario

El alcance del proyecto para el parqueadero Parcking Express será una visual de consola, es decir, solo va a funcionar bajo textos e ingreso de información, no contará con menú o diseños elaborados

### 7. Pruebas y calidad.

la aplicación debe ser funcional y estable, garantizando errores minimos que noa fecten operacion ni experiencia. Los criterios de aceptación incluyen registrar usuarios correctamente, permitir ingreso y retiro de vehículos, calcular costos y generar reportes; todas las funciones deben ser demostrables. 

Las pruebas se gestionarán realizando validaciones manuales a medida que avance el codigo, es decir, pruebas unitarias, las pruebas de aceptación se realizaran con el cliente final (profesor) y las pruebas funcionales seran realizadas por el equipo que desarrolla el codigo antes de la entrega.

### 8.  riesgos y mitigación

Los riesgos principales son errores de cálculo en el cobro, pérdida de datos o fallas de validación de usuarios.

### 9. Colaboración y Comunicación

El grupo se compromete a participar activamente en todas las etapas del proyecto, cumpliendo con las tareas asignadas y los tiempos establecidos. La comunicación se mantendrá constante y organizada a través de WhatsApp y GitHub, permitiendo la coordinación efectiva del trabajo y la resolución oportuna de cualquier inconveniente.

## Plan de trabajo 

Acontinuacion se detalla el plan de trablajo con tiempos estimados

##### Planificación (Horas: 5)
Definir requisitos del sistema, estructura de datos, lógica básica del programa, dividir tareas entre los miembros del equipo.
Responsables: Todos los miembros.
Duración: 5 horas.

##### Primeros pasos (Horas: 15)
Crear el sistema de registro de usuarios, ingresar vehículos, validaciones de datos (nombre, documento, placa).
Responsables: Persona 1 (6 horas), Persona 2 (6 horas), Persona 3 (3 horas).
Duración: 15 horas.

##### Segunda Fase reportes (Horas: 15)
Implementar generación de reportes, cálculos de tarifas, autenticación de administrador.
Responsables: Persona 2 (6 horas), Persona 3 (6 horas), Persona 1 (3 horas).
Duración: 15 horas.

##### pruebas y ajustes (Horas: 10)
Realizar pruebas de aceptación, corregir errores, optimizar el sistema, documentar código.
Responsables: Persona 1 (4 horas), Persona 2 (3 horas), Persona 3 (3 horas).
Duración: 10 horas.

| Actividad  | Horas totales | Horas Tatiana  | Horas Luis | Horas Elizabeth  | Observaciones / Version estimada para entrega |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Planificacion  |   |   |  |  |   |
| Primeros pasos  |   |   |  |  |   |
| Segunda Fase reportes  |   |   |  |  |   |
| pruebas y ajustes |   |   |  |  |   |
| entrega |   |   |  |  |   |
