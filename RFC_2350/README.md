# RFC 2350

RFC 2350, titulado "Expectations for Computer Security Incident Response," establece las expectativas para los Equipos de Respuesta a Incidentes de Seguridad Informática (CSIRT). Los aspectos principales tratados son:


1. **Introducción**: 
   - Se define un CSIRT como un equipo que proporciona servicios y soporte para manejar y prevenir incidentes de seguridad informática. Estos equipos son esenciales para mantener la seguridad y estabilidad de los sistemas de información.

2. **Alcance**: 
   - Se subraya la importancia de la transparencia en las políticas de los CSIRTs. Los equipos deben documentar y publicar claramente sus políticas, las relaciones con otros CSIRTs y garantizar que los canales de comunicación sean seguros y confiables.

3. **Información, Políticas y Procedimientos**: 
   - Los CSIRTs deben proporcionar información clara y accesible sobre su contacto, misión y ámbito de operación (constituencia). Además, deben detallar su autoridad para actuar y las políticas específicas para responder a incidentes, incluyendo procedimientos para la gestión de incidentes y coordinación con otras entidades.

4. **Apéndices**: 
   - Se incluyen recursos adicionales como un glosario de términos relevantes, referencias a materiales relacionados, una lista de CSIRTs conocidos para referencia, una plantilla de ejemplo para la documentación de CSIRT y un ejemplo completo para ilustrar cómo debería ser la documentación de un CSIRT.

Este documento proporciona un marco comprensivo para establecer y operar un CSIRT eficaz, promoviendo prácticas estándar y colaboración entre equipos de respuesta a incidentes.

