Based on different dialects, the different slots are :

**Hue Slots**
```
<Hue 1> <Hue 2> <Hue 3> ... <Hue N> or <Hue Name>
```

here the Hues will only affect the "direction" of the color
this will describe the ratio in between the strengths of different hue channels.
These numbers must not share any factors

**Saturation Slot**
this will describe how "pure" the hue will be.
Another way to understand this is "how not grey this color is"

**Vibrance Slot**
this will describe the Brightness or the vibrance of the Color
Another way to understand this is "How not black this color is"


|                                                               |                  |                  |                  |
| ------------------------------------------------------------- | ---------------- | ---------------- | ---------------- |
| ![[KosraNo_Lira.png\|50]]<br>![[KosraNo_Lira_taraka.png\|50]] | **(Slot : Hue)** | **(Slot : Sat)** | **(Slot : Vib)** |
| "Color -<br>HSVA Format"<br>/Li - Taraka/                     |                  |                  |                  |

here, the Saturation Slot and Vibrance Slot are simple numbers, but Hue is the interesting one. Which will be dicused further as below.

---

## Hues

for Every Species, each Primary Colors will be different
and therefore does not exactly has a concrete name.

This means that Astralica has different dialects for different species for different wavelengths.
Of course these primary colors can be named after measurements, but it may not be language friendly.

---

## Breaking the name

In our case, each primary color name has 3 syllables :

| Segment Index | Main Usage | Desc                                                                                      |
| ------------- | ---------- | ----------------------------------------------------------------------------------------- |
| 1             | Primary    | used for stating the main hue                                                             |
| 2             | Full       | Used for stating if the color is mixed with another primary color equally<br>(aka Level4) |
| 3             | NULL       | for now, it just makes things more natural ...                                            |

>[!example]
>for the Human dialect, /Rahaka/ refers to the primary color "red".
>Here /Rahaka/ can be broken down into 3 syllabels : /Ra/, /Ha/, /Ka/
>/Ra/ will be used when stating that the main Hue is Red
>/Ha/ combined with other Primary Colors means "Red is mixed with the other Color 50/50"


---

## Hue's Main Concept


When stating a hue, we need to think of these things mainly:
1. Which Hue is the Dominant (strongest) ?
2. Is it mixed with other primary Hues ?
3. other extra considerations

For laying down the naming convention and formats

Let's assume that  a species can see the following Primary Colors :

$$A, B, C, ...$$

This means that each of them has their 3 segments / syllables

to notate the primary part, we attach "p", so all the PrimaryParts of the colors are :


$$A_p ~,~ B_p ~,~  C_p ~,~ ...$$


Sometimes these primary colors can be mixed with other primary colors, in this case we can attach a number from 0 to 4, like so :


$$A_0 ~,~ A_1 ~,~ A_2 ~,~ A_3 ~,~ A_4$$

where 0 is none (so it can be omitted) and 4 is mixed with the other color 50/50

>[!note] $A_4$ is the 2nd Segment

the full name of a hue should be 

```
/KosraNoNi - Lira - Klari Ru Taxi - <Hue Name>/
```

or shorter

```
/Li - Ta - <Hue Name>/
```

for extreme simplification, just the hue name written in Casual Script should be good.

---

## Hue names : 2 primary colors (Dichromatic)

Cats and Canids (Dogs, Wolves, Foxes) only can see 2 Hues, let's call them X and Y for now.
So we are only dealing with a straight line, which is easier

Now we can build our Color Line :

**Step 01 : Color Line**
let's draw a color line, with 2 major ticks (beginning and end) and 1 smaller secondary tick (middle) and for each segment between a major tick and a secondary tick, we can have 4 smaller segments.

| 0   |       |      |       | 0.5 |       |      |       | 1   |
| --- | ----- | ---- | ----- | --- | ----- | ---- | ----- | --- |
|     | 0.125 | 0.25 | 0.375 |     | 0.625 | 0.75 | 0.875 |     |

Step 02 : Main Hue
Here we can say that H0 takes over the left side and H1 takes over the right side,

