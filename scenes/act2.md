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

s: Ali jeste li *videli* te viralne "vesti"?

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

a: Da, skroz lažne. Ko bi pao na to i retvitovao?

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

s: Ozbiljno druže. Kao, zdravo, otvori taj Gugl i proveri činjenice prvo?

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

s: Da ne znam! Šta, jel' mislila da sam *serijski ubica* ili tako nešto? Kakva paranoja.

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

s: Da ne znam! Možda misli da kombinacije ne mogu da popune rupu u njenom srcu?

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

s: Da ne znam! Nije toliko lepa, ali je dobar ulov!

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

b: Uništavamo raspoloženje ove žurke jer smo kao neka tužna gruda!

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

b: Mislim, Drugi Zakon Termodinamike znači da će čak i naš *univerzum* umreti!

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

b: *HA*

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
_.a2_hoodie_callback = "a quarantine";
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

b: Zakon o Čudacima, Član 74.5: (1) Bilo koja Osoba koja bulji u (a) ta mišićava ramena (b) to definisano dupe (2) će nadalje biti poznata kao

`bb({eyes:"shock", body:"two_up", mouth:"normal"})`

b: "VELIKI ODVRATNI SMEĆARSKI PERVEZNJAK"

```
_.a2_second_danger = 'law';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "the law";
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
_.a2_hoodie_callback = "World War I";
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
_.a2_hoodie_callback = "zombies";
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
_.a2_hoodie_callback = "Hitler";
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
_.a2_hoodie_callback = "carbon monoxide";
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

b: I onda će morati da sterilišu dron da ga očiste od BAKTERIJA TUŽNE GRUDE

`_.a2_attack_3 = "alone";`

`_.a2_hoodie_callback = "a quarantine";`

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

b: VELIKI ODVRATNI SMEĆARSKI PERVEZNJAK biće osuđen na 72 sata u jednom od onih srednjovekovnih sprava za javno ponižavanje

b: osim ako tajno *voli* takve stvari

`bb({body:"scream_a_1"})`

b: zato što je VELIKI ODVRATNI SMEĆARSKI PERVEZNJAK

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "the law";`

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

`_.a2_hoodie_callback = "the butterfly effect";`

