---
layout: base
title:  'Statistics of cop in UD_Wolof-WTB'
udver: '2'
---

## Treebank Statistics: UD_Wolof-WTB: Relations: `cop`

This relation is universal.

600 nodes (1%) are attached to their parents as `cop`.

411 instances of `cop` (69%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.63166666666667.

The following 6 pairs of parts of speech are connected with `cop`: <tt><a href="wo_wtb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="wo_wtb-pos-AUX.html">AUX</a></tt> (362; 60% instances), <tt><a href="wo_wtb-pos-PRON.html">PRON</a></tt>-<tt><a href="wo_wtb-pos-AUX.html">AUX</a></tt> (123; 21% instances), <tt><a href="wo_wtb-pos-PROPN.html">PROPN</a></tt>-<tt><a href="wo_wtb-pos-AUX.html">AUX</a></tt> (76; 13% instances), <tt><a href="wo_wtb-pos-VERB.html">VERB</a></tt>-<tt><a href="wo_wtb-pos-AUX.html">AUX</a></tt> (16; 3% instances), <tt><a href="wo_wtb-pos-NUM.html">NUM</a></tt>-<tt><a href="wo_wtb-pos-AUX.html">AUX</a></tt> (13; 2% instances), <tt><a href="wo_wtb-pos-ADV.html">ADV</a></tt>-<tt><a href="wo_wtb-pos-AUX.html">AUX</a></tt> (10; 2% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 cop	color:blue
1	Loolu	boobu	PRON	PRON	Deixis=Prox|DeixisRef=2|NounClass=Wol7|Number=Sing|PronType=Dem	3	nsubj	3:nsubj	_
2	a	a	AUX	INFL	FocusType=Subj|Mood=Ind	3	aux	3:aux	_
3	taxoon	tax	VERB	VERB	Mood=Ind|Tense=Past|VerbForm=Fin	0	root	0:root	_
4	ñu	mu	PRON	PRON	Case=Nom|Number=Plur|Person=3|PronType=Prs	6	nsubj	6:nsubj	_
5	di	di	AUX	COP	Aspect=Imp|Mood=Ind|Tense=Pres|VerbForm=Fin	6	cop	6:cop	_
6	réew	réew	NOUN	NOUN	_	3	ccomp	3:ccomp	_
7	yu	bu	PRON	PRON	NounClass=Wol8|Number=Plur|Person=3|PronType=Rel	8	nsubj	8:nsubj	_
8	naat	naat	VERB	VERB	Mood=Ind|VerbForm=Fin	6	acl:relcl	6:acl:relcl	SpaceAfter=No
9	.	.	PUNCT	PERIOD	_	3	punct	3:punct	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 cop	color:blue
1	Mu	mu	PRON	PRON	Case=Nom|Number=Sing|Person=3|PronType=Prs	3	nsubj	3:nsubj	_
2	doon	di	AUX	COP	Aspect=Imp|Mood=Ind|Tense=Past|VerbForm=Fin	3	cop	3:cop	_
3	ku	bu	PRON	PRON	NounClass=Wol1|Number=Sing|Person=3|PronType=Rel	0	root	0:root	_
4	sopp	sopp	VERB	VERB	Mood=Ind|VerbForm=Fin	3	acl:relcl	3:acl:relcl	_
5	Yonent	Yonent	PROPN	NAME	_	4	obj	4:obj	_
6	bi	bi	DET	DET	Definite=Def|Deixis=Prox|NounClass=Wol5|Number=Sing|PronType=Art	5	det	5:det	SpaceAfter=No
7	,	,	PUNCT	COMMA	_	8	punct	8:punct	_
8	bëgg	bëgg	VERB	VERB	Mood=Ind|VerbForm=Fin	4	conj	4:conj	_
9	ab	ab	DET	DET	Definite=Ind|NounClass=Wol5|Number=Sing|PronType=Art	10	det	10:det	_
10	sëriñam	sëriñ	NOUN	NOUN	Number=Sing|Poss=Yes	8	obj	8:obj	_
11	di	di	AUX	AUX	Aspect=Imp|Mood=Ind|Tense=Pres	12	aux	12:aux	_
12	wëye	wëye	VERB	VERB	Mood=Ind|VerbForm=Fin	4	conj	4:conj	_
13	ay	ab	DET	DET	Definite=Ind|NounClass=Wol8|Number=Plur|PronType=Art	14	det	14:det	_
14	ndigëlam	ndigël	NOUN	NOUN	Number=Sing|Poss=Yes	12	obj	12:obj	SpaceAfter=No
15	.	.	PUNCT	PERIOD	_	3	punct	3:punct	_

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 12 11 cop	color:blue
1	Mu	mu	PRON	PRON	Case=Nom|Number=Sing|Person=3|PronType=Prs	2	nsubj	2:nsubj	_
2	nangu	nangu	VERB	VERB	Mood=Ind|VerbForm=Fin	0	root	0:root	_
3	te	te	CCONJ	CONJ	_	4	cc	4:cc	_
4	seere	seere	VERB	VERB	Mood=Ind|VerbForm=Fin	2	conj	2:conj	_
5	ni	ni	SCONJ	COMP	_	7	mark	7:mark	SpaceAfter=No
6	:	:	PUNCT	COLON	_	7	punct	7:punct	_
7	Amul	am	VERB	VERB	Mood=Ind|Number=Sing|Person=3|Polarity=Neg|VerbForm=Fin	4	ccomp	4:ccomp	_
8	jenn	benn	DET	DET	Definite=Ind|NounClass=Wol4|Number=Sing|PronType=Art	9	det	9:det	_
9	Yàlla	Yàlla	PROPN	NAME	_	7	obj	7:obj	_
10	ju	bu	PRON	PRON	NounClass=Wol4|Number=Sing|Person=3|PronType=Rel	12	nsubj	12:nsubj	_
11	dul	di	AUX	COP	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Neg|Tense=Pres|VerbForm=Fin	12	cop	12:cop	_
12	Allaa	Allaa	PROPN	NAME	_	9	acl:relcl	9:acl:relcl	SpaceAfter=No
13	.	.	PUNCT	PERIOD	_	2	punct	2:punct	_

~~~


