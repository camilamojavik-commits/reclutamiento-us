# Reclutamiento US · Instructores (Coderhouse)

Tablero offline para sourcing de instructores US (AI Engineering + Data Analytics Live, evening PT).

## Cómo abrirlo

1. Abrí el archivo en el navegador (doble clic o arrastralo a Chrome/Firefox/Edge/Safari):

   `tablero-reclutamiento-us.html`

2. **Fallback siempre visible** (sin localStorage):

   `tablero-simple.html` — tabla estática de los 8 candidatos Contactado.

3. No hace falta servidor ni internet: todo corre en el navegador.

## Cómo compartirlo

- Enviá el archivo `.html` por Slack, email o Drive.
- Quien lo abra tiene **su propia copia de datos** en `localStorage` de ese navegador (no se sincroniza entre personas).
- Para pasar el listado a otra persona/máquina: usá **Export JSON** → la otra persona usa **Import JSON**.
- También podés exportar **CSV** para Sheets/Excel.

## Datos locales

- Candidatos: key `coderhouse-reclutamiento-us-v5`
- Templates editables: key `coderhouse-reclutamiento-us-templates-v3`
- Si el storage está vacío, `[]`, o solo filas EJEMPLO, al abrir se restaura el SEED (8 shortlist).
- Botón **Resetear a shortlist** fuerza el SEED y re-renderiza.
- Borrar datos del sitio / storage del navegador borra cambios locales (exportá antes).

## Features

- Tabla filtrable + vista cards (vista default al abrir)
- Filtros por curso y status
- Alta / edición / baja de candidatos
- Chips de status, copiar LinkedIn, validación liviana de URL
- Templates de primer contacto (EN, 2-step sin Cal) y Slack a Chris (ES, booking alert)
- Seed: 8 candidatos AI Engineering en status Contactado

## Tip

Si el tablero aparece vacío: usá **Resetear a shortlist**, o abrí `tablero-simple.html`.
