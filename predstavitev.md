# Besedilo za predstavitev seminarske naloge

Predstavitev traja okoli 10 minut: štirje govorci po približno 2,5 minute (okoli 300 besed na osebo). Polovica časa je namenjena Solowovemu modelu, vseh sedem enačb iz naloge pa je na prosojnicah in v tem besedilu, ker bo profesor spraševal predvsem o povedanem.

## Razdelitev

| Čas | Del | Govorec | Prosojnice |
| --- | --- | --- | --- |
| 0:00–2:30 | 1. Uvod, raziskovalno vprašanje in podatki | Andraž Ajdovec | 1 naslov · 2 motivacija in raziskovalno vprašanje · 3 ključni podatki (slika 1, tabela 2) |
| 2:30–5:00 | 2. Solowov model | Tin Cvek | 4 predpostavke, enačbi (1) in (2) · 5 enačba (3) · 6 uravnotežena pot, enačbi (4) in (5) |
| 5:00–7:30 | 3. Razčlenitev in simulacija | Jan Hrovat | 7 enačbi (6) in (7) · 8 štiri razlage in simulacija (slika 3, tabela 3) |
| 7:30–10:00 | 4. Rezultati in zaključek | Miha Ručigaj | 9 razčlenitev po obdobjih (tabela 4) · 10 kako dobro je model napovedal (tabela 5) · 11 ali je to UI · 12 zaključek |

Imena so razporejena po abecedi, zamenjajte jih po želji. Besedila ne berite dobesedno: enkrat ga preberite na glas s štoparico. Enačb ne berite simbol za simbolom, temveč pokažite nanje in povejte, kaj pomenijo.

## 1. del – Uvod, raziskovalno vprašanje in podatki (Andraž, ~2,5 min, 316 besed)

**Prosojnica 1 – naslov**

Lep pozdrav. Smo Andraž Ajdovec, Tin Cvek, Jan Hrovat in Miha Ručigaj. Predstavili bomo seminarsko nalogo Umetna inteligenca kot vir raziskav in razvoja ter dolgoročne gospodarske rasti: ZDA v obdobju od 2010 do 2025.

**Prosojnica 2 – motivacija in raziskovalno vprašanje**

Že majhne razlike v stopnji rasti so pomembne: če je letna rast višja za eno odstotno točko, je dohodek na prebivalca po 40 letih višji za približno 49 odstotkov. Po Solowovem modelu BDP na delavca dolgoročno raste le s tehnološkim napredkom, ta pa izvira iz idej, ki nastajajo z raziskavami in razvojem. Umetna inteligenca bi lahko bila nov vir idej, ocene njenega učinka pa se zelo razlikujejo. ZDA smo izbrali, ker največ vlagajo v raziskave in razvoj in v umetno inteligenco ter ker so na tehnološki meji. To pomeni, da že uporabljajo najboljše razpoložljive tehnologije, zato lahko hitreje rastejo le z novimi idejami, ne s posnemanjem drugih. Če UI pospešuje rast, bi se to moralo najprej pokazati prav v ZDA.

Naše raziskovalno vprašanje je: ali je pospešek rasti produktivnosti v ZDA v obdobju od 2010 do 2025 po Solowovem modelu posledica višjih investicij ali hitrejšega tehnološkega napredka in ali ga lahko pripišemo umetni inteligenci? Obdobje smo razdelili na tri podobdobja, zadnje pa še na leta pandemije in leta po izidu ChatGPT.

**Prosojnica 3 – ključni podatki (slika 1, tabela 2)**

Podatke smo vzeli iz uradnih virov: izdatke za raziskave in razvoj od National Science Board, BDP in investicije od BEA, vlaganja v UI od programa NITRD in iz poročila AI Index, produktivnost pa od BLS. Izstopajo tri ugotovitve. Prvič, delež raziskave in razvoj v BDP je bil do leta 2015 okoli 2,7 odstotka, leta 2023 pa 3,38 odstotka. Drugič, celotna stopnja investicij se je ustalila pri okoli 18 odstotkih BDP. Tretjič, vlaganja v UI hitro rastejo: federalna (zvezna vlada ZDA) so se med letoma 2020 in 2023 več kot podvojila, zasebne naložbe pa so leta 2024 dosegle 109 milijard dolarjev.

