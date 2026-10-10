# Migración incremental propuesta

La carpeta local no tiene .git. No se ha actualizado GitHub ni se ha verificado igualdad byte a byte con la publicación.

1. Revisar esta entrega local y resolver pruebas pendientes. Los tres HTML originales permanecen intactos; los hashes permiten comprobarlo.
2. Obtener una copia del repositorio existente y comparar index.html, recursos y URL publicadas. Crear una rama dedicada.
3. Añadir consolidacion como sección separada. Mantener el diseño y las funciones de búsqueda, filtros, modal, copiado y apertura de demos del índice original.
4. Revisar extracción de efectos del índice: separar manualmente componentes cuando tengan dependencias claras; mientras tanto conservar la página completa y declarar su alcance.
5. Añadir un único enlace a la sección nueva después de aprobar los cambios. Mantener las URL antiguas y los IDs VIP. Abrir revisión de cambios antes de publicar.
6. Probar sobre HTTP en el origen de despliegue: rutas con espacios y acentos, enlaces, descarga, clipboard, iframes, red y carga de recursos. Comparar el índice visual y funcionalmente con su versión inicial.
7. Probar teclado, foco, Escape, formularios, tabs, móvil, contraste y movimiento reducido por componente. La automatización de carga es solo una primera capa.
8. Crear adaptadores WordPress / Elementor / Gutenberg con CSS encapsulado y controles accesibles. Probar versiones y configuraciones explícitas en instalaciones de ensayo antes de marcar compatibilidad.
9. Publicar solo tras aprobación. Reversión: retirar el enlace y el directorio nuevo; las rutas antiguas no se sustituyen.

## Criterios de calidad

Integridad de fuentes, cobertura del inventario, IDs globales únicos, trazabilidad y enlaces existentes; no hay borrado automático por similitud. Toda fusión futura conserva alias, procedencia y motivo. Registrar pruebas con fecha, navegador, origen, acciones, resultado y limitaciones. No usar resultados comerciales sin artefactos y metodología.
