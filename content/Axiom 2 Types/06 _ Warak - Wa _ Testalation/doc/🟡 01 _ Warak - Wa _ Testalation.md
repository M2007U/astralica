
![[Warak.png|100]]![[empty_128.png|50]]![[c-81-w.png|25]]![[v-870-a.png|50]]![[c-83-r-EN.png|25]]![[v-870-a.png|50]]![[c-63-k.png|25]]

The symbol is derived from the shape of a normal square grid
Some categories might use this structure, but it does not mean it falls under this category

>[!note] pronunciation derivation
>Inspired by English words "Web" and "Arachnid" ("Spider")

>[!note] Evolution Tracking
>/Warak/ is a derivation of [[🟡 01 _ Kaxi - Ka _ Space]] &  [[🟡 01 _ Kosra - Koa _ NULL]]

>[!warning]
Keep in mind, it doesn't need to get stuck with squares, according to geometry, the list of available grids are triangles, squares, and hexagons. Unless we are dealing with higher dimensions.

>[!example]
Coordinates or database will be using this

---

## Deciding a name for an axis

Since we are 3 dimension creatures, the default axis are
- "Ra/Ræ"
- "Ta/Tæ"
- and "Ka/Kæ"

which you can refer to [[🟡 01 _ Kaxi - Ka _ Space]]
However, if we need to go even further, we can define a name for an axis like so :

|                                   |                              |                           |                               |                                 |                               |
| --------------------------------- | ---------------------------- | ------------------------- | ----------------------------- | ------------------------------- | ----------------------------- |
| ![[Warak.png\|50]]                | ![[KaxiAra_Fat.png\|50]]     | ![[equ_01-equal.png\|50]] | **slot : Axis Positive Name** | ![[opr_11-muldiv_thin.png\|50]] | **slot : Axis Negative Name** |
| **slot :<br>dimension<br> count** | **slot :<br>Axis<br> Index** | ^                         | ^                             | ^                               | ^                             |
/ Warak - **( slot : Dimension Count )** - ara - **( slot : Axis Index )** Kiamasæni **( slot : AxisPositiveName )** Ru **( slot : AxisNegativeName )** /

>[!example]
>let's say we decided to introduce the 4th dimension :
>declaring the 4th axis as "Fa"(Pos) and "Fæ"(Neg)
>
|                    |                          |                           |                                         |                                 |                                          |
| ------------------ | ------------------------ | ------------------------- | --------------------------------------- | ------------------------------- | ---------------------------------------- |
| ![[Warak.png\|50]] | ![[KaxiAra_Fat.png\|50]] | ![[equ_01-equal.png\|50]] | ![[c-21-f.png\|25]]![[v-870-a.png\|50]] | ![[opr_11-muldiv_thin.png\|50]] | ![[c-21-f.png\|25]]![[v-660-ae.png\|50]] |
| ![[pfr_4.png\|50]] | ![[pfr_3.png\|50]]       | ^                         | ^                                       | ^                               | ^                                        |

---

## Position In a Warak & Selecting a Single Cell

In other words, the coordinate of a cell in a Warak.
This can be easily done by using a string of ordred numbers separated by "Ru"
Let's call this string **"A coordinate String"**

|                  |                                 |                  |                                 |                  |     |                  |                                 |                  |
| ---------------- | ------------------------------- | ---------------- | ------------------------------- | ---------------- | --- | ---------------- | ------------------------------- | ---------------- |
| **slot : coord** | ![[opr_11-muldiv_thin.png\|50]] | **slot : coord** | ![[opr_11-muldiv_thin.png\|50]] | **slot : coord** | ... | **slot : coord** | ![[opr_11-muldiv_thin.png\|50]] | **slot : coord** |

**If we are only dealing with 3 dimensions only**,
we can use the following "Warak-3 notation" :

We can use the "Warak" Symbol as the origin point (where the coordinate is (0,0)),
taking the [[🟡 01 _ Kaxi - Ka _ Space]] Symbol as inspiration

to describe the "Left Right" Coordinate, we will put the number on the Left or Right of /Warak/
to describe the "Up Down" Coordinate, we will put the number on the Top or Bottom of /Warak/
to describe the "Front Back" Coordinate, we will put the number on the TopRight Corner or BottomLeft Corner of /Warak/


|     |                    |     |
| --- | ------------------ | --- |
|     | +Y                 | +Z  |
| -X  | ![[Warak.png\|50]] | +X  |
| -Z  | -Y                 |     |

---

## Selecting multiple cells

Mainly, there are 2 ways to select cells, each for a different purpose and mechanism :
- Zoiga-Mechanism : used for selecting a range of cells with specific coordinates
- Fina-Mechanism : used for selecting a group of cells with a specific shape

### [[🟡 01 _ Zoiga - Zoi _ Group]] Mechanism

The main idea is to provide 2 cells which are the "corner" of the area we want to select.
assume that the 2 corners that we have selected are :
$$(X0, Y0, Z0, ... , W0) ~~and~~ (X1, Y1, Z1, ... , W1)$$
then we can have :

|                    |                      |                                              |                     |                                            |                     |
| ------------------ | -------------------- | -------------------------------------------- | ------------------- | ------------------------------------------ | ------------------- |
|                    | ![[zoiga.png\|50]]   |                                              | ![[zoiga.png\|50]]  |                                            | ![[zoiga.png\|50]]  |
| ![[Warak.png\|50]] | ![[KaxiRae.png\|50]] | **slot : starting corner coordinate string** | ![[KaxiKo.png\|50]] | **slot : ending corner coordinate string** | ![[KaxiRa.png\|50]] |
/ Warak - ZoigaRæ - (X0)Ru(Y0)Ru(Z0)Ru...Ru(W0) - ZoigaRo - (X1)Ru(Y1)Ru(Z1)Ru...Ru(W1) - ZoigaRa / >
/ Wa - ZoiRæ - (X0)Ru(Y0)Ru(Z0)Ru...Ru(W0) - ZoiRo - (X1)Ru(Y1)Ru(Z1)Ru...Ru(W1) - ZoiRa /

