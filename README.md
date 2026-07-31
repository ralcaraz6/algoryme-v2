# Algoryme · web v2 (prototipo)

Versión minimalista de algoryme.com, para comparar enfoques. **No sustituye a la web actual.**

- En vivo: https://ralcaraz6.github.io/algoryme-v2/
- Web actual: https://algoryme.com

## Idea

Los servicios como carta de restaurante: se ven los seis de un vistazo, en tarjetas verticales
con su ilustración, una explicación de verdad (no una frase suelta) y tres puntos concretos.
Cada uno con su propia landing. Home = servicios + proceso + equipo + contacto.

Los siete, en el orden que ve el visitante:

1. **Aplicaciones y webs a medida**
2. **Auditoría de adopción de IA**
3. **Automatización de procesos**
4. **Informes automáticos**
5. **Atención al cliente automatizada**
6. **Chatbots con documentación interna**
7. **Dashboards e inteligencia de negocio**

Nombres elegidos por el cliente. Las tarjetas van sin viñetas y bajo un encabezado de sección
(«Servicios · Qué podemos construir para ti»), porque sin él no se entendía qué eran las tarjetas.

## Detalle importante

Cada landing tiene su propio formulario con un campo oculto `servicio`, y el asunto del correo
llega como `Web v2 · <servicio> · <nombre>`. Así se sabe por qué servicio entra cada contacto.

## Estado

- Solo en español (el prototipo no lleva el motor de idiomas de la web principal).
- `noindex` en todas las páginas: es un prototipo, no debe competir en Google con algoryme.com.
