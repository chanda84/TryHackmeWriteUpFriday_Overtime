# Friday Overtime - Cyber Threat Intelligence Analysis

## Descripción
Friday Overtime" es un análisis detallado de una amenaza cibernética detectada en un entorno financiero. Incluye extracción de hashes, correlación con inteligencia de amenazas, técnicas MITRE ATT&amp;CK asociadas y hallazgos clave sobre el malware MgBot y SpyAgent. Este write-up documenta el proceso de investigación y mitigación en un entorno real.

## Escenario
Es viernes por la tarde en PandaProbe Intelligence cuando una alerta en la plataforma CTI interrumpe el inicio del fin de semana. SwiftSpend Finance ha reportado una posible amenaza de malware y, como único analista en turno, tu misión es investigar, identificar los riesgos y proporcionar medidas de mitigación.

## Proceso de Análisis
1. **Descarga segura** de las muestras de malware.
2. **Extracción de hashes SHA1 y SHA256** de los archivos sospechosos.
3. **Identificación del malware** asociado a la amenaza.
4. **Correlación con inteligencia de amenazas** para vincularlo con grupos APT conocidos.
5. **Mapeo con MITRE ATT&CK** para determinar las tácticas y técnicas utilizadas.
6. **Análisis de IoCs** como IPs maliciosas y servidores C&C.
7. **Elaboración de un informe** con hallazgos clave y recomendaciones de mitigación.

## Hallazgos Clave
- El malware identificado pertenece al marco de amenazas **MgBot**, utilizado por el grupo APT **Evasive Panda**.
- La **DLL pRsm.dll** está asociada a la técnica **T1123 (Audio Capture)** de MITRE ATT&CK.
- Identificación de un servidor **C&C activo** detectado desde 2020.
- Se detectó un spyware de la familia **SpyAgent** alojado en la misma IP que afectaba dispositivos Android.

## Conclusión
El análisis revela una amenaza persistente con tácticas avanzadas de persistencia y evasión. La correlación de artefactos con inteligencia de amenazas y técnicas MITRE ATT&CK permite una respuesta efectiva. Se recomienda aplicar medidas de mitigación y fortalecer controles de seguridad para prevenir futuras infecciones.

## Recursos
- [MITRE ATT&CK - MgBot](https://attack.mitre.org/software/S1146/)
- [ESET - Evasive Panda](https://www.welivesecurity.com/2023/04/26/evasive-panda-apt-group-malware-updates-popular-chinese-software/)
- [VirusTotal](https://www.virustotal.com/)

## Autor
🚀 Investigación y análisis por [Andres Valdivieso]
