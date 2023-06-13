# act2

`SceneSetup.act2();`

{{if _.badnews && !_.factcheck}}
(#act2-preamble-news1)
{{/if}}

{{if _.badnews && _.factcheck}}
(#act2-preamble-news2)
{{/if}}

{{if _.catmilk}}
(#act2-preamble-cat)
{{/if}}

(#act2-preamble-tinder)


# act2-preamble-news1

```
publish("act2",["dee",3]);
```

s: Ali jeste li *videli* te "vesti" o užasnoj stvari koja se desila negde?

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: ć-ćao...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",3]);
```

a: Gospode koliko mrzim vesti. Sve je senzacionalizam i klikbejt.

```
publish("act2",["dum",2]);
publish("act2",["party_hong","next"]);
```

h2: s... super žurka...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",1]);
```

s: Da, ali oni samo prate podsticaje. *Pravi* problem su ljudi koji kliknu na klikbejt.

```
publish("act2",["dee",3]);
```

s: Ko bi retvitovao užasne vesti i učinio svoje prijatelje da se osećaju loše?

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Uh, znam, zar ne?

(#act2-preamble-end)


# act2-preamble-news2

```
publish("act2",["dee",3]);
```

s: Ali jeste li *videli* te "vesti" koje su postale viralne?

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: ć-ćao...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",3]);
```

a: Da, skroz su lažne. Ko bi pao na to i retvitovao?

```
publish("act2",["dum",2]);
publish("act2",["party_hong","next"]);
```

h2: s... super žurka...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Ozbiljno druže. Kao, halo, otvori taj Gugl i proveri činjenice prvo?

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Uh, znam, zar ne?

(#act2-preamble-end)


# act2-preamble-cat

```
publish("act2",["dee",3]);
```

s: Kao što sam rekla, Industrijski Kompleks Mimova eksploatiše mačke.

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: ć-ćao...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",1]);
```

a: Objasni tu tvrdnju.

```
publish("act2",["dum",0]);
publish("act2",["party_hong","next"]);
```

h2: s... super žurka...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",1]);
```

s: Pa, juče sam videla da je neko retvitovao GIF mačke koja pije mleko.

```
publish("act2",["dee",3]);
```

s: One ne mogu da svare to ^sranje^! Ko bi retvitovao *zlostavljanje životinja*?

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Uh, znam, zar ne?

(#act2-preamble-end)


# act2-preamble-tinder

```
publish("act2",["dee",1]);
```

s: Tako da mi nikada nije odgovorila!

```
publish("act2",["dee",0]);
publish("act2",["party_hong","next"]);
```

h2: ć-ćao...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",1]);
```

a: Iako ste se uparili na Tinderu?

```
publish("act2",["dum",0]);
publish("act2",["party_hong","next"]);
```

h2: s... super žurka...

```
publish("act2",["party_hong","next"]);
```

{{if _.serialkiller}}
(#act2-preamble-serialkiller)
{{/if}}

{{if _.hookuphole}}
(#act2-preamble-hookuphole)
{{/if}}

{{if _.pokemon}}
(#act2-preamble-pokemon)
{{/if}}

# act2-preamble-serialkiller

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Da, ne razumem! Šta, jel' mislila da sam *serijski ubica* ili tako nešto? Kakva paranoja.

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Uh, znam, zar ne?

(#act2-preamble-end)


# act2-preamble-hookuphole

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Da, ne razumem! Možda misli da kombinacije ne mogu da popune rupu u njenom srcu?

s: Prestani da budeš toliko čedna! Raširi um, raširi noge!

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Uh, znam, zar ne?

(#act2-preamble-end)


# act2-preamble-pokemon

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Da, ne razumem! Nije toliko lepa, ali je dobar ulov!

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Uhvati Ih Sve!™

(#act2-preamble-end)


# act2-preamble-end

```
Game.clearText();
publish("act2-out-1");
music(null, {fade:1});
```

(...3000)

```
music('battle', {volume:0.5});
publish("hp_show");
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

n: DRUGA RUNDA: *BORBA!*

[O ne svi nas mrze!](#act2a_social)

[Jesi li ti to *buljila* u crvenokosu?](#act2a_perv)

[Ej, hajde da pričamo o smislu života.](#act2a_meaning)

# act2a_social

`bb({eyes:"sad"})`

b: Uništavamo raspoloženje ove žurke jer smo tužna gruda!

`bb({eyes:"shock", body:"two_up"})`

b: Ubijamo dobre vibracije! Izvršavamo ubistvo vibracija prvog stepena!

`bb({eyes:"normal", body:"normal"})`

b: Osobo, moramo da idemo *sada* pre nego--

```
_.a2_first_danger = 'social';
_.a2_attack_1 = "alone";
```

(#act2b)

# act2a_perv

`bb({eyes:"suspect"})`

b: Mnogo je atraktivnija od nas, što znači da ako i samo *pogledamo* u nju--

`bb({eyes:"shock", body:"two_up"})`

b: MI SMO ČUDACI

`bb({body:"normal"})`

b: Mi smo čudni, zli, loši loši loši odvratni odvratni perv--

```
_.a2_first_danger = 'perv';
_.a2_attack_1 = "bad";
```

(#act2b)

# act2a_meaning

`bb({body:"one_up", eyes:"normal_r"})`

b: Kad se sve završi, šta važno uopšte možemo uraditi? 

`bb({body:"normal", eyes:"sad"})`

b: Doprineti čovečanstvu? Sva velika dela propadaju put Ozimandije. Ljubav? Smrt će uvek uraditi ono što mora.

`bb({eyes:"sad_r"})`

b: I koliko samo smrti ima! *Mi* ćemo umreti. *Oni koje volimo* će umreti.

`bb({eyes:"shock", body:"two_up"})`

b: Mislim, Drugi Zakon Termodinamike govori da će čak i naš *univerzum* umreti!

`bb({eyes:"suspect", body:"normal"})`

b: O, "zbog smrti cenimo život"? To je kao da kažeš da je ropstvo dobro jer zbog njega cenimo slobodu!

`bb({body:"one_up"})`

b: O, "treba da nađeš svoj sopstveni smisao"? To rade kultisti i teoretičari zavera!

`bb({eyes:"shock", body:"two_up"})`

b: Život nema smisao, smrt nema smisao, čak ni *smisao* nema smisao! Šta smrtna duša treba da--

```
_.a2_first_danger = 'meaning';
_.a2_attack_1 = "bad";
```

(#act2b)

# act2b

`bb({eyes:"normal", mouth:"normal", body:"normal", MOUTH_LOCK:true})`

b: ...

`bb({eyes:"suspect"})`

b: Ovaj... čuješ li me, osobo?

`bb({eyes:"normal", MOUTH_LOCK:true})`

b: ...

`bb({eyes:"shock", mouth:"small_talk", body:"chest", MOUTH_LOCK:true})`

b: *AH*

`bb({mouth:"small_talk"})`

b: MORAM DA TE UPOZORIM O...

[*Još* takve opasnosti!](#act2b_louder)

{{if _.a2_first_danger=="social"}}
[*Drugačijoj* socijalnoj opasnosti!](#act2b_different_social)
{{/if}}

{{if _.a2_first_danger=="perv" || _.a2_first_danger=="meaning"}}
[*Drugačijoj* moralnoj opasnosti!](#act2b_different_moral)
{{/if}}

[Ignorišeš opasnost! To je opasno!](#act2b_ignore)

# act2b_louder

`_.a2_first_choice = "louder"`

{{if _.a2_first_danger=="social"}}
(#act2b_louder_social)
{{/if}}

{{if _.a2_first_danger=="perv"}}
(#act2b_louder_perv)
{{/if}}

{{if _.a2_first_danger=="meaning"}}
(#act2b_louder_meaning)
{{/if}}

# act2b_louder_social

`bb({eyes:"shock", body:"two_up", mouth:"normal"})`

b: EMOCIJE SU ZARAZNE! AKO NE ODEŠ SVE ĆEŠ ZARAZITI SA SVOJOM MENTALNOM BOLEŠĆU! 

b: Stvorićeš smrtonosnu pandemiju SINDROMA TUŽNE GRUDE

`bb({eyes:"suspect", body:"normal", mouth:"normal"})`

b: Moramo da odemo odavde i zatvorimo se u karantin u maloj sobi sa Netfliksom i dostavom!

```
_.a2_second_danger = 'netflix';
_.a2_attack_2 = "alone";
_.a2_hoodie_callback = "karantinu";
```

(#act2c)

# act2b_louder_perv

`bb({eyes:"suspect", body:"two_up", mouth:"normal"})`

b: NEMOJ BITI ČUDAK. PROTIVZAKONITO JE!

`bb({eyes:"judge", body:"judge_1", mouth:"normal"})`

(...201)

```
bb({body:"judge_2"}, 0);
sfx("gravel");
```

(...168)

`bb({body:"judge_1"}, 0)`

(...168)

`bb({body:"judge_2"}, 0)`

(...168)

`bb({body:"judge_1"}, 0)`

(...501)

b: Zakon o Čudacima, Član 74.5: (1) Bilo koja Osoba koja bulji u (a) ta mišićava ramena (b) tu definisanu zadnjicu (2) će nadalje biti poznata kao

`bb({eyes:"shock", body:"two_up", mouth:"normal"})`

b: "VELIKI ODVRATNI SMEĆARSKI PERVEZNJAK"

```
_.a2_second_danger = 'law';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "zakonu";
```

(#act2c)

# act2b_louder_meaning

`bb({body:"two_up", mouth:"normal", eyes:"shock"})`

b: Zapravo, čak i da nađeš plemenitu svrhu u životu, *još uvek* možeš sve da zezneš!

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Alfred Nobel želeo je mir u svetu i da se kulture međusobno razumeju. Pa je odlučio da olakša putovanja.

`bb({eyes:"normal_r"})`

b: Trebao mu je jeftiniji način za građenje tunela za vozove. Napravio je novi materijal "dinamit"...

`bb({body:"one_up", eyes:"normal"})`

b: koji je u Prvom svetskom ratu korišćen za ubistvo MILIONA LJUDI

`bb({body:"two_up", eyes:"shock"})`

b: TO JE EFEKAT LEPTIRA, OSOBO! KOLIKO LJUDI TRENUTNO SLUČAJNO UBIJAŠ

```
_.a2_second_danger = 'butterfly';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "Prvom svetskom ratu";
```

(#act2c)

# act2b_different_social

`_.a2_first_choice = "different"`

`bb({eyes:"normal_r", body:"point", mouth:"normal"})`

b: Zapravo, znaš šta je gore od toga da te niko ne voli? da te *svi* vole.

`bb({body:"one_up", eyes:"suspect", mouth:"normal"})`

b: To je to, postaješ jedna od *ovih* životinja gladnih za zabavom.

`bb({body:"normal", mouth:"small"})`

b: Površan život sa površnim prijateljima koji poznaju samo površnog tebe!

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: Osobo, moramo da bežimo od ovih zombija za zabave pre nego što nas pretvore u jednog od njih!

```
_.a2_second_danger = 'zombies';
_.a2_attack_2 = "alone";
_.a2_hoodie_callback = "zombijima";
```

(#act2c)

# act2b_different_moral

`_.a2_first_choice = "different"`

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: Ljudi umiru od gladi i u genocidima *upravo sada*, a mi se zabavljamo!

`bb({body:"point", eyes:"closed", mouth:"small"})`

b: Mudra osoba je jednom rekla, "jedina stvar neophodna za pobedu zla je da dobar narod ne radi ništa."

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: MI NE RADIMO NIŠTA.

`bb({mouth:"small"})`

b: ZABAVLJANJEM POMAŽEMO *HITLERU*.

```
_.a2_second_danger = 'hitler';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "Hitleru";
```

(#act2c)

# act2b_ignore

`_.a2_first_choice = "ignore"`

`bb({body:"normal", mouth:"normal", eyes:"suspect"})`

b: Misliš li da si sigurna samo zato što si izvadila baterije iz detektora ugljenik monoksida?

`bb({eyes:"suspect_r"})`

b: Nećeš ni namirisati otrov! Samo će ti se prispavati i onda ćeš--

`bb({body:"scream_c_1"})`

b: UMRETIIIIIIIIIIIIIII

```
_.a2_second_danger = 'ignore';
_.a2_attack_2 = "harm";
_.a2_hoodie_callback = "ugljenik-monoksidu";
```

(#act2c)

# act2c

```
hong({body:"ignore_sweat"});
bb({eyes:"normal", mouth:"normal", body:"normal", MOUTH_LOCK:true});
```

b: ...

`bb({eyes:"happy", mouth:"smile", body:"chest"})`

b: O, dobro je, osobo, mislim da me ponovo čuješ!

`bb({eyes:"closed", body:"point"})`

b: UPOZORIĆU TE O...

{{if _.a2_first_choice=="louder"}}
[*Još više* takve opasnosti!](#act2c_louder)
{{/if}}

{{if _.a2_first_choice!="louder"}}
[*Još* takve opasnosti!](#act2c_louder)
{{/if}}

{{if _.a2_first_danger=="social"}}
[*Drugačijoj* socijalnoj opasnosti!](#act2c_different_social)
{{/if}}

{{if _.a2_first_danger=="perv" || _.a2_first_danger=="meaning"}}
[*Drugačijoj* moralnoj opasnosti!](#act2c_different_moral)
{{/if}}

[Da li si proverila taj punč pre nego što si ga popila?](#act2c_punch)

#act2c_louder

{{if _.a2_second_danger=="netflix"}}
(#act2c_louder_netflix)
{{/if}}

{{if _.a2_second_danger=="law"}}
(#act2c_louder_law)
{{/if}}

{{if _.a2_second_danger=="butterfly"}}
(#act2c_louder_butterfly)
{{/if}}

{{if _.a2_second_danger=="zombies"}}
(#act2c_louder_zombies)
{{/if}}

{{if _.a2_second_danger=="hitler"}}
(#act2c_louder_hitler)
{{/if}}

{{if _.a2_second_danger=="ignore"}}
(#act2c_louder_ignore)
{{/if}}

# act2c_louder_netflix

`bb({body:"normal", mouth:"normal", eyes:"shock"})`

b: U stvari, Netfliks i dostava nisu dovoljno izolovani! Još uvek ćemo zaraziti dostavljača!

`bb({body:"one_up", mouth:"small"})`

b: Moramo da se preselimo na teritoriju kanadskog Jukona i tražiti da nam dostave hranu dronom!

`bb({body:"two_up", mouth:"normal"})`

b: I onda će morati da sterilišu dron da ga očiste od VIRUSA TUŽNE GRUDE

`_.a2_attack_3 = "alone";`

`_.a2_hoodie_callback = "karantinu";`

(#act2d)

# act2c_louder_law

`bb({eyes:"judge", body:"judge_1", mouth:"normal"})`

(...201)

```
bb({body:"judge_2"}, 0);
sfx("gravel");
```

(...168)

`bb({body:"judge_1"}, 0)`

(...168)

`bb({body:"judge_2"}, 0)`

(...168)

`bb({body:"judge_1"}, 0)`

(...501)

b: VELIKI ODVRATNI SMEĆARSKI PERVEZNJAK biće osuđen na 72 sata u jednoj od onih srednjovekovnih sprava za javno ponižavanje

b: osim ako tajno *voli* takve stvari

`bb({body:"scream_a_1"})`

b: zato što je VELIKI ODVRATNI SMEĆARSKI PERVEZNJAK

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "zakonu";`

(#act2d)

# act2c_louder_butterfly

`bb({body:"normal", mouth:"small", eyes:"suspect"})`

b: EFEKAT LEPTIRA! Ne koristiš biorazgradivu plastičnu čašu?

`bb({body:"two_up", mouth:"normal", eyes:"shock"})`

b: BAM, DEPONIJA ISPUSTI OTROV I UBIJE DETE

`bb({body:"normal", mouth:"small", eyes:"suspect"})`

b: Znojiš se i srce ti lupa?

`bb({body:"scream_a_1"})`

b: BAM, BANKROTIRAŠ NAŠ ZDRAVSTVENI SISTEM I MILIONI UMRU

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "efektu leptira";`

(#act2d)

# act2c_louder_zombies

`bb({body:"normal", mouth:"small", eyes:"angry"})`

b: Ti zombiji za zabave će da se dogegaju do tebe mumlajući,

`bb({body:"normal", mouth:"normal", eyes:"shock"})`

b: LAAAAJKOVI. LAAAAAAAJKOVI.

`bb({body:"scream_a_1"})`

b: Onda će te UGRISTI i pretvoriti te u BRATA BEZ MOZGA i/ili KUJU BEZ NEVINOSTI!

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "zombijima";`

(#act2d)

# act2c_louder_hitler

`bb({body:"scream_a_1"})`

b: NACISTI SE ŠETKAJU ULICAMA TRENUTNO

`bb({body:"one_up", mouth:"smile", eyes:"happy"})`

b: Govoreći, *dobro je što je taj 'dobar narod' trošio vreme na 'opuštanje' i 'brigu o sebi'!*

`bb({body:"point", mouth:"smile", eyes:"happy_r"})`

b: *Gut, naši planovi se mogu nastaviti!*

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "Hitleru";`

(#act2d)

# act2c_louder_ignore

`bb({body:"normal", mouth:"normal", eyes:"normal_r"})`

b: Kad bolje razmislim, da li zasigurno znamo da ova zgrada *ima* detektor monoksida?!

`bb({body:"two_up", mouth:"small", eyes:"normal"})`

b: Šta ako se svi trujemo *UPRAVO SADA?*

`bb({body:"scream_a_1"})`

b: NE BISMO NI PRIMETILI DA SE SMRT PRIBLIŽAVA. SAMO BISMO NESTALI ZAUVEK ZAUVEK ZAU-

`_.a2_attack_3 = "harm";`

`_.a2_hoodie_callback = "ugljenik-monoksidu";`

(#act2d)

# act2c_different_social

`bb({body:"normal", mouth:"normal", eyes:"sad"})`

b: Šta ako je *u potpunosti nemoguće* da nas iko ikada voli, ili da mi volimo nekoga?

`bb({body:"normal", mouth:"small", eyes:"sad_r"})`

b: Šta ako je nešto u nama još odavno nepovratno izgubljeno? Ili jednostavno nikada nije ni postojalo?

`bb({body:"scream_a_1"})`

b: AAA MI SMO UNIŠTENI! SKROZ SLOMLJENI SKROZ SLOMLJ-

`_.a2_attack_3 = "alone";`

(#act2d)

# act2c_different_moral

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Šta ako smo jednostavno *nepopravljivo pokvareni?*

`bb({body:"one_up", eyes:"sad"})`

b: Ostale psiha vuče da čine dobro, ali jedino "dobro" koje mi pronalazimo je krivica ili stid.

`bb({body:"normal", mouth:"small", eyes:"sad_r"})`

b: Šta je u našoj prirodi slomljeno da želimo da povređujemo druge? Šta ako ne možemo biti bilo šta drugo sem *tereta* našim najbližima?

`bb({body:"scream_a_1"})`

b: AAA MI SMO UNIŠTENI! SKROZ SLOMLJENI SKROZ SLOMLJ-

`_.a2_attack_3 = "bad";`

(#act2d)

# act2c_punch

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Nisam iracionalan. Ljudi *stvarno* ubacuju drogu u punč. To je realna stvar koja se realno događa.

`bb({eyes:"suspect"})`

b: Osobo, da li te boli glava? Da li su ti udovi mlitavi? Mislim da umiremo.

`bb({body:"scream_a_1"})`

b: AAAAA MI UMIREMO! UMIREMO UMIREMO UMIREMO UMIR--

`_.a2_attack_3 = "harm";`

`_.a2_hoodie_callback = "činijama punča";`

(#act2d)

# act2d

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({body:"attacked"});
attack("20p", _.a2_attack_1);
```

(...401)

```
hong({body:"attacked_2"});
attack("20p", _.a2_attack_2);
```

(...401)

```
hong({body:"attacked_3"});
attack("20p", _.a2_attack_3);
```

(...1001)

h: S^RAANJE^!

h: S^RANJE^ S^RANJE^ S^RANJE^ *S^RAANJE^*

`bb({body:"two_up", mouth:"smile", eyes:"happy"});`

b: Hej, osobo! Drago mi je što me ponovo čuješ!

`bb({body:"normal", mouth:"small", eyes:"sad"})`

b: Zašto si me ignorisala?

`hong({body:"facepalm"})`

h: Kako misliš zašto, ti ^jebeni^ moronu?

`hong({body:"facepalm_2"})`

h: Znaš li onu priču američkih starosedelaca?

h: "Postoje dva vuka u tebi, jedan je nada, drugi je očaj, koji će pobediti? Onaj kog hraniš."

```
hong({body:"facepalm_3"});
bb({eyes:"normal"});
```

h: *Izgladnjavala* sam te, sadistični ^šupku^!

`hong({body:"smile", mouth:"smile"})`

h: ^Jebeš^ to, probaću pozitivne afirmacije.

h: *Ja sam voljena. Ja sam dobra. Ja sam pametna. Ja sam lepa. Ja sam specijalna.*

`bb({eyes:"suspect"});`

[Čoveče, to je tako narcisoidno!](#act2d_narcissist)

[Znaš li da su *opovrgnuli* afirmacije?](#act2d_disproven)

[omg ne pripisuj nasumične priče domorodačkom narodu](#act2d_racist)

# act2d_disproven

`bb({body:"point", mouth:"normal", eyes:"closed"})`

b: U stvari, one *odmažu* ljudima sa niskim samopouzdanjem! 

`bb({body:"one_up", mouth:"small", eyes:"normal"})`

b: To je dobro dizajnirano istraživanje - slučajno birana kontrolna grupa, eksperimentator nije znao ko je u kojoj grupi.

`bb({body:"two_up", mouth:"small", eyes:"normal_r"})`

b: Rezultat: ako si već imao nisko samopouzdanje, teranje da ponavljaš afirmacije napravi da se osećaš *gore* nego da nisi rekao ništa!

`bb({body:"point", mouth:"normal", eyes:"closed"})`

b: Wood 2009, Psychological Science. Potraži ga na Gugl Scholar-u, osobo,

`bb({body:"scream_b_1"})`

b: I PRESTANI DA ŠIRIŠ NENAUČNE LAŽNE VESTI

```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2d_narcissist

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Ti *moraš* da u skromnosti sagledaš svoje mane kako bi rasla kao osoba!

`bb({body:"two_up", eyes:"suspect"})`

b: Ne možeš prskati osveživač vazduha u buđavoj sobi! Prekrivanje svojih mana ih čini gorima na duže staze.

`bb({body:"chest", mouth:"smile", eyes:"closed"})`

b: Srećom te ja, tvoj verni vuk-čuvar, obaveštavam o tvojim manama. I trenutno je to-

`bb({body:"scream_b_1"})`

b: SVE. SVE JE POGREŠNO

```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2d_racist

`bb({body:"normal", mouth:"normal", eyes:"suspect"})`

b: Američki starosedeoci su *stvarni ljudi*, ne neki "plemeniti divljaci" koje možeš da pomeneš da napraviš svoje kolačiće sreće više *egzotičnima*.

`bb({eyes:"suspect_r"})`

b: Svela si individualce i kompleksne kulture na čestitku iz supermarketa! To je "blagonakloni rasizam"! 

`bb({body:"scream_b_1"})`

b: PRESTANI DA BUDEŠ RASISTA TI USKOOKI KRETENU

```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2e

h: ^JEBEM MU^.

`hong({body:"yell", mouth:"yell"})`

h: Znaš šta? Ti si *iracionalan*.

h: Svi znaju da su emocije iracionalne! Posebno strah!

`hong({body:"facepalm_2"})`

h: Ti si beskoristan evolucionalni ostatak, kao moje slepo crevo ili umnjaci!

`hong({body:"yell", mouth:"yell"})`

h: ^Jebote^, čitava metafora sa vukom je glupa! Ti si samo gomilu neuro-hemikalija u mojoj glavi.

`hong({body:"cross", mouth:"cross"})`

h: Zašto bih onda trebala da slušam jedno beskorisno, iracionalno, nepostojeće ^govno^ kao što si ti?!

`bb({eyes:"sad", MOUTH_LOCK:true})`

b: ...

[Daj, osobo. To je baš zlobno.](#act2e_hurtful)

[Ja sam osećanje. Osećanja su validna.](#act2e_valid)

[Osobo, *oboje* smo "samo hemikalije"."](#act2e_rational)

# act2e_hurtful

`bb({body:"chest"})`

b: Ja sam *deo* tebe, znaš. Kada to kažeš, povređuješ *sebe*.

`bb({body:"scream_a_1"})`

b: Zašto povređuješ sebe, osobo? PRESTANI DA POVREĐUJEŠ SEBE

```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "harm");
```

(...2500)

(#act2f)

# act2e_rational

`bb({body:"normal", mouth:"normal", eyes:"normal_r"});`

b: Tvoja najdublja motivacija je dopamin, tvoje najveće zadovoljstvo je serotonin.

`bb({body:"one_up"});`

b: Tvoja sećanja su sinaptičke veze, tvoj razum su električni signali skloni greškama.

`bb({eyes:"normal", body:"normal"});`

b: Ako to što sam "samo hemikalije" znači da sam *ja* iracionalan... onda to znači da si *ti* iracionalna!

`bb({body:"two_up", eyes:"shock"});`

b: A ako smo *oboje* iracionalni, onda *nikada* nećemo shvatiti kako da budemo zadovoljni i srećni!

`bb({body:"scream_a_1"})`

b: AAAAAA MI SMO UNIŠTENI! SLOMLJENI SMO SLOMLJENI SMO--

```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2f)

# act2e_valid

`bb({body:"normal", mouth:"normal", eyes:"suspect"});`

b: Čekaj malo... "oni" kažu da su osećanja validna, da ih uvek moraš prihvatiti.

`bb({eyes:"suspect_r"});`

b: Ali "oni" takođe kažu da su emocije iracionalne, da im se ne može verovati.

`bb({eyes:"angry"});`

b: O moj bože, "oni" nas lažu sve ovo vreme!

`bb({body:"scream_a_1"})`

b: "ONI" NAS HRANE KONTRADIKCIJAMA DA NAS UČINE ZAVISNIMA OD INDUSTRIJSKOG KOMPLEKSA SAMOPOMOĆI

```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "harm");
```

(...2500)

(#act2f)

# act2f

`hong({body:"defeated", MOUTH_LOCK:true});`

h: ...

h: Mrzim ovo. Gospode toliko boli toliko *mrzim* ovo.

h: Ne mogu da te smiriti. Ne mogu te ignorisati. Ne mogu da se izborim sa tobom. 

`bb({eyes:"suspect"});`

h: Šta god da uradim, ne uspevam da te se otar--

`bb({body:"cry_1"});`

b: Pa možda NI *NE TREBAŠ* DA ME SE OTARASIŠ.

`bb({body:"cry_2"});`

b: Kako misliš da je *ja* osećam, osobo?!

`bb({body:"cry_4", mouth:"cry", eyes:"cry"})`

b: Trudim se da budem tvoj vuk-čuvar, ali ti me samo vidiš kao Velikog Zlog Vuka!

b: Pa se *još više* trudim da te obavestim o opasnosti! *Još* opasnosti! *Drugačijoj* opasnosti!

`bb({eyes:"cry_2"})`

b: Ali koliko god se trudim da te zaštitim, ti *još uvek* misliš da sam ja tvoj neprijatelj!

`bb({body:"cry_5"});`

b: Šta radim pogrešno?!

`bb({body:"cry_2"});`

b: *Znam* da sam užasan u svom poslu. Ali *trudim se*, osobo!

`bb({body:"cry_3"});`

b: ...Trudim se.

`bb({body:"cry_6", mouth:"right", eyes:"cry_r_1"});`

b: Ne moraš obraćati pažnju na moja upozorenja, ili se slagati sa mnom, ili me *voleti*.

`bb({eyes:"cry_r_2"});`

b: Samo... sve što želim je da budeš strpljiva sa mnom.

`bb({eyes:"cry_r_3"});`

b: Samo želim da malo sediš sa mnom, a ne da se okreneš i--

```
bb({eyes:"cry_r_4"});
hong({body:"listen"});
```

r: Ej.

```
hong({body:"look"});
Game.clearText();
publish("act2-in-2");
publish("hp_hide");
music('party1', {volume:0.4, fade:2});
```

(...2000)

```
publish("act2",["party_hunter",2]);
Game.WORDS_HEIGHT_BOTTOM = 230;
```

r: Izgleda da se boriš sa samom sobom, srećo.

```
publish("act2",["party_hunter",3]);
publish("act2",["party_hong",13]);
```

h2: Jel' toliko očigledno?

```
publish("act2",["party_hunter",4]);
publish("act2",["party_hong",14]);
```

r: Ti si, ovaj, mumlala u duks o {{_.a2_hoodie_callback}} ili tako nečemu.

```
publish("act2",["party_hunter",13]);
publish("act2",["party_hong",15]);
sfx("rustle", {volume:0.6});
setTimeout(function(){
	publish("act2",["party_hong",16]);
	sfx("concrete_step3", {volume:0.6});
},401);
setTimeout(function(){
	publish("act2",["party_hong",17]);
	sfx("concrete_step4", {volume:0.6});
},801);
```

h2: gospode kakav sam ja haos.

```
publish("act2",["party_hunter",7]);
publish("act2",["party_hong",18]);
sfx("squeak");
```

r: Ej. Nisi sama, sestro. Anksioznost je vrlo uobičajena.

```
publish("act2",["party_hunter",5]);
publish("act2",["party_hong",19]);
```

{{if _.act1_ending=="fight"}}
r: Mislim, baš juče sam čula da je neko imao nervni slom i slupao svoj telefon!
{{/if}}

{{if _.act1_ending=="flight"}}
r: Mislim, baš juče sam čula da se neko sklupčao kao armadilo i plakao u javnosti!
{{/if}}

```
publish("act2",["party_hunter",2]);
```

r: Slušaj: Znam kako je kad imaš tu životinju u glavi.

```
publish("act2",["party_hunter",8]);
```

r: *Svi* znamo. Zato pravimo žurke svakog vikenda, da zaboravimo brige, tu životinju.

```
publish("act2",["party_hunter",9]);
publish("act2",["party_hong",20]);
```

h2: ali moja anksioznost...

```
publish("act2",["party_hunter",2]);
publish("act2",["party_hong",21]);
```

r: Ne brini, srećo. Bila sam kao ti. Ali onda sam otkrila jedan mali trik da ugasim taj negativni glas zauvek...

```
publish("act2",["party_hunter",3]);
Game.clearText();
music(null, {fade:1});
```

(...2001)

```
publish("act2",["party_hunter",10]);
publish("act2",["party_hong",22]);
sfx("rustle");
```

(...2501)

```
publish("act2",["party_hunter",10]);
publish("act2",["party_hong",23]);
sfx("rustle2");
```

(...1001)

```
publish("act2",["party_hunter",11]);
```

r: Moja specijalna mešavina. Malo je jača od... pa, bilo čega legalnog.

```
publish("act2",["party_hunter",12]);
publish("act2",["party_hong",24]);
```

r: Naiskap, ^kujo^!

```
hong({body:"hold"});
bb({body:"normal", mouth:"small", eyes:"wat"});
Game.clearText();
Game.WORDS_HEIGHT_BOTTOM = -1;
publish("act2-out-3");
publish("hp_show");
```

(...3500)

[O moj Bože.](#act2g_1) `Game.OVERRIDE_CHOICE_LINE=true`

[To je loš odbrambeni mehanizam.](#act2g_2) `Game.OVERRIDE_CHOICE_LINE=true`

[Ne uzimaj piće od stranaca.](#act2g_3) `Game.OVERRIDE_CHOICE_LINE=true`

# act2g_1

b: O--

(#act2g)

# act2g_2

b: T--

(#act2g)

# act2g_3

b: N--

(#act2g)

# act2g

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("40p", "harm");
```

(...2000)

```
hong({body:"forward", mouth:"forward"});
bb({body:"frazzled", mouth:"frazzled", eyes:"frazzled"});
```

h: Mmm, kakvi izuzetni ukusi!

h: Bogati ukus "začepi glas u glavi", sa suptilnim notama "više nikada ništa neću osetiti"!

b: Ovo je loše, osobo. Ovo je mnogo, mnogo loše.

[To je *upravo* kako počinje zavisnost.](#act2h_opt1) `Game.OVERRIDE_CHOICE_LINE=true`

[*Znao* sam da je domaćin duboko zeznut!](#act2h_opt3) `Game.OVERRIDE_CHOICE_LINE=true`

[Takođe, mogla je da stavi drogu u to!](#act2h_opt2) `Game.OVERRIDE_CHOICE_LINE=true`


# act2h_opt1

b: To je *upr*--

(#act2h)

# act2h_opt2

b: Takođe, mogl--

(#act2h)

# act2h_opt3

b: *Znao* sam d--

(#act2h)

# act2h

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("40p", "harm");
```

(...2000)

```
hong({body:"back", mouth:"back"});
bb({body:"panicked", mouth:"panicked", eyes:"panicked"});
```

h: Preukusno, *i* jeftinije od terapije!

b: OSOBO MOLIM TE PRESTANI

h: Hehehe!

h: A *šta* ćeš da uradiš, ^šupku^?

b: Tako mi je žao, osobo.

b: Moraću da iskoristim svoj SPECIJALNI NAPAD

```
bb({body:"special_a"});
music('battle', {volume:0.5});
```

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_harm"`

[](#act2h_attack) `_.SPECIAL_ATTACK="harm"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_alone"`

[](#act2h_attack) `_.SPECIAL_ATTACK="alone"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_bad"`

[](#act2h_attack) `_.SPECIAL_ATTACK="bad"; Game.OVERRIDE_CHOICE_LINE=true`

# act2h_attack

```
bb({body:"special_b_1"});
hong({body:"forward", mouth:"forward"});
sfx("charging");
```

h: Šta je ovo ^sranje^?

h: Hoćeš li lajati još glupavih *reči* da--

```
bb({body:"special_c"});
sfx("hadouken");
```

(...901)

(#act2i)

# act2i

```
publish("hide_tabs");
publish("show_special_attack");
Game.FORCE_CANT_SKIP = true;
music(null);
stopAllSounds();
```

(...5000)

```
publish("show_tabs");
hong({ body:"final", mouth:"final" });
bb({ body:"normal", mouth:"normal", eyes:"sad" });
attack("100p", _.SPECIAL_ATTACK);
Game.FORCE_CANT_SKIP = false;
setTimeout(function(){
	publish("remove_special_attack");
},30);
```

(...2500)

h: KOJI ^KURAC^ JE TO BILO

b: Žao mi je. Morao sam da ti pokažem posledice.

{{if _.SPECIAL_ATTACK=="harm"}}
h: MOGLA SAM DA *VIDIM* SVOJ LEŠ. *OSETILA SAM* DA SAM ZAPRAVO MRTVA.
{{/if}}

{{if _.SPECIAL_ATTACK=="alone"}}
h: MOGLA SAM DA *VIDIM* KAKO ME GLEDAJU U GAĐENJU. *ČULA* SAM ŠTA GOVORE.
{{/if}}

{{if _.SPECIAL_ATTACK=="bad"}}
h: MOGLA SAM DA *ČUJEM* KRCKANJE REBARA. *OKUSILA* SAM KRV U VAZDUHU.
{{/if}}

b: Žao mi je, osobo.

n: *DOKRAJČI JE*

[{BORBA: Udari domaćina.}](#act2j_fight) `Game.OVERRIDE_CHOICE_LINE=true`

[{BEG: Idemo odavde.}](#act2j_flight) `Game.OVERRIDE_CHOICE_LINE=true`

# act2j_fight

`bb({ eyes:"angry" });`

b: Taj psihopata te je koristio.

b: Pokušavala je da te pokvari, da te učini pokvarenom koliko je i ona!

`bb({ body:"yell_angry_1" });`

b: Udari tu budalu! Razbij joj vilicu!

`bb({ body:"final_1" });`

b: UDARI JE UDARI JE UDARI JE UDARI JE UDARI JE UDARI JE UDARI JE UDARI JE UDARI JE UD--

`_.a2_ending = "fight";`

(#act2k)

# act2j_flight

b: *Znao* sam da su ovi ludaci nenormalni. Gase svoju bol sa užasnim stvarima!

`bb({ body:"yell_1" });`

b: I hoće da te prevare da uradiš isto! Korumpiraju te! Moramo da idemo!

`bb({ body:"final_1" });`

b: IDI IDI IDI IDI IDI IDI IDI IDI IDI IDI IDI IDI IDI IDI IDI IDI IDI IDI IDI IDI ID--

`_.a2_ending = "flight";`

(#act2k)

# act2k

```
Game.clearText();
publish("act2-in-4");
publish("hp_hide");
music('party1', {volume:0.6, fade:1.5});
```

(...2001)

```
publish("act2",["party_hong",26]);
sfx("slide");
```

(...1001)

```
publish("act2",["party_hunter",14]);
Game.WORDS_HEIGHT_BOTTOM = 230;
```

r: Jesi li u redu, srećo?

`publish("act2",["party_hunter",13]);`

{{if _.a2_ending=="fight"}}
(#act2k_fight)
{{/if}}

{{if _.a2_ending=="flight"}}
(#act2k_flight)
{{/if}}

# act2k_fight

```
Game.clearText();
publish("act2",["party_hunter",21]);
publish("act2",["party_hong",33]);
music(null);
sfx("hit");
```

(...1000)

```
sfx("record_scratch");
publish("act2",["party_hunter",22]);
publish("act2",["party_hong",34]);
publish("act2",["dee",6]);
publish("act2",["dum",6]);
```

r: T-ti...

```
publish("act2",["party_hunter",23]);
publish("act2",["party_hong",35]);
publish("act2",["dee",5]);
publish("act2",["dum",5]);
music('party1', {volume:0.6, fade:6});
```

r: si *opasna*.

r: To mi se sviđa. Dođi na moju žurku sledećeg vikenda, šećeru.

```
publish("act2",["party_hunter",19]);
publish("act2",["party_hong",36]);
```

h2: okej zdravo, ciao, adios, au revoir

r: Životinja je možda pobedila danas, ali dođi ponovo, i napraviću ti nešto još jače!

h2: sayōnara, auf wiedersehen, zài jiàn, shalom

r: Ti i ja, srećo, mi ćemo pokazati životinji ko je glavni!

(#act2k_end)

# act2k_flight

`publish("act2",["party_hong",36]);`

h2: okej izvini moram da idem

`publish("act2",["party_hunter",16]);`

r: ^Jebiga^. Znači, životinja je pobedila danas?

`publish("act2",["party_hunter",15]);`

h2: ne ne, samo, ovaj, trčim maraton. brzinom svetla.

`publish("act2",["party_hunter",19]);`

r: Dođi na moju žurku sledećeg vikenda, šećeru. Napraviću ti nešto još jače.

h2: okej hvala moram da trčim trčim trčim trčim trčim

r: Ti i ja, srećo, mi ćemo pokazati životinji ko je glavni!

(#act2k_end)

# act2k_end

```
Game.clearText();
publish("act2-out-5");
publish("act2-outro", ["end1"]);
music("hum", {fade:2, volume:0.6});
Game.WORDS_HEIGHT_BOTTOM = -1;
```

(...2500)

```
publish("act2", ["act2_end",2]);
sfx("whoosh");
```

(...1000)

b: Osobo! Jesi li dobro?!

```
publish("act2", ["act2_end","next"]);
```

b: Jao, to je bilo *blizu.* Stavrno bismo mogl--

```
Game.clearText();
publish("act2", ["act2_end","next"]);
music(null);
sfx("squeak");
```

(...1500)

```
publish("act2", ["act2_end","next"]);
sfx("hit");
```

(...1000)

h: Dolazim na žurku sledećeg vikenda.

h: Kada se sledećeg puta budemo borili, neću te samo *pobediti*...

h: ^Jebe^no ću te *ubiti*.

```
Game.clearText();
publish("act2", ["act2_end","next"]);
sfx("concrete_step1");
````

(...901)

```
publish("act2", ["act2_end","next"]);
sfx("concrete_step2", {volume:0.8});
```

(...901)

```
publish("act2", ["act2_end","next"]);
sfx("concrete_step3", {volume:0.5});
```

(...901)

`sfx("concrete_step4", {volume:0.25});`

(...3000)

`_.INTERMISSION_STAGE = 2;`

(#intermission)
