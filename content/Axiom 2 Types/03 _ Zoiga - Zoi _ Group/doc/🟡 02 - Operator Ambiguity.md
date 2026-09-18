If the sentence is simple enough such that we do not end up with ambiguity, then these are enough, otherwise, extra parts are required.

sometimes to avoid ambiguity, different dialect uses different solutions


## [[🐞 Forutaxi]] Dialect : InFix

these folks evolves naturally, and therefore pickup what most natural languages has : infix
some operator will have a "left side", "separator" and "right side"
here we have the side by side comparison.


|        |     |                          |     |                          |     |                         |
| ------ | --- | ------------------------ | --- | ------------------------ | --- | ----------------------- |
|        |     | ![[zoiga - not.png\|50]] |     | ![[zoiga - not.png\|50]] |     |                         |
| not A  |     | ![[KaxiRae.png\|50]]     | A   | ![[KaxiRa.png\|50]]      |     |                         |
|        |     |                          |     |                          |     |                         |
|        |     | ![[zoiga - or.png\|50]]  |     | ![[zoiga - or.png\|50]]  |     | ![[zoiga - or.png\|50]] |
| A or B |     | ![[KaxiRae.png\|50]]     | A   | ![[KaxiKo.png\|50]]      | B   | ![[KaxiRa.png\|50]]     |
to pronounce it, we have /(slot 1) - (slot 2)/ where
**slot 1 : which operator it is ?** : and ? or ? xor ? but ?
**slot 2 : left side or right side ?** : /ræ/ or /ra/, inspired by [[🟡 01 _ Kaxi - Ka _ Space]]

sometime we have a long chain of the same operator, for example :
"A or B or C or D"
in this case we can have :

|                         |     |                         |     |                         |     |                         |     |                         |
| ----------------------- | --- | ----------------------- | --- | ----------------------- | --- | ----------------------- | --- | ----------------------- |
| ![[zoiga - or.png\|50]] |     | ![[zoiga - or.png\|50]] |     | ![[zoiga - or.png\|50]] |     | ![[zoiga - or.png\|50]] |     | ![[zoiga - or.png\|50]] |
| ![[KaxiRae.png\|50]]    | A   | ![[KaxiKo.png\|50]]     | B   | ![[KaxiKo.png\|50]]     | C   | ![[KaxiKo.png\|50]]     | D   | ![[KaxiRa.png\|50]]     |

but why with these complex ness ? to deal with weird and complex boolean expressions. let's say we are making a breakfast menu and we wrote something like :

"bread xor kwasohnt and tea"
do we mean :
"bread xor kwasohnt, ... and tea" or
"bread xor, ... kwasohnt and tea" ?

in this case we can use the mechanism to state both situations :

|                          |                          |                          |                          |                             |                          |                          |                        |                          |
| ------------------------ | ------------------------ | ------------------------ | ------------------------ | --------------------------- | ------------------------ | ------------------------ | ---------------------- | ------------------------ |
| ![[zoiga - and.png\|50]] | ![[zoiga - xor.png\|50]] |                          | ![[zoiga - xor.png\|50]] |                             | ![[zoiga - xor.png\|50]] | ![[zoiga - and.png\|50]] |                        | ![[zoiga - and.png\|50]] |
| ![[KaxiRae.png\|50]]     | ![[KaxiRae.png\|50]]     | ![[Emoji_Bread.png\|50]] | ![[KaxiKo.png\|50]]      | ![[Emoji_kwasohnt.png\|50]] | ![[KaxiRa.png\|50]]      | ![[KaxiKo.png\|50]]      | ![[Emoji_Tea.png\|50]] | ![[KaxiRa.png\|50]]      |
(🍞xor🥐) and☕