BDP na uro dela je v treh podobdobjih rasel po 1,1, 1,4 in 2,2 odstotka na leto. Ali je pospešek posledica investicij ali tehnologije, nam pove model, ki ga bo predstavil Tin.

## 2. del – Solowov model (Tin, ~2,5 min, 283 besed)

**Prosojnica 4 – predpostavke in osnovni enačbi.** Na prosojnici:

$$
Y_t = K_t^{\alpha}(A_t L_t)^{1-\alpha} \quad (1) \qquad\qquad K_{t+1} = (1-\delta)K_t + sY_t \quad (2)
$$

Uporabili smo Solowov model z rastjo prebivalstva in tehnologije v diskretnem času, kot je predstavljen na predavanjih. Gospodarstvo je zaprto, trgi so popolnoma konkurenčni, gospodinjstvo pa ničesar ne optimizira, temveč varčuje eksogen delež s dohodka. Delo raste po stopnji n, tehnologija po stopnji g, kapital pa se amortizira po stopnji delta.

Proizvodnja je podana z enačbo ena. To je Cobb-Douglasova funkcija kapitala in učinkovitega dela, kjer A povečuje produktivnost dela, alfa pa je delež kapitala v dohodku. Ker so investicije enake varčevanju, se kapital kopiči po enačbi dve: kapital v naslednjem obdobju je kapital, ki ostane po amortizaciji, plus investicije, s krat Y.

**Prosojnica 5 – dinamika kapitala.** Na prosojnici:

$$
\tilde k_t \equiv \frac{K_t}{A_t L_t}, \qquad \tilde k_{t+1}=\frac{(1-\delta)\tilde k_t+s\,\tilde k_t^{\alpha}}{(1+g)(1+n)} \quad (3)
$$

Ker A in L rasteta, kapital na delavca ne konvergira k stalni vrednosti. Zato model zapišemo s kapitalom na enoto učinkovitega dela, k z valovnico, torej K deljeno z A krat L. Če enačbo dve delimo z A krat L v naslednjem obdobju, dobimo enačbo tri. Ko je k z valovnico pod ustaljeno vrednostjo, kapital raste hitreje kot učinkovito delo, ko je nad njo, pa počasneje. Razlog je padajoči mejni produkt kapitala.

**Prosojnica 6 – uravnotežena pot rasti.** Na prosojnici:

$$
\tilde k^{\star}=\left(\frac{s}{g+n+gn+\delta}\right)^{\frac{1}{1-\alpha}}, \qquad y^{\star}_t=A_t\left(\frac{s}{g+n+gn+\delta}\right)^{\frac{\alpha}{1-\alpha}} \quad (4)
$$

$$
\frac{K}{Y}=\frac{s}{g+n+gn+\delta}=\frac{0{,}2}{0{,}02+0{,}01+0{,}0002+0{,}06}\approx 2{,}2 \quad (5)
$$

Na uravnoteženi poti je k z valovnico konstanten. Če v enačbi tri izenačimo k v obeh obdobjih, dobimo enačbo štiri. Iz nje sledi ključno sporočilo modela: BDP na delavca je sorazmeren z A, zato dolgoročno raste s stopnjo g. Stopnja varčevanja vpliva le na raven, ne na rast.

Iz istega pogoja sledi enačba pet: razmerje med kapitalom in BDP je na uravnoteženi poti konstantno in ni odvisno od A. S parametri s predavanj, delta 0,06, alfa 0,33 in s 0,2, ter z g 2 odstotka in n 1 odstotek je to razmerje okoli 2,2, kar se ujema s Kaldorjevim dejstvom. Kako model uporabimo na podatkih, bo predstavil Jan.

## 3. del – Razčlenitev rasti in simulacija (Jan, ~2,5 min, 303 besede)

**Prosojnica 7 – računovodska razčlenitev.** Na prosojnici:

$$
y=A^{1-\alpha}k^{\alpha}h^{1-\alpha} \qquad\text{oziroma}\qquad y=A\left(\frac{K}{Y}\right)^{\frac{\alpha}{1-\alpha}}h \quad (6)
$$

