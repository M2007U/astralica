sometimes, a flow of events is not a perfect straight line
sometimes they branch of, sometimes it repeats.

here there are 4 mechanisms to control the flow of events :
- if
- switch
- while
- for



---



## Sæyanæ - Kikuo - KaxiRæoa > Sækio - RæRoRa : If

basically it branches the event flow if a certain boolean expression is true.
in other words, "If (...){...} else if (...){...} else {...}"
here we use [[🟡 01 _ Kikuo - Kio _ Tree]]

|                                                  |                      |                                      |                                                  |                     |                                      |                                                  |                     |
| ------------------------------------------------ | -------------------- | ------------------------------------ | ------------------------------------------------ | ------------------- | ------------------------------------ | ------------------------------------------------ | ------------------- |
| ![[Saeyanae.png\|50]]<br>![[Kio_0-Tree.png\|50]] | ![[KaxiRae.png\|50]] | ![[AstralicaSlots_Number-1.png\|50]] | ![[Saeyanae.png\|50]]<br>![[Kio_0-Tree.png\|50]] | ![[KaxiKo.png\|50]] | ![[AstralicaSlots_Number-2.png\|50]] | ![[Saeyanae.png\|50]]<br>![[Kio_0-Tree.png\|50]] | ![[KaxiRa.png\|50]] |
/SækioRæ - (slot1) - SækioRo - (slot2) - SækioRa/

where **slot 1** is the boolean expression
and **slot 2** is where the other statements will go
in other words : "if the things in slot 1 happens, then the things in slot 2 will happen"

if we have multiple if statements in a row,
we can repeat as many /SækioRæ ... SækioRo .../ as we need
here's a more concrete way to see it :

|                                                  |                      |                                        |                                                 |
| ------------------------------------------------ | -------------------- | -------------------------------------- | ----------------------------------------------- |
| ![[Saeyanae.png\|50]]<br>![[Kio_0-Tree.png\|50]] | ![[KaxiRae.png\|50]] | /Sæyanæ - Kikuo - KaxiRæ/<br>/SækioRæ/ | to provide a boolean expression, or a condition |
|                                                  |                      |                                        |                                                 |
| ![[Saeyanae.png\|50]]<br>![[Kio_0-Tree.png\|50]] | ![[KaxiKo.png\|50]]  | /Sæyanæ - Kikuo - KaxiRo/<br>/SækioRo/ | to provide a result, a list of predicated       |
|                                                  |                      |                                        |                                                 |
| ![[Saeyanae.png\|50]]<br>![[Kio_0-Tree.png\|50]] | ![[KaxiRa.png\|50]]  | /Sæyanæ - Kikuo - KaxiRa/<br>/SækioRa/ | finish the if-else statement                    |



---


## Sæyanæ - Kikuo - NoiæaLoi > Sækio - NoiæaLoi : switch

this is a compression or shorthand for an if-else statement refering to the same parameter but with slightly different possible conditions

here's an example if we use classic if-else statements :

```
if (pedestrianLight.color === "red")
{
	you.standstill()
}
else if (pedestrianLight.color === "orange")
{
	you.prepareStop()
}
else if (pedestrainLight.color === "green")
{
	you.cross(street)
}
else
{
	you.check(onlineDocumentation)
}
```

but here you can see all boolean expression are based on `pedestrainLight.color`, which is quite repetitive, here we can use switch to crompress the above to the following :

```
switch( pedestrianLight.color )
{
	case "red"    then you.standStill()               ; break ;
	case "orange" then you.prepareStop()              ; break ;
	case "green"  then you.cross(street)              ; break ;
	default       then you.check(onlineDocumentation) ; break ;
}
```

now we can translate it into Astralica :

```
SækioNo pedestrianLight.color
	SækioNi "red"    SækioNæ you.standStill()
	SækioNi "orange" SækioNæ you.prepareStop()
	SækioNi "green"  SækioNæ you.cross(street)
	SækioNa you.check(onlineDocumentation)
SækioLo
```

here's are all the labels and their functionalities

