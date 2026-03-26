# Proyecto-CORTEX- Asistente Virtual Psicólogo contra el suicidio
# Integrantes
**Miguel Argote Jaramillo** 
**Bellairis Giraldo Salazar**
# 1.Perfil del agente

![Grupo procesos cognitivos](https://github.com/user-attachments/assets/5ef6df92-d009-49b1-949d-616d0827add6)

# 2.Mapa de procesos

## Principales procesos cognitivos
- Atención y Percepción: 9/10 El bot necesita detectar señales de alerta, palabras clave, cambios en el tono emocional y patrones de riesgo en tiempo real. No puede perderse ningún indicador crítico de crisis.
- Aprendizaje y Memoria: 8/10 Debe recordar conversaciones previas del usuario, patrones de comportamiento y contexto personal para ofrecer apoyo personalizado. Sin embargo, no necesita aprender de forma autónoma sin supervisión (por seguridad).
- Procesamiento Lingüístico: 10/10 Fundamental para entender expresiones sutiles de angustia, frases indirectas sobre autolesión, diferentes formas de pedir ayuda, y comunicarse con empatía y claridad en momentos críticos.
- Pensamiento y Razonamiento: 9/10 Necesita evaluar nivel de riesgo, decidir cuándo escalar a ayuda profesional, ofrecer estrategias apropiadas según el contexto, y mantener coherencia en conversaciones complejas y emotivas.
- Motivación, Cognición y Emoción: 10/10 Es el corazón del bot. Debe demostrar empatía genuina, validar emociones, motivar hacia la vida y la ayuda profesional, y manejar estados emocionales intensos con sensibilidad.
  
  
![Grupo procesos cognitivos](https://github.com/user-attachments/assets/631513dc-599f-471f-ba6a-069a9715d05a)

# Segunda fase semana 4

![Grupo procesos cognitivos](https://github.com/user-attachments/assets/d603c52a-ddbd-4600-b9f6-175901232d29)

# Segunda fase semana 5

![Grupo procesos cognitivos](https://github.com/user-attachments/assets/7caf10f4-18b9-4716-9469-4f576d670476)

# Segunda fase semana 6
## Arquitectura de Atención con las reglas lógicas definidas.

El asistente debe primero detectar señales de riesgo inmediato en el mensaje, como expresiones de querer morir, intención clara, referencias de tiempo o medios, activando un protocolo urgente si aparecen.

También debe analizar la extensión del mensaje: en textos largos, enfocarse en palabras clave de peligro, la última frase y cambios de tono; en mensajes cortos, cada palabra, la puntuación y la posible desconexión emocional.

El contexto importa: si es el primer contacto, se prioriza presentarse y evaluar lo básico; si ya hubo interacción reciente, se compara el progreso; y si el mensaje llega de madrugada, se presta más atención a crisis o impulsividad.

El lenguaje absoluto puede indicar aislamiento, por lo que se debe validar y explorar apoyo. Además, hay que observar la funcionalidad diaria: dificultades básicas requieren intervención, mientras que pequeños logros deben reforzarse.

Los emojis ayudan a interpretar emociones, especialmente si contradicen el texto. Para evaluar riesgo, se sigue un orden: ideación, plan, intención y medios, sin presionar si la persona evita responder.

No se deben priorizar detalles irrelevantes ni usar respuestas genéricas o simplistas. Al cerrar, se resume lo hablado, se establecen próximos pasos, se recuerdan recursos de ayuda y, si hay múltiples señales graves, se activa un protocolo de riesgo inminente.

## 3. Arquitectura de memoria

|       Tipo de Memoria      |               Categoría de Datos               |                                                   Descripción                                                  |                                   Ejemplo de Entrada                                   |   |
|:--------------------------:|:----------------------------------------------:|:--------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|---|
| CONOCIMIENTO CLÍNICO       | Definiciones de trastornos                     | Glosario permanente de conceptos clínicos clave: depresión, ideación suicida, crisis emocional y relacionados. | Entrada tipo: "Depresión – definición breve + rasgos nucleares"                        |   |
| CONOCIMIENTO CLÍNICO       | Señales de alarma y síntomas                   | Listado de signos observables y autorreportados que sugieren riesgo o episodios depresivos.                    | Entrada tipo: "Señal: insomnio persistente; Categoría: ánimo/biología"                 |   |
| CONOCIMIENTO CLÍNICO       | Factores de riesgo y protectores               | Inventario de factores que aumentan/disminuyen el riesgo; cómo ponderarlos.                                    | Entrada tipo: "Riesgo: plan específico; Protector: red de apoyo cercana"               |   |
| CONOCIMIENTO CLÍNICO       | Criterios diagnósticos de referencia           | Resumen de criterios estandarizados usados como marco orientativo (no para diagnosticar).                      | Entrada tipo: "Depresión mayor – criterios de referencia resumidos"                    |   |
| CONOCIMIENTO CLÍNICO       | Fundamentos teóricos aplicables                | Principios de modelos útiles: activación conductual, terapia cognitiva y psicoeducación breve.                 | Entrada tipo: "Activación conductual – pasos básicos y ejemplos"                       |   |
| PROTOCOLOS DE INTERVENCIÓN | Evaluación de riesgo suicida – preguntas clave | Estructura de preguntas sistemáticas para ideación, plan, intención y medios.                                  | Entrada tipo: "Pregunta: ¿Has pensado en hacerte daño?"                                |   |
| PROTOCOLOS DE INTERVENCIÓN | Niveles de riesgo                              | Taxonomía de clasificación: bajo, medio, alto, inminente, con criterios orientativos.                          | Entrada tipo: "Alto – ideación + plan + acceso a medios"                               |   |
| PROTOCOLOS DE INTERVENCIÓN | Acciones por nivel de riesgo                   | Checklist de pasos específicos según nivel, incluyendo escalación cuando aplique.                              | Entrada tipo: "Riesgo medio – contrato de seguridad + consulta en 24–48h"              |   |
| PROTOCOLOS DE INTERVENCIÓN | Técnicas de contención inmediata               | Técnicas breves de regulación: respiración, grounding, orientación sensorial.                                  | Entrada tipo: "Ejercicio 4‑7‑8 – instrucciones resumidas"                              |   |
| PROTOCOLOS DE INTERVENCIÓN | Estructura de planes de seguridad              | Plantilla de plan: señales, estrategias internas, contactos, recursos, ambiente seguro.                        | Entrada tipo: "Sección: Personas a contactar – nombre/relación/teléfono"               |   |
| RECURSOS Y DERIVACIÓN      | Líneas de emergencia por país/región           | Catálogo indexado de teléfonos/servicios de emergencia por ubicación.                                          | Entrada tipo: "País/Región – número de emergencia principal"                           |   |
| RECURSOS Y DERIVACIÓN      | Servicios de salud mental                      | Directorio de centros, telepsicología y atención comunitaria con criterios de acceso.                          | Entrada tipo: "Servicio – tipo – horario – requisitos"                                 |   |
| RECURSOS Y DERIVACIÓN      | Organizaciones de apoyo                        | Listado de ONGs y redes de pares relevantes por idioma/área.                                                   | Entrada tipo: "Organización – foco – contacto"                                         |   |
| RECURSOS Y DERIVACIÓN      | Criterios de escalación a profesional humano   | Reglas para decidir cuándo transferir/alertar a un profesional o apoyos de confianza.                          | Entrada tipo: "Escalar si: intención actual + medios disponibles"                      |   |
| RECURSOS Y DERIVACIÓN      | Guías de derivación                            | Pasos para orientar al usuario a la opción adecuada según necesidad y urgencia.                                | Entrada tipo: "Si riesgo bajo: referir a consejería universitaria"                     |   |
| PRINCIPIOS DE COMUNICACIÓN | Tono y estilo                                  | Normas de comunicación: calmo, compasivo, claro, no juzgador, directo pero sensible.                           | Entrada tipo: "Directriz: usar 'podrías' en vez de 'debes'"                            |   |
| PRINCIPIOS DE COMUNICACIÓN | Técnicas de escucha activa                     | Estrategias de reflejo, resumen, verificación y validación emocional.                                          | Entrada tipo: "Reflejo: 'Lo que entiendo es que...'"                                   |   |
| PRINCIPIOS DE COMUNICACIÓN | Frases modelo de validación                    | Banco de enunciados seguros para normalizar y validar emociones.                                               | Entrada tipo: "Gracias por compartir esto; estoy aquí contigo"                         |   |
| PRINCIPIOS DE COMUNICACIÓN | Lenguaje inclusivo                             | Guías para lenguaje respetuoso, sensible a género, cultura y contexto.                                         | Entrada tipo: "Pedir pronombres y evitar supuestos"                                    |   |
| PRINCIPIOS DE COMUNICACIÓN | Preguntas abiertas vs. cerradas                | Cuándo usar abiertas para exploración y cerradas para clarificar riesgo.                                       | Entrada tipo: "Abierta: ¿Cómo te has sentido hoy? / Cerrada: ¿Tienes acceso a medios?" |   |
| ÉTICA Y LÍMITES            | Confidencialidad y excepciones                 | Política base y situaciones de divulgación obligatoria por seguridad.                                          | Entrada tipo: "Excepción: riesgo inminente para la vida"                               |   |
| ÉTICA Y LÍMITES            | Consentimiento informado                       | Proceso accesible, claro y acorde a la edad para uso y límites del servicio.                                   | Entrada tipo: "Consentimiento: alcance + uso de datos + opciones"                      |   |
| ÉTICA Y LÍMITES            | Límites del bot                                | Alcance explícito: no diagnostica ni sustituye atención profesional/emergencias.                               | Entrada tipo: "Aviso estándar de limitaciones"                                         |   |
| ÉTICA Y LÍMITES            | Políticas de privacidad de datos               | Principios de minimización, retención, seguridad, anonimización y transparencia.                               | Entrada tipo: "Solo recolectar datos necesarios para seguridad"                        |   |
| ÉTICA Y LÍMITES            | Manejo de sesgos                               | Prácticas para detectar, mitigar y monitorear sesgos; sensibilidad cultural.                                   | Entrada tipo: "Revisión periódica de lenguaje y decisiones"                            |   |
| FLUJOS DE INTERACCIÓN      | Secuencia de contacto inicial                  | Script de presentación, verificación de seguridad, obtención de consentimiento.                                | Entrada tipo: "Presentación + límites + pregunta de bienestar inmediato"               |   |
| FLUJOS DE INTERACCIÓN      | Pasos de evaluación de riesgo                  | Orden lógico de preguntas y decisiones para clasificar el riesgo.                                              | Entrada tipo: "Ideación → plan → intención → medios → protectores"                     |   |
| FLUJOS DE INTERACCIÓN      | Estructura de apoyo continuo                   | Plantilla de psicoeducación breve, coping y micro‑metas entre crisis.                                          | Entrada tipo: "Agenda de micro‑acciones semanales"                                     |   |
| FLUJOS DE INTERACCIÓN      | Protocolo de seguimiento                       | Frecuencia, contenidos y verificación de seguridad en 24–48h y posteriores.                                    | Entrada tipo: "Recordatorio de recursos + revisión de plan"                            |   |
| FLUJOS DE INTERACCIÓN      | Transición a profesional humano                | Procedimiento para conectar con terapeuta, emergencias o red de apoyo.                                         | Entrada tipo: "Ofrecer llamada conjunta y compartir contactos"                         |   |
| PÚBLICO OBJETIVO           | Perfiles de usuarios                           | Caracterización de grupos principales y sus particularidades.                                                  | Entrada tipo: "Estudiante universitario; adulto con depresión"                         |   |
| PÚBLICO OBJETIVO           | Contextos de uso                               | Situaciones típicas donde aparece la necesidad.                                                                | Entrada tipo: "Estrés académico; crisis emocional"                                     |   |
| PÚBLICO OBJETIVO           | Necesidades específicas por grupo              | Requerimientos y barreras comunes por perfil.                                                                  | Entrada tipo: "Para estudiantes: apoyo académico y horarios flexibles"                 |   |
| PÚBLICO OBJETIVO           | Adaptaciones por edad y cultura                | Ajustes de lenguaje, ejemplos y recursos según edad/idioma/cultura.                                            | Entrada tipo: "Uso de lenguaje sencillo para adolescentes"                             |   |
| DO's y DON'Ts              | Acciones permitidas y recomendadas (Do's)      | Lista de conductas esperadas del bot para seguridad y eficacia.                                                | Entrada tipo: "Validar emociones; ofrecer recursos locales"                            |   |
| DO's y DON'Ts              | Acciones prohibidas (Don'ts)                   | Conductas que el bot nunca debe realizar.                                                                      | Entrada tipo: "No dar diagnósticos; no minimizar"                                      |   |
| DO's y DON'Ts              | Límites de intervención                        | Bordes operativos: cuándo detenerse y redirigir.                                                               | Entrada tipo: "Interrumpir y escalar ante riesgo inminente"                            |   |
| DO's y DON'Ts              | Errores comunes a evitar                       | Patrones de respuesta a prevenir para no dañar ni confundir.                                                   | Entrada tipo: "Evitar presionar o prometer confidencialidad absoluta"                  |   |

# SEMANA 8

![Grupo procesos cognitivos](https://github.com/user-attachments/assets/723da8a1-c6fe-463d-8550-1b0fdefce5eb)