Para obtener más detalles, puedes consultar el documento completo [aquí](https://www.rfc-editor.org/rfc/rfc2350).

### Taller.

1. En grupos realizar la tradución del RFC 2350 (526312754-rfc2350.PDF) respetando el formato del mismo. Para ello respetar la asignación de páginas realizado en clase, de marera colaborativa sobre este README.md de esta carpeta.

2. Estudiar de manera individual el documento generado.

3. Participar en la exploración grupal que se realizará en clase.

4. De la actividad general,  se realizará una prueba escrita individual en clase (quizzis). 


###  RFC 2350

### GRUPO 6 PAG 
### 34
suficiente para la transmisión de datos de baja sensibilidad. Si es necesario enviar datos altamente sensibles por correo electrónico, se debe usar PGP. Se considerará que las transferencias de archivos de red ser similar al correo electrónico para estos fines: los datos confidenciales deben cifrarse para su transmisión.
Cuando sea necesario establecer confianza, por ejemplo antes de confiar en la información proporcionada al XYZ-CERT, o antes de revelar información confidencial, la identidad y la buena. La fidelidad de la otra parte se determinará en un grado razonable. grado de confianza. Dentro de la Universidad XYZ, y con conocidos
sitios vecinos, las referencias de personas conocidas y confiables basta para identificar a alguien. De lo contrario, métodos apropiados se utilizará, como la búsqueda de miembros de FIRST, el uso de WHOIS y otra información de registro en Internet, etc., junto con con devolución de llamada telefónica o devolución de correo electrónico para garantizar que el partido no es un impostor. Correo electrónico entrante cuyos datos deben ser confiable será verificado personalmente con el autor, o mediante firmas digitales (PGP en particular es soportado).
### Servicios
### 5.1  Respuesta a incidentes
XYZ-CERT ayudará a los administradores de sistemas a manejar los aspectos técnicos y organizativos de los incidentes. En particular, prestará asistencia o asesoramiento respecto de los siguientes aspectos de la gestión de incidentes:
### 5.1.1 Clasificación de incidentes
- Investigar si efectivamente ocurrió un incidente.
- Determinar el alcance del incidente.
### 5.1.2 Coordinación de incidentes
- Determinar la causa inicial del incidente (vulnerabilidad explotada).
- Facilitar el contacto con otros sitios que puedan ser involucrado.
- Facilitar el contacto con la Seguridad de la Universidad XYZ y/o los funcionarios encargados de hacer cumplir la ley correspondientes, si es necesario.
- Realización de informes a otros CSIRT.
- Redactar anuncios a los usuarios, en su caso.
### 5.1.3 Resolución de incidentes
- Eliminación de la vulnerabilidad.
- Asegurar el sistema de los efectos del incidente.
- Evaluar si determinadas acciones pueden dar resultados en proporción a su coste y riesgo, en particular aquellas acciones encaminadas a un eventual procesamiento o acción disciplinaria: recogida de pruebas a posteriori, observación de un incidente en curso, colocación de trampas para intrusos, etc.
- Recolectar pruebas cuando se prevea un proceso penal o una acción disciplinaria universitaria.
Además, XYZ-CERT recopilará estadísticas sobre incidentes que ocurran dentro o involucren a la comunidad de la Universidad XYZ, y notificará a la comunidad según sea necesario para ayudarla a protegerse contra ataques conocidos.
Para hacer uso de los servicios de respuesta a incidentes de XYZ-CERT, envíe un correo electrónico según la sección 2.11 anterior. Recuerde que la cantidad de asistencia disponible variará según los parámetros descritos en el apartado 4.1.
### 5.2 Actividades Proactivas
El XYZ-CERT coordina y mantiene los siguientes servicios en la medida de lo posible dependiendo de sus recursos:
- Servicios de información
- Listado de contactos departamentales de seguridad, administrativos y técnicos. Estas listas estarán disponibles para el público en general, a través de canales comúnmente disponibles, como la World Wide Web y/o el Servicio de Nombres de Dominio.
- Listas de correo para informar a los contactos de seguridad sobre nuevas información relevante para sus entornos informáticos.Estas listas estarán disponibles únicamente para los administradores del sistema de la Universidad XYZ.
- Repositorio de parches proporcionados por proveedores y otros parches relacionados con la seguridad para varios sistemas operativos. Este repositorio estará disponible para el público en general siempre que las restricciones de licencia lo permitan y se proporcionará a través de canales comúnmente disponibles, como la World Wide Web y/o ftp.
-  Repositorio de herramientas de seguridad y documentación para uso de administradores de sistemas. Siempre que sea posible, se proporcionarán versiones precompiladas listas para instalar.Estos se suministrarán al público en general a través de www o ftp como se indicó anteriormente.
- Servicio de "recorte" de diversos recursos existentes, como las principales listas de correo y grupos de noticias. Los recortes resultantes estarán disponibles en la lista de correo restringido o en el sitio web, dependiendo de su sensibilidad y urgencia.
- Servicios de entrenamiento
  - Los miembros del XYZ-CERT impartirán seminarios periódicos sobre temas relacionadoscon la seguridad informática; Estos seminarios estarán abiertos a los 
    administradores del sistema de la Universidad XYZ.
- Servicios de auditoria
  - Servicio central de comprobación de integridad de archivos para máquinas Unix y para cualquier otra plataforma capaz de ejecutar "tripwire".
  - Asignaciones de niveles de seguridad; Las máquinas y subredes de la Universidad XYZ serán auditadas y se les asignará un nivel de seguridad. Esta información 
    sobre el nivel de seguridad estará disponible para la comunidad de la Universidad XYZ, para facilitar la configuración de los privilegios de acceso adecuados. 
    Sin embargo, los detalles de los análisis de seguridad serán confidenciales y estarán disponibles únicamente para las partes interesadas.
- Servicios de archivo
   - Servicio de registro central para máquinas capaces de Registro remoto estilo Unix. Las entradas de registro entrantes serán supervisadas por un programa de 
     análisis de registros automatizado, y los eventos o tendencias indicativos de un posible problema de seguridad se informarán a los administradores del sistema 
     afectados.
- Se llevarán registros de las incidencias de seguridad atendidas.
    - Si bien los registros permanecerán confidenciales, los informes estadísticos periódicos estarán disponibles para la comunidad de la Universidad XYZ.

Las descripciones detalladas de los servicios anteriores, junto con instrucciones para unirse a listas de correo, descargar información o participar en ciertos servicios, como los servicios de registro central y verificación de integridad de archivos, están disponibles en el sitio web de XYZ-CERT, según la sección 2.10 anterior.
### 6. Formularios de notificación de incidentes

Aún no se han desarrollado formularios locales para informar incidentes a XYZ-CERT. Si es posible, utilice el Formulario de informe de incidentes del Centro de coordinación del CERT (Pittsburgh, PA). La versión actual está disponible en:
ftp://info.cert.org/incident_reporting_form
### 7. Descargos de responsabilidades
Si bien se tomarán todas las precauciones en la preparación de información, notificaciones y alertas, XYZ-CERT no asume ninguna responsabilidad por errores u omisiones, ni por daños resultantes del uso de la información contenida en ella.
### Agradecimientos
Los editores agradecen el material aportado y el escrutinio editorial de Anne Bennett. Gracias también a Don Stikvoort por su ayuda para reelaborar la descripción de los servicios del Equipo de Respuesta a Incidentes.
### Referencias
[RFC 2196] Fraser, B., "Manual de seguridad del sitio", FYI 8, RFC 2196, Septiembre de 1997.
[RFC 1983] Malkin, G., "Glosario de usuarios de Internet", FYI 18, RFC 1983, Agosto de 1996.
### Consideraciones de seguridad
Este documento analiza el funcionamiento de los equipos de respuesta a incidentes de seguridad informática y las interacciones de los
equipos con sus miembros y con otras organizaciones. Por lo tanto, no está directamente relacionado con la seguridad de los protocolos, las
aplicaciones o los propios sistemas de red. Ni siquiera se ocupa de respuestas y reacciones particulares a incidentes de
seguridad, sino sólo de la descripción adecuada de las respuestas proporcionadas por los CSIRT.

No obstante, es vital que los propios CSIRT operen de forma segura, lo que significa que deben establecer canales de comunicación
seguros con otros equipos y con miembros de su electorado. También deben proteger sus propios sistemas e infraestructura, para
proteger los intereses de sus electores y mantener la confidencialidad de la identidad de las víctimas y los denunciantes de incidentes de
seguridad.

### Direcciones de los autores
Nevil Brownlee
Desarrollo Tecnológico ITSS
La Universidad de Auckland
Teléfono: +64 9 373 7599 x8941
Correo electrónico: n.brownlee@auckland.ac.nz

Erik Guttman Sun
Microsystems, Inc.
Bahnstraße. 2
74915 Waibstadt Alemania
Teléfono: +49 7263 911484
Correo electrónico: Erik.Guttman@sun.com

### Declaración completa de derechos de autor

Copyright (C) Sociedad de Internet (1998). Reservados todos los derechos.

Este documento y sus traducciones pueden copiarse y proporcionarse a otros, y los trabajos derivados que lo comenten, lo expliquen o ayuden
en su implementación pueden prepararse, copiarse, publicarse y distribuirse, en su totalidad o en parte, sin restricción de ningún tipo. , siempre que
el aviso de derechos de autor anterior y este párrafo estén incluidos en todas dichas copias y trabajos derivados. Sin embargo, este documento
en sí no puede modificarse de ninguna manera, como eliminar el aviso de derechos de autor o las referencias a Internet Society u otras
organizaciones de Internet, excepto cuando sea necesario para desarrollar estándares de Internet, en cuyo caso se aplicarán los procedimientos para
derechos de autor definidos en Se debe seguir el proceso de Estándares de Internet, o según sea necesario, traducirlo a idiomas distintos
del inglés.

Los permisos limitados otorgados anteriormente son perpetuos y no serán revocados por Internet Society ni por sus sucesores o cesionarios.

Este documento y la información contenida en él se proporcionan en un TASK FORCE RENUNCIA A TODAS LAS GARANTÍAS, EXPRESAS O IMPLÍCITAS, INCLUYENDO Copyright (C) Sociedad de Internet (1998). Reservados todos los derechos. Base "TAL CUAL" y LA SOCIEDAD DE INTERNET Y LA INGENIERÍA DE INTERNET Declaración completa de derechos de autor RFC 2350 Expectativas de respuesta a incidentes de seguridad informática, junio de 1998 PERO NO LIMITADO A CUALQUIER GARANTÍA DE QUE EL USO DE LA INFORMACIÓN AQUÍ NO INFRINGIRÁ NINGÚN DERECHO NI GARANTÍA IMPLÍCITA DE COMERCIABILIDAD O IDONEIDAD PARA UN PROPÓSITO PARTICULAR. 