$$
g_y=g_A+\frac{\alpha}{1-\alpha}\,g_{K/Y}+g_h \quad (7), \qquad g_A\approx\frac{g_{\mathrm{TFP}}}{1-\alpha}
$$

Za empirični del uporabimo računovodsko razčlenitev rasti s predavanj. Proizvodno funkcijo razširimo s človeškim kapitalom h in jo zapišemo na delavca. Dobimo prvi zapis v enačbi šest. Predavanje priporoča drugi zapis, v katerem namesto kapitala na delavca nastopa razmerje K proti Y. Kapital na delavca je namreč odvisen od A, saj boljša tehnologija poveča tudi investicije, razmerje K proti Y pa po enačbi pet od A ni odvisno.

Če drugi zapis logaritmiramo in vzamemo časovno razliko, dobimo enačbo sedem: rast BDP na delavca je vsota rasti produktivnosti, prispevka razmerja K proti Y in rasti človeškega kapitala. Pri alfi ena tretjina je utež pri K proti Y enaka 0,5. Produktivnost A izmerimo kot ostanek in jo preverimo z uradno TFP, saj je TFP enaka A na ena minus alfa.

**Prosojnica 8 – štiri razlage in simulacija (slika 3).** Na prosojnici je ta tabela (povzetek tabele 3 iz naloge) in slika 3:

| Razlaga | Sprememba v simulaciji | Učinek na rast BDP na delavca | K/Y |
| --- | --- | --- | --- |
| (A) višje investicije | s z 0,20 na 0,21 | +0,15 o. t. v prvem letu, nato nazaj na 2 % | naraste (2,22 → 2,31) |
| (B) enkraten dvig produktivnosti | A enkrat za 3 % | v tem letu 4,04 %, nato skoraj 2 % | najprej pade, nato se vrne |
| (C) trajno hitrejši tehnološki napredek | g z 2 na 2,5 % | takoj +0,33 o. t., nato proti 2,5 % | rahlo pade (proti 2,10) |
| (D) več R&R (Jones, 1995) | višji delež R&R v BDP | nekaj let višja rast A, dolgoročno enaka | kot pri (B) |

UI v modelu ne nastopa neposredno, zato jo vključimo kot spremembo parametrov modela. Tako dobimo štiri možne razlage pospeška, ki so v nalogi označene s črkami od A do D. Prve tri smo simulirali z enačbama ena in dve.

Prva razlaga so višje investicije, na primer v podatkovne centre. Če se stopnja varčevanja poveča za eno odstotno točko, se rast v prvem letu poveča le za 0,15 odstotne točke, nato pa se vrne na 2 odstotka. Druga razlaga je enkraten dvig produktivnosti: če se A enkrat poveča za 3 odstotke, rast v tem letu skoči na 4 odstotke in se nato vrne na osnovo. Tretja razlaga je trajno hitrejši tehnološki napredek: če se g poveča z 2 na 2,5 odstotka, rast takoj naraste za 0,33 odstotne točke in se nato približuje 2,5 odstotka. Samo ta razlaga trajno zviša rast. Četrta razlaga izhaja iz Jonesovega modela: več raziskav in razvoja prinese nekaj let višjo rast produktivnosti, ne pa trajno.

Ključno je, da razmerje K proti Y poveča le prva razlaga. Kaj kažejo podatki, bo predstavil Miha.

## 4. del – Rezultati in zaključek (Miha, ~2,5 min, 286 besed)

**Prosojnica 9 – razčlenitev po obdobjih (tabela 4)**

Hvala. V tabeli je razčlenitev rasti BDP na uro dela po enačbi sedem. Od 2010 do 2014 je razmerje K proti Y upadalo, kar je prilagajanje po recesiji. Od 2015 do 2019 se je stopnja investicij povečala in rast je pospešila na 1,44 odstotka, predvsem zaradi razmerja K proti Y. Od 2020 do 2025 je stopnja investicij ostala pri 18 odstotkih, rast BDP na uro pa je pospešila na 2,23 odstotka. Ta pospešek izvira iz produktivnosti, skoncentriran pa je v letih od 2023 do 2025, ko je produktivnost rasla po 2,25 odstotka.

