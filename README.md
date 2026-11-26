# KOD skills

Skills abiertas para agentes de IA (Claude, ChatGPT, Kody): ventas, cobranzas, recursos humanos, soporte, compras y más. En español y basadas en métodos probados. Úsalas, cópialas y adáptalas.

Las hace [KOD](https://usekod.com), y sirven igual aunque no uses KOD.

## Áreas

| Área | Para qué |
| --- | --- |
| [Ventas](ventas/) | Vender con honestidad: entender por qué el cliente quiere esto, resolver dudas y acordar el siguiente paso. |
| [Cobranzas](cobranzas/) | Cobrar a tiempo sin romper la relación: recordatorios, acuerdos de pago y seguimiento. |
| [Recursos humanos](rrhh/) | Personas y equipo: búsquedas, entrevistas, bienvenida, conversaciones difíciles y comunicados. |
| [Soporte y servicios](soporte/) | Atender clientes que ya compraron: entender el problema, resolver o derivar, y cerrar el caso. |
| [Compras y proveedores](compras/) | Pedir cotizaciones, comparar proveedores y negociar condiciones. |
| [Stock e inventario](stock-inventario/) | Controlar existencias, reponer a tiempo y avisar faltantes. Próximamente. |
| [Resolución de conflictos](conflictos/) | Reclamos, desacuerdos, clientes molestos y pedidos fuera de lo acordado. |
| [Legales](legales/) | Contratos y temas legales, siempre con revisión de un profesional. Próximamente. |

Cada área trae una **guía base** (cómo trabajar bien en esa área aunque no haya una ficha puntual) y sus **fichas**, una por situación concreta.

## Cómo se usan

**Claude Code o Claude:** agrega este repositorio como marketplace e instala el área que quieras.

```
/plugin marketplace add pl-eas/kod-skills
/plugin install kod-ventas@kod-skills
```

**ChatGPT u otro agente:** copia el texto de un `SKILL.md` en las instrucciones del agente o del proyecto.

**KOD:** Kody usa estas fichas dentro de las propuestas. Se activan en Ajustes › IA y Kody › Habilidades.

## Reglas de todas las fichas

- Frente al cliente nunca se menciona la ficha ni la técnica. Solo se responde mejor.
- Solo datos reales: nada de montos, plazos, casos o promesas inventadas.
- Las decisiones de precio, dinero, contratos y personas las toma una persona del equipo.

## Contribuir

Abre un pull request con una ficha nueva dentro de `<área>/skills/<nombre>/SKILL.md`. Sigue el formato de las fichas de `ventas`: cuándo se usa, pasos, un ejemplo y lo que no se hace nunca. Escribe desde los métodos originales y en tus palabras.

## Licencia

MIT. Puedes usar, copiar, modificar y compartir todo, también con fines comerciales.
