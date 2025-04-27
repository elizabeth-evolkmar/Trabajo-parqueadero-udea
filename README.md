# Trabajo-parqueadero-udea
Gestión de Parqueadero Parking Express.

Integrantes del grupo:
Tatiana Carvajal Carvajal
Luis Eduar León Bernal
Elizabeth Escobar Volkmar

Descripción del Problema.
El parqueadero Parking Express brinda servicio exclusivamente para carros a la Universidad de Antioquia. Actualmente, el registro de entrada y salida de vehículos se realiza manualmente, lo que puede generar errores y lentitud en el servicio.
- Se busca automatizar este proceso a través de un programa, que permita:
- Registrar usuarios y vehículos.
- Ingresar y retirar vehículos.
- Generar recibos de ingreso y cobros.
- Crear reportes administrativos.

## Objetivo del proyecto.
- Automatizar la gestión de Parking Express, permitiendo registrar usuarios, controlar el ingreso y salida de vehículos, calcular pagos y generar reportes básicos, todo a través de una interfaz sencilla y amigable para el usuario.
- Gestionar la información de forma organizada, reduciendo errores humanos y mejorando la eficiencia del parqueadero.
- Suplir las necesidades de cada uno de los roles (administrador, conductores y encargados) donde el software sea fácil de usar, ingreso rápido de datos y el registro de información y registro de pagos sea confiable 
### 3. Funcionalidades y requisitos.

### 3.1 Funcionalidades obligatorias.
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
Interfaz simple e intuitiva.
Mensajes de error comprensibles para el usuario.
Código documentado internamente.
