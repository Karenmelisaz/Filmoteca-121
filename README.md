# Filmoteca-121

<p align="center">
  <img src="Logo.jpg" alt="Logo Filmoteca 121" width="350"/>
</p>

## Descripción
Filmoteca 121 es un proyecto académico de estudiantes de Ingeniería Industrial de la UdeA. Consiste en un programa en Python que automatiza la gestión de un espacio cinematográfico en la ciudadela, permitiendo a estudiantes y personal disfrutar de funciones los fines de semana.

## Reporte de visión 
Este software tiene como objetivo gestionar el sistema universitario La Filmoteca-121, ofreciendo una manera organizada de administrar sus 121 asientos y funciones de cine de fin de semana.
Este sistema beneficiará tanto a los usuarios (estudiantes,docentes,administrativos,oficiales internos y público externo),quienes podrán reservar facilmente y obtener su factura, como a los administradores,que tendrán control centralizado sobre las reservas, los ingresos, la generación de reportes estadísticos y la gestión general de la Filmoteca-121. De esta manera, se busca mejorar la organización, reducir errores y ofrecer un experiencia mas ágil y profesional.
El alcance del software incluye: el registro y validación de usuarios, la creación y cancelaón de reservas,la consulta de funciones del fin de semana, la generación de facturas, la obtención de reportes administrativos (ventas,ingresos, usuarios con más o menos reservas), la exportación de resultados a archivos CSV y la interacción mediante un menú en consola que facilita la navegación.

## Requisisitos funcionales

- **Registro de Usuarios**: Permitir la creación de usuarios con datos básicos (nombre, documento, correo, etc.).  
- **Gestión de Reservas**: Facilitar la creación, modificación y cancelación de reservas de sillas.  
- **Consulta de Funciones**: Mostrar la cartelera disponible para el fin de semana, con asientos libres en tiempo real.  
- **Facturación**: Generar comprobantes de pago de las reservas realizadas.  
- **Módulo de Administración**: Gestión interna de reportes, ingresos y control de usuarios.  
- **Exportación de Datos**: Posibilidad de exportar reportes o información relevante en formatos externos (CSV, TXT, etc.).  
- **Interfaz de Consola**: Navegación amigable por menús, permitiendo al usuario acceder fácilmente a cada funcionalidad.  

## Requisitos No Funcionales

### Rendimiento
- El sistema debe responder en un tiempo menor a **2 segundos** en operaciones de registro, reserva y cancelación de tiquetes.  
- Debe soportar la gestión de las **121 sillas disponibles** garantizando la consistencia de los datos.  
- Las operaciones de consulta de la cartelera deben ejecutarse de manera eficiente, mostrando disponibilidad **en tiempo real**.  

### Seguridad
- El **módulo de administración** debe estar protegido con usuario y contraseña, validando contra una lista de credenciales permitidas.  
- El acceso a los **reportes administrativos** (ingresos, usuarios con más reservas, promedio de ventas, etc.) debe estar restringido únicamente al personal autorizado.  

### Fiabilidad
- El sistema debe mantener la integridad de la información: un asiento no puede asignarse a dos usuarios al mismo tiempo.  
- Ante una cancelación, el asiento debe liberarse **de inmediato** y reflejarse correctamente en el sistema.  
- El programa debe garantizar la coherencia entre reservas, facturación y reportes administrativos.  

### Usabilidad
- La interfaz de consola debe ser **amigable, clara y entendible** incluso para usuarios sin conocimientos técnicos.  
- Los errores de validación (ejemplo: nombres con números, documentos con letras, etc.) deben mostrarse con mensajes explicativos para orientar al usuario.  
- El menú principal debe permitir una navegación intuitiva entre las opciones: *registrar usuario, reservar, cancelar, consultar funciones, administración, salir*.  

### Mantenibilidad y Escalabilidad
- Se debe emplear un repositorio en **GitHub** para control de versiones, asegurando trazabilidad de los cambios.  
- El sistema debe estar diseñado para permitir la incorporación de futuras funcionalidades (ejemplo: **pago en línea, reservas múltiples, reportes adicionales**).  

