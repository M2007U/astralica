
![[Taxi.png|100]]![[empty_128.png|50]]![[c-54-t.png|25]]![[v-870-a.png|50]]![[c-41-x.png|25]]![[v-160-i.png|50]]

The symbol is derived from the shape of an hourglass.
And obvious enough this symbol represents "time".

>[!note] Pronunciation Inspiration
>from "time" from English, "shi" from Chinese,
> by concatinating the underlined part, we have /Taxø/,
> "Japanize beaming" it, we can have /Taxi/


---

## Time Moment & Duration

time telling words can be constructed by using the structure below :

|               |                                      |                                            |                                 |
| ------------- | ------------------------------------ | ------------------------------------------ | ------------------------------- |
| ![[Taxi.png\|50]] | **Slot :<br>Moment /<br>Duration ?** | **Slot : <br> Predefined /<br>Standard ?** | **Slot :<br>Time Segments ...** |

---

## Moment or Duration ?

when we look at "03:45:16",
do we mean "3 hours, 45 minutes and 16 seconds"
or "3 in the morning, past 45 minutes and 16 seconds ?". 

In this case we need to specify if we are referring to
**a moment (a position of time) or a quantity of time (duration).**


|                                              |     |                                           |
| -------------------------------------------- | --- | ----------------------------------------- |
| ![[Taxi-thin.png\|50]]![[Kaxi-thin.png\|50]] |     | ![[Taxi-thin.png\|50]]![[Klari.png\|50]]  |
| A position<br>in time<br>a moment            |     | A quantification<br>of time<br>a duration |
| /Ta-Ka/                                      |     | /Ta-Kla/                                  |





## Predefined or Standard ?

There are 2 types of time units :

| choices    | ok what it means ?                                                                                         |
| ---------- | ---------------------------------------------------------------------------------------------------------- |
| Predefined | those that are only usable at a certain location and may vary from planet to planet                        |
| Standard   | those that are not easy to use but same accross the universe, used for scientific researches or travelling |

Based on the situation,
we can choose wheter we want to time keeping with predefined context or go full-blast accurate.

if we go for STANDARD units, we can ignore this slot.
if we go for PREDEFINED units, we need to specify the location, and thus declaring the allowed set of units

To specify the current planet or predefinations, this segment will be :

|                                                           |                           |
| --------------------------------------------------------- | ------------------------- |
| ![[Saeyanae.png\|50]]<br>![[Respond.png\|50]]             | ![[Kosra - thin.png\|50]] |
| ![[Kaxi.png\|50]]<br>![[AstralicaSlots_Number-1.png\|50]] |                           |

where
slot 1 is the name of the location,

|                                               |                           |
| --------------------------------------------- | ------------------------- |
| ![[Saeyanae.png\|50]]<br>![[Respond.png\|50]] | ![[Kosra - thin.png\|50]] |

means "provide information"

![[Kaxi.png|50]]
to represent "location specification"

>[!note] OK, just normal stuff~ no space travel or anything wonky
>in this case, the current location can be /KaxiKo/,
> so the current location slot can be /Ko/, then the location segment will be /SvækKaKo/.
> and the slot for the name of the location can be omited

the name of the location, or if the location has a predefined symbol, which also fits.
this is also helpful when specifying time when we are dealing with different time zones

---

## Time Segments

Just like in normal time telling,
a "clock" can be divided into different parts:
year, month, day, hour, minutes, seconds etc.

Here we have a slightly different mechanism: Time Segment accumulation
Having a list of time segments, such that each time segment contains a specific value.
This also means that a Taxi word can have some of the time segments omitted or appended.

In this case, the time segment will act differently based on if we has choosen to go with PREDEFINED context or went with STANDARD time telling

and here are some of the time units :

| Type         | symbol                        | unit        | pron 2023              | pron 2026          | symbol derivation                        |
| ------------ | ----------------------------- | ----------- | ---------------------- | ------------------ | ---------------------------------------- |
| Predefined   | ![[Circle2.png\|50]]          | year        | /Ta - Kla - æRa/       | /Ta - Kla - æRi/   | a planet's full single orbit             |
|              | ![[Circle0.png\|50]]          | day         | /Ta - Kla - æRæ/       | /Ta - Kla - æRu/   | a planet's full single rotation          |
|              | ![[TaxiLa.png\|50]]           | minute      | /Ta - Kla - Ri/        | /Ta - Kla - æRuRu/ | a half of an hourglass, a half of /Taxi/ |
| Standardized | ![[03 - KoNa - Atom.png\|50]] | Kona second | /Ta - Kla - Kona - No/ |                    | will explain below OwO>                  |
|              | ![[nikro_01.png\|50]]         | Kona minute | /Ta - Kla - Kona - Ni/ |                    | 64 Kona seconds                          |
|              | ![[nikro_02.png\|50]]         | Kona hour   | /Ta - Kla - Kona - Næ/ |                    | 64 Kona minutes                          |
|              | ![[nikro_03.png\|50]]         | Kona day    | /Ta - Kla - Kona - Na/ |                    | 64 Kona hours                            |

before moving on, let's derive the standard unit "Kona Second" /Ta - Kla - Kona - No/
Here we will use something universal as our standard reffernce :

According to Wikipedia,
The frequency of the Electron Spin Flip for a Hydrogen Atom in its ground state is approximately :

>[!abstract] from Wikipedia : 
>$14~2040~5751.768~Hz$

