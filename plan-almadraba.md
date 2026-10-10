# Plan: Almadraba Diseño

## 1. Fuentes de evidencia identificadas

- **Portátil de Marta:** es una fuente principal porque estaba encendido y conectado a dos monitores mediante una base USB-C. Debemos ver cómo conservar la información sin apagarlo directamente.
- **Disco externo de 2 TB:** puede contener archivos, copias o información relacionada con los diseños.
- **Pendrive de Javier:** Javier afirma que Marta lo utilizó el jueves y se lo devolvió al día siguiente. Conviene identificarlo y guardarlo.
- **Móvil corporativo de Marta:** puede contener conversaciones con clientes y otra información de trabajo.
- **Móvil personal de Marta:** debe tratarse con precaución, comprobando primero si entra dentro de la autorización y si puede contener información importante.
- **Servidor de la empresa y OneDrive:** pueden contener los diseños originales, versiones de los archivos y datos sincronizados.
- **Copias de seguridad del NAS:** hay 14 copias retenidas, por lo que debemos comprobar su rotación y evitar que se pierdan las copias relevantes.
- **Registros del cortafuegos:** pueden ayudar a reconstruir actividad de red, pero se sobrescriben y tienen una retención aproximada de una semana.
- **Impresora multifunción:** conserva un historial de trabajos de duración desconocida que podría aportar información.
- **Cámaras del pasillo:** dependen de la comunidad del edificio y las grabaciones se almacenan en un dispositivo de conserjería.
- **Ordenador compartido de la entrada:** tiene abierta una sesión web de Outlook de otro empleado. Hay que documentar su estado y evitar acceder a información ajena sin autorización.

## 2. Prioridad de recogida

1. **Información volátil del portátil encendido:** antes de apagarlo o reiniciarlo, vería qué datos podrían perderse. No realizaría ninguna acción sin un procedimiento adecuado.
2. **Registros del cortafuegos:** solicitaría su preservación cuanto antes porque se sobrescriben y solo se conservan aproximadamente una semana.
3. **Grabaciones de las cámaras:** contactaría con el responsable de la comunidad para evitar que las grabaciones importantes se eliminen por la política de retención.
4. **Copias del NAS:** comprobaría las fechas de las copias y la rotación para identificar cuáles pueden ser relevantes.
5. **Pendrive de Javier y disco externo:** los identificaría y preservaría, documentando su ubicación y evitando conectarlos a un equipo sin un procedimiento adecuado.
6. **Servidor, OneDrive e historial de la impresora:** Ordenaria su preservación con el personal responsable, teniendo en cuenta los permisos y la disponibilidad de los datos.
7. **Móviles y ordenador compartido:** documentaría su estado y vería qué información puede ser relevante.

## 3. Medidas inmediatas

- Registrar la hora de llegada, las personas presentes y el estado inicial de los dispositivos.
- Fotografiar el portátil, sus conexiones, la base USB-C, los monitores y los dispositivos cercanos.
- Evitar que las personas manipulen los posibles elementos de prueba sin saberlo el equipo que lo investigue.
- No apagar, reiniciar ni desconectar el portátil automáticamente; primero valoraría el riesgo de perder datos.
- Solicitar al responsable informático que ayude a identificar y preservar los registros del cortafuegos, las copias de seguridad y los datos del servidor.
- Contactar con el responsable de las cámaras para conocer la retención y solicitar que se conserven las grabaciones relevantes.
- Solicitar la preservación del pendrive de Javier y documentar quién lo tiene.
- Anotar cada actuación, quién la realiza y cuándo, junto con las decisiones tomadas y sus motivos.

## 4. Límites de la intervención

- **Móvil personal de Marta:** no accedería a su contenido sin comprobar primero si la autorización lo permite y si existe una justificación relacionada con el incidente.
- **Cuenta de Outlook de otro empleado:** no revisaría su contenido por el simple hecho de que la sesión esté abierta. Documentaría su estado y veria cómo actuar.
- **OneDrive y portal de Microsoft:** organizaría como actuar con el personal autorizado y comprobaría el alcance de los permisos disponibles.
- **Cámaras de la comunidad:** solicitaría la conservación de las grabaciones al responsable correspondiente, sin acceder por mi cuenta al dispositivo.
- **Servidor, NAS y cortafuegos:** coordinaría la preservación con el personal informático para evitar pérdidas o cambios innecesarios.
- **Portátil de Marta:** tendría en cuenta que usa el equipo en casa y que se conecta mediante VPN algunos viernes. Por tanto, podría haber fuentes de información fuera de la oficina.

## 5. De dónde sale cada decisión

| Decisión del plan | Lista de comprobación | Referencia normativa |
|---|---|---|
| Documentar la escena y a las personas presentes | Preguntas 2, 4, 5 y 9 | RFC 3227, apartado 3.2; ENFSI BPM, apartado 8.2 |
| Documentar el ordenador compartido y la sesión de Outlook | Preguntas 5, 6, 8 y 10 | RFC 3227, apartado 3.2; ENFSI BPM, apartados 8.2 y 9.2 |
| Valorar los datos volátiles del portátil | Preguntas 6, 17 y 18 | RFC 3227, apartados 2, 2.1 y 2.2; ENFSI BPM, apartado 9.2 |
| Identificar el pendrive y el disco externo | Pregunta 11 | NIST SP 800-86, apartado 3.1.1 |
| Identificar el servidor, OneDrive y el NAS | Preguntas 12 y 14 | NIST SP 800-86, apartado 3.1.1 |
| Preservar los registros del cortafuegos | Preguntas 13 y 19 | NIST SP 800-86, apartado 3.1.1; RFC 3227, apartado 3.2 |
| Considerar los móviles y la información de terceros | Pregunta 15 | NIST SP 800-86, apartado 3.1.1; ENFSI BPM, apartado 9.2 |
| Identificar la impresora y las cámaras | Pregunta 16 | NIST SP 800-86, apartado 3.1.1, como criterio general para identificar fuentes potenciales |
| Valorar la urgencia de conservar las copias de seguridad y las grabaciones | Preguntas 19 y 20 | NIST SP 800-86, apartado 3.1.1, para identificar las fuentes; la urgencia concreta se justifica por los riesgos descritos en el caso |
| Comprobar las autorizaciones y las fuentes externas | Preguntas 1 y 21 | RFC 3227, apartado 2; NIST SP 800-86, apartado 3.1.1 |
| Establecer un orden de adquisición justificado | Preguntas 17, 18, 20 y 22 | RFC 3227, apartados 2 y 3.2; ENFSI BPM, apartados 9.1 y 9.2 |