(#act2d)

# act2c_louder_zombies

`bb({body:"normal", mouth:"small", eyes:"angry"})`

b: Ti zombiji za zabave će da se dogegaju do tebe mumlajući,

`bb({body:"normal", mouth:"normal", eyes:"shock"})`

b: LAAAAJKOVI. LAAAAAAAJKOVI.

`bb({body:"scream_a_1"})`

b: Onda će te UGRISTI i pretvoriti te u BRATA BEZ MOZGA i/ili KUJU BEZ NEVINOSTI!

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "zombies";`

(#act2d)

# act2c_louder_hitler

`bb({body:"scream_a_1"})`

b: NACISTI SE ŠETKAJU ULICAMA TRENUTNO

`bb({body:"one_up", mouth:"smile", eyes:"happy"})`

b: Govoreći, *dobro je što je taj 'dobar narod' trošio vreme sa 'opuštanjem' i 'brizi o sebi'!*

`bb({body:"point", mouth:"smile", eyes:"happy_r"})`

b: *Gut, naši planovi se mogu nastaviti!*

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "Hitler";`

(#act2d)

# act2c_louder_ignore

`bb({body:"normal", mouth:"normal", eyes:"normal_r"})`

b: Kad bolje razmislim, da li zasigurno znamo da ova zgrada *ima* detektor monoksida?!

`bb({body:"two_up", mouth:"small", eyes:"normal"})`

b: Šta ako se svi trujemo *UPRAVO SADA?*

`bb({body:"scream_a_1"})`

b: NE BISMO NI PRIMETILI DA SE SMRT PRIBLIŽAVA. SAMO BISMO NESTALI ZAUVEK ZAUVEK ZAU-

`_.a2_attack_3 = "harm";`

`_.a2_hoodie_callback = "carbon monoxide";`

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

b: Šta je u našoj prirodi ako želimo da povređujemo druge? Šta ako nemožemo biti bilo šta drugo sem *tereta* našim najbližima?

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

`_.a2_hoodie_callback = "punch bowls";`

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

[Znaš li da su afirmacije *opovrgnute?*](#act2d_disproven)

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

b: PA PRESTANI DA ŠIRIŠ NENAUČNE LAŽNE VESTI

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

b: Svela si individualce i kompleksne kulture na čestitku iz supermarketa! to je "blagonakloni rasizam"! 

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

h: Znaš šta? Ti si *iracionalna*.

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

b: AAAAAA MI SMO UNIŠTENI! UNIŠTENI SMO UNIŠTENI SMO--

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

b: Oh my gosh, "they" have been lying to us this whole time!

`bb({body:"scream_a_1"})`

b: "THEY" FEED US CONTRADICTIONS TO MAKE US DEPENDENT ON THE SELF-HELP INDUSTRIAL COMPLEX

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

h: I hate this. God it hurts so much I *hate* this.

h: I can't appease you. I can't ignore you. I can't fight you. 

`bb({eyes:"suspect"});`

h: No matter what I do, I can't seem to get rid of yo--

`bb({body:"cry_1"});`

b: Well maybe you're NOT *SUPPOSED* TO GET RID OF ME.

`bb({body:"cry_2"});`

b: How do you think *I* feel, human?!

`bb({body:"cry_4", mouth:"cry", eyes:"cry"})`

b: I'm trying my best to be your guard-dog, but you keep seeing me as some Big Bad Wolf!

b: So I try even *harder* to alert you to danger! *More* danger! *Different* danger!

`bb({eyes:"cry_2"})`

b: But no matter how hard I try to protect you, you *still* think I'm your enemy!

`bb({body:"cry_5"});`

b: What am I doing wrong?!

`bb({body:"cry_2"});`

b: I *know* I suck at my job. But I'm *trying*, human!

`bb({body:"cry_3"});`

b: ...I'm trying.

`bb({body:"cry_6", mouth:"right", eyes:"cry_r_1"});`

b: You don't have to heed my warnings, or agree with me, or even *like* me.

`bb({eyes:"cry_r_2"});`

b: I just... all I want is for you to be patient with me.

`bb({eyes:"cry_r_3"});`

b: I just want for you to sit with me for a while, instead of turning away and--

```
bb({eyes:"cry_r_4"});
hong({body:"listen"});
```

r: Hey.

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

r: Looks like you're caught in a fight with yourself, kid.

```
publish("act2",["party_hunter",3]);
publish("act2",["party_hong",13]);
```

h2: Was it that obvious?

```
publish("act2",["party_hunter",4]);
publish("act2",["party_hong",14]);
```

r: You were, uh, mumbling at your hoodie about {{_.a2_hoodie_callback}} or something.

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

h2: oh god i'm such a mess.

```
publish("act2",["party_hunter",7]);
publish("act2",["party_hong",18]);
sfx("squeak");
```

r: Hey. You're not alone, friend. Anxiety's super common.

```
publish("act2",["party_hunter",5]);
publish("act2",["party_hong",19]);
```

{{if _.act1_ending=="fight"}}
r: Heck, just yesterday, I heard someone on campus had a nervous breakdown and smashed their phone!
{{/if}}

{{if _.act1_ending=="flight"}}
r: Heck, just yesterday, I heard someone curled up into an armadillo ball and cried in public!
{{/if}}

```
publish("act2",["party_hunter",2]);
```

r: Listen: I know what it's like to have that animal in your head.

```
publish("act2",["party_hunter",8]);
```

r: We *all* do. That's why I throw these parties every weekend, to forget our worries, forget that animal.

```
publish("act2",["party_hunter",9]);
publish("act2",["party_hong",20]);
```

h2: but my anxiety...

```
publish("act2",["party_hunter",2]);
publish("act2",["party_hong",21]);
```

r: Don't worry, kid. I used to be like you. But then I found a little trick to get that negative voice to shut up forever...

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

r: My own specialty blend. It's a bit stronger than... well, anything legal really.

```
publish("act2",["party_hunter",12]);
publish("act2",["party_hong",24]);
```

r: Bottoms up, ^bee-yatch^!

```
hong({body:"hold"});
bb({body:"normal", mouth:"small", eyes:"wat"});
Game.clearText();
Game.WORDS_HEIGHT_BOTTOM = -1;
publish("act2-out-3");
publish("hp_show");
```

(...3500)

[Oh my God.](#act2g_1) `Game.OVERRIDE_CHOICE_LINE=true`

[This is a bad coping mechanism.](#act2g_2) `Game.OVERRIDE_CHOICE_LINE=true`

[Don't take drinks from strangers.](#act2g_3) `Game.OVERRIDE_CHOICE_LINE=true`

# act2g_1

b: O--

(#act2g)

# act2g_2

b: T--

(#act2g)

# act2g_3

b: D--

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

h: Mmm, what an exquisite palette!

h: A full-bodied flavor of "shut your mind up," with a subtle aftertaste of "never feel anything ever again"!

b: This is bad, human. This is really, really bad.

[This is *actually* how addiction starts.](#act2h_opt1) `Game.OVERRIDE_CHOICE_LINE=true`

[I *knew* the host was deeply messed up!](#act2h_opt3) `Game.OVERRIDE_CHOICE_LINE=true`

[Also, they could have drugged that!](#act2h_opt2) `Game.OVERRIDE_CHOICE_LINE=true`


# act2h_opt1

b: This is *actu*--

(#act2h)

# act2h_opt2

b: Also, they co--

(#act2h)

# act2h_opt3

b: I *knew* th--

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

h: Delicious, *and* cheaper than therapy!

b: HUMAN PLEASE STOP

h: Hehehe!

h: And what are *you* gonna do about it, ^asshole^?

b: I'm so sorry, human.

b: I'm going to have to use my SPECIAL ATTACK

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

h: What's this ^crap^?

h: You're gonna yap more stupid *words* at me to--

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

h: WHAT THE ^HELL^ WAS THAT

b: I'm sorry. I needed to show you the consequences.

{{if _.SPECIAL_ATTACK=="harm"}}
h: I COULD *SEE* MY OWN CORPSE. I COULD *FEEL* THE SENSATION OF BEING ACTUALLY DEAD.
{{/if}}

{{if _.SPECIAL_ATTACK=="alone"}}
h: I COULD *SEE* EVERYONE'S LOOK OF DISGUST. I COULD *HEAR* ALL THE THINGS THEY SAID.
{{/if}}

{{if _.SPECIAL_ATTACK=="bad"}}
h: I COULD *HEAR* THE CRUNCHING OF RIBS. I COULD *TASTE* THE BLOOD IN THE AIR.
{{/if}}

b: I'm sorry, human.

n: *FINISH THEM*

[{FIGHT: Punch the host.}](#act2j_fight) `Game.OVERRIDE_CHOICE_LINE=true`

[{FLIGHT: Let's get out of here.}](#act2j_flight) `Game.OVERRIDE_CHOICE_LINE=true`

# act2j_fight

`bb({ eyes:"angry" });`

b: That psychopath was taking advantage of you.

b: They were trying to corrupt you, make you as messed up as they are!

`bb({ body:"yell_angry_1" });`

b: Punch that jerk! Knock their friggin' lights out!

`bb({ body:"final_1" });`

b: PUNCH THEM PUNCH THEM PUNCH THEM PUNCH THEM PUNCH THEM PUNCH THEM PUNCH THEM PUNCH THE--

`_.a2_ending = "fight";`

(#act2k)

# act2j_flight

b: I *knew* all these partygoers were deeply messed up. They all dull their pain with horrible things!

`bb({ body:"yell_1" });`

b: And they're tricking you into doing the same thing! They're corrupting you! We need to get out!

`bb({ body:"final_1" });`

b: GET OUT GET OUT GET OUT GET OUT GET OUT GET OUT GET OUT GET OUT GET OUT GET OU--

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

r: You alright, kid?

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

r: Y-you...

```
publish("act2",["party_hunter",23]);
publish("act2",["party_hong",35]);
publish("act2",["dee",5]);
publish("act2",["dum",5]);
music('party1', {volume:0.6, fade:6});
```

r: are *kinky*.

r: I like that. Come to my party next weekend, cutie.

```
publish("act2",["party_hunter",19]);
publish("act2",["party_hong",36]);
```

h2: ok bye, ciao, adios, au revoir

r: The animal might have won today, but come back, and I'll mix something even stronger for you!

h2: sayōnara, auf wiedersehen, zài jiàn, shalom

r: You and me, kid, we'll show that beast who's boss!

(#act2k_end)

# act2k_flight

`publish("act2",["party_hong",36]);`

h2: ok sorry i have to run

`publish("act2",["party_hunter",16]);`

r: ^Damn^ it. The animal won today, huh?

`publish("act2",["party_hunter",15]);`

h2: no no, just, uh, gotta run a marathon. gotta go fast.

`publish("act2",["party_hunter",19]);`

r: Come to my party next weekend, cutie. I'll mix something even stronger for you.

h2: ok thanks gonna run run run run run

r: You and me, kid, we'll show that beast who's boss!

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

b: Human! Are you okay?!

```
publish("act2", ["act2_end","next"]);
```

b: Gosh, that was *close.* We really could've--

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

h: I'm coming back to the party next weekend.

h: The next time we fight, I'm not just going to *defeat* you...

h: I'm going to ^fuck^ing *kill* you.

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