this means that each oscillation takes approximately

>[!abstract] multiplication
> $1 s \div 14~2040~5751.768 = 7.0402~4183~7624~8142 ...~\times~ ~10^{-10} s$

a KoNa second is the duration for 2^32 oscillations, which is approximately

>[!abstract] 1 Kona second is :
>$2^{32} ~\times~ 7.0402~4183~7624~8142~...~ \times ~ 10^{-10}~s = 3.~0237~6084~4852~9519~...~s$

with this conversion, we can have a feel of how long is each Kona Time Units :

| Kona   | Human days | Human hours | Human minutes | Human seconds          |
| ------ | ---------- | ----------- | ------------- | ---------------------- |
| Second |            |             |               | 3. 0237 6084 4852 9519 |
| Minute |            |             | 3             | 13.5206940705889216    |
| Hour   |            | 3           | 26            | 25.3244205176909824    |
| Day    | 9          | 4           | 11            | 0.7629131322228736     |

>[!warning]
>the Time Segment may look the same for both Predefined Units and Standard Units, but they behave differently.
>

for both Predefined units and Standard units, a Time Segment is :

|                  |
| ---------------- |
| **Upper Slot**   |
| **Middle Slot ** |
| **Lower Slot**   |
the Middle Slot will be the Units, **BUT**

| if the Middle Slot is a | then the Upper Slot will be              | and the Lower Slot will be                  |
| ----------------------- | ---------------------------------------- | ------------------------------------------- |
| Predefined Unit         | the number of a Whole amount of the unit | the number of PREDEFINED PIECES of the unit |
| Standard Unit           | the Nominator of a fraction              | the Denominator of a fraction               |

for Predefined Units, we have the following predefined agreement :

| Whole Unit | Predefined Fragmented Pieces |
| ---------- | ---------------------------- |
| year       | month                        |
| day        | hour                         |
| minute     | second                       |

---


## Pronunciation

the pronunciation order for a time word is :
*/Ta/ - (/Ka/ or /Kla/) - (a list of time segments)*

where a time segment pronunciation order is :
*(Unit) - (Upper Slot) - Ru - (Lower Slot)*

---

## now all together


>[!example]
>1 year 2 months 3 days 4 hours 5 minutes 6 seconds, on earth
>

|                                                                    |                                               |                                                 |                                                                  |                                                                  |                                                                 |
| ------------------------------------------------------------------ | --------------------------------------------- | ----------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------- | --------------------------------------------------------------- |
|                                                                    | ![[Saeyanae.png\|50]]<br>![[Respond.png\|50]] | ![[Kosra - thin.png\|50]]                       |                                                                  |                                                                  |                                                                 |
| ![[empty_128.png\|25]]<br>![[Taxi-thin.png\|50]]![[Klari.png\|50]] |                                               | ![[empty_128.png\|50]]<br>![[Kaxi.png\|50]]<br> | ![[stk_1.png\|50]]<br>![[Circle2.png\|50]]<br>![[stk_2.png\|50]] | ![[stk_3.png\|50]]<br>![[Circle0.png\|50]]<br>![[stk_4.png\|50]] | ![[stk_5.png\|50]]<br>![[TaxiLa.png\|50]]<br>![[stk_6.png\|50]] |
|                                                                    | ![[v-440-e.png\|50]]                          | ![[c-83-r-EN.png\|25]]![[c-21-f.png\|25]]       |                                                                  |                                                                  |                                                                 |

/Ta - Kla - æRi - NiRuNæ - æRu - NaRuLo - æRuRu - LiRuLæ/

>[!example]
2/3 Kona Seconds, 5/7 Kona Minutes, 11/13 Kona Hours, 19/17 Kona Days

|                                                                    |                                                                           |                                                                   |                                                                   |                                                                                                       |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------- | ----------------------------------------------------------------- | ----------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| ![[empty_128.png\|25]]<br>![[Taxi-thin.png\|50]]![[Klari.png\|50]] | ![[stk_2.png\|50]]<br>![[03 - KoNa - Atom.png\|50]]<br>![[stk_3.png\|50]] | ![[stk_5.png\|50]]<br>![[nikro_01.png\|50]]<br>![[stk_7.png\|50]] | ![[stk_B.png\|50]]<br>![[nikro_02.png\|50]]<br>![[stk_D.png\|50]] | ![[stk_1.png\|50]]![[stk_3.png\|50]]<br>![[nikro_03.png\|50]]<br>![[stk_1.png\|50]]![[stk_1.png\|50]] |

/Ta - Kla - KonaNo - NæRuNa - KonaNi - LiRuLa - KonaNæ - DaRuTi - KonaNa - NiNaRuNiNi/

## Preposition of Time

"Before", "Now", "Future"

these provides when things are happening (or happened)
in Astralica, since these words has a "taste" of direction,
the marker is used on the Kaxi symbol

|                                            |           |                |
| ------------------------------------------ | --------- | -------------- |
| ![[Taxi-thin.png\|50]]![[KaxiKae.png\|50]] | /Ta-Kakæ/ | before / Past  |
| ![[Taxi-thin.png\|50]]![[KaxiKo.png\|50]]  | /Ta-Kako/ | now / Present  |
| ![[Taxi-thin.png\|50]]![[KaxiKa.png\|50]]  | /Ta-Kaka/ | after / Future |


>[!hint]
>you can also attach time segments to show how much time in that direction












