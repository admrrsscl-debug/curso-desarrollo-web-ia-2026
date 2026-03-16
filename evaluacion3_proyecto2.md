# EVALUACIÓN 3: PROYECTO 2 - APLICACIÓN WEB CON PHP Y MYSQL
## Curso: Desarrollo y Diseño Web + IA
## Hito: 3 - Desarrollo Backend con PHP y MySQL
## Fecha: Semana 11 (25-29 de mayo 2026)
## Ponderación: 20%
## Tipo: Evaluación docente + Cuestionario técnico

## DESCRIPCIÓN DEL PROYECTO

Desarrolle una aplicación web completa con PHP y MySQL que implemente un sistema CRUD (Crear, Leer, Actualizar, Eliminar) para gestionar cualquier entidad (productos, usuarios, posts, etc.). La aplicación debe incluir interfaz frontend y backend funcional.

### Requisitos técnicos obligatorios:
1. **Base de datos MySQL** con al menos 2 tablas relacionadas
2. **Conexión PHP-MySQL** usando MySQLi o PDO
3. **Sistema CRUD completo** para al menos una entidad
4. **Formularios HTML** con validación cliente y servidor
5. **Manejo de sesiones** (login/logout básico)
6. **Interfaz responsive** (Bootstrap o CSS personalizado)
7. **Estructura organizada** (separación lógica de archivos)
8. **Despliegue local** (XAMPP/WAMP) o en hosting

### Funcionalidades mínimas:
- Registro y login de usuarios (puede ser básico)
- Listado de elementos con paginación o filtros
- Formulario para crear nuevos elementos
- Edición de elementos existentes
- Eliminación con confirmación
- Búsqueda o filtrado de elementos

## RÚBRICA DE EVALUACIÓN - PROYECTO (60%)

### A. FUNCIONALIDAD Y COMPLETITUD (35 puntos)
| Criterio | Puntos | Descripción | Puntaje |
|----------|--------|-------------|---------|
| **CRUD completo** | 0-10 | Las 4 operaciones funcionan correctamente | |
| **Base de datos** | 0-8 | Estructura adecuada, relaciones, normalización | |
| **Validaciones** | 0-7 | Validación cliente y servidor, mensajes claros | |
| **Sesiones/login** | 0-5 | Sistema de autenticación funcional | |
| **Navegación** | 0-5 | Interfaz intuitiva, flujo lógico | |

### B. CÓDIGO PHP Y MYSQL (25 puntos)
| Criterio | Puntos | Descripción | Puntaje |
|----------|--------|-------------|---------|
| **Seguridad** | 0-8 | Prepared statements, sanitización, protección XSS/SQLi | |
| **Organización** | 0-7 | Código bien estructurado, separación de responsabilidades | |
| **Consultas SQL** | 0-5 | Consultas eficientes, joins apropiados | |
| **Manejo errores** | 0-5 | Try/catch, mensajes de error útiles | |

### C. INTERFAZ Y USABILIDAD (15 puntos)
| Criterio | Puntos | Descripción | Puntaje |
|----------|--------|-------------|---------|
| **Diseño** | 0-6 | Interfaz profesional, coherente | |
| **Responsividad** | 0-5 | Funciona en diferentes dispositivos | |
| **Experiencia usuario** | 0-4 | Flujo intuitivo, feedback claro | |

### D. EXTRAS Y CALIDAD (15 puntos)
| Criterio | Puntos | Descripción | Puntaje |
|----------|--------|-------------|---------|
| **Features avanzadas** | 0-6 | Funcionalidades beyond requisitos básicos | |
| **Código limpio** | 0-5 | Buenas prácticas, comentarios, naming | |
| **Documentación** | 0-4 | README completo, instrucciones claras | |

**TOTAL PROYECTO:** _____ / 100 (convertido a 60% de la evaluación)

## CUESTIONARIO TÉCNICO SOBRE CÓDIGO (40%)

### Instrucciones:
Responda preguntas específicas sobre secciones de su código PHP/MySQL.

### Pregunta 1: Conexión y seguridad
**Archivo:** [Nombre archivo conexión]  
**Líneas:** [Línea inicio] a [Línea fin]

