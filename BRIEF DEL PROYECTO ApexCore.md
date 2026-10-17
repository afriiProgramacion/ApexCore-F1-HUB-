# BRIEF DEL PROYECTO: ApexCore

## 1. El problema respaldado por datos
La información sobre la Fórmula 1 está fragmentada y, a menudo, es hostil para los nuevos espectadores. Durante los fines de semana de carrera, los aficionados se ven obligados a saltar entre distintas plataformas para consultar horarios, clasificaciones y normativas. Mientras las webs tradicionales saturan al usuario con artículos de opinión técnicos asumiendo un conocimiento previo elevado, el público más casual carece de un lugar centralizado para entender qué está pasando en la pista. El problema radica en la alta curva de aprendizaje del deporte y la fricción para acceder a datos puros y rápidos, lo que frustra tanto al espectador novato que no entiende la estrategia, como al veterano que solo busca un dato concreto.

## 2. Alcance (MVP - Producto Mínimo Viable)
Para solucionar este problema, ApexCore centraliza la consulta de datos y el aprendizaje en una única plataforma. Siguiendo la priorización MoSCoW, el alcance del MVP incluye:
*   **Must Have (Imprescindibles):** 
    *   *Dashboard principal:* Horarios de la próxima carrera y tablas de clasificación (Pilotos y Constructores).
    *   *ApexCore Academy (Núcleo diferenciador):* Un módulo educativo interactivo con un Glosario técnico y Cuestionarios básicos autoevaluables (estilo Duolingo) sobre normas y monoplazas.
    *   *Fichas básicas:* Información clave de Pilotos, Escuderías y Circuitos.
*   **Won't Have (Fuera de alcance inicial):** Para garantizar la viabilidad del proyecto, el MVP **no** incluirá el sistema complejo de rachas, vidas, perfiles de usuario con guardado de progreso en base de datos, ni automatización de noticias en tiempo real. 

## 3. Personas
El diseño, la navegación y el contenido de la Academia están orientados a resolver las necesidades de dos perfiles empíricos de usuarios:
*   **Persona 1: El Espectador Casual (21 años).** Se incorporó a la F1 recientemente. No quiere perder tiempo buscando información compleja. Su objetivo es resolver dudas puntuales sobre motores o normas durante la carrera usando la *ApexCore Academy* sin aburrirse.
*   **Persona 2: El Veterano Pragmático (51 años).** Sigue el deporte desde hace décadas. Su objetivo es entrar, comprobar a qué hora es la carrera, ver cómo va el mundial de constructores y salir de la web en menos de un minuto, sin distracciones.

## 4. Criterios de éxito
El MVP se considerará un éxito si cumple los siguientes criterios comprobables empíricamente sobre las personas definidas:
*   **Criterio de Aprendizaje (Espectador Casual):** El usuario es capaz de acceder a la *ApexCore Academy*, localizar la definición de un término técnico (ej. *Undercut* o *DRS*) y completar un cuestionario básico de 5 preguntas en menos de 3 minutos de reloj.
*   **Criterio de Consulta (Veterano Pragmático):** El usuario es capaz de localizar la hora exacta de la próxima sesión y los puntos actuales de su piloto favorito en un máximo de 3 clics desde la pantalla de inicio.

## 5. Restricciones del proyecto
*   **Restricciones Técnicas y de Tiempo:** El proyecto debe construirse utilizando HTML, CSS y JavaScript estructurado, limitando la carga del backend en la fase MVP para cumplir con los plazos de entrega del módulo DIWEB.
*   **Restricción Ambiental (W3C Web Sustainability Guidelines - Criterio 2.4):** Para asegurar el acceso a usuarios con conexiones inestables (ej. consultando datos móviles en un bar o en el propio circuito) y reducir la huella de carbono digital, **se establece un peso máximo estricto por página de 1.5 MB**. Esto restringe el uso de imágenes pesadas, obligando a emplear gráficos vectoriales (SVG) para los trazados de los circuitos, reutilización eficiente de componentes y tipografías optimizadas.

Aquí dejo un enlace a mi proyecto en figjam: [Figjam](https://www.figma.com/board/fclRkkbiL3VhQ4WqDIhkWk/PROYECTO-DIWEB?node-id=0-1&t=MJ3QH80HhSx80u4A-1)
