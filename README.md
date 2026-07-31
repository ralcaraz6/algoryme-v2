# Algoryme · web v2 (prototipo)

Versión minimalista de algoryme.com, para comparar enfoques. **No sustituye a la web actual.**

- En vivo: https://ralcaraz6.github.io/algoryme-v2/
- Web actual: https://algoryme.com

## Idea

Los servicios como carta de restaurante: se ven los seis de un vistazo, cada uno con su
ilustración, y cada uno con su propia landing. Home = servicios + proceso + equipo + contacto.

## Detalle importante

Cada landing tiene su propio formulario con un campo oculto `servicio`, y el asunto del correo
llega como `Web v2 · <servicio> · <nombre>`. Así se sabe por qué servicio entra cada contacto.

## Estado

- Solo en español (el prototipo no lleva el motor de idiomas de la web principal).
- `noindex` en todas las páginas: es un prototipo, no debe competir en Google con algoryme.com.
