# Plan: Almadraba Diseño

En este caso no debemos centrarnos solamente en el portátil de Marta, porque puede haber información filtrada en otros dispositivos y sistemas.

## 1. Fuentes de evidencia identificadas

- **Portátil de Marta:** es una fuente principal porque estaba encendido y conectado a dos monitores mediante una base USB-C. Debemos valorar cómo preservar la información sin apagarlo directamente.
- **Disco externo de 2 TB:** puede contener archivos, copias o información relacionada con los diseños.
- **Pendrive de Javier:** Javier afirma que Marta lo utilizó el jueves y se lo devolvió al día siguiente. Conviene identificarlo y solicitar su preservación.
- **Móvil corporativo de Marta:** puede contener conversaciones con clientes y otra información de trabajo.
- **Móvil personal de Marta:** debe tratarse con precaución, comprobando primero si entra dentro de la autorización y si puede contener información relevante.
- **Servidor de la empresa y OneDrive:** pueden contener los diseños originales, versiones de los archivos y datos sincronizados.
- **Copias de seguridad del NAS:** hay 14 copias retenidas, por lo que debemos comprobar su política de rotación y evitar que se pierdan las copias relevantes.
- **Registros del cortafuegos:** pueden ayudar a reconstruir actividad de red, pero se sobrescriben y tienen una retención aproximada de una semana.
- **Impresora multifunción:** conserva un historial de trabajos de duración desconocida que podría aportar información.
- **Cámaras del pasillo:** dependen de la comunidad del edificio y las grabaciones se almacenan en un dispositivo de conserjería.
- **Ordenador compartido de la entrada:** tiene abierta una sesión web de Outlook de otro empleado. Hay que documentar su estado y evitar acceder a información ajena sin autorización.

Esta identificación sigue el criterio de buscar distintas fuentes potenciales de información, como propone NIST SP 800-86, §3.1.1. También se debe documentar la ubicación y el estado inicial de los dispositivos, según ENFSI BPM, §8.2.

## 2. Prioridad de recogida

No recogería todas las evidencias en el mismo orden, sino que tendría en cuenta su volatilidad, el riesgo de pérdida y la urgencia de preservarlas.

1. **Información volátil del portátil encendido:** antes de apagarlo o reiniciarlo, valoraría qué datos podrían perderse. No realizaría ninguna acción sin un procedimiento adecuado.
2. **Registros del cortafuegos:** solicitaría su preservación cuanto antes porque se sobrescriben y solo se conservan aproximadamente una semana.
3. **Grabaciones de las cámaras:** contactaría con el responsable de la comunidad para evitar que las grabaciones relevantes se eliminen por la política de retención.
4. **Copias del NAS:** comprobaría las fechas de las copias y la rotación para identificar cuáles pueden ser relevantes.
5. **Pendrive de Javier y disco externo:** los identificaría y preservaría, documentando su ubicación y evitando conectarlos a un equipo sin un procedimiento adecuado.
6. **Servidor, OneDrive e historial de la impresora:** coordinaría su preservación con el personal responsable, teniendo en cuenta los permisos y la disponibilidad de los datos.
7. **Móviles y ordenador compartido:** documentaría su estado y determinaría qué información puede ser relevante y qué límites de autorización se aplican.

El orden definitivo debe ajustarse a las condiciones reales de la escena. La prioridad de los datos volátiles se basa en RFC 3227, §§2 y 2.1; la evaluación de los dispositivos activos, en ENFSI BPM, §9.2.

## 3. Medidas inmediatas

Antes de adquirir evidencias, tomaría las siguientes medidas:

- Registrar la hora de llegada, las personas presentes y el estado inicial de los dispositivos.
- Fotografiar el portátil, sus conexiones, la base USB-C, los monitores y los dispositivos cercanos.
- Evitar que las personas presentes manipulen los posibles elementos de prueba sin coordinación con el equipo investigador.
- No apagar, reiniciar ni desconectar el portátil automáticamente; primero valoraría el riesgo de perder datos.
- Solicitar al responsable informático que ayude a identificar y preservar los registros del cortafuegos, las copias de seguridad y los datos del servidor.
- Contactar con el responsable de las cámaras para conocer la retención y solicitar que se conserven las grabaciones relevantes.
- Solicitar la preservación del pendrive de Javier y documentar quién lo custodia.
- Anotar cada actuación, quién la realiza y cuándo, junto con las decisiones tomadas y sus motivos.

Estas medidas se apoyan en RFC 3227, §§2 y 3.2, y ENFSI BPM, §8.2. Para valorar cómo tratar el portátil encendido, también se tendrá en cuenta ENFSI BPM, §9.2.

## 4. Límites de la intervención

La investigación debe mantenerse dentro de la autorización firmada por Elena. No se debe asumir que todos los dispositivos o datos accesibles están autorizados para su examen.

- **Móvil personal de Marta:** no accedería a su contenido sin comprobar primero si la autorización lo permite y si existe una justificación relacionada con el incidente.
- **Cuenta de Outlook de otro empleado:** no revisaría su contenido por el simple hecho de que la sesión esté abierta. Documentaría su estado y consultaría cómo proceder.
- **OneDrive y portal de Microsoft:** coordinaría las actuaciones con el personal autorizado y comprobaría el alcance de los permisos disponibles.
- **Cámaras de la comunidad:** solicitaría la conservación de las grabaciones al responsable correspondiente, sin acceder por mi cuenta al dispositivo.
- **Servidor, NAS y cortafuegos:** coordinaría la preservación con el personal informático para evitar pérdidas o cambios innecesarios.
- **Portátil de Marta:** tendría en cuenta que usa el equipo en casa y que se conecta mediante VPN algunos viernes. Por tanto, podría haber fuentes de información fuera de la oficina.

NIST SP 800-86, §3.1.1, destaca la importancia de considerar la propiedad de los datos, las políticas y los aspectos legales al identificar fuentes, incluidas las externas. ENFSI BPM, §9.2, permite considerar la intervención de un tercero de confianza para extraer datos cuando corresponda.

## 5. De donde sale cada decisión

Las decisiones anteriores se relacionan con los siguientes puntos de la lista de comprobación:

| Decisión del plan | Lista de comprobación | Referencia normativa |
|---|---|---|
| Documentar la escena y a las personas presentes | Preguntas 2, 4, 5 y 9 | RFC 3227, 3.2; ENFSI BPM, 8.2 |
| Valorar los datos volátiles del portátil | Preguntas 6, 17 y 18 | RFC 3227, 2, 2.1 y 2.2; ENFSI BPM, 9.2 |
| Identificar el pendrive y el disco externo | Pregunta 11 | NIST SP 800-86, 3.1.1 |
| Identificar el servidor, OneDrive y el NAS | Preguntas 12 y 14 | NIST SP 800-86, 3.1.1 |
| Preservar los registros del cortafuegos | Preguntas 13 y 19 | NIST SP 800-86, 3.1.1; RFC 3227, 3.2 |
| Considerar los móviles y la información de terceros | Pregunta 15 | NIST SP 800-86, 3.1.1; ENFSI BPM, 9.2 |
| Identificar la impresora y las cámaras | Pregunta 16 | NIST SP 800-86, 3.1.1, como criterio general de identificación de fuentes |
| Valorar la urgencia de copias y grabaciones | Pregunta 20 | NIST SP 800-86, 3.1.1, para identificar las fuentes; la urgencia concreta deriva de los riesgos descritos en el caso |
| Comprobar autorizaciones y fuentes externas | Preguntas 1 y 21 | RFC 3227, 2; NIST SP 800-86, 3.1.1 |
| Establecer un orden de adquisición justificado | Pregunta 22 | RFC 3227, 2 y 3.2; ENFSI BPM, 9.1 y 9.2 |