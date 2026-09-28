
![[Kio_0-Tree.png|100]]![[empty_128.png|50]]![[c-63-k.png|25]]![[v-160-i.png|50]]![[c-63-k.png|25]]![[v-121-u.png|50]]![[v-321-o.png|50]]

The symbol is derived from the shape of a Tree.

Some categories might use this structure, but it does not mean it falls under this category

Keep in mind, this is not the "Plant" Tree, instead it is the structure for a node graph such that every node only has exactly one way to travel to another node via connected edges

>[!example]
BodyParts will be using this mechanism

>[!note] Evolution Tracking
>/Kikuo/ can be treated as a derivation of [[🟡 01 _ Kosra - Koa _ NULL]]

>[!note] pronunciation derivation
>Inspired by Japanese word "Ki" ("Tree") and the Chinese word "kuo" ("to spread")


---

## Treenode Identifying Operators

Each glyph is used to identify a node of a tree.
Here are a few ways to understand what does a Tree Identifier Operator does :
- will tell you which path (edge) to take to reach the target node
- can be treated as a nametag that an edge can have
- can be treated as a function to bring you from one node to another

| glyph                     | pronunciation             | main function                                                                                                                                                                                                                                                                                                                                                       | omitable ?                                                                                                                                      |
| ------------------------- | ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| ![[Kio_1-Root.png\|50]]   | /Kikuo-kio/               | "Start Tree Path", to declare a tree path                                                                                                                                                                                                                                                                                                                           | ❌                                                                                                                                               |
| ![[Kio_2-Stem.png\|50]]   | /ko/                      | Start from Root                                                                                                                                                                                                                                                                                                                                                     | ✅, unless we are targeting the root node                                                                                                        |
| ![[Kio_3-Leaf.png\|50]]   | /ki - **(slot : depth)**/ | "go Pass **slot:depth** of Edges"<br><br>Sometimes a tree may contain a long strand of nodes such that all nodes only has one child. This operator can literally mean "go up/down the strand", to make things shorter, the "travel distance" or "depth" will be a number, however, if the given depth is "ka", it means "keep going down until you are at a branch" | ⚠️                                                                                                                                              |
| ![[Kio_4-Branch.png\|50]] | /kæ - **(slot : index)**/ | "go to the indexth Child"<br><br>selects a branch, attaches the index of the branch to the end of the segment<br><br>by default, the index starts from 0. But not all trees uses numbers for indexing, when that happens, use the designated labels                                                                                                                 | ⚠️                                                                                                                                              |
| ![[Kio_5-Chain.png\|50]]  | /ka - **(slot : index)**/ | "leaf / a dead end"<br><br>                                                                                                                                                                                                                                                                                                                                         | ✅, when a path is a dead end, you can use this to signify it. But it still needs to be indexed if there are other possible but undesired paths. |

>[!example]
>"Kio - kæNi - kæNæ - kiNæ - kæNo"
>"treePath - goto 1st Child - goto 2nd Child - goPass 2 edges - goto 0th Child "

---

## Tree Structure with Frequency Distribution

Consider the given example :

```
Root
+- A
+- B
   +- C
   +- D
      +- E
	     +- G
		 +- H
			+- I
	  +- F
```

in order to address Node H, we need

/Kio - kæNi - kæNi - kæNo - kæNi/

Which is a bit mouthful. This is fine for small cases or rare/specific cases
but for Important and Everyday Structures, it is better to have a Main Route

Based on different structures or situation, the Main Route are all different.
the Main Route is not chosen by rule, instead it is chosen by design.

In this case, the Main Route for a certain Purpose is decided by a committee or a team of leaders or experts.

>[!example]
>The Main Route for [[🟡 01 _ Kosrani Zoiga Kaxitæ - Koiztæ _ Body Parts]]  is decided by Biology Experts, and it is reviewed, agreed, and approved.

If an Alternative Main Route is suggested, it is possible to update the convention.

>[!tip] An ideal Main Route is to cover as many Junctions as possible (not always)

since the main route consist of Stems /Ki/ and Branches /Kæ/
the glyph and pronunciation for Main Route is :

| glyph                    | pronunciation              | main function                             |
| ------------------------ | -------------------------- | ----------------------------------------- |
| ![[Kio_5-Chain.png\|50]] | /kiæ - **(slot : depth)**/ | go Pass **slot:depth** of MainRoute Edges |

In our example, we will be parenthesising our MainRoute :

```
(Root)
+- A
+- (B)
   +- C
   +- (D)
      +- (E)
	     +- G
		 +- (H)
			+- (I)
	  +- F
```

And now we can index them / give them depths :

```
(Root)
+- A
+- (B) = /kiæ-Ni/
   +- C
   +- (D) = /kiæ-Næ/
      +- (E) = /kiæ-Na/
	     +- G
		 +- (H) = /kiæ-Lo/
			+- (I) = /kiæ-Li/
	  +- F
```

with this mechanism
we can shrink /Kio - kæNi - kæNi - kæNo - kæNi/ down to /Kio - kiæLi/

---

## Back at Mah Days

EN : tri, ZH : Xu, JP : Ki, NOT PLANT, but the STRUCTURE
Trixki -> Trik : Tree / Tree Structure

Triku : trunk
Triko : branch
Trika : leaf

Trik-xu : the rootNode
Trik-xu-xo{N} : rootNode - Nth Node
Trik-xu-xo{A}-xo{B}-xo{C}-xa{F} : starting from the rootNode, then ChildA, then ChildB, then ChildC, then LeafF

xu : no parent, has children, aka root
xi : has parent, has children
xæ : has parent, one child
xa : has parent, no children, aka leaf