
Since Astralica is Base16, hexadecimal can be converted into binary easily.
Here Astralica uses a "stem-based" pattern, each binary glyph has a "stem", with different branches, it represents the quantity of the powers

![[bin_Z_con.png\|50]]

and here are the numbers from 0x0 to 0x10


|     | +0             | +1             | +2             | +3             | +4             |
| --- | -------------- | -------------- | -------------- | -------------- | -------------- |
| 0   | ![[bin_0.png\|50]] | ![[bin_1.png\|50]] | ![[bin_2.png\|50]] | ![[bin_3.png\|50]] | null           |
| 4   | ![[bin_4.png\|50]] | ![[bin_5.png\|50]] | ![[bin_6.png\|50]] | ![[bin_7.png\|50]] | null           |
| 8   | ![[bin_8.png\|50]] | ![[bin_9.png\|50]] | ![[bin_A.png\|50]] | ![[bin_B.png\|50]] | null           |
| 12  | ![[bin_C.png\|50]] | ![[bin_D.png\|50]] | ![[bin_E.png\|50]] | ![[bin_F.png\|50]] | ![[bin_P.png\|50]] |

>[!note] What is Binary ?
>Binary is a Positional Counting System such that it only has 2 glyphs/digits : 0 and 1, in other words, when a digit reaches 2, it needs to be carried to the next digit.
> One feature of Binary is that 4 bits can be grouped to form a "nibble", and a nibble can hold 16 values, which is perfect for Astralica

