## 🔖 _Taller 2 - Modelo_Informacion_

## 👥 Integrantes del equipo
- Juliana Moreno
- Esteban Díaz

## 🧠 Descripción general del trabajo
Modelar las entidades principales del dominio del cliente y los flujos de información entre actores y sistemas, mediante un modelo entidad-relación (ERD) y un diagrama de contexto de negocio.

## 🔧 Proceso de desarrollo
Lo primero que realizamos fue identificar las entidades que ya teníamos, luego de esto, asignamos unos atributos que definimos necesarios para un proceso de negocio. Con esto realizado, comenzamos con las relaciones y cardinalidades de cada una de las entidades. Con esto realizado, fue más fpacil entender cómo realizar el Diagrama de Contexto de Negocio teniendo en cuenta que este diagrama es más técnico.

## 🧩 Análisis del modelo propuesto
El diagrama ERD de Clínica Salud Viva modela el proceso de agendamiento de citas médicas. Las entidades principales son Paciente, Cita, Médico, Especialidad, Disponibilidad y Notificación.

El paciente agenda una cita, y cada cita queda asociada a un único paciente. A su vez, cada cita es atendida por un médico, quien pertenece a una especialidad. Los médicos también tienen registrada su disponibilidad, que representa los horarios y modalidades en que pueden atender. Cuando una cita se agenda, esta reserva una disponibilidad específica y además genera una o varias notificaciones para informar o confirmar el proceso.

Los supuestos que se tomaron son los atributos de cada una de las entidades, teniendo en cuenta un contexto de centro médico y sistemas internos que podrían tener

## 📈 Diagrama final entregado


_Este documento hace parte de la entrega del taller 2 del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana._
