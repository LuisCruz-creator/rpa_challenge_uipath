# RPA Challenge - Data Migration Automator 🤖🚀

Este repositorio contiene un proceso automatizado desarrollado en **UiPath (Modern Design)** diseñado para resolver el desafío operativo de migración de datos masivos desde un origen estructurado hacia un formulario web dinámico.

## 🎯 Objetivo del Proyecto
Automatizar el procesamiento por lotes (Batch Processing) de registros de usuarios, garantizando un **100% de efectividad** en el llenado de información en interfaces web cuyos elementos cambian de posición dinámicamente en cada transacción.

## ⚙️ Características Técnicas y Arquitectura
* **Lectura de Datos Estructurados:** Integración con Google Sheets / Excel para la extracción de vectores de datos (`DataTables`).
* **UI Automation Avanzada:** Uso de **Anclas Modernas (Anchors)** y selectores difusos (*Fuzzy Matches*) para ubicar de manera exacta los campos objetivo sin importar cambios en la interfaz de usuario.
* **Procesamiento de Ciclo Iterativo:** Implementación de un bucle `For Each Row` optimizado para la inserción limpia de variables tipo *String* independientes por cada iteración.
* **Manejo de Eventos de Interfaz:** Configuración de propiedades avanzadas de verificación de clics (`Verify Execution`) para mitigar errores de sincronización y cargas asíncronas de la página.

## 📊 Resultados Obtenidos
* **Tasa de éxito:** 100% (70/70 campos procesados de forma consecutiva).
* **Tiempo promedio de ejecución:** ~88 segundos para el lote completo.
