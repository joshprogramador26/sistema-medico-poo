# Sistema de Gestión de Consultorio Médico

## Descripción
Este sistema permite administrar de forma sencilla **doctores** y **pacientes** en un consultorio, gestionando el registro y priorización de la atención médica.  
Fue desarrollado en **Java** con **Swing** como interfaz gráfica, y simula el flujo real de trabajo en un consultorio: registro de personal médico, registro de pacientes y gestión de la lista de atención según urgencia.

---

## Requisitos del sistema
- **Java SE** 8 o superior
- IDE compatible (**IntelliJ IDEA**, **NetBeans**, **Eclipse**)

---

## Estructura del proyecto
- **Main.java**: Clase principal que inicia la aplicación.
- **AppUI.java**: Ventana principal con la interfaz gráfica y control de eventos.
- **Doctor.java**: Modelo que representa a un médico registrado.
- **Patient.java**: Modelo que representa a un paciente, incluyendo su prioridad de atención.

---

## Funcionalidades
- Menú principal para acceder a las funciones del sistema.
- Registro de doctores con sus datos básicos.
- Registro de pacientes con información personal y nivel de prioridad.
- Visualización de la lista de pacientes ordenada por prioridad.
- Gestión de turnos para atención médica.
- Interfaz gráfica sencilla e intuitiva.

---

## Instrucciones de uso
1. **Ejecuta** la clase principal del proyecto (`Main`).
2. Desde el menú principal:
   - **Registrar doctor** ingresando nombre, especialidad y demás datos solicitados.
   - **Registrar paciente** con nombre, datos personales y prioridad.
3. El sistema verificará:
   - Que los datos ingresados sean válidos (sin campos vacíos).
   - Que el paciente tenga asignada una prioridad correcta.
4. Una vez registrados, los pacientes aparecerán en la lista ordenada por prioridad.
5. Los turnos se gestionan desde la interfaz, permitiendo seleccionar y marcar como atendido al paciente actual.

---

## Ayuda sobre el proyecto
Errores comunes y sus soluciones:
- **Datos vacíos**: Todos los campos deben ser llenados para registrar doctores o pacientes.
- **Prioridad inválida**: Debe seleccionarse una prioridad existente (por ejemplo: Alta, Media, Baja).
- **Lista vacía**: Si no hay pacientes registrados, no se podrá gestionar turnos.
- **Registro duplicado**: Verificar que no se ingresen doctores o pacientes con datos idénticos innecesariamente.

---

## Contacto
En caso de dudas o problemas técnicos, usted puede comunicarse a:
- **2330242@upv.edu.mx**
- **2330309@upv.edu.mx**
- **2330014@upv.edu.mx**
- **2330222@upv.edu.mx**


---
