# Apuntes de Logs en Java

Este repositorio es un apunte personal sobre el uso y configuración de logs en Java utilizando `Log4j`. Aquí se documentan los fundamentos y la práctica de logging, incluyendo niveles de logs y cómo estructurarlos para obtener información detallada de la ejecución de un proyecto.

### Contenido

- **Fundamentos de los logs**: Explicación de los beneficios y estructura de los logs, incluyendo fecha, hora, nivel de log, etiqueta (tag) y mensaje.
- **Niveles de logs**:
  - **TRACE**: Información más detallada, ideal para depuración exhaustiva.
  - **DEBUG**: Información específica para depuración.
  - **INFO**: Información general de la ejecución.
  - **WARN**: Advertencias sobre posibles problemas.
  - **ERROR**: Errores que afectan el funcionamiento.
  - **FATAL**: Errores críticos.
- **Configuración de Log4j**: Configuración de niveles, archivos de salida, y patrones de formato mediante `log4j2.xml`.
- **Archivos de log**: Los logs se almacenan en archivos separados (`informativeLogs.log`, `debugLogs.log`, `traceLogs.log`) con configuraciones específicas de nivel.

### Dependencias

Este proyecto utiliza las siguientes dependencias de Log4j, que se pueden agregar al archivo `pom.xml` de Maven:

```xml
<!-- Dependencia para el API de Log4j -->
<dependency>
    <groupId>org.apache.logging.log4j</groupId>
    <artifactId>log4j-api</artifactId>
    <version>2.24.1</version>
</dependency>

<!-- Dependencia para el núcleo de Log4j -->
<dependency>
    <groupId>org.apache.logging.log4j</groupId>
    <artifactId>log4j-core</artifactId>
    <version>2.24.1</version>
</dependency>
```

### Uso

Este repositorio está diseñado para consultas rápidas sobre el uso de logs en Java y cómo configurarlos para diferentes niveles de información. Si necesitas recordar un concepto o cómo configurar los logs, revisa los ejemplos y configuraciones provistas.

### Notas

Este material está organizado como referencia personal para profundizar en logging en Java con `Log4j`. Sin embargo, si te resulta útil, eres bienvenido a utilizarlo.

---

¡Espero que te sea de ayuda!