|                         |     |       |      |       |       |       |      |       |     |
| ----------------------- | --- | ----- | ---- | ----- | ----- | ----- | ---- | ----- | --- |
| Tickmarks               | 0   |       |      |       | 0.5   |       |      |       | 1   |
| ^                       |     | 0.125 | 0.25 | 0.375 |       | 0.625 | 0.75 | 0.875 |     |
| Pronunciation Structure | X   | X     | X    | X     | X / Y | Y     | Y    | Y     | Y   |

Step 03 : Level of Mixing
Now we can append the Mix Level of the other primary colors

|                         |       |           |           |           |                       |           |           |           |       |
| ----------------------- | ----- | --------- | --------- | --------- | --------------------- | --------- | --------- | --------- | ----- |
| Tickmarks               | 0     |           |           |           | 0.5                   |           |           |           | 1     |
| ^                       |       | 0.125     | 0.25      | 0.375     |                       | 0.625     | 0.75      | 0.875     |       |
| Pronunciation Structure | $X_p$ | $X_p~Y_1$ | $X_p~Y_2$ | $X_p~Y_3$ | $X_p~Y_4$ / $Y_p~X_4$ | $Y_p~X_3$ | $Y_p~X_2$ | $Y_p~X_1$ | $Y_p$ |

>[!example] Colors for the [[🪴 02a _ Kæmaganæ _ Felis]] Dialect
>
>Cats only has 2 primary colors :
>let $X = /Nyawawi/$ and $Y = /Makonyo/$
>then $X_p = /Nya/$
>then $Y_p =/Ma/$
>
>from here we can have the following :
> $$X_0, X_1 , X_2 , X_3 , X_4 = /Nyo/ , /Ni/ , /Nyæ/ , /Nya/ , /Wa/ $$ 
> $$Y_0, Y_1 , Y_2 , Y_3 , Y_4 = /Myo/ , /Mi/ , /Myæ/ , /Mya/ , /Ko/ $$
> 
> and  we can have the following hues for our Cat fwiends OwO :
> /Nya/, /NyaMi/ , /NyaMyæ/ , /NyaMa/, /NyaKo/ or /MyoWa/ , /MyoNya/ , /MyoNyæ/ , /MyoNi/, /Myo/
> 


---

## Hue Names : 3 Primary Colors (Trichromatic)

Since the Human Dialect only has 3 primary colors, Itis guaranteed that a "Hue Circle" can be formed, In this case, Astralica Human Dialect uses the Hue Circle approach, let's try to construct this circle step by step

### Step 01 : Color wheel

let's draw a color wheel, with 3 major ticks and 3 secondary ticks and for each segment between a major tick and a secondary tick, we can have 4 smaller segments.

Here we will have our primary hue as $X$, $Y$, and $Z$
The convention here is to have $X$ as 0 deg, $Y$ as 120 deg and $Z$ as 240 deg,
and the angle starts on the right hand side, clockwise, just like back in trigonometry.

![[ColorWheel_00-01.png|1024]]
### Step 02 : Primary Chunks

For now we will list the 3 major chunks for $X$, $Y$, and $Z$
so at least we know which part of the circle will be covered by which primary color.

For every tick, this will contain the general color
![[ColorWheel_01-01.png]]

### Step 03 : Mixing Magnitude

now for every tick, we can append the Mixing Level of the other primary colors.

![[ColorWheel_02-01.png]]

>[!warning]
>These Hue names by themselves represents it's hue with Sat=1 and Vbr=1


---

## Hue Names : 4 primary colors (Tetrachromatic)

Avians (Birds) can see 4 Primary colors, and so does some fishes.
the [[🪴 02a _ Ariatovi _ Avians]] Dialect uses this mechanism.
According to the pattern : from a 1D Line, a 2D triangle, the next shape is a 3D tetrahedron.

For the Hue Triangle (3-primary-colors) when a color is chosen inside the triangle, it can be projected on the vertices or the sides of the triangle and be saturated (except the middle point). In this case, we can treat the side of the triangle as the skin.

By using a similar concept :

For the Hue Tetrahedron (4-primary-colors) when a color is chosen inside the tetrahedron, it can be projected onto the vertices, the edges and the faces and be saturated (except the middle point)

**Vertices and Edges**
The vertices and Edges can use the Dichromatic system and Trichromatic Edge system.

**Triangle**
The vertices and Edges can use the Dichromatic system and Trichromatic Edge system.