**Prosojnica 10 – kako dobro je model napovedal (tabela 5).** Na prosojnici:

| Napoved modela | Podatki | Ujemanje |
| --- | --- | --- |
| K/Y je konstanten | prispevek K/Y: −0,48 → −0,06 → −0,05 | po letu 2015 se potrdi |
| višje investicije zvišajo rast le malo | 2015–19: napoved +0,28, dejansko +0,34 o. t.; 2020–25: napoved +0,03, dejansko +0,79 o. t. | v drugem obdobju da, v tretjem velik razkorak |
| produktivnost raste s stalno stopnjo g ≈ 2 % | rast A: 1,22 → 1,10 → 1,71 %; 2023–25: 2,25 % | največje odstopanje |

Kako dobro je model napovedal? Preverimo lahko tri njegove napovedi. Prvič, da je razmerje K proti Y konstantno: to se po letu 2015 potrdi. Drugič, da višje investicije rast zvišajo le malo: za drugo obdobje model napove 0,28 odstotne točke pospeška, dejansko je bilo 0,34, kar se dobro ujema. Za tretje obdobje napove le 0,03, dejansko pa je bilo 0,79. Tretjič, da produktivnost dolgoročno raste s stalno stopnjo, za ZDA okoli 2 odstotka. Tu je odstopanje največje: do leta 2019 je rasla le po 1,1 do 1,2 odstotka, po letu 2023 pa po 2,25 odstotka. Model tega ne more napovedati, ker je g eksogen, zato ves razkorak pripiše tehnologiji.

**Prosojnica 11 – ali je to UI?**

Ali je ta tehnološki napredek posledica UI? Menimo, da ne v celoti. Prvič, Acemoglujeva ocena učinka UI je manj kot desetina pospeška. Drugič, nove tehnologije izmerjeno produktivnost na začetku podcenijo, zato takojšen skok po izidu ChatGPT ni prepričljiv. Tretjič, pospešek enako dobro pojasni četrta razlaga, saj se je delež raziskav in razvoja po letu 2015 povečal.

**Prosojnica 12 – zaključek**

Pospešek je torej posledica hitrejšega tehnološkega napredka, ne višjih investicij, jasnega učinka UI pa do leta 2025 še ne moremo zaznati. Hvala za pozornost, z veseljem odgovorimo na vprašanja.

## Možna vprašanja in odgovori

Vprašanja so razvrščena po delih predstavitve. Odgovarja naj praviloma govorec tistega dela, razumeti pa jih morate vsi, saj lahko profesor vpraša kogarkoli. Izpeljave 1–9 znajte narediti tudi na tabli.

### Solowov model (Tin)

**1. Kako iz enačb (1) in (2) dobite enačbo (3)?** Enačbo (2) delimo z $A_{t+1}L_{t+1}=(1+g)(1+n)A_tL_t$. Po enačbi (1) je $Y_t/(A_tL_t)=\tilde k_t^{\alpha}$.

$$
\tilde k_{t+1}=\frac{K_{t+1}}{A_{t+1}L_{t+1}}=\frac{(1-\delta)K_t+sY_t}{(1+g)(1+n)\,A_tL_t}=\frac{(1-\delta)\tilde k_t+s\,\tilde k_t^{\alpha}}{(1+g)(1+n)}
$$

**2. Kako iz (3) dobite (4)?** Na uravnoteženi poti velja $\tilde k_{t+1}=\tilde k_t=\tilde k^{\star}$. Ker je $y=Y/L=A\tilde k^{\alpha}$, sledi še $y^{\star}_t=A_t(\tilde k^{\star})^{\alpha}$.

$$
(1+g)(1+n)\,\tilde k^{\star}=(1-\delta)\tilde k^{\star}+s(\tilde k^{\star})^{\alpha}\;\Rightarrow\;(g+n+gn+\delta)\,\tilde k^{\star}=s(\tilde k^{\star})^{\alpha}\;\Rightarrow\;\tilde k^{\star}=\left(\frac{s}{g+n+gn+\delta}\right)^{\frac{1}{1-\alpha}}
$$

