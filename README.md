# Algoryme · web v2 (prototipo)

Versión minimalista de algoryme.com, para comparar enfoques. **No sustituye a la web actual.**

- En vivo: https://ralcaraz6.github.io/algoryme-v2/
- Web actual: https://algoryme.com

## Idea

Los servicios como carta de restaurante: se ven los seis de un vistazo, en tarjetas verticales
con su ilustración, una explicación de verdad (no una frase suelta) y tres puntos concretos.
Cada uno con su propia landing. Home = servicios + proceso + equipo + contacto.

Los seis, en el orden que ve el visitante:

1. **Aplicaciones y webs a medida** — lo que más se pide ahora mismo
2. **Auditoría de IA** — la puerta de entrada
3. **Agentes de IA**
4. **Respuesta automática**
5. **Informes automáticos**
6. **Automatización de procesos**

«Documentos y facturas» y «Datos entre sistemas» se retiraron: nadie entendía qué se vendía en
cada una y en la práctica eran el mismo trabajo. Ahora viven dentro de «Automatización de procesos».

## Detalle importante

Cada landing tiene su propio formulario con un campo oculto `servicio`, y el asunto del correo
llega como `Web v2 · <servicio> · <nombre>`. Así se sabe por qué servicio entra cada contacto.

## Estado

- Solo en español (el prototipo no lleva el motor de idiomas de la web principal).
- `noindex` en todas las páginas: es un prototipo, no debe competir en Google con algoryme.com.
