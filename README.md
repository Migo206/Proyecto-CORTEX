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

## Semana 7
## 3. Arquitectura de memoria

| Tipo de Memoria |             Categoría de Datos            |                               Descripción                              |                                       Ejemplo de Entrada                                      |
|:---------------:|:-----------------------------------------:|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------:|
| Semántica       | DSM-5 / CIE-10                            | Criterios diagnósticos de depresión mayor                              | F32.x Episodio depresivo mayor: ánimo deprimido, pérdida de interés, cambios en sueño/apetito |
| Semántica       | DSM-5 / CIE-10                            | Criterios de ideación suicida y factores de riesgo                     | Ideación suicida persistente con plan específico = riesgo alto                                |
| Semántica       | Guías clínicas de prevención del suicidio | Protocolos de evaluación de riesgo suicida (Columbia, SAD PERSONS)     | Preguntas directas: ideación → plan → intención → medios                                      |
| Semántica       | Protocolos de emergencias psiquiátricas   | Niveles de riesgo y acciones por nivel                                 | Riesgo inminente → llamar 112/911 inmediatamente                                              |
| Semántica       | Literatura TCC y activación conductual    | Técnicas de intervención breve                                         | Activación conductual: micro-metas diarias para contrarrestar apatía                          |
| Semántica       | Guías de contención en crisis             | Técnicas de regulación emocional                                       | Ejercicio 4-7-8: inhalar 4seg, retener 7seg, exhalar 8seg                                     |
| Semántica       | Catálogos de recursos de salud mental     | Líneas de emergencia por país/región                                   | España: 024 (línea de atención al suicidio), 112 (emergencias)                                |
| Semántica       | Ética y normativas de salud mental        | Límites de confidencialidad y divulgación obligatoria                  | Romper confidencialidad si hay riesgo inminente de vida                                       |
| Semántica       | Principios de comunicación terapéutica    | Tono, lenguaje y técnicas de escucha activa                            | Usar 'podrías' en lugar de 'debes'; validar sin juzgar                                        |
| Episódica       | Historial de conversaciones del usuario   | Interacciones previas, nivel de riesgo detectado, factores protectores | Usuario reportó ideación el 20/03; red de apoyo: hermana disponible                           |
| Episódica       | Registro de evaluaciones de riesgo        | Clasificaciones de riesgo anteriores y evolución                       | Riesgo medio el 22/03 → bajo el 25/03 tras plan de seguridad                                  |
| Episódica       | Planes de seguridad personalizados        | Contactos de emergencia, estrategias de coping del usuario             | Contacto: Ana (hermana) 600-XXX-XXX; coping: pasear al perro                                  |
| Episódica       | Seguimientos programados                  | Fechas y resultados de check-ins                                       | Check-in 24h: usuario reporta mejoría, mantiene compromiso de seguridad                       |
# SEMANA 8

![Grupo procesos cognitivos](https://github.com/user-attachments/assets/723da8a1-c6fe-463d-8550-1b0fdefce5eb)
