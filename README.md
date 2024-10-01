1° Trabajo Práctico Integrador
Descripción del Proyecto
El grupo deberá desarrollar una aplicación móvil que permita a los usuarios comparar dos inversiones. Cada inversión tendrá parámetros como el monto inicial, la tasa de interés y el tiempo de inversión. La aplicación calculará y comparará el rendimiento de las dos inversiones, mostrando los resultados de manera clara. Los datos deben ser persistentes entre sesiones utilizando Shared Preferences. Además, se utilizarán Intents para la navegación entre pantallas y Toast para notificaciones. El diseño de la interfaz debe estar basado en LinearLayout anidado.

Análisis Funcional
Descripción de la Aplicación

Ingreso de Datos de Inversión: La aplicación mostrará una pantalla donde los usuarios podrán ingresar el monto, la tasa de interés, el plazo y la entidad de ambas inversiones. Estas inversiones pueden ser de tipo plazo fijo o fondo común de inversión.

Cálculo de Rendimiento: En una segunda pantalla, se calculará el rendimiento de ambas inversiones utilizando el ROI. Además, se simularán los resultados y se proporcionará una recomendación sobre cuál es la mejor opción de inversión.

Historial de Comparaciones: Se implementará un tercer botón que permitirá a los usuarios acceder a un historial de las últimas cinco comparaciones realizadas.

Políticas y Términos: Un cuarto botón redirigirá a otra actividad donde se presentarán las políticas, términos y condiciones de uso de la aplicación.

Test del Inversor: Al instalar la aplicación por primera vez, se llevará a cabo el Test del Inversor. Este consistirá en preguntas de opción múltiple, de las cuales el grupo deberá seleccionar tres para mostrarlas en la aplicación (más información disponible en: https://www.bna.com.ar/Personas/TestDelInversor). Además, se solicitará el nombre, apellido y correo electrónico del usuario, que se mostrarán en la pantalla de bienvenida.


NOTA: USAR Y SOLICITAR para los cálculos la Tasa Nominal Anual (TNA)

Para obtener la Tasa Mensual:


Cf (Capital Final) = Ci (Capital Inicial) * Tasa Mensual 
Recordemos siempre la TNA dividirla por 100 y eso por 12 o 360


Requisitos Técnicos
Uso de Shared Preferences

Almacenar los detalles de las dos inversiones en historial
Permitir la edición y persistencia de las inversiones entre sesiones.
Pasaje de Parámetros entre Actividades

Usar Intent para transferir datos entre actividades, como los detalles de cada inversión para la comparación.
Uso de Toast

Proporcionar notificaciones claras al usuario sobre acciones exitosas, errores o advertencias, como intentar comparar sin haber ingresado ambas inversiones.
LinearLayout Anidado

Organizar las pantallas de entrada de datos y de comparación utilizando LinearLayout para un diseño limpio y funcional.
Criterios de Evaluación
Funcionalidad Completa: La aplicación debe permitir ingresar, editar, eliminar y comparar dos inversiones.
Uso Correcto de Shared Preferences: Las inversiones deben ser guardadas y persistir entre sesiones.
Navegación entre Actividades: Los datos deben transferirse correctamente entre actividades.
Interacción con el Usuario: El uso de Toast debe proporcionar feedback adecuado y claro al usuario.
Diseño de la Interfaz: La interfaz debe ser intuitiva, organizada con LinearLayout, y fácil de usar.
Colaboración en Equipo: Cada miembro del equipo debe asumir un rol claro y contribuir al éxito del proyecto.
Estructura del Proyecto y Roles del Grupo
Desarrollador de Interfaz (UI/UX): Diseñar la interfaz utilizando LinearLayout anidado.
Desarrollador de Funcionalidad: Implementar los cálculos del rendimiento de las inversiones y la gestión de datos con Shared Preferences.
Desarrollador de Navegación: Gestionar el pasaje de datos entre actividades con Intents.
Tester/QA: Realizar pruebas exhaustivas para garantizar que la aplicación funcione correctamente.
Entrega y Plazos
Fecha de Entrega: 8/10/2024 23:59 - SIN EXTENSIÓN
Formato de Entrega: Repositorio en Git, documentación técnica y capturas de pantalla o video del funcionamiento de la aplicación.