**3. Kako dobite (5)?** $K/Y=\tilde k/\tilde k^{\alpha}=\tilde k^{1-\alpha}$, vanj vstavimo $\tilde k^{\star}$ iz (4). A se pokrajša, zato K/Y od A ni odvisen (pros. 77).

**4. Od kod člen gn?** Čas je diskreten: $(1+g)(1+n)-(1-\delta)=g+n+gn+\delta$. V zveznem času tega člena ni, pri naših parametrih pa je gn = 0,0002 zanemarljiv.

**5. Zakaj s vpliva le na raven?** V enačbi (4) je s samo v konstanti, $y^{\star}$ pa je $A_t$ krat konstanta, zato raste z g. Višji s zviša raven, rast pa je višja le med prilagajanjem.

**6. Zakaj padajoči mejni produkt pomeni konvergenco?** Ker je α < 1, so pri majhnem $\tilde k$ investicije $s\tilde k^{\alpha}$ večje od potrebnih $(g+n+gn+\delta)\tilde k$, zato $\tilde k$ raste; pri velikem $\tilde k$ je obratno.

**7. Kaj je Kaldorjevo dejstvo?** Razmerje med kapitalom in outputom je dolgoročno približno konstantno, okoli 2,2 (Polanec, str. 9). Model ga pojasni z enačbo (5).

### Razčlenitev in simulacija (Jan)

**8. Kako dobite drugi zapis v (6)?** V prvi zapis vstavimo $k=(K/Y)\,y$ in izrazimo y.

$$
y=A^{1-\alpha}\Big(\frac{K}{Y}\Big)^{\alpha}y^{\alpha}h^{1-\alpha}\;\Rightarrow\;y^{1-\alpha}=A^{1-\alpha}\Big(\frac{K}{Y}\Big)^{\alpha}h^{1-\alpha}\;\Rightarrow\;y=A\Big(\frac{K}{Y}\Big)^{\frac{\alpha}{1-\alpha}}h
$$

**9. Kako iz (6) dobite (7)?** Logaritmiramo in vzamemo časovno razliko; razlika logaritmov je približno stopnja rasti.

$$
\ln y_t=\ln A_t+\frac{\alpha}{1-\alpha}\ln\Big(\frac{K}{Y}\Big)_t+\ln h_t\;\Rightarrow\;g_y\approx g_A+\frac{\alpha}{1-\alpha}\,g_{K/Y}+g_h
$$

**10. Zakaj α = 1/3?** Ustreza povprečnemu dohodkovnemu deležu kapitala (pros. 78; Polanec, str. 9 in 23). Drugačen α spremeni le utež pri K/Y; ker je prispevek K/Y po letu 2015 skoraj nič, se sklep ne spremeni.

**11. Zakaj velja $g_A\approx g_{TFP}/(1-\alpha)$?** TFP je $A^{1-\alpha}$, zato je rast TFP enaka $(1-\alpha)g_A$. Razlika do naše ocene (največ 0,26 o. t.) nastane, ker BLS uporablja dejanske deleže stroškov kapitala namesto stalnega α.

**12. Zakaj se pri višjih investicijah (A) rast poveča le za 0,15 o. t.?** Investicije se povečajo za 0,01·Y, kapital v naslednjem letu pa za približno 0,01/2,22 ≈ 0,45 %. BDP se poveča za α krat to, torej za okoli 0,15 %.

**13. Zakaj je pri enkratnem dvigu produktivnosti (B) rast 4,04 %?** Če se A poveča za 3 %, se Y takoj poveča za $1{,}03^{1-\alpha}-1\approx 2$ %, ker se kapital ne prilagodi takoj. Skupaj z običajno 2-odstotno rastjo je to 1,02·1,02 ≈ 1,0404. Po isti logiki podvojitev A takoj poveča BDP za faktor $2^{1-\alpha}\approx 1{,}59$ (pros. 46).

**14. Zakaj se pri trajno višjem g (C) rast takoj poveča za 0,33 o. t.?** V prvem obdobju je kapital dan, zato se rast poveča le prek člena $(AL)^{1-\alpha}$: (1−α)·0,5 ≈ 0,33. Nato se kapital prilagodi in rast se približa 2,5 %. K/Y pade, ker je imenovalec v (5) večji.

