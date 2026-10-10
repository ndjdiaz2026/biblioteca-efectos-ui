# Diagnóstico de las fuentes locales

El índice contiene 15 entradas de páginas completas: títulos, cliente/contexto, categorías, paletas y etiquetas de efectos; ofrece búsqueda, filtros, modal iframe, apertura y copiado de colores. Clasifica principalmente por cliente y presentación, no por problema. Sus entradas no tienen IDs de patrón: se conserva la ausencia y se añade un ID global por ocurrencia. El índice depende de Tailwind por CDN y fuentes externas.

Web VIP 01 y 02 contienen 16 patrones cada uno, con IDs originales, marca, título, etiquetas, referencia, observed, why, use, measure, adapt, CSS, HTML y JavaScript. Generan demos autónomas mediante documentFor y las presentan en iframes, con descarga y copiado. Esa estructura permite extraer 32 fichas sin reescribir los ejemplos.

Se distinguen 171 registros: 32 patrones, 15 páginas y 124 ocurrencias de etiquetas de efecto. No son 171 patrones independientes probados. Las 124 ocurrencias tienen procedencia y página de demostración, pero no aislamiento de código por efecto. La unidad se declara en kind y en cada ficha.

Las afirmaciones observadas en sitios de terceros se conservan como declaraciones de los volúmenes: no se han verificado de nuevo en los sitios externos. El texto sobre conversión del índice es hipótesis, no resultado. No hay evidencia comercial aportada que permita afirmar eficacia.

## Relaciones

El catálogo registra duplicados de demo por hash, títulos coincidentes como candidatos a variante y problemas compartidos como relaciones propuestas. No se elimina ninguna ocurrencia. Los títulos idénticos de laboratorios pueden corresponder a versiones diferentes; comparar alcance y código antes de fusionar. Efectos repetidos en páginas diferentes conservan sus contextos.

## Arquitectura entregada y límites

sources conserva HTML, caché y manifiesto; records contiene fichas; demos mantiene páginas y componentes VIP; catalog reúne metadatos y originales; presentation ofrece búsqueda y filtro por problema con el logo; evidence registra pruebas; schemas define el contrato; docs guía consulta y migración.

Los IDs globales usan fuente y ocurrencia original estable de esta extracción. Congelarlos después de revisar el inventario: reordenar el índice no debe regenerar identidades. Para nuevas entradas asignar UUID y mantener un mapa explícito de identidad; nunca sustituir original_ids. El constructor actual utiliza ordinales para el índice y requiere esa mejora antes de automatizar futuras reimportaciones.

Las advertencias son curatoriales y orientadas a familias de interacción, no una auditoría exhaustiva de cada implementación. La taxonomía es inicial y requiere revisión contextual de cada registro. WordPress, Elementor y Gutenberg permanecen no evaluados.

## Calidad

Se probaron 47 demos en Edge Chromium sobre archivos locales. Cinco muestran tailwind is not defined en este entorno; no se reescriben para ocultar el fallo. Consultar evidence/quality.json para carga e interacciones básicas. La prueba local no equivale a funcionamiento sobre GitHub Pages: faltan origen HTTP, recursos de red, contraste, lectores de pantalla y recorridos completos por teclado. Los originales conservan sus hashes. El repositorio remoto no fue modificado.
