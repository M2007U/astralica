"RGBA Format" strictly speaking is a misnomer, as not every species has Red Green Blue cone cells.
Based on the different dialects, multiple slots are defined :

First is the Hue Slots

```
<Hue 1> <Hue 2> <Hue 3> ... <Hue N>
```

Due to how Additive Mixing works, this also controls the Saturation and the Luminance of the Color
Then finally the Opacity Slot

```
<Alpha>
```

Every slot is then filled with a single digit  number, ranging from 0 to F

|                                       |                    |                    |     |                    |                    |
| ------------------------------------- | ------------------ | ------------------ | --- | ------------------ | ------------------ |
| ![[KosraNo_Lira.png\|50]]             | **(Slot : Hue 1)** | **(Slot : Hue 2)** | ... | **(Slot : Hue N)** | **(Slot : Alpha)** |
| ![[KosraNo_Lira_TaKlaKla.png\|50]]    | ^                  | ^                  | ^   | ^                  | ^                  |
| "Color - RGBAFormat"<br>/Li - KlaZoi/ |                    |                    |     |                    |                    |

this means that every color in this format can be treated as a Hexadecimal number.