**15. Zakaj več R&R (D) ne prinese trajno višje rasti?** Jones (1995) pokaže, da je v pol-endogenem modelu dolgoročna rast odvisna le od parametrov, kot je rast prebivalstva. Višja intenzivnost R&R zato trajno zviša raven A, rast pa le prehodno (pros. 136).

### Rezultati (Miha)

**16. Kaj pomeni, da je A ostanek?** A je vse, česar ne pojasnita K/Y in človeški kapital: tehnologija, pa tudi napake merjenja, izkoriščenost zmogljivosti in prerazporeditev dela. Zato odboj leta 2010 napihne A.

**17. Ali niso naložbe v UI, npr. podatkovni centri, že v kapitalu?** Da, BLS v kapital šteje tudi programsko opremo in R&R. Če bi pospešek izviral iz teh naložb, bi se K/Y povečal, v letih 2023–2025 pa je bil njegov prispevek −0,15 o. t.

**18. Zakaj ne ločite enkratnega dviga produktivnosti, trajno višjega g in več R&R (B, C in D)?** Vse tri v kratkem obdobju dajo višjo rast A, razlikujejo se šele po tem, ali je povečanje trajno. Tri leta podatkov in padec rasti TFP na 0,8 % leta 2025 za to ne zadoščajo.

**19. Zakaj je Acemoglujevih 0,06 v vaših enotah 0,1?** Acemoglu ocenjuje rast TFP. Ker je TFP = $A^{1-\alpha}$, je 0,064/(2/3) ≈ 0,1 o. t. rasti A.

**20. Zakaj je sestava delovne sile leta 2020 poskočila za 2,8 %?** Med pandemijo so delo izgubili predvsem manj izobraženi in slabše plačani delavci, zato se je povprečni človeški kapital zaposlenih povečal. Gre za učinek sestave, ne za hitrejše izobraževanje.

**21. Ali je K/Y v tabeli 4 isto kot v modelu?** Ne povsem. BLS meri kapital s kapitalskimi storitvami, zato je naš K/Y razmerje indeksov. Uporabljamo le njegovo rast, ne ravni, zato razlika do 2,2 iz modela (ali 3–3,5 iz učbenika) ni pomembna.

**22. Kako ste izračunali napovedi +0,28 in +0,03 o. t.?** Povprečna stopnja investicij je bila 15,96 %, 17,84 % in 18,05 % (BEA). Spremembo za 1,88 oziroma 0,21 o. t. pomnožimo z učinkom iz simulacije, 0,15 o. t. na o. t. višjega s. V tabeli 4 so povprečja zaokrožena, zato se razlike med zaokroženimi številkami (1,8 in 0,3) ne ujemajo povsem.

**23. Zakaj model ne napove pospeška rasti?** Ker je g v Solowovem modelu eksogen: model pove, kaj se zgodi pri danem g, ne pa, zakaj se g spremeni. Zato ves pospešek, ki ga ne pojasnita K/Y in človeški kapital, pripiše A. Vir tehnološkega napredka pojasnjuje teorija endogene rasti (pros. 122–128).

### Splošno (Andraž)

**24. Zakaj Solowov model in ne model endogene rasti?** Navodila zahtevajo en model, Solowov pa da preverljivo napoved o K/Y, ki loči investicije od tehnologije. Ne pove, od kod tehnologija, zato kot alternativo dodamo Jonesov pol-endogeni model.

**25. Zakaj BLS za zasebni nekmetijski sektor, delež R&R pa za celotno gospodarstvo?** BLS TFP objavlja za ta sektor; neskladje navajamo med omejitvami. Delež R&R kaže le smer in ne vstopa v izračun razčlenitve.

**26. Ali torej UI nima učinka?** Tega ne trdimo. Pospešek produktivnosti obstaja, s podatki do leta 2025 pa ga ne moremo povezati z UI: ocene so premajhne, časovni potek se ne ujema, enako dobro pa ga pojasni višji delež R&R.
