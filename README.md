# Sistema de Gestión de Consultorio Médico

## Descripción
El **Sistema de Gestión de Consultorio Médico** es una aplicación de escritorio desarrollada en **Java SE** bajo el paradigma de **Programación Orientada a Objetos (POO)**, utilizando **Swing** para la interfaz gráfica de usuario.
Su objetivo es optimizar la administración de doctores y pacientes, permitiendo su registro, la asignación de niveles de prioridad y la gestión de turnos de atención.
El sistema simula el flujo real de trabajo en un consultorio, desde el alta de personal médico hasta la atención de pacientes en orden de urgencia.

---

## Requisitos del sistema
- **Java SE** 8 o superior.
- Entorno de desarrollo compatible (**IntelliJ IDEA**, **NetBeans** o **Eclipse**).
- Sistema operativo con soporte para Java (Windows, Linux o macOS).

---

## Estructura del proyecto
- **Main.java**: Punto de entrada de la aplicación; inicializa la interfaz gráfica y carga los componentes.
- **AppUI.java**: Clase encargada de la interfaz principal y la gestión de eventos de usuario.
- **Doctor.java**: Clase modelo que representa a un médico, con sus atributos y métodos asociados.
- **Patient.java**: Clase modelo que representa a un paciente, incluyendo la lógica para manejar niveles de prioridad (por ejemplo: ALTA, MEDIA, BAJA).

---

## Funcionalidades
- Menú principal para navegación entre las funciones del sistema.
- Registro de doctores con información esencial.
- Registro de pacientes con datos personales y prioridad de atención.
- Ordenamiento automático de la lista de pacientes según la prioridad asignada y el orden de registro.
- Gestión de turnos: selección del paciente en turno, marcado como atendido y paso al siguiente.
- Interfaz gráfica clara e intuitiva para facilitar el uso.

---

## Instrucciones de uso
1. Ejecutar la clase principal del proyecto (**Main**).
2. Desde el menú principal:
   - Registrar doctores ingresando nombre, especialidad y demás datos requeridos.
   - Registrar pacientes con datos personales y asignación de prioridad.
3. El sistema validará:
   - Que no existan campos vacíos.
   - Que la prioridad asignada sea válida (ALTA, MEDIA o BAJA).
4. Los pacientes se mostrarán en una lista ordenada por prioridad y orden de registro.
5. Desde la interfaz, se podrá seleccionar un paciente para atención y marcarlo como atendido.

---

## Ayuda y solución de problemas
- **Datos vacíos**: Todos los campos deben completarse para registrar doctores o pacientes.
- **Prioridad inválida**: Solo se aceptan valores predefinidos (ALTA, MEDIA o BAJA).
- **Lista de pacientes vacía**: Registre al menos un paciente antes de gestionar turnos.
- **Registros duplicados**: Evite ingresar la misma información para doctores o pacientes salvo que sea intencional.

---

## Contacto
En caso de dudas o problemas técnicos, puede comunicarse a:
- 2330242@upv.edu.mx
- 2330309@upv.edu.mx
- 2330014@upv.edu.mx
- 2330222@upv.edu.mx

---

## Autores
- Joshua André Alvarado Tovar
- Diego Emmanuel Salas Morales
- Ángel Guadalupe Rivera Portillo
- Manuel Alejandro Rodríguez Reséndiz
