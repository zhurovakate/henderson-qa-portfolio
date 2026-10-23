# HQP-2 — Los números de teléfono de la cabecera presentan formatos diferentes

**Tipo:** Bug / Error  
**Estado registrado en Jira:** Por hacer  
**Prioridad propuesta:** Low

Referencia: BR-02

## Entorno
Captura de pantalla de HENDERSON proporcionada en un ejercicio académico de Netology. Sistema operativo y navegador desconocidos.

## Contexto
En la parte superior de la captura aparecen dos números de contacto.

## Pasos de revisión

1. Abrir la captura de pantalla proporcionada.
2. Localizar los números de teléfono en la cabecera.
3. Comparar los separadores y la agrupación de los dígitos.

## Resultado actual
El número «+7 (495) 7-440-300» utiliza paréntesis, espacios y guiones. El número «8 800 333 57 75» utiliza únicamente espacios.

## Resultado esperado
Si las pautas de diseño establecen un formato común, ambos números deben seguirlo, respetando sus prefijos y códigos correspondientes.

## Severidad
Trivial

## Observación
Requiere aclaración de los requisitos de diseño. La diferencia de formato por sí sola no confirma un defecto.

## Evidencia

![Captura del ejercicio de Netology](../evidence/search-results.png)

## Alcance de la revisión

Hallazgo documentado a partir de una imagen estática. La severidad y la prioridad son estimaciones del ejercicio. No se verificó la reproducibilidad en el sitio actual ni una corrección del producto.
