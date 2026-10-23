# HQP-4 — Los precios mostrados en el primer y tercer producto no corresponden a los descuentos anunciados

**Tipo:** Bug / Error  
**Estado registrado en Jira:** Por hacer  
**Prioridad propuesta:** High

Referencia: BR-04

## Entorno
Captura de pantalla de HENDERSON proporcionada en un ejercicio académico de Netology. Sistema operativo y navegador desconocidos.

## Contexto
Se revisan las tarjetas del primer y tercer producto de la fila superior. Ambas muestran un precio anterior tachado, un precio actual y una etiqueta de descuento.

## Pasos de revisión

1. Abrir la captura de pantalla proporcionada.
2. Localizar el primer y tercer producto de la fila superior.
3. Comparar sus precios anteriores, precios actuales y descuentos anunciados.
4. Calcular los precios correspondientes a los descuentos indicados.

## Resultado actual
Primer producto: precio anterior de 23 999 ₽, descuento del 50 % y precio actual de 41 995 ₽.

Tercer producto: precio anterior de 23 999 ₽, descuento del 90 % y precio actual de 11 995 ₽.

En ambos casos, el precio actual no corresponde al descuento anunciado.

## Resultado esperado
El precio anterior, el precio actual y el porcentaje de descuento son coherentes entre sí. Si los descuentos indicados se aplican al precio anterior de 23 999 ₽:

Primer producto: 23 999 × 0,50 = 11 999,50 ₽.

Tercer producto: 23 999 × 0,10 = 2 399,90 ₽.

Los importes mostrados deben respetar la regla de redondeo definida para el sitio.

## Severidad
Mayor (Major)

## Evidencia

![Captura del ejercicio de Netology](../evidence/search-results.png)

## Alcance de la revisión

Hallazgo documentado a partir de una imagen estática. La severidad y la prioridad son estimaciones del ejercicio. No se verificó la reproducibilidad en el sitio actual ni una corrección del producto.
