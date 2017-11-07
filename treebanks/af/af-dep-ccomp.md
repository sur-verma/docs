---
layout: base
title:  'Statistics of ccomp in UD_Afrikaans'
udver: '2'
---

## Treebank Statistics: UD_Afrikaans: Relations: `ccomp`

This relation is universal.

905 nodes (2%) are attached to their parents as `ccomp`.

877 instances of `ccomp` (97%) are left-to-right (parent precedes child).
Average distance between parent and child is 7.08397790055249.

The following 12 pairs of parts of speech are connected with `ccomp`: <tt><a href="af-pos-NOUN.html">NOUN</a></tt>-<tt><a href="af-pos-VERB.html">VERB</a></tt> (629; 70% instances), <tt><a href="af-pos-VERB.html">VERB</a></tt>-<tt><a href="af-pos-VERB.html">VERB</a></tt> (166; 18% instances), <tt><a href="af-pos-PRON.html">PRON</a></tt>-<tt><a href="af-pos-VERB.html">VERB</a></tt> (42; 5% instances), <tt><a href="af-pos-AUX.html">AUX</a></tt>-<tt><a href="af-pos-VERB.html">VERB</a></tt> (32; 4% instances), <tt><a href="af-pos-SCONJ.html">SCONJ</a></tt>-<tt><a href="af-pos-VERB.html">VERB</a></tt> (14; 2% instances), <tt><a href="af-pos-PROPN.html">PROPN</a></tt>-<tt><a href="af-pos-VERB.html">VERB</a></tt> (8; 1% instances), <tt><a href="af-pos-ADV.html">ADV</a></tt>-<tt><a href="af-pos-VERB.html">VERB</a></tt> (4; 0% instances), <tt><a href="af-pos-DET.html">DET</a></tt>-<tt><a href="af-pos-VERB.html">VERB</a></tt> (3; 0% instances), <tt><a href="af-pos-SYM.html">SYM</a></tt>-<tt><a href="af-pos-VERB.html">VERB</a></tt> (3; 0% instances), <tt><a href="af-pos-ADP.html">ADP</a></tt>-<tt><a href="af-pos-VERB.html">VERB</a></tt> (2; 0% instances), <tt><a href="af-pos-CCONJ.html">CCONJ</a></tt>-<tt><a href="af-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="af-pos-NUM.html">NUM</a></tt>-<tt><a href="af-pos-VERB.html">VERB</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 5 ccomp	color:blue
1	Die	die	DET	LB	Definite=Def|PronType=Art	2	det	_	_
2	inligting	inligting	NOUN	NM	Number=Sing	10	nsubj:pass	_	_
3	wat	wat	PRON	PB	PronType=Rel	5	nsubj	_	_
4	jy	jy	PRON	PTENP	Case=Nom|Number=Sing|Person=2|PronType=Prs	5	nsubj	_	_
5	verstrek	verstrek	VERB	VTHOG	Subcat=Tran|Tense=Pres|VerbForm=Fin,Inf	2	ccomp	_	SpaceAfter=No
6	,	,	PUNCT	ZM	_	5	punct	_	_
7	word	word	AUX	VTUOP	Tense=Pres|VerbForm=Fin,Inf|VerbType=Pas	10	aux:pass	_	_
8	aan	aan	ADP	SVS	AdpType=Prep	9	case	_	_
9	speurders	speurder	NOUN	NSM	Number=Plur	10	iobj	_	_
10	oorgedra	oordra	VERB	VVHOG	Subcat=Tran|Tense=Past|VerbForm=Part	0	root	_	SpaceAfter=No
11	.	.	PUNCT	ZE	_	10	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 7 ccomp	color:blue
1	Wat	wat	PRON	PB	PronType=Rel	7	nsubj	_	_
2	huishoudelike	huishoudelik	ADJ	ASA	AdjType=Attr|Case=Nom|Degree=Pos	3	amod	_	_
3	toegang	toegang	NOUN	NA	Number=Sing	7	obj	_	_
4	tot	tot	ADP	SVS	AdpType=Prep	6	case	_	_
5	basiese	basies	ADJ	ASA	AdjType=Attr|Case=Nom|Degree=Pos	6	amod	_	_
6	dienste	diens	NOUN	NSM	Number=Plur	3	nmod	_	_
7	aanbetref	aanbetref	VERB	VTHOG	Subcat=Tran|Tense=Pres|VerbForm=Fin,Inf	9	ccomp	_	SpaceAfter=No
8	,	,	PUNCT	ZM	_	7	punct	_	_
9	spreek	spreek	VERB	VTHOG	Subcat=Tran|Tense=Pres|VerbForm=Fin,Inf	0	root	_	_
10	die	die	DET	LB	Definite=Def|PronType=Art	11	det	_	_
11	syfers	syfer	NOUN	NSM	Number=Plur	9	nsubj	_	_
12	vanself	vanself	ADV	BS	Degree=Pos	9	advmod	_	SpaceAfter=No
13	.	.	PUNCT	ZE	_	9	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 7 ccomp	color:blue
1	Indien	indien	SCONJ	KO	_	19	amod	_	_
2	jy	jy	PRON	PTENP	Case=Nom|Number=Sing|Person=2|PronType=Prs	11	nsubj	_	_
3	of	of	CCONJ	KN	_	2	cc	_	_
4	iemand	iemand	PRON	PO	PronType=Ind	2	conj	_	_
5	wat	wat	PRON	PB	PronType=Rel	7	nsubj	_	_
6	jy	jy	PRON	PTENP	Case=Nom|Number=Sing|Person=2|PronType=Prs	7	nsubj	_	_
7	ken	ken	VERB	VTHOG	Subcat=Tran|Tense=Pres|VerbForm=Fin,Inf	4	ccomp	_	_
8	hierdie	hierdie	DET	PA	PronType=Dem	10	det	_	_
9	soort	soort	NOUN	NSE	Number=Sing	10	nmod	_	_
10	mishandeling	mishandeling	NOUN	NA	Number=Sing	11	obj	_	_
11	beleef	beleef	VERB	VTHOG	Subcat=Tran|Tense=Pres|VerbForm=Fin,Inf	1	dep	_	SpaceAfter=No
12	,	,	PUNCT	ZM	_	11	punct	_	_
13	kan	kan	AUX	VTUOM	Tense=Pres|VerbForm=Fin,Inf|VerbType=Mod	19	aux	_	_
14	jy	jy	PRON	PTENP	Case=Nom|Number=Sing|Person=2|PronType=Prs	19	nsubj	_	_
15	om	om	ADP	SVS	AdpType=Prep	17	case	_	_
16	'n	'n	DET	LO	Definite=Ind|PronType=Art	17	det	_	_
17	beskermingsbevel	beskermingsbevel	NOUN	NSE	Number=Sing	19	obl	_	_
18	aansoek	aansoek	NOUN	NSE	Number=Sing	19	obj	_	_
19	doen	doen	VERB	VTHOG	Subcat=Tran|Tense=Pres|VerbForm=Fin,Inf	0	root	_	SpaceAfter=No
20	.	.	PUNCT	ZE	_	19	punct	_	_

~~~

