
## Fundamental Frequency

In normal music theory, in human culture, the note A is

$$440 Hz$$

and humans use this as a reference point to create other pitches.
Astralica does the similar thing :
pick a frequency and let it be the default fundamental frequency.

Keep in mind that the fundamental frequency can be changed when specific,
otherwise the default value is :

$$
\begin{align*}
& 256~oscilations ~~\div~~ 1~Kona~Second \\
&= 256~oscilations ~~\div~~ 3.~0237~6084~4852~9519 ~Kona~Second \\
&= 84.~6627~8027~1053~32 ~Hz
\end{align*}
$$

In Astralica, we call this /Hækios-Taxi-Tæga-Ni/ > /HætaTæni/
which can be translated to "Sound-pitch-Name-1st"

In human music theory,
82.41Hz is the note E and 87.31 Hz is the note F and the fundamental frequency /Hætani/ which is 84.66278027105332 Hz falls in between that range (closer to note E)

|                             |                        |                    |     |                           |     |                                                        |                             |                           |
| --------------------------- | ---------------------- | ------------------ | --- | ------------------------- | --- | ------------------------------------------------------ | --------------------------- | ------------------------- |
| ![[Haekios - thin.png\|50]] | ![[Taxi-thin.png\|50]] | ![[Taega.png\|50]] |     | ![[equ_01-equal.png\|50]] |     | ![[pfr_1.png\|50]]![[pfr_0.png\|50]]![[pfr_0.png\|50]] | ![[opr_11-muldiv_thin.png]] | ![[Klari_Square.png\|50]] |
| ^                           | ^                      | ![[pfr_1.png\|50]] |     | ^                         |     | ^                                                      | ^                           | ![[Taxi.png\|50]]         |
/Hætatæni Kiamasæni Ninono Klaruta/
*"Fundamental Frequency is 0x100 Hz"*

---



## Pitch Interval

|                             |                        |                           |                    |
| --------------------------- | ---------------------- | ------------------------- | ------------------ |
| ![[Haekios - thin.png\|50]] | ![[Taxi-thin.png\|50]] | ![[Kaxi.png\|50]]         | ![[Taega.png\|50]] |
| ^                           | ^                      | ![[Klari_Square.png\|50]] | **(Slot:Factor)**  |
/HækiosTaxi - KaxiKlari - Tæga **(Slot:Factor)**/

>[!tip]
>the part /HækiosTaxi - KaKla/ can be interpreted as "the Logarithmic Distance for HækiosFrequency"

given 2 pitches $A$ and $B$
and assume :
$$
\begin{align*}
B = f A
\end{align*}
$$
this means that based on different $f$, these 2 pitches will have different relationships,
and we can use logarithmic distance

| f   | English     | Astralica         |
| --- | ----------- | ----------------- |
| 2   | Octave      | /Hæta-Kakla-Tænæ/ |
| 3   | Perfect 5th | /Hæta-Kakla-Tæna/ |
| 5   | Major 3rd   | /Hæta-Kakla-Tæli/ |
| 7   | (null)      | /Hæta-Kakla-Tæla/ |
| 11  | (null)      | /Hæta-Kakla-Tæda/ |

>[!note] back at mah days
>before 20260917, an octave is called /Hækios - Taxi - KosraNi - Kiamasæni - Kaxi - Klari/ > /Hæta-Makla/


---

## Pitch Selection

here is the PROPER WAY to say/write it :

|                             |                        |                           |                    |                                                                                 |                           |
| --------------------------- | ---------------------- | ------------------------- | ------------------ | ------------------------------------------------------------------------------- | ------------------------- |
| ![[Haekios - thin.png\|50]] | ![[Taxi-thin.png\|50]] | ![[Kaxi.png\|50]]         | ![[Taega.png\|50]] | ![[c-63-k.png\|25]]![[v-160-i.png\|50]]![[v-660-ae.png\|50]]![[c-21-f.png\|25]] | **(slot:NoteIndex)**      |
| ^                           | ^                      | ![[Klari_Square.png\|50]] | ![[pfr_2.png\|50]] | ^                                                                               | **(slot:OctaveDivision)** |
/Hæta-Kakla-Tænæ-kiæf-(slot:NoteIndex)-ru-(slot:OctaveDivision)/
but if this is too long to say we can crop it into
/Hækiæf - (slot:NoteIndex) Ru (slot:OctaveDIvision)/

in normal Music Theory, Octave division is 12
in Astralica, Octave division is 16


---

## Astralica Traditional Scale

by borrowing the 12 EDO Major scale from Humans
Astralica also has 2 sets of 7 notes (plus 1 more root note, an octave higher)

Standard Astralica 16 EDO Major Scale
```
0---1---2---3---4---5---6---7---8---9---A---B---C---D---E---F---X
^           ^       ^       ^       ^           ^           ^   ^
```

Alternative Astralica 16 EDO Major Scale
```
0---1---2---3---4---5---6---7---8---9---A---B---C---D---E---F---X
^           ^       ^   ^           ^           ^       ^       ^
```

