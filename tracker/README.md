# Mi tracker de comidas y peso

App de una sola página (`index.html`), sin dependencias ni servidor. Pensada para cargar desde el celular en menos de un minuto por día.

## Cómo usarla

- Abrí `index.html` en el navegador. En el celular conviene servirla (por ejemplo con GitHub Pages) y usar **"Agregar a pantalla de inicio"**.
- Los datos se guardan **solo en ese navegador** (localStorage). Exportá un respaldo cada tanto desde **Ajustes**: la app te avisa si pasaron más de 14 días.

## Qué tiene

| Pestaña | Contenido |
|---|---|
| **Hoy** | Desayuno, almuerzo, merienda, cena y snacks: qué comiste, porción (chica/mediana/grande), verdura y proteína. Desplegable con hambre antes (1–5), energía después (1–5) y calorías opcionales. Agua (vasos), movimiento (actividad + pasos), sueño, etiquetas rápidas ("comí afuera", "día de estrés"…) y notas. Recordatorio para pesarte los días elegidos. |
| **Peso** | Objetivo con barra de progreso, ritmo reciente contra el ritmo necesario para la fecha tentativa, gráfico con promedio móvil de las últimas 3 pesadas, historial y medidas (cintura/cadera). |
| **Semana** | Grilla de hábitos cumplidos por día (L–D), resumen (agua, sueño, cambio de peso, hambre/energía, kcal) y patrones por comida de las últimas 4 semanas. |
| **Ajustes** | Peso inicial, meta, fecha, metas diarias, días de pesaje, exportar JSON/CSV, importar JSON y borrar datos. |

### Cuándo se cuenta un hábito como cumplido

- **Comidas:** 3 o más registradas.
- **Agua:** llegar a la meta de vasos.
- **Verduras:** en almuerzo **y** cena.
- **Proteína:** en desayuno, almuerzo y cena.
- **Movimiento:** cualquier actividad marcada o llegar a la meta de pasos.
- **Sueño:** llegar a la meta de horas.