```php
// [Se insertará código específico del estudiante]
```

**Preguntas:**
1. Explique cómo esta conexión previene inyección SQL.
2. ¿Qué mejoras de seguridad adicionales implementaría?
3. ¿Cómo maneja esta función los errores de conexión?
4. Proponga una mejora para conexiones persistentes.

**Puntaje pregunta 1:** _____ / 10

### Pregunta 2: Consulta SQL y prepared statements
**Archivo:** [Nombre archivo]  
**Líneas:** [Línea inicio] a [Línea fin]

```php
// [Se insertará código específico del estudiante]
```

**Preguntas:**
1. Analice la eficiencia de esta consulta SQL.
2. ¿Cómo podría optimizarse si la tabla tuviera miles de registros?
3. Explique cómo los prepared statements previenen SQL injection.
4. Proponga una mejora usando transacciones si es apropiado.

**Puntaje pregunta 2:** _____ / 10

### Pregunta 3: Lógica de negocio PHP
**Archivo:** [Nombre archivo]  
**Líneas:** [Línea inicio] a [Línea fin]

```php
// [Se insertará código específico del estudiante]
```

**Preguntas:**
1. Describa el flujo completo de esta función.
2. Identifique posibles puntos de falla y cómo los maneja.
3. ¿Cómo podría refactorizarse para mejor mantenibilidad?
4. Proponga una implementación usando POO si es apropiado.

**Puntaje pregunta 3:** _____ / 10

### Pregunta 4: Arquitectura y decisiones
**Preguntas generales:**
1. Justifique la estructura de archivos y carpetas que utilizó.
2. ¿Qué consideraciones de escalabilidad tomó en cuenta?
3. ¿Cómo separó la lógica de presentación de la lógica de negocio?
4. Si tuviera que convertir esta aplicación a un framework (Laravel, etc.), ¿qué cambiaría?

**Puntaje pregunta 4:** _____ / 10

**TOTAL CUESTIONARIO:** _____ / 40 (40% de la evaluación)

## CALIFICACIÓN FINAL INTEGRADA

### Proyecto: _____ / 60 (60%)
### Cuestionario: _____ / 40 (40%)
### **TOTAL: _____ / 100**

**Convertido a escala 1.0-7.0:** _____
(Fórmula: (puntos/100)*6 + 1)

## COMENTARIOS Y RETROALIMENTACIÓN

### Fortalezas técnicas identificadas:
[Áreas donde el estudiante demostró buen dominio de PHP/MySQL]

### Áreas de mejora técnica:
[Aspectos específicos del código que necesitan mejora]

### Recomendaciones para aprendizaje:
[Sugerencias de temas a profundizar: seguridad, performance, patrones]

### Observaciones sobre comprensión conceptual:
[Evaluación de comprensión backend vs. solo implementación]

## ADAPTACIONES APLICADAS

[Registro de adaptaciones para estudiantes con necesidades especiales]

## FIRMAS Y FECHAS

**Evaluado por:** Cristian Iglesias Vera
**Fecha evaluación:** _________________________
**Fecha entrega feedback:** _________________________

**Firma estudiante (acuse de recibido):** _________________________
**Fecha:** _________________________

---

## INSTRUCCIONES PARA EL DOCENTE

### Proceso de evaluación:
1. **Revisión código:** Analizar estructura, seguridad, funcionalidad
2. **Pruebas:** Verificar CRUD completo, validaciones, manejo errores
3. **Selección código:** Elegir secciones representativas para preguntas
4. **Personalización:** Adaptar preguntas al código específico

### Criterios clave:
- **Seguridad:** Uso de prepared statements, sanitización
- **Organización:** Separación lógica/presentación
- **Calidad código:** Buenas prácticas, comentarios
- **Comprensión:** No solo funciona, sino que es seguro y mantenible

### Para estudiantes con necesidades especiales:
- **Proyecto simplificado:** CRUD básico sin relaciones complejas
- **Preguntas guiadas:** Opción múltiple o preguntas más concretas
- **Tiempo extendido:** Para cuestionario técnico
- **Evaluación por partes:** Dividir proyecto en hitos más pequeños