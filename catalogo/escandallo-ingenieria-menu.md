# escandallo-ingenieria-menu

`escandallo-ingenieria-menu` · v1.1.1 · Hostelería

> 

**Precio:** Instalación Esencial 2.500 € · Completa 4.900 €

## Qué hace

Convierte una carta con precios, un export de ventas por plato del POS y las recetas con gramajes en un informe que dice, plato por plato, cuánto cuesta de verdad, cuántos euros de margen deja cada unidad vendida, en qué cuadrante de la matriz de Kasavana-Smith cae, y qué hacer con él el lunes: proteger, bajar coste, trabajar la venta o retirar. Cierra en una cifra: los euros al año que valen las acciones recomendadas.

Esto no es una tabla de costes que cualquier hoja de cálculo produce. Un escandallo hecho con el precio del albarán por los gramos de la receta está mal por construcción: le faltan tres capas —rendimiento tras limpieza, merma de cocción y costes que nadie imputa (pan y aceite de mesa, fondos, aceite de fritura, envase de reparto)— que en conjunto mueven el coste del plato varios puntos enteros. En la carta de prueba de esta skill, la merluza pasa de 11,4% de food cost a 30,4% con solo aplicar rendimiento (52%) y merma de plancha (18%): tres veces más coste, la misma receta. Y la decisión final no se toma con el porcentaje, sino con el margen de contribución en euros, porque el banco cobra en euros.

## Para quién es



**Para quién NO es:** 

## Qué NO hace

- No es contabilidad ni asesoría fiscal, y no es una auditoría. Los tipos de IVA que aplica son los vigentes verificados en `references/FUENTES.md`; el tipo real de cada línea lo confirma el asesor del cliente.
- No calcula la carta de vinos con rotación de bodega ni valora existencias a efectos contables.
- No cambia precios en ningún sistema: recomienda, y la decisión de precio la firma el dueño.
- No sustituye la medición de rendimientos en esa cocina. Con rendimientos estimados el informe es una hipótesis de trabajo, y así se declara plato por plato.
- El análisis de reparto a domicilio queda fuera del informe estándar: la comisión de plataforma cambia el signo de platos rentables en sala y exige una carta analizada aparte.
- Cuando el diagnóstico apunte a sustracción o a un descuadre que implique a personas, se entrega la cifra y se deriva la decisión al dueño y, si procede, a asesoría laboral. Esta skill no acusa a nadie.

## Cómo se compra

**Se vende como instalación presencial**, ejecutada en tu local con tus datos, nunca con una demo. Abre un *issue* en este repositorio con el nombre del local y la ciudad.

## Licencia

Uso comercial permitido en la actividad del comprador, sin límite de ejecuciones. Prohibida la
redistribución, reventa o publicación. Copyright 2026 Sergio Berriozábal Serrano.
