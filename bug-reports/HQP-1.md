# HQP-1 — El término de búsqueda del encabezado no coincide con el de la ruta de navegación

**Tipo:** Bug / Error  
**Estado registrado en Jira:** Por hacer  
**Prioridad propuesta:** Medium

Referencia: BR-01

## Entorno
Captura de pantalla de HENDERSON proporcionada en un ejercicio académico de Netology. Sistema operativo y navegador desconocidos.

## Contexto
La captura muestra una página de resultados de búsqueda. La ruta de navegación indica el término «пиджак» (chaqueta).

## Pasos de revisión

1. Abrir la captura de pantalla proporcionada.
2. Localizar el término de búsqueda en la ruta de navegación.
3. Compararlo con el término del encabezado de resultados.

## Resultado actual
La ruta de navegación muestra «Поиск по запросу "пиджак"», mientras que el encabezado muestra «По вашему запросу "носки" найдено:». Los términos «пиджак» (chaqueta) y «носки» (calcetines) no coinciden.

## Resultado esperado
El encabezado y la ruta de navegación muestran el mismo término de búsqueda: «пиджак».

## Severidad
Menor (Minor)

## Evidencia

![Captura del ejercicio de Netology](../evidence/search-results.png)

## Alcance de la revisión

Hallazgo documentado a partir de una imagen estática. La severidad y la prioridad son estimaciones del ejercicio. No se verificó la reproducibilidad en el sitio actual ni una corrección del producto.
