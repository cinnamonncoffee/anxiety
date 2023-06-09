# act1

```
SceneSetup.act1();
```

(...300)

n: A OVO JE NJENA ANKSIOZNOST

n: _TI_ SI ANKSIOZNOST

{{if window.localStorage.continueChapter=="replay"}}
(#act1_replay)
{{/if}}

{{if window.localStorage.continueChapter!="replay"}}
(#act1_normal)
{{/if}}



# act1_replay

`hong({mouth:"0_neutral", eyes:"0_neutral"})`

h: Ej! Ponovo smo ovde?

`hong({eyes:"0_neutral"})`

n: TVOJ POSAO JE DA ŠTITIŠ SVOJU OSOBU OD *OPASNOSTI*

`bb({eyes:"look", mouth:"small_lock"})`

n: U STVARI, PONOVNO IGRANJE JE DOVODI U *OPASNOST* BAŠ SADA

n: BRZO, UPOZORI IH!

```
sfx("squeak");
bb({body:"squeeze_talk"});
hong({body:"0_squeeze"});
```

b: Osobo! Slušaj, u opasnosti smo! Igrač...

[...će da nas muči ponovo!](#act1_replay_torture)

[...neće naći alternativni kraj!](#act1_replay_alternate)

[...će uvideti ludonarativnu disonancu!](#act1_replay_dissonance)

# act1_replay_torture

```
window.HACK_REPLAY = JSON.parse(localStorage.act4);
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich"});
```

{{if window.HACK_REPLAY.act1_ending=="fight"}}
b: Nateraće nas da se sklupčamo u loptu i plačemo!
{{/if}}

{{if window.HACK_REPLAY.act1_ending=="flight"}}
b: Nateraće nas da ubijemo tvoj telefon jer nam je dao napad panike!
{{/if}}

{{if window.HACK_REPLAY.a2_ending=="fight"}}
b: Nateraće nas da *NE* udarimo domaćina žurke!
{{/if}}

{{if window.HACK_REPLAY.a2_ending=="flight"}}
b: Nateraće nas da udarimo Simpatičnog Anti-Zlikovca domaćina žurke!
{{/if}}

{{if window.HACK_REPLAY.a3_ending=="jump"}}
h: Bar nećemo skočiti sa krova ovog pu--
{{/if}}

{{if window.HACK_REPLAY.a3_ending=="walkaway"}}
b: NATERAĆE NAS DA SKOČIMO SA KROVA.
{{/if}}

`bb({body:"fear"});`

b: DESIĆE NAM SE SVE OVE UŽASNE NOVE STVARI, I ONDA ĆEMO--

(#act1_replay_end)


#act1_replay_alternate

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich"});
```

h: Dobro, priča kao *priča* je ista, ali svako poglavlje ima dva moguća završetka, plus sve opcije dijaloga--

`bb({body:"fear"});`

b: Igrač će biti razočaran, zatvori ovaj prozor, izbriši nam softver, i onda ćemo--

(#act1_replay_end)


# act1_replay_dissonance

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich"});
```

h: Ludo-šta?

`bb({eyes:"normal"});`

b: Poenta priče bila je da možeš da *IZABEREŠ* da izgradiš zdrav odnos sa svojim strahom,

`bb({eyes:"normal_right"});`

b: Ali igranjem igrice ispočetka dobićeš istu priču, što govori da tvoji *IZBORI* nisu važni,

`bb({eyes:"narrow_eyebrow"});`

b: A to prikazuje kontradikciju između poente igre i njene mehanike,

`bb({eyes:"fear"});`

b: A to otkriva realnost ovog narativnog univerzuma,

`bb({body:"fear"});`

b: A onda ćemo--

(#act1_replay_end)


# act1_replay_end

`bb({body:"panic"})`

b: UMRETIIIIII

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
Game.clearText();
```

(...1001)

```
bb({body:"laugh"});
hong({body:"laugh"});
Game.clearText();
sfx("laugh");
```

(...5001)

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({body:"0_sammich"});
```

h: Okej uživimo se u likove ponovo.

```
Game.clearText();
```

n4: (PUSTI _SVOJU_ ANKSIOZNOST BLA BLA BLA NAJSLIČNIJE _SVOM_ STRAHU BLA BLA SVE VEĆ ZNAŠ)

```
sfx("squeak");
hong({body:"0_squeeze"});
bb({body:"squeeze"});
```

(#act1_normal_choice)



# act1_normal

`hong({mouth:"0_neutral", eyes:"0_annoyed"})`

h: O dobro je, moj vuk se vratio. Faaaaantastično.

`hong({eyes:"0_neutral"})`

n: TVOJ POSAO JE DA ČUVAŠ SVOJU OSOBU OD *OPASNOSTI*

`bb({eyes:"look", mouth:"small_lock"})`

n: U STVARI, TAJ SENDVIČ IH STAVLJA U *OPASNOST* BAŠ SADA

n: BRZO, UPOZORI IH!

```
sfx("squeak");
bb({body:"squeeze_talk"});
hong({body:"0_squeeze"});
```

b: Osobo! Slušaj, u opasnosti smo! Opasnost je...

`bb({body:"squeeze"})`

n4: (PUSTI _TVOJU_ ANKSIOZNOST DA DOĐE DO IZRAŽAJA! IZABERI ONO ŠTO JE NAJSLIČNIJE _TVOM_ STRAHU)

(#act1_normal_choice)

# act1_normal_choice

[Jedemo sami na pauzi! Ponovo!](#act1a_alone) `bb({body:"squeeze_talk"})`

[Nismo produktivni dok jedemo!](#act1a_productive) `bb({body:"squeeze_talk"})`

[Taj beli hleb nije dobar za nas!](#act1a_bread) `bb({body:"squeeze_talk"})`

# act1a_alone

```
bb({body:"normal", mouth:"small", eyes:"narrow"});
hong({body:"0_sammich"});
```

b: Znaš li da je usamljenost povezana sa preranom smrću koliko i pušenje 15 cigareta na dan?-

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({mouth:"normal", eyes:"normal_right"})`

b: (Holt-Lunstad 2010, PLoS Medicine)

`hong({eyes:"0_annoyed"})`

h: Ovaj, hvala za citiranje izvora ali--

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({body:"fear", mouth:"normal", eyes:"fear"})`

b: Što znači da ako se ne družimo sa nekim *sada* mi ćemo-

`bb({body:"panic"})`

b: UMRETIIIIIIIIIIII

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("18p", "alone");
publish("hp_show");
```

(...2500)

`_.fifteencigs = true`

n: ISKORIŠĆEN JE *STRAH OD NEVOLJENOSTI*

(#act1b)

# act1a_productive

```
bb({body:"normal", mouth:"small", eyes:"normal"});
hong({body:"0_sammich"});
```

b: Izvuci svoj laptop i počni sa poslom odmah!

`hong({eyes:"0_annoyed"})`

h: Ovaj, ne želim mrvice u svojoj tastat--

```
bb({mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Ako ne doprinosimo društvenom telu onda smo društveni paraziti!

b: Društveno telo će otići kod društvenog doktora po lekove koji će ubiti njegove društvene parazite i onda ćemo--

```
bb({body:"panic", mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: UMRETIIIIIIIIIIIIII

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("18p", "bad");
publish("hp_show");
```

(...2500)

`_.parasite = true`

n: ISKORIŠĆEN JE *STRAH DA SI LOŠA OSOBA*

(#act1b)

# act1a_bread

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich", eyes:"0_annoyed"});
```

h: Da li su ta istraživanja pokaz--

```
bb({body:"fear", mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Prerađena pšenica će pojačati šećer u našoj krvi pa će morati da nam amputiraju udove i onda ćemo-

`bb({body:"panic"})`

b: UMRETIIIIIIIIIII

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("18p", "harm");
publish("hp_show");
```

(...2500)

`_.whitebread = true`

n: ISKORIŠĆEN JE *STRAH OD POVREĐIVANJA*

(#act1b)

# act1b

n: VRLO JE EFEKTIVNO

`bb({mouth:"smile", eyes:"smile"});`

b: Vidiš, osobo? Ja sam tvoj verni vuk-čuvar!

`bb({body:"pride_talk"});`

b: Veruj svojim instinktima! Tvoja osećanja su uvek validna!

`bb({body:"pride"});`

n: SMANJI ENERGIJU SVOJE OSOBE DO NULE

n: DA SAČUVAŠ NJIHOVE FIZIČKE + SOCIJALNE + MORALNE POTREBE, MOŽEŠ DA KORISTIŠ:

n: STRAH OD *POVREĐIVANJA* #harm#

n: STRAH OD *NEVOLJENOSTI* #alone#

n: I STRAH *DA SI LOŠA OSOBA* #bad#

`Game.OVERRIDE_TEXT_SPEED = 1.25;`

n4: (SAVET: BIRAJ IZBORE KOJI POGAĐAJU TVOJE NAJDUBLJE, NAJMRAČNIJE STRAHOVE!~)

h: ...

```
hong({body:"putaway"});
sfx("rustle");
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

(...1000)

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

h: znaš šta vreme je da pogledam u telefon.

```
sfx("rustle2");
hong({body:"phone1", mouth:"neutral", eyes:"neutral"})
```

n: SAČUVAJ SVOJU OSOBU

n: OD SVETA. OD DRUGIH LJUDI. OD NJIH SAMIH.

n: SREĆNO

(...500)

`Game.clearText()`

(...500)

(#act1c)

# act1c

`music('battle', {volume:0.5})`

n: PRVA RUNDA: *BORBA!*

`bb({body:"normal", mouth:"normal", eyes:"normal"});`

h: Ha. Fid na Fejsu kaže da se dešava žurka ovog vikenda.

`bb({eyes:"uncertain"});`

b: Zar taj čudak ne održava žurke *svakog* vikenda?

`bb({eyes:"uncertain_right"});`

b: Koju unutrašnju prazninu pokušavaju da popune! Mora da su duboko zeznuti iznutra!

`hong({eyes:"surprise"});`

h: Takođe, dobila sam poziv?

`bb({eyes:"fear", mouth:"normal"});`

b: Pa onda!

[Reci da, ili ćemo umreti od usamljenosti!](#act1c_loner)

[Reci ne, žurke su pune droga!](#act1c_drugs)

[Ignoriši poziv, samo upropaštavamo žurke.](#act1c_sad)

# act1c_loner

{{if _.fifteencigs}}
b: Petnaest cigareta na dan, osobo! Petnaest!
{{/if}}

{{if !_.fifteencigs}}
`Game.OVERRIDE_TEXT_SPEED = 1.5;`
{{/if}}

{{if !_.fifteencigs}}
b: Onda se niko neće pojaviti na našoj sahrani, baciće naš pepeo u okean, poješće nas kit,
{{/if}}

{{if !_.fifteencigs}}
b: i postaćemo KITOV IZMET!
{{/if}}

{{if !_.fifteencigs}} `_.whalepoop = true` {{/if}}

(...500)

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`bb({eyes:"normal"});`

{{if !_.fifteencigs}}
b: Tako da treba da idemo na žurku!
{{/if}}

{{if _.parasite}}
b: Samo ponesi svoj laptop da možemo da radimo, i ne budemo socijalni parazit.
{{/if}}

{{if _.whitebread}}
b: Sve je okej dok ne služe BELI HLEB
{{/if}}

`hong({mouth:"anger", eyes:"anger"});`

h: GOSPODE. Ako ćeš ućutati, u redu.

h: Reći ću da.

{{if _.whalepoop}}
b: Kitovski izmet, osobo! Kitovski izmet!
{{/if}}

`_.partyinvite="yes"`

(#act1d)

# act1c_drugs

`bb({mouth:"small", eyes:"fear"});`

{{if _.whitebread}}
b: ili još gore... BELOG HLEBA
{{/if}}

{{if _.whitebread}}
`Game.OVERRIDE_TEXT_SPEED = 1.5;`
{{/if}}

{{if _.whitebread}}
b: Toliko ćemo se predozirati na metamfetaminu i belom hlebu da neće moći da stave naš debeli leš u peć za kremiranje!
{{/if}}

{{if !_.whitebread}}
b: Toliko ćemo se predozirati da će se pogrebnik pitati kako je moguće da je naše telo *već* pre-balsamovano!
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

{{if _.parasite}}
b: Pored toga, ne možemo da se zabavljamo, moramo da radimo ili smo užasan socijalni parazit!
{{/if}}

`hong({mouth:"anger", eyes:"anger"});`

h: GOSPODE. Ako ćeš da ućutiš, u redu.

h: Reći ću ne.

`_.partyinvite="no"`

(#act1d)

# act1c_sad

`bb({eyes:"uncertain_right", mouth:"normal"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

{{if _.fifteencigs}}
b: Sve što mi ikada radimo je da plačemo o tome kako je usamljenost smrtonosna koliko i 15 cigareta na dan.
{{/if}}

{{if _.parasite}}
b: Sve što mi ikada radimo na žurkama je da brinemo o tome što treba da budemo produktivni.
{{/if}}

{{if _.whitebread}}
b: Sve što mi ikada radimo je da brinemo o tome kako će nas nezdrava hrana ubiti.
{{/if}}

```
bb({mouth:"normal", eyes:"normal"});
hong({mouth:"neutral", eyes:"lookaway"});
```

h: pa pitam se zašto.

`hong({eyes:"neutral"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

b: Ako odemo učinićemo da se osećaju loše, ali ako odbijemo takođe ćemo učiniti da se osećaju loše!

`bb({body:"fear", eyes:"fear"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

b: SVE ŠTO MI IKADA RADIMO JE DA ČINIMO LJUDE DA SE OSEĆAJU LOŠE, PA TREBA DA SE OSEĆAMO LOŠE

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

`hong({mouth:"anger", eyes:"anger"});`

h: Uh. Ako ćeš da ućutiš, u redu.

h: Ignorisaću poziv.

`_.partyinvite="ignore"`

(#act1d)

# act1d

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"neutral", eyes:"annoyed"});
```

h: Svejedno. Fejs je previše. Treba mi nešto smirenije, nešto sa manje anksioznosti.

`hong({eyes:"neutral"});`

h: Šta je novo na Tviteru?

`bb({eyes:"look"});`

[O ne, pogledaj te užasne vesti!](#act1d_news)

[O ne, da li je taj tvit potajno o *nama*?](#act1d_subtweet)

[Hej, GIF mačke koja pije mleko](#act1d_milk)


# act1d_news

```
bb({eyes:"pained1"});
music(null, {fade:2});
```

b: Čoveče, čini se kao da svet gori, zar ne?

```
bb({eyes:"pained2"});
hong({mouth:"sad", eyes:"sad"});
```

b: Čini se kao da se sve završava, kao da sve umire i osuđeni smo na propast i ne možemo ništa da uradimo.

```
Game.OVERRIDE_TEXT_SPEED = 0.5;
bb({mouth:"shut"});
```

b: ...

`bb({mouth:"smile", eyes:"smile"});`

b: Hajde da retvitujemo to!

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

`_.badnews=true`

```
music('battle', {volume:0.5});
hong({mouth:"anger", eyes:"anger"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Okej retvitovaću samo molim te ćuti!

`hong({mouth:"neutral", eyes:"annoyed"});`

h: Kako god, hajde da vidimo Snepčet.

(#act1e)


# act1d_subtweet

`bb({eyes:"fear"});`

b: To je sabtvit! Lukavi, lukavi sabtvit!

`hong({eyes:"annoyed"});`

h: Verovatno nije?

`bb({eyes:"narrow", mouth:"small"});`

b: ali šta ako svi oni pričaju nama iza leđa

h: Oni su bl--

`bb({body:"fear", eyes:"fear", mouth:"normal"});`

b: ISPRED NAŠIH LEĐA

`hong({eyes:"sad", mouth:"sad"});`

h: Ja sumnj--

`bb({eyes:"narrow", mouth:"small"});`

b: ali *šta ako*

h: S--

`bb({eyes:"narrow_eyebrow"});`

b: *šta ako*

```
Game.OVERRIDE_TEXT_SPEED = 0.5;
hong({mouth:"shut"});
```

h: ...

(...1000)

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`_.subtweet=true`

```
hong({mouth:"anger", eyes:"annoyed"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

h: o-KEJ, probaću Snepčet.

(#act1e)

# act1d_milk

`hong({mouth:"smile", eyes:"neutral"});`

h: Hah da to je slatko, upravo sam retvitovala, misl--

```
hong({mouth:"shock", eyes:"shock"});
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.8;
```

b: MAČKE NE VARE MLEKO I MI SMO UŽASNI ŠTO UŽIVAMO U ZLOSTAVLJANJU ŽIVOTINJA

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
attack("18p", "bad");
```

(...2500)


`_.catmilk=true`

```
hong({mouth:"anger", eyes:"annoyed"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

h: o-KEJ, probaću Snepčet.

(#act1e)

# act1e

`hong({mouth:"neutral", eyes:"neutral"});`

h: Ah, slike od juče uveče. Znači *tako* izgledaju te žurke.

{{if _.partyinvite=="yes"}} (#act1e_said_yes) {{/if}}

{{if _.partyinvite=="no"}} (#act1e_said_no) {{/if}}

{{if _.partyinvite=="ignore"}} (#act1e_said_ignore) {{/if}}

# act1e_said_yes

`hong({mouth:"sad", eyes:"annoyed"});`

h: Uuh, prevelika je gužva za moju anskioznost.

h: Možda nisam trebala da prihvatim poziv?

```
hong({mouth:"neutral", eyes:"neutral"});
bb({mouth:"normal", eyes:"normal"});
```

[Da promenimo odgovor? Kao kreten?!](#act1e_yes_dontchange)

[Hajde da promenimo odgovor! Prevelika je gužva!](#act1e_yes_changetono)

{{if _.subtweet}}
[Da definitivno su nas sabtvitovali.](#act1e_ignore_subtweet)
{{/if}}

{{if _.badnews}}
[Čekaj retvitovali smo bez provere informacija.](#act1e_ignore_factcheck)
{{/if}}

{{if (!_.subtweet && !_.badnews)}}
[Znaš li da imaš jako kriva leđa?](#act1e_ignore_posture)
{{/if}}

# act1e_yes_dontchange

```
bb({eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Računali su na nas a sada izdajemo njihovo poverenje? Da li želiš da umreš sama?!

{{if _.fifteencigs}}
b: PETNAEST. CIGARETA.
{{/if}}

{{if _.whalepoop}}
b: KITOV. IZMET.
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

```
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Umukni umukni neću menjati odgovor!

(#act1f)

# act1e_yes_changetono

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Zar nisi čula za ljudske stampedoe?

```
bb({body:"fear", mouth:"small", eyes:"narrow"});
hong({eyes:"sad", mouth:"sad"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 2003 godine desio se požar u noćnom klubu u Rod Ajlandu i ljudi su zbog panike zaglavili izlaz pa je 100 ljudi izgorelo na smrt-

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({mouth:"shock"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: DA LI HOĆEŠ DA SE TO DESI NAMA-

```
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 2.5;
```

b: RECI NE RECI NE RECI NE RECI NE RECI NE RECI NE RECI NE RECI-


```
bb({body:"normal", eyes:"fear", mouth:"normal"});
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

```
hong({eyes:"anger", mouth:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Umukni umukni promeniću odgovor! Gospode!

(#act1f)

# act1e_said_no

`hong({mouth:"sad", eyes:"sad"});`

h: Hm... to izgleda zabavno.

h: Možda nisam trebala da odbijem poziv?

`bb({mouth:"normal", eyes:"normal"});`

[Da promenimo odgovor? Kao kreten?!](#act1e_no_dontchange)

[Hajde da promenimo odgovor! Nećemo da umremo usamljeni!](#act1e_no_changetoyes)

{{if _.subtweet}}
[Da definitivno su nas sabtvitovali.](#act1e_ignore_subtweet)
{{/if}}

{{if _.badnews}}
[Čekaj retvitovali smo bez provere informacija.](#act1e_ignore_factcheck)
{{/if}}

{{if (!_.subtweet && !_.badnews)}}
[Znaš li koliko su ti kriva leđa?](#act1e_ignore_posture)
{{/if}}

# act1e_no_dontchange

`bb({eyes:"anger"})`

b: Svi su računali na nas!

b: ...da ih ostavimo na miru i pustimo ih da se provedu bez užasnog odvratnog {{if _.whitebread}}white-bread-munching{{/if}} čudaka poput tebe--


```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

```
bb({body:"normal", eyes:"uncertain", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Umukni neću menjati odgovor!

(#act1f)

# act1e_no_changetoyes

```
bb({body:"fear", eyes:"fear", mouth:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Hronična usamljenost povećava naš nivo kortizola i rizik za kardiovaskularnu bolest i infarkt!

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

{{if _.fifteencigs}}
b: PETNAEST. CIGARETA.
{{/if}}

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Umukni umukni promeniću moj odgovor! Gospode!

(#act1f)

# act1e_ignore_subtweet

```
bb({eyes:"fear", mouth:"small"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Svi naši problematični tvitovi dovešće nas u problem!

```
bb({body:"fear", eyes:"fear", mouth:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.7;
```

b:Prozivaće nas i cancelovati i vući konopcem na konju niz informacioni superautoput!

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Zašto si ovakav?!

(#act1f)

# act1e_ignore_factcheck

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Širimo dezinfromacije! Rušimo poverenje u slobodne medije!

```
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Mi smo razlog što će se fašizam preporoditi iz slomljene demokratije!

```
bb({body:"normal", eyes:"anger"});
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

```
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
_.factcheck = true;
```

h: Zašto si ovakav?!

(#act1f)

# act1e_ignore_posture

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Hoćeš da ti kičma bude kao kifla? Prestani da se grbiš!

```
bb({body:"meta"});
```

b: Ti takođe.

```
bb({body:"normal", mouth:"normal"});
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Zašto si ovakav?!

(#act1f)

# act1e_said_ignore

`hong({mouth:"sad", eyes:"sad"});`

h: Hm... to izgleda baš zabavno.

h: Možda ne treba da ignorišem poziv?

`bb({mouth:"normal", eyes:"normal"});`

[Ma samo ignoriši, još uvek smo parti-brejkeri.](#act1e_ignore_continue)

[Zapravo, reci da.](#act1e_ignore_changetoyes)

[Zapravo, reci ne.](#act1e_ignore_changetono)

# act1e_ignore_continue

`hong({eyes:"annoyed"});`

h: Nekako je bezobrazno da ih ignorišemo, zar ne?

`bb({eyes:"normal_right"});`

b: Mislim odstali ljudi uvek ignorišu *nas*, pa

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`bb({eyes:"normal"});`

b: pa sad ste kvit.

(#act1f)

# act1e_ignore_changetoyes

`hong({eyes:"surprise", mouth:"smile"});`

h: Ti me... puštaš da se zabavim?

b: Pa, mislim, usamljenost *može* da nas ubije.

`hong({eyes:"neutral", mouth:"neutral"});`

(#act1e_no_changetoyes)

# act1e_ignore_changetono

`bb({eyes:"narrow"});`

b: Prevelika je gužva. Gužve su opasne.

(#act1e_yes_changetono)


# act1f

```
hong({mouth:"neutral", eyes:"neutral"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

h: Kako god. Nova Tinder notifikacija.

`bb({eyes:"uncertain"})`

b: Šta, ta aplikacija za kombinacije?

`hong({eyes:"annoyed"})`

h: Nije to aplikacija za kombinacije, to je način da upoznaš nove lj--

`bb({eyes:"narrow"})`

b: To je aplikacija za kombinacije.

```
hong({eyes:"surprise", mouth:"smile"});
bb({eyes:"normal"});
```

h: O, imam podudaranje! Slatki su!

```
bb({eyes:"narrow_eyebrow"});
hong({eyes:"sad", mouth:"anger"})
```

h: Molim te nemoj i ovo da un--

```
bb({body:"panic"});
Game.OVERRIDE_TEXT_SPEED = 2.0;
```

b: OPASNOST OPASNOST OPASNOST OPASNOST OPASNOST

`bb({body:"fear", eyes:"fear", mouth:"normal"})`

[Drugi ljudi nas *iskorišćavaju*.](#act1f_used_by_others)

[Mi *iskorišćavamo* druge ljude.](#act1f_using_others)

[TAJ LIK JE SERIJSKI UBICA](#act1f_killer)

# act1f_used_by_others

`bb({body:"point_crotch", eyes:"normal", mouth:"normal"})`

b: Kombinacije možda mogu da popune rupu dole,

b: ali nikada neće moći da popune rupu...

`bb({body:"point_heart", eyes:"pretty", mouth:"small"})`

b: *ovde*.

(...1000)

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Poenta je DA ĆEMO DA UMREMO SAMI

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`_.hookuphole=true`

(#act1g)

# act1f_using_others

`bb({eyes:"narrow", mouth:"small"})`

b: Miliš li da su genitalije drugih ljudi Pokemoni da ih mi sakupljamo?

```
bb({body:"sing", eyes:"pretty", mouth:"shut"});
music("pokemon");
Game.clearText();
Game.FORCE_CANT_SKIP = true;
```

```
Game.FORCE_TEXT_DURATION = 1000;
Game.FORCE_NO_VOICE = true;
```

b: ♫ (pokemon theme song)-

(...5600)

```
bb({mouth:"normal"});
Game.FORCE_TEXT_DURATION = 2400;
```

b: ♫ Želim da budem, naj^kurvas^tiji-

(...500)

```
bb({eyes:"narrow", mouth:"small"});
Game.FORCE_TEXT_DURATION = 2100;
```

b: ♫ Kao niko pre mene-

(...1500)

```
bb({eyes:"pretty"});
Game.FORCE_TEXT_DURATION = 2300;
```

b: ♫ Butine i ^dupe^, sladostrasne grudi-

(...500)

```
bb({eyes:"fear", mouth:"normal"});
Game.FORCE_TEXT_DURATION = 2000;
```

b: ♫ sa znojavim ^kurcem^ i jajima!-

(...1000)

```
bb({eyes:"smile", mouth:"smile"});
Game.FORCE_TEXT_DURATION = 1000;
```

b: ♫ PERVO-MON! MORAM IH SVE-

```
Game.FORCE_CANT_SKIP = false;
Game.clearText();
music(false);
bb({body:"normal", mouth:"normal", eyes:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Poenta je da smo mi manipulativni čudak.

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

`_.pokemon=true`

(#act1g)

# act1f_killer

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

{{if _.whitebread}}
b: They'll trap you in a well and force-feed you white bread to fatten you up so they can wear your skin like a suit!
{{/if}}

{{if _.parasite}}
b: They'll bludgeon you with a pomodoro timer and say "YOU SHOULDA BEEN MORE PRODUCTIVE YOU PARASITE"
{{/if}}

{{if !_.whitebread && !_.parasite}}
b: They'll tear your flesh to gory confetti, turn your entrails into streamers, and mix your blood into a punch bowl!
{{/if}}

{{if !_.whitebread && !_.parasite}}
b: How's THAT for a party invite?!
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

`_.serialkiller=true`

(#act1g)

# act1g

```
bb({body:"normal", mouth:"normal", eyes:"look"});
hong({body:"2_tired"});
Game.OVERRIDE_TEXT_SPEED = 0.5;
music(false);
```

h: ...

(...500)

h: i'm so sick of this game.

(...700)

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

h:
{{if _.fifteencigs}}"loneliness will kill us"... {{/if}}
{{if _.parasite}}"we're a society-parasite"... {{/if}}
{{if _.whitebread}}"don't eat that, it'll kill us"... {{/if}}
{{if _.subtweet}}"they're talking behind our back"... {{/if}}
{{if _.badnews}}"the world is burning"... {{/if}}
{{if _.hookuphole}}"we'll die alone"... {{/if}}
{{if _.serialkiller}}"they're a serial killer"... {{/if}}
{{if _.catmilk}}"cats can't digest milk"... {{/if}}
{{if _.pokemon}}a ^crappy^ parody song... {{/if}}

h: i just want to live my life.

h: i just want to be free from all this... pain.

`bb({eyes:"look_sad"});`

b: Hey... human...

`Game.OVERRIDE_TEXT_SPEED = 0.5;`

b: It'll be okay.

(...600)

`bb({body:"point_heart", eyes:"look_sad_smile", mouth:"smile"});`

b: As your loyal guard-wolf, I'll always keep an eye out for danger, and do my best to keep you safe.

`bb({body:"normal", eyes:"look_sad", mouth:"smile"});`

b: I promise.

(...600)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({body:"phone1", eyes:"neutral", mouth:"neutral"});
```

h: Last app. Instagram. What you got?

`hong({eyes:"sad"});`

h: It's... more party pictures.

`hong({mouth:"sad"});`

h: Everyone looks so happy. Free from worry. Free from anxiety.

`hong({mouth:"anger"});`

h: God, why can't I be like them? Why can't I just be *normal?*

`bb({eyes:"normal_right"});`

b: Speaking of parties, about this weekend's invite. Here's my FINAL decision:

`bb({eyes:"normal"});`

[We should go.](#act1g_go) `Game.OVERRIDE_CHOICE_LINE=true`

[We should not go.](#act1g_dont) `Game.OVERRIDE_CHOICE_LINE=true`

# act1g_go

`_.act1g = "go"`

(#act1h)

# act1g_dont

`_.act1g = "dont"`

(#act1h)

# act1h

b: We sh--

```
bb({eyes:"wat", mouth:"small"});
hong({body:"2_fuck"});
```

h: *^FUCK^.*

`hong({body:"2_you"});`

h: YOU.

(...500)

b: w

(...1500)

`bb({eyes:"wat_2"});`

b: wha?

`hong({body:"phone1", eyes:"anger", mouth:"anger"});`

h: I'm going to say YES to that party,

{{if _.act1g=="go"}}
h: NOT because you want me to, but because *I* want to.
{{/if}}

{{if _.act1g=="dont"}}
h: Precisely BECAUSE you don't want me to.
{{/if}}

```
hong({body:"putaway"});
sfx("rustle");
```

h: You're NOT in control of me.

```
sfx("rustle2");
hong({body:"0_sammich", eyes:"0_annoyed", mouth:"0_neutral"});
```

h: Now excuse me while I eat this delicious sandwich in ^goddamn^ peace.

`hong({body:"2_sammich_eat"});`

(...601)

```
sfx("sandwich");
hong({body:"2_sammich_eaten", eyes:"0_lookaway", mouth:"0_chew1"})
```

(...601)

```
bb({body:"normal", eyes:"uncertain", mouth:"shut"});
Game.OVERRIDE_TEXT_SPEED = 0.5;
```

b: ...

```
bb({eyes:"normal_right"});
Game.OVERRIDE_TEXT_SPEED = 1;
```

b: ...

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 4;
```

b: ..................

(...500)

`bb({mouth:"normal"});`

[AHHHH WE'RE GONNA DIE](#act1h_death) `Game.OVERRIDE_CHOICE_LINE = true;`

[AHHHH EVERYONE HATES US](#act1h_loneliness) `Game.OVERRIDE_CHOICE_LINE = true;`

[AHHHH WE'RE HORRIBLE PEOPLE](#act1h_worthless) `Game.OVERRIDE_CHOICE_LINE = true;`

# act1h_death

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: AHHHH WE'RE GONNA DIE AAAAAAHHHHHHH

```
hong({body:"3_defeated1"});
attack("100p", "harm");
```

(...2500)

(#act1i)

# act1h_loneliness

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: AHHHH EVERYONE HATES US AAAAAAHHHHHHH

```
hong({body:"3_defeated1"});
attack("100p", "alone");
```

(...2500)

(#act1i)

# act1h_worthless

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: AHHHH WE'RE HORRIBLE PEOPLE AAAAAAHHHHHHH

```
hong({body:"3_defeated1"});
attack("100p", "bad");
```

(...2500)

(#act1i)

# act1i

```
bb({mouth:"smile_lock", eyes:"smile", body:"normal"});
music('battle', {volume:0.5});
```

n: CONGRATULATIONS

(...500)

n: YOU'VE SUCCESSFULLY PROTECTED YOUR HUMAN'S PHYSICAL + SOCIAL + MORAL NEEDS

n: WHY, LOOK HOW GRATEFUL THEY ARE!

(...500)

n: NOW THAT THEIR ENERGY IS ZERO, YOU CAN DIRECTLY CONTROL THEIR ACTIONS

`bb({mouth:"smile", eyes:"normal"});`

n: PICK YOUR ENDING MOVE

`bb({mouth:"small_lock", eyes:"fear"});`

n: *FINISH THEM*

[{FIGHT: Punish your stressful phone!}](#act1i_phone) `Game.OVERRIDE_CHOICE_LINE=true`

[{FLIGHT: Curl up in a ball and cry!}](#act1i_cry) `Game.OVERRIDE_CHOICE_LINE=true`

# act1i_phone

`bb({mouth:"normal", eyes:"narrow"})`

b: Your phone was giving you a panic attack!

`bb({eyes:"anger"})`

b: Zuckerberg and Co are hijacking your mental health for venture capitalist money!

```
bb({body:"fear", eyes:"fear"});
hong({body:"3_defeated2"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Punish your phone! Destroy it! Kill it!

```
Game.OVERRIDE_TEXT_SPEED = 2.5;
bb({body:"flail"});
hong({body:"3_defeated3"});
_.act1_ending = "fight";
```

b: KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL I--

(#act1j)

# act1i_cry

`bb({eyes:"fear", mouth:"normal"})`

b: The whole world is filled with danger!

```
bb({body:"fear"});
hong({body:"3_defeated2"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Do like the armadillo! Curl up into a ball for self-defense!

```
Game.OVERRIDE_TEXT_SPEED = 2.5;
bb({body:"flail"});
hong({body:"3_defeated3"});
_.act1_ending = "flight";
```

b: CURL UP AND CRY CURL UP AND CRY CURL UP AND CRY CURL UP AND CRY CURL UP AND CRY CURL UP AND CR-- 

(#act1j)

# act1j

`SceneSetup.act1_outro()`
