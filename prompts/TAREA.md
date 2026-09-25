# Tarea: Mi prompt profesional

## Funcionalidad elegida
Sistema de registro y gestión de pacientes para un área de admisión hospitalaria en Python.

## Version 1: prompt basico

```text
Crea un programa para registrar pacientes.
```

- **Qué cambió:** Es el punto de partida genérico.

- **Por qué se cambió:** Carece de contexto técnico y reglas de negocio.

- **Qué mejoró:** Genera una estructura muy simple y abierta.


## Version 2

```text
Actúa como desarrollador Python. Crea un programa para registrar pacientes en un hospital usando una lista.
```
- **Qué cambió:** Se añadió el rol técnico y el contexto del hospital.

- **Por qué se cambió:** Para orientar el código al lenguaje y al sector salud.

- **Qué mejoró:** El enfoque ya responde a la temática hospitalaria.


## Version 3: prompt final
```text
Actúa como desarrollador Python senior. Crea un script para registrar pacientes de un hospital usando un diccionario que guarde DNI, nombre y especialidad médica. Por ejemplo, la estructura debe incluir entradas como: {"dni": "12345678", "nombre": "Ana Pérez", "especialidad": "Cardiología"}. Explica primero la lógica del código y luego preséntalo comentado. Restricción: no uses librerías externas.
```
- **Qué cambió:** Se integraron rol, instrucción, contexto, ejemplo, formato y restricciones estrictas.

- **Por qué se cambió:** Para asegurar un resultado limpio, profesional y estructurado.

- **Qué mejoró:** La IA estructuró la explicación teórica separada del código y cumplió con las restricciones.

## Componentes del prompt final 

|**Componente** |                 **Text de mi prompt**             | 
|---------------|---------------------------------------------------|
|    **Rol**    |Actúa como desarrollador Python senior.|
|**Instrucción**|Crea un script para registrar pacientes de un hospital...|
|  **Contexto** |...usando un diccionario que guarde DNI, nombre y especialidad médica.|
|  **Ejemplo**  |Por ejemplo, la estructura debe incluir entradas como: {"dni": "12345678", "nombre": "Ana Pérez", "especialidad": "Cardiología"}|
|  **Formato**  |Explica primero la lógica del código y luego preséntalo comentado.|
|**Restricción**| No uses librerías externas. |
## Evaluacion del resultado

|             **Preguntas**                                   |**Cumple** (Si/No)|
|-------------------------------------------------------------|------------------|
|¿Está escrito en Python?                                     |        Si        |
|¿Registra los datos del paciente (DNI, nombre, especialidad)?|        Si        |
|¿Respeta la restricción de no usar librerías externas?       |        Si        |
|¿Explica la teoría antes de presentar el código?             |        Si        |

## Errores que evite
- **Ser demasiado general:**
 Evitado al especificar exactamente qué datos del paciente registrar (DNI, nombre, especialidad) en lugar de pedir un sistema médico al aire.

- **No indicar el formato:** 
Evitado al ordenar explícitamente a la IA que separe la explicación teórica del bloque de código.