Here we will be focusing on the triangle.
Let's assume that all the Hues are $X$, $Y$, $Z$, and $W$. On a triangle, a hue will be absent, in this case, take W for example.

![[ColorTet_01.png]]

on these edges, make a midpoint, these midPoints can be known as : $XY_4$ or $YX_4$, $YZ_4$ or $ZY_4$, ZX4 or $XZ_4$

for each of these Midpoints, connect each of them to the centerPoint of the triangle.
at this point we will have 3 kiteshapes, each belong to their dominant primary color.

![[ColorTet_02.png|320]]![[ColorTet_03.png|320]]

>[!example]
>if a color is found in the X-kiteshape region, then it has X as it's dominant primary color

**Region Dividing : Kit Webing**

let's focus on the X-Kite, since the same principles can be applied to the Y-Kite and the Z-Kite.

the X-Kite has 4 edges :
- X to XY4
- XY4 to TriangleCenterPoint
- TriangleCenterPoint to XZ4
- XZ4 to X

each of these edges can be cut into 4 equal segments, meaning each of these edges will have 3 tickmarks.​

​
for the edge X to XY4, all the tick marks are : $X ~,~ XY_1 ~,~ XY_2 ~,~ XY_3 ~,~ XY_4$
in this direction, you can see that the primary color Y is increasing

for the edge X to XZ4, all the tick marks are : $X ~,~ XZ_1 ~,~ XZ_2 ~,~ XZ_3 ~,~ XZ_4$
in this direction, you can see that the primary color Z is increasing

​

we can use both of these edges to say that :

from $XY_4$ to CenterPoint, $Z$ is increasing, so the tickmarks are $XY_4 ~,~ XY_4Z_1 ~,~ XY_4Z_2 ~,~ XY_4Z_3 ~,~ XY_4Z_4$ aka CenterPoint

from $XZ_4$ to CenterPoint, $Y$ is increasing, so the tickmarks are $XZ_4 ~,~ XY_1Z_4 ~,~ XY_2Z_4 ~,~ XY_3Z_4 ~,~ XY_4Z_4$ aka CenterPoint

![[ColorTet_04.png]]

with these tickmarks, we can then create a "squished Cartesian plane" inside this kite.
with this, nine more hues can be created

this principle can be applied to other kites
and with the other kites, a triangle is complete, we can also apply the same principle to other triangles, and the whole tetrahedron is done.

![[ColorTet_05.png]]

![[ColorTet_06.png]]

>[!warning] Wait ... CenterPoint ? isn't that the Neutral Color with no Saturation
>
>Keep in mind, here we are dealing with 4 primary colors. To make sure that a color is fully saturated, we need to make sure that :
>
>among the primary color channels, at least one color channel needs to be full, which is the dominant color, and one of the color channels needs to be 0.
>
For humans, the entire spectrum is the triangle, when the triangle is missing a verticex (one color channel is 0), it collapses into a line, at this point the MidPoint is the Blend of the 2 remaining colors, but still saturated.
>
For avians, the entire spectrum is the tetrahedron, when the tetrahedron is missing a vertex (one color channel is 0), it collapses into a triangle, at this point the MidPoint is the Blend of the 3 remaining colors, but it is still saturated.
>
In order for a color to be neutral, all color channels must all share the same value.

---

## Species Specifications

Now we can finally list what are the primary hues for different species :


