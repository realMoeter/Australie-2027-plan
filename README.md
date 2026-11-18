# Australia 2027 – Gantt Chart

Timeline for the field and lab work in Australia (Sydney / Oberon), Feb–May 2027.

Open `index.html` in a browser to see the chart. The red dashed line always shows today's date.

## How to edit

All bars are in the `rows` list inside the `<script>` part of `index.html`:

```js
{t:'W2 Pilot: attack behaviour, P/S criteria', s:'2027-02-15', e:'2027-02-21', c:'obe'},
```

| Key | Meaning |
|-----|---------|
| `t` | Text on the left |
| `s` / `e` | Start / end date (YYYY-MM-DD) |
| `m` | Milestone (diamond) instead of `s`/`e` |
| `c` | Colour: `prep`, `syd`, `obe`, `data`, `buf`, `hol` |
| `n` | Optional note shown on hover |
| `{sec:'…'}` | Section heading |

`START` / `END` set the time axis, `holidays` the shaded holidays.
