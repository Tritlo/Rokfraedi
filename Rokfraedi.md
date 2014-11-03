# Rökfræði

## Athugasemdir um texta

Stærðfræði jöfnur eru ritaðar á LaTeX mátann, umlukið hornklofum, þ.e.
\[ x + 2 = 4 \].
Innskot í texta eru táknuð með pípum, þ.e. \| innskot \|.
Orð sem sérstök áhersla er lögð á er táknað með stjörnum, þ.e. *orð*.
Feitletruð tákn og orð eru tvíundirstrikuð á töflu, en táknuð með feitletrun hér, t.d. **breyta**. Texta sem ætlað er til að sé lesinn beint í LaTeX er táknaður á milli tveggja samsemdarmerkja með skástriki fyrir framan, þ.e.
\= \begin{gather} 2 + x \end{gather} \=.

## Formáli um texta.

### Breytur, rökbreytur og stæður

Við tölum um mál sem notuð eru í stærðfræði, sem við köllum
*viðfangsmál* á máli sem við köllum *yfirmál*. Viðfangsmálið notar *breytur*, þ.e. bókstafi sem eru notaðir sem heiti. Þurfum nöfn yfir bókstafina.
Nafn bókstafs fæst með því að setja hann í einfaldar enskar gæsalappir.
Þegar að við segjum að x sé talan þ.a. \[2 + x = 4 \], þá er 'x' heitið sem við gefum óþekktu stærðinni x í dæminu 'x' er þriðji síðasti stafurinn í latneska stafrófinu, en x er það ekki.

Búum til *táknasamstæður*, stytt í *stæður*, með því að skrifa bókstafi og sérstök tákn hvert á eftir öðru, og nafn slíkrar stæðu fæst með því að setja einfaldar enskar gæsalappir utan um stæðuna. Til dæmis er 'tala' orðið sem fæst með því að skrifa fyrst bókstafinn 't', næst bókstafinn 'a', svo bókstafinn 'l' og loks bókstafinn 'a'. \| Þetta sýnir að bókstafur getur komið tvisvar fyrir í stæðu og röðin skiptir máli \|. Líka er 'x' heiti óþekktu stærðarinnar 'x' í jöfnunni '2 + x = 4', og í þeirri jöfnu eru notuð tvö sérstök tákn,
samlagningar merkið '+' og samasemmerkið '='; og í jöfnunni '4 - (3-1) = 2' koma fyrir frádáttarmerkið '-' og vinstri sviginn '(' og hægri sviginn ')'. Getum líka sagt að stæðan ')(+-()2++++' sé óskiljanlega mynduð og merkingarlaus. \| Athugið að við notum hérna ' ' til að bæta læsileika, en það er þó ekki tekið með í þessu. \|

Þutfum breytur á yfirmálinu, t.d. til að tala um almennar breytur (og fleira) í viðfangsmálinu. Breyta á yfirmálinu eru feitletraðir bókstafir (undirstrikaðir á töflu). Getum sagt: Látum **a** og **b** vera bókstafi. Þá er **ab** stæðan sem fæst með því að skrifa fyrst stafinn **a** og svo stafinn **b**. Ef **a** er 'a' og **b** er 'b', þá er **ab** stæðan 'ab'. Ef **a** er 'b' og **b** er 'a', þá er **ab** stæðan 'ba'. Ef **a** er 'x' og **b** er 'x', þá er stæðan **ab** stæðan 'xx'.

Ef **A**, **B** eru stæður, þá er **AB** stæðan sem fæst með því að skrifa stæðuna **A** og strax á eftir stæðuna **B**. Notum sama tákn fyrir bókstaf **a** og stæðuna **a** sem hefur bara einn bókstaf, nefnilega bókstafinn **a**. Ef **a** er 'a' og **B** er stæðan 'bba', þá er **aB** stæðan 'abba' en **Ba** stæðan 'bbaa'. Ef **a** er 'a', þá skrifum við "a**B**" í stað "**aB**", frekar en "'a'**B**". \| Nafn stæðu á viðfangsmálinu táknað með tvöföldum gæsalöppum á yfirmálinu, þ.e. "a**B**" er nafn stæðunnar a**B**. \| Sama um stök tákn meðan stæðan hefur a.m.k. eina breytu á yfirmálinu.
T.d. er 2 + **x** = 4 stæðan sem fæst með því að skrifa '2', '+', breytuna  **x**, jafnaðarmerkið '=' og '4' í þessari röð, frekar en að segja að það sé stæðan '2+'x'=4'.

