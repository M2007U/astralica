
## 20221007

since colors can be represented in different format, each format will have different parameters, which can be cranked up and down to describe different colors.

the big space in the middle is a simple cartesian multiplication to generate CV syllables,
i.e. /k/ concat /i/ = /ki/

|         |     | /u/ | /o/ | /a/ | /æ/ | /i/ | /oæ/ | /ai/ | /æi/ | /iæ/ | full     |
| ------- | --- | --- | --- | --- | --- | --- | ---- | ---- | ---- | ---- | -------- |
|         |     | 0   | 1   | 2   | 3   | 4   | 5    | 6    | 7    | 8    |          |
| red     | /r/ |     |     |     |     |     |      |      |      |      | /haraka/ |
| green   | /n/ |     |     |     |     |     |      |      |      |      | /nawari/ |
| blue    | /k/ |     |     |     |     |     |      |      |      |      | /koqosa/ |
| alpha   | /t/ |     |     |     |     |     |      |      |      |      | /tahira/ |
| yellow  | /l/ |     |     |     |     |     |      |      |      |      | /linari/ |
| cyan    | /s/ |     |     |     |     |     |      |      |      |      | /koqosæ/ |
| magenta | /h/ |     |     |     |     |     |      |      |      |      | /harakæ/ |

---

## 20251222

the color wheel for humans is quite similiar to the current one, but here's how it is different :
before 20251222, we use "how pure a primary color is" to describe a hue.

before 20251222, for all color full names, the second syllable is used to mention that a hue is purely that primary color, no mixes
here the color name can be broken into 

$$C = C_p ~ C_e ~ C_{extra} $$

to describe how pure a primary color is , we take $C_p$ to derive $C_3, C_2, C_1, C_0$, which is the 1st slot for the hue name.

>[!example]
>red, /Rahaka/ can be torn into /Ra/ + /Ha/ + /Ka/
>/Ra/ is $C_p$
>so $R_0,R_1,R_2,R_3$ are /Ro, Ri, Ræ, Ra/
>and $R_e$ is /Ha/

but this is not enough, assume we have $Red_2$,
is it the $Red_2$ closer to $Green$ or the one closer to $Blue$ ?
so in the second slot we will need to specify which side it is, i.e. $Red_2Green$ or $Red_2Blue$

here we will use from Red to Green as an example to differentiate the both versions :

|                   | 20251222         | now              |
| ----------------- | ---------------- | ---------------- |
| Red               | $R_3R_e$         | $R$              |
| Vermillion        | $R_3G$           | $RG_1$           |
| Orange            | $R_2G$           | $RG_2$           |
| Marigold          | $R_1G$           | $RG_3$           |
| Yellow            | $R_0G$ or $G_0R$ | $RG_f$ or $GR_f$ |
| Chartreuse Yellow | $G_1R$           | $GR_3$           |
| Chartreuse        | $G_2R$           | $GR_2$           |
| Chartreuse Green  | $G_3R$           | $GR_1$           |
| Green             | $G_3G_e$         | $G$              |

>[!hint] key take away
>before 20251222, we focus on "how pure a primary color is ? and then which side ?"
>now, we focus on "what is the dominant color ? and then how much other colors take part ?"

