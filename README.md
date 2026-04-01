# 📱 Urban.Lunch - Mobile Testing (Android)
**QA Engineer:** Daniel Chacon | **Location:** Chile 🇨🇱

Este proyecto consistió en el testing integral de la primera versión para Android de **Urban.Lunch**, una plataforma de pedidos de comida. El enfoque principal fue validar la usabilidad, funcionalidad y flujo de fin a fin (E2E) desde la selección del menú hasta la asignación del punto de recogida.

## 🎯 Alcance de las Pruebas
* **Exploratory Testing:** Exploración de la interfaz para detectar errores de diseño y navegación.
* **Functional Testing:** Validación de los requisitos críticos en negrita (Selección de restaurante, carrito y checkout).
* **Compatibilidad:** Pruebas ejecutadas en emulador con diferentes versiones de Android a través de **Android Studio**.
* **Puntos de Recogida:** Verificación de la lógica de asignación de locaciones para retiro.

## 🛠️ Tecnologías y Herramientas
* **Android Studio / AVD:** Para la emulación de diversos dispositivos y versiones de sistema operativo.
* **Jira:** Reporte y seguimiento de bugs con evidencia (screenshots y logs).
* **Google Docs/Sheets:** Documentación de requisitos, listas de comprobación y reportes de ejecución.
* **Mind Maps:** Visualización de flujos de usuario para cubrir todos los caminos posibles.

## 🧠 Retos Técnicos y Soluciones (Mobile Mindset)

| Escenario de Prueba | Estrategia de Resolución |
| :--- | :--- |
| **Interrupciones de Sistema:** ¿Qué pasa si entra una llamada o se cambia de app mientras pido comida? | Se realizaron pruebas de interrupción para asegurar que el estado del carrito no se perdiera al minimizar la aplicación. |
| **Diversidad de Pantallas:** La aplicación debe ser responsiva en diferentes densidades de píxeles. | Uso del emulador para probar en diferentes tamaños de pantalla (Phone vs Tablet), detectando errores de superposición de botones. |
| **Navegación de Android:** Uso del botón físico/gesto "Atrás" del sistema. | Validación de que la navegación interna de la app no rompiera el flujo al usar los controles nativos del sistema operativo. |



## 📊 Informe de Ejecución y Estado del Producto
Tras completar la lista de comprobación de los requisitos críticos:

* **Casos de Prueba (Checklist):** [71] Total ejecutados.
* **Resultados:** [65] APROBADOS | [6] NO APROBADOS.
* **Bugs Críticos:** Se identificaron errores en el flujo de selección de puntos de recogida que impedían finalizar la orden en ciertas condiciones.

### 📝 Conclusión del QA
"La aplicación presenta una base sólida en cuanto a UI, pero requiere ajustes urgentes en la lógica de confirmación de pedidos. El estado actual es **Beta Inestable**, recomendando una segunda iteración de desarrollo antes del lanzamiento oficial en la Play Store."

## 🚀 Cómo revisar este proyecto
1. **Lista de Comprobación:** [Enlace a mi Google Sheets](https://docs.google.com/spreadsheets/d/18507kN22gydp_4Vd7Livl8jgydJOziaD/edit?usp=sharing&ouid=111900472603636147925&rtpof=true&sd=true) (Modo Comentador).
2. **Evidencia de Bugs:** Se adjuntan enlaces a Jira en el reporte de resultados:

* **https://danielchaconberrueta.atlassian.net/browse/URBL-1**
* **https://danielchaconberrueta.atlassian.net/browse/URBL-2**
* **https://danielchaconberrueta.atlassian.net/browse/URBL-5**
* **https://danielchaconberrueta.atlassian.net/browse/URBL-6**
* **https://danielchaconberrueta.atlassian.net/browse/URBL-7**
* **https://danielchaconberrueta.atlassian.net/browse/URBL-8**
