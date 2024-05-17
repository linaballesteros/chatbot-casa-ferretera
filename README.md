<h1 align="center">🛠️ Casa Ferretera - Chatbot de Atención al Cliente <img src="https://i.imgur.com/FDGi0fy.png" width="60"/> </h1>

## 📋 Descripción del Proyecto

Este repositorio contiene el backlog y documentación de un chatbot para WhatsApp diseñado para la empresa Casa Ferretera, como parte del curso de Sistemas de Información de la Universidad EAFIT. El objetivo del proyecto es mejorar la atención al cliente mediante la automatización de respuestas a consultas frecuentes y la gestión eficiente de conversaciones en WhatsApp.

## 👥 Integrantes del Equipo

- **Alejandro Ríos Muñoz**
- **Camilo Córdoba Bedoya**
- **Lina Sofía Ballesteros Merchán**
- **Manuela Caro Villada**

### Profesora
- **Liliana González-Palacio**

## Índice de Contenidos

1. [Introducción](#introducción)
2. [Descripción de la Organización](#descripción-de-la-organización)
3. [Refinamiento de la Solución Propuesta](#refinamiento-de-la-solución-propuesta)
4. [Funcionalidad Lograda](#funcionalidad-lograda)
5. [Implementación Detallada](#implementación-detallada)
6. [Indicadores y Lecciones Aprendidas](#indicadores-y-lecciones-aprendidas)
7. [Conclusiones](#conclusiones)

## 📖 Introducción

En este proceso, hemos desarrollado una solución que automatiza la atención al cliente en Casa Ferretera mediante un chatbot para WhatsApp. Esta implementación busca resolver el problema identificado durante todo el curso sobre la gestión de un elevado volumen de chats, proporcionando respuestas rápidas y mejorando la eficiencia operativa.

## 🏢 Descripción de la Organización

**Nombre:** Casa Ferretera  
**Sector:** Artículos de Construcción y Ferretería

**Misión:** Ofrecemos soluciones integrales en ferretería liviana, seguridad industrial y complementarios, trabajando en equipo por la satisfacción del cliente, siendo su aliado estratégico con un gran compromiso por la sostenibilidad.

**Visión:** Seremos en el año 2023 líderes en soluciones integrales en ferretería liviana, seguridad industrial y complementarios con mayor presencia a nivel nacional, incorporando nuevas líneas de negocio mediante la innovación de procesos que fortalezcan la efectividad en la negociación.

## 🔧 Refinamiento de la Solución Propuesta

Inicialmente realizamos un MVP con la plataforma [NegocioBot](https://negociobot.com/), que nos proporcionó diversas herramientas para ofrecer la experiencia esperada. Esta plataforma fue seleccionada debido a su amigabilidad para el desarrollo y una documentación precisa que facilita la configuración del entorno.

## ✅ Funcionalidad Lograda

La implementación del chatbot con NegocioBot incluye:

- **Mensajes Automatizados:** Respuestas automáticas con información básica.
- **Secuencias a través de Botones:** Navegación intuitiva y simplificada.
- **Integración con Fuentes Externas:** Conexión con sistemas de e-commerce y VTex.

## 📜 Implementación Detallada

### Diagrama de Flujo

El flujo del chatbot fue diseñado para asegurar una experiencia de usuario fluida y eficiente. A continuación, se presenta el diagrama de flujo que describe las interacciones principales:

![image](https://github.com/linaballesteros/chatbot-casa-ferretera/assets/65176988/1cb3156e-fbdf-4450-9af7-494798542e8a)

![Diagrama de Flujo](https://github.com/linaballesteros/chatbot-casa-ferretera/blob/main/flowchart-chatbot.pdf)

### Modulo de Respuestas

El módulo de respuestas de NegocioBot es donde se configuran las respuestas automáticas basadas en la entrada del usuario. Se utilizan técnicas de procesamiento de lenguaje natural para proporcionar la respuesta más relevante.

### Secuencias a través de Botones

NegocioBot permite la creación de secuencias interactivas utilizando botones. Esto facilita la navegación del usuario a través de diferentes opciones y proporciona una experiencia de usuario más dinámica.

### Integración con APIs Externas

Utilizamos la herramienta Make para la integración con APIs externas. Make es una herramienta de automatización que permite conectar diferentes servicios y APIs a través de WebHooks.

#### Configuración de Make

Make fue configurado para manejar solicitudes GET y POST, permitiendo al chatbot recuperar información en tiempo real, como el estado de pedidos de Casa Ferretera.

### Ejemplo de Flujo de Pedido

El flujo de consulta de pedidos fue una de las funcionalidades implementadas utilizando Make y WebHooks. A continuación, se muestra un ejemplo del flujo:

1. El usuario envía un mensaje solicitando el estado de su pedido.
2. El chatbot activa un WebHook configurado en Make.
3. Make realiza una solicitud GET a la API interna de Casa Ferretera.
4. La respuesta de la API se procesa y se envía de vuelta al usuario a través del chatbot.

![image](https://github.com/linaballesteros/chatbot-casa-ferretera/assets/65176988/8c5212e5-a723-4054-bc71-9312a58e0100)

## 📈 Indicadores y Lecciones Aprendidas

Implementando la solución propuesta, se espera:

- **Reducción en el Tiempo de Respuesta:** Gracias a la capacidad del chatbot de manejar múltiples conversaciones simultáneas.
- **Incremento en la Tasa de Resolución:** Mayor porcentaje de consultas resueltas en los primeros 2 contactos.
- **Mejora en la Eficiencia Operativa:** Reducción en el número de chats que los empleados deben responder diariamente.
- **Incremento en la Satisfacción del Cliente:** Respuestas rápidas y concretas, mejorando la experiencia de usuario.

## 🔍 Conclusiones

La implementación del chatbot para Casa Ferretera ha resultado en la automatización de respuestas a preguntas frecuentes, mejorando los tiempos de respuesta y la eficiencia operativa. Esto contribuye a la fidelización de los clientes y proporciona una base sólida para futuras mejoras y expansiones del sistema.

---

Este proyecto es parte del curso de Sistemas de Información de la Universidad EAFIT. Agradecemos a Casa Ferretera por la colaboración y oportunidad de implementar esta solución.