|                                                                        |                                    |                                                       |
| ---------------------------------------------------------------------- | ---------------------------------- | ----------------------------------------------------- |
| ![[Saeyanae.png\|25]]<br>![[Kio_0-Tree.png\|25]]<br>![[pfr_0.png\|25]] | /Sæyanæ - Kikuo - No/<br>/SækioNo/ | start switch snippet and provide parameter or subject |
| ![[Saeyanae.png\|25]]<br>![[Kio_0-Tree.png\|25]]<br>![[pfr_1.png\|25]] | /Sæyanæ - Kikuo - Ni/<br>/SækioNi/ | provide possible value                                |
| ![[Saeyanae.png\|25]]<br>![[Kio_0-Tree.png\|25]]<br>![[pfr_2.png\|25]] | /Sæyanæ - Kikuo - Næ/<br>/SækioNæ/ | provide statement / predicate                         |
| ![[Saeyanae.png\|25]]<br>![[Kio_0-Tree.png\|25]]<br>![[pfr_3.png\|25]] | /Sæyanæ - Kikuo - Na/<br>/SækioNa/ | provide default case predicate                        |
| ![[Saeyanae.png\|25]]<br>![[Kio_0-Tree.png\|25]]<br>![[pfr_4.png\|25]] | /Sæyanæ - Kikuo - Lo/<br>/SækioLo/ | end switch snippet                                    |



---



## Sæyanæ - Jusaihak - KaxiRæoa > Sæju - Ræoa : while

in most programming language, a while loop is use to repetitively carry out a list of statements or predicates when a given boolean expression is true

```
while( pedestrainLight.color === "red" )
{
	car.stop()
}
```

and now we can convert this into Astralica
here we use [[🟡 01 _ Jusaihak - Ju _ Cycle]]

```
SæjuRæ
	pedestrianLight.color === "red"
SæjuRo
	Car.stop()
SæjuRa
```

|                                                |                      |                                          |                                                                      |
| :--------------------------------------------: | -------------------- | ---------------------------------------- | -------------------------------------------------------------------- |
| ![[Saeyanae.png\|50]]<br>![[Jusaihak.png\|25]] | ![[KaxiRae.png\|50]] | /Sæyanæ - Jusaihak - KaxiRæ/<br>/SæjuRæ/ | start While loop and provide a boolean expression, or a condition    |
|                                                |                      |                                          |                                                                      |
| ![[Saeyanae.png\|50]]<br>![[Jusaihak.png\|25]] | ![[KaxiKo.png\|50]]  | /Sæyanæ - Jusaihak - KaxiRo/<br>/SæjuRo/ | to end Boolean expression and provide a list of result or predicates |
|                                                |                      |                                          |                                                                      |
| ![[Saeyanae.png\|50]]<br>![[Jusaihak.png\|25]] | ![[KaxiRa.png\|50]]  | /Sæyanæ - Jusaihak - KaxiRa/<br>/SæjuRa/ | finish the while loop                                                |



---



## Sæyanæ - Jusaihak - Noiæ > Sæju - Noiæ : for

sometimes we want to repeat a list of steps for a certain number of times
of course it can be done by using while loops

```
let counter = 0
while(counter < 5)
{
	doWhatever();
	counter = counter + 1
}
```

this can be translated into a forloop

```
for(let i = 0 ; i < 5 ; i++)
{
	doWhatever();
}
```

here we can translate it into Astralica

```
SæjuNo
	5
SæjuNi
	doWhatever()
SæjuNæ
```

|                                                                      |                                      |                                           |
| :------------------------------------------------------------------: | ------------------------------------ | ----------------------------------------- |
| ![[Saeyanae.png\|25]]<br>![[Jusaihak.png\|12]]<br>![[pfr_0.png\|25]] | /Sæyanæ - Jusaihak - No/<br>/SæjuNo/ | start forloop and provide repeat quantity |
| ![[Saeyanae.png\|25]]<br>![[Jusaihak.png\|12]]<br>![[pfr_1.png\|25]] | /Sæyanæ - Jusaihak - Ni/<br>/SæjuNi/ | provide predicates                        |
| ![[Saeyanae.png\|25]]<br>![[Jusaihak.png\|12]]<br>![[pfr_2.png\|25]] | /Sæyanæ - Jusaihak - Næ/<br>/SæjuNæ/ | end forloop                               |