|                                                   |               |           |           |           |           |           |           |
| ------------------------------------------------- | ------------- | --------- | --------- | --------- | --------- | --------- | --------- |
| Species & Dialect                                 | Primary Color |           | $Color_p$ | $Color_1$ | $Color_2$ | $Color_3$ | $Color_f$ |
|                                                   | English       | Astralica | Dominant  | Mix1      | Mix2      | Mix3      | MixFull   |
|                                                   |               |           |           |           |           |           |           |
| Canids<br>*dogs, foxes, wolves*<br>[[🪴 02a _ Kainuqu _ Canids]] |               |           |           |           |           |           |           |
|                                                   | Yellow        | /Yarafa/  | /Ya/      | /Yi/      | /Yæ/      | /Ya/      | /Ra/      |
|                                                   | Blue          | /Wafusa/  | /Wa/      | /Wi/      | /Wæ/      | /Wa/      | /Fu/      |
|                                                   |               |           |           |           |           |           |           |
| Felis<br>*Cats, Tigers, Lions*<br>[[🪴 02a _ Kæmaganæ _ Felis]] |               |           |           |           |           |           |           |
|                                                   | Chartreuse    | /Nyawawi/ | /Nya/     | /Ni/      | /Nyæ/     | /Nya/     | /Wa/      |
|                                                   | Indigo        | /Makonyo/ | /Ma/      | /Mi/      | /Mæ/      | /Ma/      | /Ko/      |
|                                                   |               |           |           |           |           |           |           |
| Homo-Sapien<br>*Humans*<br>[[🪴 02a _ Hiureni _ Human]]         |               |           |           |           |           |           |           |
|                                                   | Red           | /Rahaka/  | /Ra/      | /Ri/      | /Ræ/      | /Ra/      | /Ha/      |
|                                                   | Green         | /Nawari/  | /Na/      | /Ni/      | /Næ/      | /Na/      | /Wa/      |
|                                                   | Blue          | /Koqosa/  | /Ko/      | /Ki/      | /Kæ/      | /Ka/      | /Qo/      |
|                                                   |               |           |           |           |           |           |           |
| Avians<br>*Birds*<br>[[🪴 02a _ Ariatovi _ Avians]]              |               |           |           |           |           |           |           |
|                                                   | Red           | /Haraka/  | /Ha/      | /Hi/      | /Hæ/      | /Ha/      | /Ra/      |
|                                                   | Green         | /Kafaxa/  | /Ka/      | /Ki/      | /Kæ/      | /Ka/      | /Fa/      |
|                                                   | Blue          | /Gæhofu/  | /Gæ/      | /Gi/      | /Gæ/      | /Ga/      | /Ho/      |
|                                                   | Ultraviolet   | /Qiziri/  | /Qi/      | /Qi/      | /Qæ/      | /Qa/      | /Zi/      |

>[!note] is $Mix_0$ or $Color_0$ a valid move ?
>if you want to describe a hue that it has no such said primary color but with a tendency to have that primary color, you can use $Color_0$ to hint "hey, perhaps this hue may contain that primary color, but for now it is 0"
>>[!example] 
>>if I were to say the color of the sky is now /KoRo/ ($BR_0$), it means that most of the time it is /Koqosa/ ("Blue"), and for now it contains "no Red" (/Ro/), but at some point, the sky may contain some extend of red, just not now
>
>from the table above, to construct $Mix_0$, we just need to follow the pattern : Grab $Mix_1$ and replace the vowel from /i/ to /o/


>[!faq] I would love to contribute to my species ~
> If you are a furry (or a human) who wants to give color ideas
> join the Discord Server and give a suggestion OwO/

---

## Wait a minute ... That sounds familiar XD

Due to coincidence, some of the names are charracters or people from the Internet,
which can be fun and interesting :


|                            |                         |                               |
| -------------------------- | ----------------------- | ----------------------------- |
| ![[Koni (Conny).png\|200]] | ![[Kora.png\|200]]      | ![[Koro.png\|200]]            |
| /Koni/ (Human, $BG_1$)     | /Kora/ (Human, $BR_3$)  | /Koro/ (Human, $BR_0$)        |
| ![[Naka.png\|200]]         | ![[Nako.png\|200]]      | ![[NaQo.png\|200]]            |
| /Naka/ (Human, $GB_3$)     | /Nako/ (Human, $GB_0$)  | /NaQo/ (Human, $GB$ = "Cyan") |
| ![[Nyami.png]]             | ![[Nyamo.png]]          | ![[Qika (Chika).png]]         |
| /Nyami/ (Felis, $CM_1$)    | /Nyamo/ (Felis, $CM_0$) | /Qika/ (Avian, $UG_3$)        |
| ![[Qiki.png]]              | ![[Waya (wire).png]]    | ![[Kara.png]]                 |
| /Qiki/ (Avian, $UG_1$)     | /Waya/ (Canid, $BY_3$)  | /Kara/ (Avian, $GR_4$)        |
| ![[Kona.png]]              | ![[Rana.png]]           |                               |
| /Kona/ (Human, $BG_3$)     | /Rana/ (Human, $RG_3$)  |                               |

