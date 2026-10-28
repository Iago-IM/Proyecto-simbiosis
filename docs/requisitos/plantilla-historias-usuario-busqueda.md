# Historias de usuario de búsqueda

| Campo | Valor |
| --- | --- |
| Proyecto | Proyecto Simbiosis |
| Fecha | [28/10/2026] |
| Versión | [Versión de trabajo] |
| Estado | Borrador |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda

Como usuario, quiero buscar recetas, para encontrar recetas que se ajusten a mis preferencias.

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división

[Justificación de los resultados útiles que separa la división.]

## US-01

**Título:** Buscar mediante una palabra o frase

Como usuario, quiero poder filtrar recetas por palabra o frase, para agilizar la búsqueda de recetas.

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado un usuario que está filtrando recetas, cuando introduce una palabra o frase para filtrar recetas, entonces se muestran todas las que tengan ese texto, sin diferenciar las mayúsculas de las minúsculas.
- **CA-02.** Dado un usuario que está filtrando recetas, cuando introduce un texto que no contiene ninguna receta, entonces el sistema indica que no hay resultados para esa búsqueda y mantiene los criterios para que puedan ser modificados.
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## US-02

**Título:** Buscar por ingredientes incluidos

Como usuario, quiero filtrar recetas por los ingredientes que incluyen, para encontrar recetas que se adecuen a mis preferencias.

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado un usuario que busca recetas, cuando filtra por ingredientes incluidos, dentro de las opciones de ingredientes que tiene, entonces el sistema muestra recetas que contengan esos ingredientes.
- **CA-02.** Dado un usuario que está buscando recetas, cuando filtra por ingredientes incluidos un ingrediente marcado como excluido, entonces el sistema muestra el conflicto y no se ejecuta la búsqueda hasta que se corrija.
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## US-03

**Título:** Excluir ingredientes

Como usuario quiero excluir ingredientes de mi búsqueda para buscar recetas que se ajusten a mis preferencias.

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado un usuario que busca recetas, cuando selecciona ingredientes a excluir, entonces el sistema muestra recetas que no contengan esos ingredientes.
- **CA-02.** Dado un usuario que busca recetas, cuando selecciona ingredientes a excluir de forma que no haya recetas que no contengan alguno de los ingredientes, entonces el sistema indica que no hay resultados para esa búsqueda y mantiene los criterios para que puedan ser modificados.
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## Revisión INVEST

La revisión abarca US-01, US-02 y US-03. «Aplicado» indica si se ha realizado la comprobación. «Cumple» indica si todas las historias cumplen el criterio. Si alguna no lo cumple, indicar «No» e identificar la historia y el motivo en la justificación. Si no se ha realizado la comprobación o faltan datos, indicar «Pendiente» en «Cumple».

| Criterio | Pregunta de revisión | Aplicado | Cumple | Justificación |
| --- | --- | --- | --- | --- |
| Independiente | ¿Puede implementarse cada historia y ofrecer un resultado útil sin implementar antes las otras historias del conjunto? Puede compartir infraestructura con ellas. | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Negociable | ¿Cada historia explica qué necesita la persona y deja margen para discutir los detalles de la solución, respetando los acuerdos confirmados? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Valiosa | ¿La parte «para…» de cada historia explica el beneficio que obtiene la persona al usar esa capacidad? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Estimable | ¿Están claros el alcance y los datos necesarios para estimar el trabajo de cada historia? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Pequeña | ¿Se centra cada historia en una única capacidad de alcance manejable? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Comprobable | ¿Los criterios de aceptación de cada historia describen acciones y resultados observables que permiten distinguir un comportamiento correcto de uno incorrecto? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |

## Dudas pendientes

[Cuestiones pendientes de aclaración. Si no quedan cuestiones, indicar «Ninguna».]
