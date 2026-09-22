**Original Sentence**
*"Helping him painting the big blue wall of his house white this noon makes him happy"*

Here we can break it down for the first layer :
```
( Helping Him )
Causes
( painting the big blue wall of his house white this noon )
( Him happy )
```

Here some of the sentences or clauses has missing subjects,
let's complete the clauses by giving it subjects
```
( Me Help Him )
Causes
( Me paint Wall ) //here let's take care the main struture first
( He Happy )
```

Now we can tackle the possessive chain
```
( Me Help Him )
Causes
( Me paint He > House > Wall )
( He Happy )
```

Now we can attach information about "Paint"
which is "painting something WHITE, and during THIS NOON"
```
( Me Help Him )
Causes
( Me paint info{ color:white , time:thisNoon } He > House > Wall )
( He Happy )
```

we can also start to describe the wall "was originally blue" and "big"
```
( Me Help Him )
Causes
( Me paint info{ color:white , time:thisNoon } He > House > Wall info{ color:white , size:big } )
( He Happy )
```

now here we can see the Subject and Medium and Object is an entire NounClause,
```
NounClauseStart Me Help Him NounClauseEnd
Causes
NounClauseStart Me paint InfoStart color:white time:thisNoon InfoEnd He > House > Wall infoStart color:white size:big InfoEnd NounClauseEnd
NounClauseStart He Happy NounClauseEnd
```

now we can use indentation to show the structure of the sentence :
```
NounClauseStart
	Me
	Help
	Him
NounClauseEnd
Causes
NounClauseStart
	Me
	Paint
	InfoStart
		color : white
		time : this Noon
	InfoEnd
	He
	Possessive-Dettach
	House
	Possessive-Attach
	Wall
	InfoStart
		color : blue
		size : crank-up
	InfoEnd
NounClauseEnd
NounClauseStart
	He
	Happy
NounClauseEnd
```

and now we can finally translate it to
```
Tæræf
	Koix-ino
	Ji-Hælp
	Koix-oni-to
Tæraf
Krut-Sæni
Tæræf
	Koix-ino
	Ji-Krut-Pæint
	Svæk
		LiTaraka RahaNoTa
		Takakæ æru-NiRuNæ
	Svok
	Koix-oni-to
	Tæya
	Ji-Haus
	Tæyu
	Ji-Wol
	Svæk
		LiTaraka Koqosa
		KaRaæTaæ-KlaNæ Skla
	Svok
Tæraf
Tæræf
	Koix-oni-to
	Ji-Hæpi
Tæraf
```

here if we want to add more confirmation that we are dealing with the same "him" through out the sentence, we can use the /Tædæf/ mechanism
```
Tæræf
	Koix-ino
	Ji-Hælp
	Koix-oni-to Tædæf ALPHA //we mark it here
Tæraf
Krut-Sæni
Tæræf
	Koix-ino
	Ji-Krut-Pæint
	Svæk
		LiTaraka RahaNoTa
		Takakæ æru-NiRuNæ
	Svok
	ALPHA // here we are refer to the same person
	Tæya
	Ji-Haus
	Tæyu
	Ji-Wol
	Svæk
		LiTaraka Koqosa
		KaRaæTaæ-KlaNæ Skla
	Svok
Tæraf
Tæræf
	ALPHA //the same as here
	Ji-Hæpi
Tæraf
```