## Yrðingarökfræði

Yrðingarökfræði fjallar um samtengingar, næstum eingöngu um

+ ... eða ...,
+ ... og ...,
+ ef ..., þá ...,
+ ... þá og því aðeins að ... (ef og aðeins ef líka notað),

og  neitunina

+ ekki.

Viðfangsefni hennar eru *fullyrðingar*, þ.e. setningar sem eru annaðhvort sannar eða ósannar. \| "En" þýðir það sama og "og", eini munurinn eru blæbrigði. Eða er ekki útilokandi. \|

+ Ef yrðingin **A** er sönn, þá er yrðingin "ekki **A**" ósönn, en ef yrðingin **A** er ósönn, þá er yrðingin " ekki **A**" sönn.
+ Ef yrðingin **A** og **B** eru báðar sannar, þá er "**A** og **B**" sönn, annars er hún ósönn.
+ Ef yrðingar **A** og **B** eru báðar ósannar, þá er yrðingin "**A** eða **B**" ósönn, annars er hún sönn.
+ Ef yrðingin **A** er sönn og **B** er ósönn, þá er yrðingin "ef **A** þá **B**" ósönn, annars er hún sönn.
+ Yrðingin "**A** þþaa **B**" er sönn ef **A** og **B** eru báðar sannar, eða báðar ósannar, annars eru hún ósönn.

Yrðingin "**A** og **B**" segir hið sama og "ekki gildir (ekki **A** eða ekki **B**)".
Yrðingin "ef **A**, þá **B**" segir hið sama og "(ekki **A**) eða **B**".
Yrðingin "**A** þþaa **B**" segir hið sama og "(ef **A**, þá **B**) og (ef **B**, þá **A**)".

### Formlegt mál fyrir yrðinga rökfræði

Almennt er formlegt mál gefið með því að tiltaka *stafróf* (bókstafi og tákn) fyrir málið og mengi af stæðum á málinu sem við köllum *segðir*. Venjulega viljum við að ganga megi í endanlega mörgum skrefum úr skugga um hvort stæða er segð eða ekki. \| Röð tákna í segðum skiptir máli \| Venjulega er segðir skilgreindar með *reglu*, svokölluðum *myndunarreglum*.

*Skilgreining*. Skilgreinum formlegt mál *L*(*P*) fyrir yrðingarrökfræði þannig:

+ 	(A) Táknin í *L*(*P*) eru
	- 	(i) fjögur sérstök tákn, nefnilega *vinstri sviginn* '(', *hægri sviginn* ')', *neitunartáknið* '\[ \not \]', *eðunartáknið* '\[ \vee \]';
	- 	(ii) bókstafirnir
		'p', 'q', 'r', 's', 't', '\[ p_1 \]', '\[ q_2 \]', '\[ r_1 \]', ...
		við leyfum alla stafi í latneska stafrófinu, hugsanlega tölusetta með með lágvísi sem er náttúruleg tala skrifuð í tugakerfi; köllum bókstafi *yrðingabreytur*.
+ 	(B) Úr táknunum má setja saman leyfilegar samsetningar (segðir formlega málsins) sem kallast *yrðingasnið* með því að nota eftirfarandi myndunarreglur.
	-	(i) Ef **x** er yrðingabreyta, þá er stæðan **x** sem hefur bara eitt tákn, nefnilega **x**, yrðingasnið
	-	(ii) Ef **A** er yrðingasnið, þá er \[ \not **A** \] yrðingasnið.
	-	(iii) ef **A** og **B** er yrðingasnið, þá er ( **A** \[ \vee \] **B**) yrðingasnið.

