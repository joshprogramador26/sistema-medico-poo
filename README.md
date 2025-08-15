#  Sistema de atención médica, con uso de hilos

##  Descripción
Este sistema simula un centro de atención médica virtual donde los pacientes son atendidos por doctores según su nivel de prioridad. Utiliza una cola de prioridad y múltiples hilos para simular atención concurrente. La interfaz gráfica permite registrar pacientes, monitorear doctores y visualizar el registro de actividades.

##  Requisitos del sistema
- Java SE 8 o superior
- IDE compatible (Eclipse, IntelliJ, NetBeans)
- No requiere librerías externas

##  Estructura del proyecto
- `AppUI`: Interfaz gráfica principal con pestañas para recepción, consultorios y panel de control
- `Doctor`: Hilo que simula la atención de pacientes
- `Patient`: Modelo que representa a un paciente con su prioridad
- `Main`: Clase principal que inicia el sistema

##  Funcionalidades
- Registro de pacientes con niveles de prioridad: Emergencia, Urgente, Consulta general
- Cola de prioridad que asegura atención preferente a casos urgentes
- Simulación de 3 doctores trabajando en paralelo
- Generación automática de pacientes aleatorios
- Visualización en tiempo real del estado de cada doctor
- Registro detallado de actividades del sistema
- Interfaz moderna, intuitiva y responsive

##  Instrucciones de uso
1. Ejecuta la clase `Main` para iniciar el sistema
2. En la pestaña **Recepción**:
   - Ingresa el nombre del paciente
   - Selecciona la prioridad
   - Haz clic en **Registrar Paciente**
3. En la pestaña **Consultorios**:
   - Observa el estado de cada doctor (Libre o Atendiendo)
4. En la pestaña **Panel de Control**:
   - Visualiza el registro completo de actividades
   - Incluye tiempos de espera por paciente

##  Características técnicas
- Uso de `PriorityBlockingQueue` para la cola de pacientes
- Implementación de hilos con `Runnable` para doctores concurrentes
- Sincronización segura usando estructuras concurrentes
- Interfaz gráfica con Swing
- Actualización de UI desde hilos secundarios con `SwingUtilities.invokeLater`
- Tiempos de atención aleatorios (1–5 segundos)
- Generación automática de pacientes cada 3 segundos

##  Posibles errores y soluciones
| Problema | Solución |
|---------|----------|
| Interfaz no responde | Usa `SwingUtilities.invokeLater` para actualizar la UI |
| Pacientes no se atienden por prioridad | Verifica que `Patient` implemente correctamente `Comparable` |
| Doctores no cambian de estado | Asegúrate de llamar `updateDoctorStatus` correctamente |
| Registro no se actualiza | Confirma que `addLog` se invoque en cada evento importante |

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

##  Agradecimientos

¡Muchas gracias! 