|                          |                          |                          |                          |                             |                          |                        |                          |                          |
| ------------------------ | ------------------------ | ------------------------ | ------------------------ | --------------------------- | ------------------------ | ---------------------- | ------------------------ | ------------------------ |
| ![[zoiga - xor.png\|50]] |                          | ![[zoiga - xor.png\|50]] | ![[zoiga - and.png\|50]] |                             | ![[zoiga - and.png\|50]] |                        | ![[zoiga - and.png\|50]] | ![[zoiga - xor.png\|50]] |
| ![[KaxiRae.png\|50]]     | ![[Emoji_Bread.png\|50]] | ![[KaxiKo.png\|50]]      | ![[KaxiRae.png\|50]]     | ![[Emoji_kwasohnt.png\|50]] | ![[KaxiKo.png\|50]]      | ![[Emoji_Tea.png\|50]] | ![[KaxiRa.png\|50]]      | ![[KaxiRa.png\|50]]      |
🍞 xor (🥐and☕)

---

## [[🐞 Tækizamæ]]  Dialect : Reverse Polish Notation

these folks has computer based memories, this includes : stacks, which is perfect for reverse polish notation

instead of "A and B", we have "A B and"
the main idea of how to understand the boolean structure of a reverse polish notation boolean expression is : 

1. by starting from the left
2. you go right one token at a time
3. whenever you get a /Zoiga/ operator, look on the 2nd left token and 1st left token of the /Zoiga/ operator
4. the 2nd left token from the /Zoiga/ operator is the 1st operand
5. the 1st left token from the /Zoiga/ operator is the 2nd operand
6. replace the 1st operand, 2nd operand and the /Zoiga/ operator with the result
7. continue doing the rest of the string the same way

>[!example]
>assume we have the following expression :
>`A not B C xor D E and F and and or G H or xor`
>
>here we can use ` | ` to keep track of the progress
>
>then we can calculate the expression as :
>` | A not B C xor D E and F and and or G H or xor `
>` A | not B C xor D E and F and and or G H or xor `
>` A not | B C xor D E and F and and or G H or xor `
>let `A not = T1`
>` T1 | B C xor D E and F and and or G H or xor `
>` T1 B | C xor D E and F and and or G H or xor `
>` T1 B C | xor D E and F and and or G H or xor `
>` T1 B C xor | D E and F and and or G H or xor `
>let `B C xor = T2`
>` T1 T2 | D E and F and and or G H or xor `
>` T1 T2 D | E and F and and or G H or xor `
>` T1 T2 D E | and F and and or G H or xor `
>` T1 T2 D E and | F and and or G H or xor `
>let `D E and = T3`
>` T1 T2 T3 | F and and or G H or xor `
>` T1 T2 T3 F | and and or G H or xor `
>` T1 T2 T3 F and | and or G H or xor `
>let `T3 F and = T4`
>` T1 T2 T4 | and or G H or xor `
>` T1 T2 T4 and | or G H or xor `
>let `T2 T4 and = T5`
>` T1 T5 | or G H or xor `
>` T1 T5 or | G H or xor `
>let `T1 T5 or = T6`
>` T6 | G H or xor `
>` T6 G | H or xor `
>` T6 G H | or xor `
>` T6 G H or | xor `
>let `G H or = T7`
>` T6 T7 | xor `
>` T6 T7 xor | `
>let `T6 T7 xor = R`
>`R`
>
>now with the entire thing with the help of parenthesis
>`A not B C xor D E and F and and or G H or xor`
>`(A not) B C xor D E and F and and or G H or xor`
>`(A not) (B C xor) D E and F and and or G H or xor`
>`(A not) (B C xor) (D E and) F and and or G H or xor`
>`(A not) (B C xor) ( (D E and) F and ) and or G H or xor`
>`(A not) ( (B C xor) ( (D E and) F and ) and ) or G H or xor`
>`( (A not) ( (B C xor) ( (D E and) F and ) and ) or ) G H or xor`
>`( (A not) ( (B C xor) ( (D E and) F and ) and ) or ) ( G H or ) xor`

so with the "🍞 xor 🥐 and☕" example, we can have the following :
🍞 🥐 xor ☕ and
🥐 ☕ and 🍞 xor