Then the selected cells are those whose coordinates are in between the 2 corners.
If a selected cell has the coordinate $(Xs, Ys, Zs, ... , Ws)$
Then we can guarantee that :
$$
\begin{gather}
X_0 ~≤~ X_s ~≤~ X_1 \\
Y_0 ~≤~ Y_s ~≤~ Y_1 \\
Z_0 ~≤~ Z_s ~≤~ Z_1 \\
... \\
W_0 ~≤~ W_s ~≤~ W_1 \\
\end{gather}
$$

>[!example]
>selecting the cell : (3,5,-7) : /Wa - Zoi - Na - Ru - Li - Ru - klæLa/
>
|                    |                    |                    |
| ------------------ | ------------------ | ------------------ |
|                    | ![[pfr_5.png\|50]] |                    |
|                    | ![[Warak.png\|50]] | ![[pfr_3.png\|50]] |
| ![[pfr_7.png\|50]] |                    |                    |
>
>selecting the range of cell from (3,5,-7) to (6,2,-1)
>/Wa - ZoiRæ - Na Ru Li Ru KlæLa - ZoiRo - Læ Ru Næ Ru KlæNi - ZoiRa/
>
|                    |                      |                    |                    |                    |                     |                    |                    |                    |                     |
| ------------------ | -------------------- | ------------------ | ------------------ | ------------------ | ------------------- | ------------------ | ------------------ | ------------------ | ------------------- |
|                    | ![[zoiga.png\|50]]   |                    | ![[pfr_5.png\|50]] |                    | ![[zoiga.png\|50]]  |                    | ![[pfr_2.png\|50]] |                    | ![[zoiga.png\|50]]  |
| ![[Warak.png\|50]] | ![[KaxiRae.png\|50]] |                    | ![[Warak.png\|50]] | ![[pfr_3.png\|50]] | ![[KaxiKo.png\|50]] |                    | ![[Warak.png\|50]] | ![[pfr_6.png\|50]] | ![[KaxiRa.png\|50]] |
| ^                  | ^                    | ![[pfr_7.png\|50]] |                    |                    | ^                   | ![[pfr_1.png\|50]] |                    |                    | ^                   |

>[!tip] This feels ... familiar
>If you play Minecraft and you are an architect, chances are you have used the command "/fill" before.
>What it does is it will fill in the area  which is defined by 2 opposing corners of the area with whatever block the user defined.
>
>![[Screenshot-minecraft-fill-command.png]]

say you selected the following cells by using the Zoiga Method :

/Wa - ZoiRæ - (Coordinate String Start) - ZoiRo - (Coordinate String End) - ZoiRa/

here by convention, the origin point is the cell $(0,0,...,0)$
To shift the selection, we can have the following word structure :

|                    |                                               |                      |                                              |                     |                                            |                     |
| ------------------ | -------------------------------------------- | -------------------- | -------------------------------------------- | ------------------- | ------------------------------------------ | ------------------- |
|                                                                    | ![[zoiga.png\|50]]   |                                              | ![[zoiga.png\|50]]  |                                            | ![[zoiga.png\|50]]  |
| ![[Warak.png\|50] **slot : shifting amount coordinate string**  :  | ![[KaxiRae.png\|50]] | **slot : starting corner coordinate string** | ![[KaxiKo.png\|50]] | **slot : ending corner coordinate string** | ![[KaxiRa.png\|50]] |
To put this is a more math friendlier way,

let Starting Corner Coordinate $= (A_0,B_0,C_0, ... ,Z_0)$
let Endding Corner Coordinate $= (A_1,B_1,C_1, ... ,Z_1)$

if we have a shift of $(A_s, B_s, C_s, ..., Z_s)$

then the absolute Starting Corner would be $( A_0+A_s , B_0+B_s , C_0+C_s , ... , Z_0+Z_s )$
and the absolute Ending Corner would be $( A_1+A_s , B_1+B_s , C_1+C_s , ... , Z_1+Z_s)$

### [[🟡 01 _ Fina - Fi _ Path , 1D-Manifold]] mechanism

The main idea is to imagine a pen "walking" on the Warak, and provided a series of actions to record a cell, start record, stop record, and move the pen. 

This is clearly defined and explained in the page [[🟡 01 _ Fina - Fi _ Path , 1D-Manifold]]

To use it here, the whole word should look something like 
/Warak - (Shifting Amount) - Fina - (Fina Path String)/ or /Wa - Fi - (Fina Path String)/

|                    |                            |                   |                      |
| ------------------ | -------------------------- | ----------------- | -------------------- |
| ![[Warak.png\|50]] | **slot : shifting amount** | ![[Fina.png\|50]] | **slot : fina path** |
|                    |                            |                   |                      |

---

## Pivot Point Shifting

>[!warning] Pivot Point Shifting Clear up
> In the Zoiga Method,
the Starting Corner Coordinate and the Endding Corner Coordinate is relative to the Pivot Point
the Shifting Coordinate is the pivot point position relative to the WarakSpace Origin Point
>
In the Fina Method,
The Starting Point and the Endding Point are not the Pivot Point
Instead, the Pivot Point is set among the Fina-String (Refer to [[🟡 01 _ Fina - Fi _ Path , 1D-Manifold]] )