Köllum ( \[ \vee \] **A** ) *neitun* yrðingasniðsins **A** og lesum "ekki **A**", og (**A** \[ \vee \] **B**) *eðun* yrðingasniðanna **A** og **B** og lesum "**A** eða **B**" í töluðu máli.

*Dæmi*. Skv. (i) eru 'p' og 'q' yrðingasnið, skv. (ii) eru þá '( \[ \not p \] )' og '( \[ \not q \] )' yrðingasnið, skv. (iii) eru þá '\[ (( \not p ) \vee (\not q)) \]' yrðingasnið, skvi (ii) er '\[ ( \not ((\not p) \vee (\not q )))' yrðingasnið. Eins sést að 
	
	'((\not p) \vee q)' og  '(\not (( \not (( \not p) \vee q)) \vee ( \not ((\not q) \vee p))))'

*Skilgreining*. Tökum upp *skammstafanir*: Ef **A** og **B** eru yrðingasnið, þá er
	+ (i) (\[ **A** \wedge **B** \] ) skammstöfun fyrir '\[ ( \not ((\not **A** ) \vee (\not **B** )));
	+ (ii) \[ ( **A** \leftarrow **B**) skammstöfun fyrir '(( \not **A**) \vee **B**);
	+ (iii) '\[ ( **A** \leftrightarrow **B** ) \] skammstöfun fyrir 
	'\[ (( **A** \leftarrow **B** ) \wedge (**B** \leftarrow **A**))'
	sem er skammstöfun fyrir (\not (( \not (( \not **A** ) \vee **B** )) \vee ( \not ((\not **B** ) \vee **A**))))

*Afleiddar myndunarreglur*. Ef **A**, **B** eru yrðingasnið, þá eru \[ ( **A** \wedge **B** ) \], \[ ( **A** \leftarrow **B**) \] og \[ ( **A** \leftrightarrow **B** ) \] yrðingasnið.

*Skilgr**. Látum \[ **x_1**, \dotsc, **x_n** \] vera ólíkar yrðingabreytur og **A** vera yrðingasnið, \[ **B_1**, \dotsc, **B_n** \] vera stæður á málinu *L*(*P*). Við táknum með

	\[ **A**_{ **x**_1, \dotsc, **x**_n} [ **B**_1, \dostc, **B**_n ] \]
eða
	I^{ **B**_1, \dotsc, **B**_n }_{**x**_1, \dotsc, **x**_n} **A**

stæðuna sem fæst úr **A** með því að setja **B**_k inn í stað **x**_k á hverjum þeim stað þar sem **x**_k kemur fyrir í **A** fyrir öll \[ k = 1, \dotsc, n \].

*Viðvörun*. Þetta þarf að gerast samtímis.

**Dæmi**: Látum **x** vera 'p', **y** vera 'q', **A** vera '\[ ((p \leftarrow q) \vee p) \]', B vera '\[( p \leftarrow q )\]', **C** vera '\[( q \wedge p ) \]'. þá er
	
	\[ **I**^{**B**, **C**}_{**x**, **y**} **A** \] stæðan '\[((( p \leftarrow q) \leftarrow (q \wedge p)) \vee (q \leftarrow p)\]',

	\[ I^{**B**}_{**x**} I^{**C**}_{**y**} **A** stæðan '((( p \leftarrow q) \leftarrow (q \wedge (p \leftarrow q))) \vee (q \leftarrow p))',


	\[ I^{**C**}_{**y**} I^{**B**}_{**x**} **A** stæðan '((((q \wedge p) \leftarrow p) \leftarrow (q \wedge p) \vee ((q \vee p))',

*Setning* Ef \[ **x**_1, \dotsc, **x**_n \] eru ólíkar breytur,
	\[ **A**, **B**_1, \dotsc, **B**_n**, eru yrðingasnið, þá er
	**A**_{**x**_1, \dotsc, **x**_n} [**B**_1, \dotsc, **B**_n] yrðingasnið. Þetta má sanna með þrepun yfir lengd **A**.
	
Getum notað:
*Þrepunarlögmál fyrir stæður í *L*(*P*)*

Látum *E* vera eiginleika sem stæða í *L*(*P*) getur haft eða ekki og g.r.f. að
	
+	(i) ef **x** er yrðingarbreyta, þá hefur **x** eiginleika *E*;
+	(ii) ef **A** er yrðingasnið með eiginleikann *E*, þá hefur \[ (\not A) \] eiginleika *E*;
+	(iii) ef **A**, **B** eru yrðingasnið með eiginleika *E*, þá hefur \[(**A** \vee **B**)\] eiginleikann *E*

Þá hafa öll yrðingasnið eiginleikann *E*.

*Reglur um svigasetningu*
Leyfum okkur að sleppa svigum ef við getum sett þá einn aftur með því að fylgja eftirfarandi reglum:
Alltaf má sleppa yztu svigum.

Röðum röktáknunum í röð:

	\[ '\not', '\vee', '\wedge', '\leftarrow', '\leftrightarrow' \]

til að setja inn svia setjum við fyrst sviga utan um '\not', og sytzta yrðungasnið sem kemur á eftir því í stæðunni.
Setjum næst sviga utanum '\[ \vee \]' og styzta yrðingarsnið báðu megin.
Ef það kemur oftar en einu sinni fyrir, þá göngum við á röðina frá hægri til vinztri. Næst er það sama fyrir \['\wedge'\], svo fyrir \['\leftarrow'\] og svo loks fyrir \[ ' \leftrightarrow ' \]. Síðast yzta sviga.

*Dæmi*

+	' \[ p \wedge q \wedge r \leftarrow \not p \leftarrow r \leftrightarrow \not \not q \]', verður fyrst
+	' \[ p \wedge q \wedge r \leftarrow \not p \leftarrow r \leftrightarrow \not (\not q) \]', næst
+	' \[ p \wedge q \wedge r \leftarrow (\not p) \leftarrow r \leftrightarrow \not (\not q) \]', næst
+	' \[ p \wedge q \wedge r \leftarrow (\not p) \leftarrow r \leftrightarrow ( \not (\not q)) \]', næst
+	' \[ p \wedge (q \wedge r) \leftarrow (\not p) \leftarrow r \leftrightarrow ( \not (\not q)) \]', næst
+	' \[ ( p \wedge (q \wedge r)) \leftarrow (\not p) \leftarrow r \leftrightarrow ( \not (\not q)) \]', næst
+	' \[ ( p \wedge (q \wedge r)) \leftarrow ( (\not p) \leftarrow r ) \leftrightarrow ( \not (\not q)) \]', næst
+	' \[ (( p \wedge (q \wedge r)) \leftarrow ( (\not p) \leftarrow r ) ) \leftrightarrow ( \not (\not q)) \]', loks
+	' \[ (( p \wedge (q \wedge r)) \leftarrow ( (\not p) \leftarrow r ) \leftrightarrow ( \not (\not q)) )\]'.

Athugum sérstaklega að

	\[ **A** \leftarrow **B** \leftarrow **C** \]

þýðir

	\[ **A** \leftarrow (**B** \leftarrow **C**) \]

svo að í 

	\[ ( **A** \leftarrow **B** ) \leftarrow **C** \]

má ekki sleppa svigum.

### Pólskur ritháttur

Búum til nýtt mál *L*'(*P*) með sama stafróf og *L*(*P*) en nýjum myndunarreglum

+	(i) ef *x* er yrðingabreyta, þá er *x* segð í *L*'(*P*)
+	(ii) ef *A* er segð í *L*'(*P*), þá er \[ \not **A** \] segð í *L*'(*P*)
+	(iii) Ef *A*, *B* er segð í *L*'(*P*), þá er \[ \vee *A* *B* \] segð í *L*'(*P*).

Til að sjá að það megi lesa *A* og *B* út úr \[ \vee *A* *B* \].
Þurfum að sjá: Ef *A*, *B*, *C*, *D* eru segðir og \[ \vee *A* *B* \] er sama stæða og \[ \vee *C* *D* \], þá er *A* sama og *C* og *B* sama og *D*.

Ef \[ \vee *A* *B* \] er sama og \[ \vee *C* *D* \], þá er önnurstæðan *A*, *C* upphafskafli í hinni.

Það nægir að sýna:

Ef *A*, *C* eru segðir á *L*'(*P*) og önnur er upphafskafli hinnar, þá eru þær sama segðin.

*Sö*: Þrepum yfir lengd minni segðar. Ef lengdin er 1, þá er minni stæðan breyta, en einu stæðurnar í *L*'(*P*) sem byrja á breytu eru breytur. Ef lengdin er stærri en 1, þá byrja annaðvhort báðar á '\[ \not \]' eða báðar á \[ \vee \].

Í fyrra tilvikinu má skrifa **A** sem \[ \not **A**_1 \] og **C** sem \[ \not **C**_1 \], þar sem \[ **A**_1, **C_1** \] eru segðir og önnur upphafskafli hinnar, svo að \[ **A**_1 er **C**_1 \] skv. þf. og þá **A** sama og **C**. Í seinna tilviki er **A** stæðan \[ \vee **A**_1 **A**_2 \] og **C** er \[ \vee **C**_1, **C**_2 \], þar sem \[ **A**_1, **A**_2, **C**_1, **C**_2 \] eru segðir í *L*'(*P*), og önnur af segð \[ **A**_1, **C**_1 \] er upphafssegð hinnar. Skv. Þ.f. er \[ **A**_1\] sama og \[ **C**_1 \] og þá er \[ **A**_2 \] sama og \[ **C**_2 \] og þvi **A** sama og **C**.

Látum *p* vera mengi stæða í *L*(*P*) og *p*' vera mengi stæða í *L*'(*P*). Fáum varpanir

\[

+	\theta: *p* \leftarrow *p*'
+	\eta: *p*' \leftarrow *p*

 \]

með þrepun þ.a.

\[
+	\theta[x] er **x** ef x er breyta
+ 	\theta[(\not **A**)] er \not \theta[**A**],
+	\theta[(**A** \vee **B**)] er \vee \theta[**A**] \theta[**B**]
\]
og
\[
+	\eta[x] er **x** ef x er breyta
+ 	\eta[\not **A**] er (\not \theta[**A**]),
+	\eta[ \vee **A** **B**] er ( \theta[**A**] \vee \theta[**B**]),
\]
sem eru andhverfur hvor annarar.
Skammstafanir í *L*'(*P*)
\[
+	\wedge **A** **B** fyrir \not \vee \not **A** \not **B**
+	\leftarrow **A** **B** fyrir \vee \not **A** **B**
+	\leftarrow **A** **B** fyrir \not \vee \not \vee \ot **A** **B** \not \vee \not **B** **A**.
\]


Segjum að yrðing hafi *sanngildið* 0 ef hún er ósönn og *sanngildið* 1 ef hún er sönn.

*Skilgreining*

1.	Látum $n \in \N, n \geq 1$. Vörpun
	\[ f: \set{0,1}^n \to \set{0,1}
	kallast n-*stætt sannfall* (*Boole-fall*)
2.
	Látum $ **x**_1, \dotsc **x**_n $ vera yrðingabreytur

...

	\[ f_{**x**_1, \dotsc, x_n}^{**A**} : \set{0,1}^n \to \set{0,1} \]
	þannig að
	
	+ 	(i). Ef **A** er yrðingabreyta $ **x**_k $, og $ $ t = (t_1, \dotsc, t_n) \in \set{0,1}^n $, þá er
	 	\[ f_{**x**_1, \dotsc, x_n}^{**A**} (t) := t_k \].
	+	(ii). Ef **A** er yrðingarsnið $ ( \not **t**)$, þá er
		\[ f_{**x**_1, \dotsc, x_n}^{**A**} (t) := \bcondef 1 & \ef f_{**x**_1, \dotsc, x_n}^{**C**} (t) = 0 \\ 0 & \annars \econdef \]
	+	(iii). Ef **A** er yrðingarsnið $ ( **C** \vee **D**)$, þá er
		\[ f_{**x**_1, \dotsc, x_n}^{**A**} (t) = \bcondef 0 & \ef f_{**x**_1, \dotsc, x_n}^{**C**} = f_{**x**_1, \dotsc, x_n}^{**D**} (t) = 0 \\ 1 & \annars \econdef \]

	Köllum $f_{**x**_1, \dotsc, x_n}^{**A**}$ sannfall yrðingarsniðsins **A** m.t.t. $ **x**_1 \dotsc, **x**_n $.

	
Sannföllum yrðingasniða má lýsa með töflum, svokölluðum *sanntöflum*. Tafla fyrir n-stætt yrðingarsnið hefur $2^n$ reiti. Einföldustu töflunar fyrir yrðingarsnið með aðeins einni breytu, t.d. 'p' og '$\not p $'; töflur fyrir þau eru
	\= \begin{tabular}[| c || c ]
		p & p \\
		\hline \\
		0 & 0	\\
		1 & 1 \\
		\hline
	   \end{tabular}

	\begin{tabular}[| c || c ]
		p & \not p \\
		\hline \\
		0 & 1	\\
		1 & 0 \\
		\hline
	   \end{tabular}

	það eru fleiri yrðinarsnið með aðeins eina breytu, t.d. 
	'$ p \vee \not p $' og '$ p \wedge \not p $' töflur fyrir þau eru

	\begin{tabular}[| c || c ]
		p & p \\
		\hline \\
		0 & 0	\\
		1 & 1 \\
		\hline
	\end{tabular}

	\begin{tabular}[| c || c ]
		p & p \vee \not p \\
		\hline \\
		0 & 1	\\
		1 & 1 \\
		\hline
	\end{tabular}

	\begin{tabular}[| c || c ]
		p & p \wedge \not p \\
		\hline \\
		0 & 0	\\
		1 & 0 \\
		\hline
	\end{tabular}

sanntöflur fyrir "samtengingarnar"

	\begin{tabular}[| c  | c || c ]
		p & q & p \vee q \\
		\hline \\
		0 & 0 & 0 \\
		0 & 1 & 1 \\
		1 & 0 & 1 \\
		1 & 1 & 1 \\
		\hline
	\end{tabular}

	\begin{tabular}[| c  | c || c ]
		p & q & p \wedge q \\
		\hline \\
		0 & 0 & 0 \\
		0 & 1 & 0 \\
		1 & 0 & 0 \\
		1 & 1 & 1 \\
		\hline
	\end{tabular}

	\begin{tabular}[| c  | c || c ]
		p & q & p \leftarrow q \\
		\hline \\
		0 & 0 & 1 \\
		0 & 1 & 1 \\
		1 & 0 & 0 \\
		1 & 1 & 1 \\
		\hline
	\end{tabular}

	\begin{tabular}[| c  | c || c ]
		p & q & p \leftrightarrow q \\
		\hline \\
		0 & 0 & 1 \\
		0 & 1 & 0 \\
		1 & 0 & 0 \\
		1 & 1 & 1 \\
		\hline
	\end{tabular}

Finnum sanntöflu fyrir '((p \leftarrow q) \wedge p) \leftarrow q'
	\begin{tabular}[| c  | c || c | c | c ]
		p & q & p \leftarrow q  & (p \leftarrow q) \wedge p & ((p \leftarrow q) \wedge ) \leftarrow q \\
		\hline \\
		0 & 0 & 1 & 0 & 1 \\
		0 & 1 & 1 & 0 & 1 \\
		1 & 0 & 0 & 0 & 1 \\
		1 & 1 & 1 & 1 & 1 \\
		\hline
	\end{tabular}

*Skilgreining* 

1.	Látum **A** vera yrðingasnið og $ **x**_1, \dotsc, **x**_n $ vera upptalningu á breytunum í **A**. Við segjum að **A** sé sísanna *sísanna* (tautology) ef sannfallið $ f_{**x**_1, \dotsc, x_n}^{**A**} $ er fastafallið 1. (Þetta er óháð hvernig við tölusetjum breyturnar). Við segjum að **A** sé *mótsögn* ef sannfall þess er 0.
2.	Segjum að yrðingarsnið **B** sé *rökafleiða* yrðingarsniðs **A** ef
	$**A** \leftarrow **B** $ sé sísanna.
3.	Segjum að yrðingarsnið **A** og **B** séu *rökfræðilega jafngild* ef
	$(**A** \leftrightarrow **B**)$ er sísanna.

*Dæmi*: Yrðingarsniðin '$p \vee \not p$' og '$ (( p \leftarrow q) \wedge p) \leftarrow $' eru sísönnur. Því er 'q' rökafleiðing af '$(p \leftarrow q) \wedge p $'. Auðvelt er að sjá að 'p' og '$ \not \not p $' rökfræðilega jafngild, eins eru '$ p \leftarrow q $' og '$ \not q \leftarrow \not p $' rökfræðilega jafngild.

*Setning*. Ef **A** og $**A** \to **B**$ eru sísönnur, þá er **B** sísanna.

*Sönnun*. Látum $**x**_1, \dotsc, **x**_n $ vera upptalningu bretynanna sem koma fyrir í **A** eða **B**. G.r.f. að **B** sé ekki sísanna. Þá er til stak $ t = (t_1, \dotsc, t_n) \in \set{0,1}^n$ þ.a. $f_{**x**_1, \dotsc, x_n}^{**B**} (t) = 0)$. Nú er **A** sísanna, svo að $ f_{**x**_1, \dotsc, x_n}^{**A**} (t) = 1$ og þá $ f_{**x**_1, \dotsc, x_n}^{\not **A**} = 0$. En þá er
$ f_{**x**_1, \dotsc, x_n}^{**A** \leftarrow **B**} (t) = f_{**x**_1, \dotsc, x_n}^{ \not **A** \vee **B** } = 0$, í móstögn við að $**A** \to **B**$ sé sísanna.

*Setning*. Gr.r.f að **A** sé sísanna,	 $**x**_1, \dotsc, **x**_n$ vera ólíkar yrðingabreytur og $**B**_1, \dotsc, **B**_n$ vera yrðingarsnið. Þá er $**A**_{**x**_1, \dotsc, **x**_n} [**B**_1, \dotsc, **B**_n]$ sísanna.

"*Sö*": Sannfall fyrir $**A**_{**x**_1, \dotsc, **x**_n} [**B**_1, \dotsc, **B**_n]$ er samskeyting af $f_{**x**_1, \dotsc, x_n}^{**A**}$ og einhverju öðru, en $ f_{**x**_1, \dotsc, x_n}^{**A**}$ er fastafallið, svo að útkoman er fastafallið 1.

*Setning*. Látum $f: \set{0,1}^n \to \set{0,1}$ vera sannfall. Þá er til yrðingarsnið **A** ásamt ólíkum breytum $ **x**_1, \dotsc, **x**_n$, þ.a.
\[ f = f_{**x**_1, \dotsc, x_n}^{**A**}. \]

Geymum sönnun.

Tvístæð sannföll eru $2^{2^} = 2^4 = 16 $ talsins.
Látum $*L*^{*}$ vera mál, útvíkkun á *L*(*p*) með tvístæðum röktánum að auki fyrir þau tvístæðu sannföll sem vantar.

Þar af tvö, '$ \downarrow $' og '$ | $' með sanntöflu


	\begin{tabular}[| c  | c || c ]
		p & q & p \downarrow q \\
		\hline \\
		0 & 0 & 1 \\
		0 & 1 & 0 \\
		1 & 0 & 0 \\
		1 & 1 & 0 \\
		\hline
	\end{tabular}

og

	\begin{tabular}[| c  | c || c ]
		p & q & p | q \\
		\hline \\
		0 & 0 & 1 \\
		0 & 1 & 1 \\
		1 & 0 & 1 \\
		1 & 1 & 0 \\
		\hline
	\end{tabular}
