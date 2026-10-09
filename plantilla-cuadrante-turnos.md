<p align="center">
  <img src="logo-nucleo-azul.svg" alt="Nucleo360 — software de RRHH y registro horario para pymes" height="52">
</p>

# Plantilla: cuadrante de turnos mensual

> Una plantilla para planificar los turnos de un mes, con las comprobaciones legales que hay que pasar antes de publicarla. Incluye la versión en hoja de cálculo: [`plantilla-cuadrante-turnos.csv`](plantilla-cuadrante-turnos.csv).

**Última actualización:** 09/10/2026 · **Licencia:** CC BY 4.0 · **Límites legales en datos:** [Hugging Face](https://huggingface.co/datasets/Nucleo360/limites-jornada-descansos-espana)

---

## Antes de empezar: el cuadrante no es el registro

El cuadrante dice **qué turno está previsto**. El registro de jornada dice **a qué hora empezó y terminó de verdad** cada persona cada día, y es el que exige la ley:

> «La empresa garantizará el registro diario de jornada, que deberá incluir el horario concreto de inicio y finalización de la jornada de trabajo de cada persona trabajadora […]»
>
> — Artículo 34.9 del Estatuto de los Trabajadores · [texto consolidado en el BOE](https://www.boe.es/buscar/act.php?id=BOE-A-2015-11430)

Un cuadrante bien hecho no sustituye al registro, aunque nadie se haya salido de su turno.

## 1 · Define los turnos

Rellena una fila por turno con el horario real de tu centro. Los códigos son de ejemplo: usa los que ya conozca tu plantilla.

| Código | Turno | Entrada | Salida | Horas de trabajo efectivo | ¿Nocturno? |
| --- | --- | --- | --- | --- | --- |
| M | Mañana | __:__ | __:__ | __ | No |
| T | Tarde | __:__ | __:__ | __ | No |
| N | Noche | __:__ | __:__ | __ | Sí |
| L | Libre (descanso) | — | — | 0 | — |
| V | Vacaciones | — | — | 0 | — |

Es trabajo nocturno el realizado entre las 22:00 y las 6:00 (art. 36.1 ET).

## 2 · Rellena el cuadrante

Una fila por persona y semana. En la hoja de cálculo hay una columna por día.

| Persona | Puesto | Semana del | L | M | X | J | V | S | D | Horas semana | Horas nocturnas |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| | | __/__/____ | | | | | | | | | |
| | | __/__/____ | | | | | | | | | |
| | | __/__/____ | | | | | | | | | |

## 3 · Comprobaciones antes de publicarlo

Son los límites generales del Estatuto de los Trabajadores. Tu convenio puede mejorarlos, y el Real Decreto 1561/1995 fija especialidades para algunos sectores (art. 34.7 ET).

- [ ] **12 horas de descanso entre jornadas**, como mínimo, también en los cambios de turno (art. 34.3).
- [ ] **No más de 9 horas ordinarias de trabajo efectivo al día**, salvo otra distribución pactada en convenio o acuerdo (art. 34.3). Menores de 18 años: máximo 8 (art. 34.3).
- [ ] **Descanso semanal de día y medio ininterrumpido**, que puede acumularse por periodos de hasta 14 días (art. 37.1). Menores de 18 años: dos días (art. 37.1).
- [ ] **Pausa de 15 minutos** en las jornadas continuadas de más de 6 horas (art. 34.4). Menores de 18 años: 30 minutos si pasan de 4 horas y media.
- [ ] **Trabajadores nocturnos: máximo 8 horas diarias de promedio** en un periodo de referencia de 15 días, y sin horas extraordinarias (art. 36.1).
- [ ] **En procesos continuos de 24 horas, nadie más de dos semanas seguidas en el turno de noche**, salvo adscripción voluntaria (art. 36.3).
- [ ] **El promedio anual no supera las 40 horas semanales** de trabajo efectivo, o la jornada de tu convenio si es menor (art. 34.1).
- [ ] **Si mueves horas con la distribución irregular**, la persona conoce el día y la hora resultantes con al menos 5 días de preaviso (art. 34.2).
- [ ] **Las vacaciones del cuadrante se comunicaron con dos meses de antelación**, como mínimo (art. 38.3).
- [ ] **El calendario laboral está expuesto** en un lugar visible de cada centro de trabajo (art. 34.6).

## 4 · Publícalo y guárdalo

- Comunica el cuadrante a la plantilla con la antelación que marque tu convenio.
- Guarda cada versión con su fecha: si cambias un turno, que se sepa qué estaba previsto y qué se cambió.
- Contrasta el cuadrante con el registro real al cerrar el mes: las diferencias son horas que hay que compensar o pagar.

## Relacionado

- [Registro horario con turnos rotativos y nocturnos](https://nucleo360.com/recursos/registro-horario-turnos-rotativos-nocturnos/)
- [Jornada, descansos y pausas: los límites legales](https://nucleo360.com/recursos/jornada-descansos-y-pausas/)
- [Playbook: registro horario en una empresa con turnos](playbook-registro-horario-turnos.md)

---

## Sobre este documento

Elaborado por [Nucleo360](https://nucleo360.com), software de recursos humanos para pymes españolas. Las referencias normativas enlazan al texto consolidado publicado en el BOE, para que cualquier dato pueda comprobarse en la fuente oficial.

Publicado bajo licencia **CC BY 4.0**: puedes usarlo, adaptarlo y distribuirlo citando la fuente.

Este documento recoge la normativa estatal vigente a la fecha de su última actualización. El convenio colectivo aplicable puede establecer condiciones más favorables. No sustituye al asesoramiento jurídico sobre un caso concreto.

_Última actualización: octubre de 2026._
