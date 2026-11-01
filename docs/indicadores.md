# Indicadores de control y estándares de desempeño

Los indicadores permiten evaluar la calidad de la información registrada, el correcto comportamiento funcional y el rendimiento técnico del Módulo de Gestión de Oportunidades Comerciales.

## 1. Indicadores y Estándares

| Indicador | Forma de medición | Estándar esperado |
| :--- | :--- | :--- |
| **Integridad de datos** | Porcentaje de registros que cuentan con todos los campos obligatorios completos. | 100% |
| **Asociación de oportunidades** | Porcentaje de oportunidades vinculadas a un cliente o prospecto registrado. | 100% |
| **Trazabilidad comercial** | Porcentaje de oportunidades que cuentan con un historial de seguimientos registrado. | 100% |
| **Disponibilidad del Sistema (Uptime)** | Tiempo que el módulo se encuentra en línea y accesible para los usuarios. | 99.9% |
| **Latencia de consultas** | Tiempo máximo de respuesta al cargar el pipeline comercial o guardar un nuevo registro. | < 10 segundos |

## 2. Mecanismos de Control

Para auditar técnicamente el sistema y alcanzar los estándares establecidos, se proponen los siguientes mecanismos:

* **Validación de campos obligatorios (Frontend/Backend):** Configurar restricciones en el sistema para impedir el guardado de información incompleta o huérfana (control de asociaciones).
* **Registro inmutable de seguimientos:** Conservar un historial automatizado de las interacciones, cambios de estado y próximas acciones de cada oportunidad.
* **Pruebas funcionales y automatizadas:** Ejecutar el 100% de los casos de prueba definidos para comprobar el comportamiento esperado de cada funcionalidad antes de su pase a producción.
* **Monitoreo de Infraestructura:** Utilizar herramientas de monitoreo en la nube para auditar constantemente los tiempos de carga y la disponibilidad del servidor.

Los indicadores permitirán detectar inconsistencias técnicas de forma temprana, asegurar la calidad de la base de datos y facilitar la adopción por parte del área comercial.