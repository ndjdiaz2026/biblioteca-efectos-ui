# Submenú contextual fuera de la cabecera

- ID global: postsicionate:web-vip-01:K01
- IDs originales: K01
- Fuente: Web-VIP-01-biblioteca.html
- Localizador: {"anchor":"K01","line":28}
- Tipo: pattern
- Problema propuesto: orientacion

## Observación preservada

Bajo «About Kensington» aparecen enlaces a Why Us, Kensington Cares, Our Team y Careers. Cada uno apunta a una página distinta.

Observación atribuida a la fuente local; los sitios de referencia no se han auditado de nuevo.

## Justificación / hipótesis

Agrupa contenido relacionado en el lugar donde el usuario ya está explorando ese tema.

## Contexto de aplicación

Acerca de, servicios, documentación y categorías. En producción usar enlaces reales y aria-current="page".

## Adaptación y límites

La demo cambia vistas locales para funcionar en un único archivo. En el original los enlaces son /why-us, /kensington-cares, /about-us y /careers. No confundir este menú con el índice de beneficios.

## Medición propuesta

Éxito al encontrar equipo, propósito o condiciones; pasos necesarios para hacerlo.

Definir línea base, eventos, población, periodo y criterio antes de medir. Resultados comerciales comprobados: ninguno aportado.

## Advertencias y cuándo evitar

- La eficacia comercial es una hipótesis: validar con usuarios y medición contextual.
- WordPress, Elementor y Gutenberg: integración no evaluada; aislar estilos, IDs y eventos, y probar en el entorno objetivo.
- Datos: etiquetas persistentes, errores anunciados y validación en servidor; no recoger datos reales con la demo. Evitar formularios sin finalidad y tratamiento definidos.
- Compatibilidad de navegador y accesibilidad completa pendientes de pruebas específicas; la carga sin errores no basta.

## Demostración y evidencia

[HTML conservado](../demos/postsicionate--web-vip-01--K01.html)

HTML extraído sin cambiar documentFor de la fuente.

Pruebas: consultar evidence/quality.json; no implican compatibilidad con CMS ni resultados de conversión.

## Relaciones

[
  {
    "target": "postsicionate:web-vip-01:K02",
    "type": "shared-problem",
    "confidence": "proposed"
  },
  {
    "target": "postsicionate:web-vip-01:B03",
    "type": "shared-problem",
    "confidence": "proposed"
  },
  {
    "target": "postsicionate:web-vip-01:C02",
    "type": "shared-problem",
    "confidence": "proposed"
  },
  {
    "target": "postsicionate:web-vip-02:P01",
    "type": "shared-problem",
    "confidence": "proposed"
  }
]

## Fuente externa citada en el volumen

https://kensingtontours.com/why-us