## Integrantes
| Integrante                        | Perfil Académico                    | Rol en el Proyecto                           |
| --------------------------------- | ----------------------------------- | -------------------------------------------- |
| **Karen Meliza Zapata Gutiérrez** | Estudiante de Ingeniería Industrial | Líder del Proyecto – Gestión del repositorio |
| **Yuliana Andrea Quirós Pareja**  | Estudiante de Ingeniería Industrial | Documentación y actas                        |
| **Jaider Osorio González**        | Estudiante de Ingeniería Industrial | Soporte técnico y lógica interna             |
| **Luisa Fernanda Galeano Serna**  | Estudiante de Ingeniería Industrial | Gestión de módulos y seguimiento             |


## Vínculos académicos y descripción

- **Karen Meliza Zapata Gutierrez**:
Soy estudiante de Ingeniería Industrial y tengo el gusto de liderar el proyecto Filmoteca-121, además de encargarme del repositorio en GitHub. Me considero organizada, responsable y siempre con disposición para aprender y mejorar cada día. Me apasiona trabajar en equipo y comunicarme de manera clara. Tengo conocimientos en Visual Studio Code, Sublime Text y MongoDB, pero lo que más me motiva es seguir creciendo, aprendiendo nuevas herramientas y aportando al grupo de la mejor manera posible.

- **Yuliana Andrea Quiros Pareja**:
Estudiante de Ingeniería Industrial, actualmente cursando el 4º semestre en la sede Norte. Vivo en el municipio de Angostura. Mis expectativas para este grupo de trabajo son que cada integrante pueda aportar de manera significativa, logrando un flujo de trabajo efectivo y un proyecto de calidad.

- **Jaider Osorio González**:
Estudiante de Ingeniería Industrial en la Universidad de Antioquia, perteneciente a la sede Norte, con 21 años. Me interesa el aprendizaje práctico de la programación y cómo aplicarlo para optimizar procesos, mejorar la gestión de recursos y crear soluciones útiles en la vida universitaria y profesional. Me considero comprometido, organizado y con disposición para trabajar en equipo, aportando tanto al desarrollo técnico como a la coordinación de actividades dentro del proyecto. 

- **Luisa Fernanda Galeano Serna**:
Apasionada por el aprendizaje continuo y estudiante de Ingeniería Industrial. Me considero responsable, disciplinada y con capacidad para trabajar en equipo. Valoro las buenas relaciones interpersonales y procuro actuar siempre con respeto, empatía y consideración hacia los demás.

## Presupuesto
El presupuesto del proyecto se medirá en **tiempo de práctica profesional**, no en dinero.    
- Este tiempo es un estimado y puede ajustarse según el avance del proyecto y eventualidades del equipo, garantizando que todos los miembros contribuyan de manera equilibrada.

|     **Integrante**           | **Horas estimadas**|**Actividades principales**|
| -----------------------------|------------------- | --------------------------|
| Karen Meliza Zapata          |     20 horas       |     Diseñar y programar el módulo de consulta de funciones (películas disponibles, horarios y asientos libres |
| Yuliana Andrea Quiros        |     20 horas       | Desarrollar el módulo de registro de usuarios (estudiantes y asistentes del cine) |
| Jaider Osorio González       |     20 horas       |    Desarrollar el módulo de cancelación de reservas y validar la integridad de datos   |
| Luisa Fernanda Galeano Serna |     20 horas       |      Desarrollar el módulo de registro de reservas de películas y entradas       |

# Diagrama de Gantt - Proyecto Cine

**Periodo:** Septiembre – Noviembre  

| Módulo              | Responsable | S6 | S7 | S8 | S9 | S10 | S11 | S12 |
| ------------------- | ----------- | -- | -- | -- | -- | --- | --- | --- |
| Integración inicial | Todos       | ✔  |    |    |    |     |     |     |
| Registro usuarios   | Yuliana     |    | ●  | ●  |    |     |     |     |
| Reservas            | Luisa       |    | ●  | ●  |    |     |     |     |
| Cancelación         | Jaider      |    |    | ●  | ●  |     |     |     |
| Cartelera           | Karen       |    |    |    | ●  | ●   |     |     |
| Administración      | Karen       |    |    |    |    | ●   | ●   |     |
| Facturación         | Todos       |    |    |    |    |     | ●   | ●   |
| Cierre              | Todos       |    |    |    |    |     |     | ●   |

✔ = Entregado
● = Desarrollo activo

## Licencia
Filmoteca-121  © 2025 by Karen Meliza Zapata Gutiérrez, Yuliana Andrea Quirós Pareja, Luisa Fernanda Galeano Serna, Jaider Osorio González is licensed under CC BY-NC-SA 4.0. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/4.0/



