# act4

```
SceneSetup.act4();
publish("SAVE_GAME", ["act4"]);
Game.FORCE_CANT_SKIP = true;
```

(...5001)

```
publish("set_how_many_prompts", [1]);
Game.FORCE_CANT_SKIP = false;
Game.CLICK_TO_ADVANCE = true;
```

n3: (igrica je automatski sačuvana)

```
Game.clearText();
Game.FORCE_CANT_SKIP = true;
```

(...1001)

```
var hong_frame = _.INJURED ? 9 : 0;
publish("act4", ["hong_walks_in",hong_frame]);
sfx("grass_step1", {volume:0.1});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step2", {volume:0.2});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step1", {volume:0.25});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step2", {volume:0.3});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step1", {volume:0.35});
```

(...1667)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step2", {volume:0.35});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step1", {volume:0.35});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step2", {volume:0.35});
```

(...1333)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step1", {volume:0.20});
```

(...167)

```
publish("act4_hong_sits");
```

(...66)

```
publish("act4", ["hong_transition", "next"]);
sfx("squeak");
```

(...133)

`publish("act4", ["hong_transition", "next"]);`

(...1333)

```
publish("act4", ["hong_transition", "next"]);
sfx("rustle");
```

(...333)

`publish("act4", ["hong_transition", "next"]);`

(...1001)

```
publish("act4", ["hong_transition", "next"]);
```

(...333)

```
publish("act4", ["hong_transition", 9]);
sfx("sandwich");
```

(...333)

`publish("act4", ["hong_transition", 10]);`

(...333)

`publish("act4", ["hong_transition", 9]);`

(...333)

`publish("act4", ["hong_transition", 10]);`

(...333)

`publish("act4", ["hong_transition", 9]);`

(...333)

`publish("act4", ["hong_transition", 10]);`

(...333)

`publish("act4", ["hong_transition", "next"]);`

(...1466)

`publish("act4-out-1");`

(...201)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

```
publish("act4-show-chars");
Game.FORCE_CANT_SKIP = false;
```

(...901)

`hong({body:"sigh_1"})`

(...601)

```
hong({body:"sigh_2"});
bb({eyes:"look_down"});
```

h: *uzdah*

```
hong({body:"hold", eyes:"normal", mouth:"normal"});
bb({eyes:"normal"});
```

h: Znači šta je u stvari poenta ove priče?

`hong({body:"one_up", eyes:"annoyed"})`

h: Đta smo uopšte *naučili*? *Ja* sam bila glupa, *moji "prijatelji"* su me koristili, i zamalo smo prokleto *umrli*.

`hong({body:"normal", eyes:"normal"})`

{{if _.INJURED}}
[Da, da ne pominjem račun iz bolnice.](#act4a_bill)
{{/if}}

{{if !_.INJURED}}
[Da, da ne pominjem oštećenje jetre.](#act4a_liver)
{{/if}}

[Da, to *jeste* bio najgori mogući scenario.](#act4a_worst)

[Da, bio sam u pravu.](#act4a_right)

# act4a_bill

`hong({eyes:"annoyed_l", mouth:"narrow"});`

h: Tačno. Mislim da moje osiguranje ne pokriva "povrede zbog kretenskog ponašanja".

`hong({eyes:"annoyed", mouth:"normal"});`

b: Ali ipak... preživeli smo!

`hong({eyes:"normal"});`

h: ?

(#act4b)

# act4a_liver

`bb({eyes:"normal_d"});`

b: Definitivno smo skratili sebi život za koju godinu...

`bb({eyes:"surprise"});`

b: Ali smo bar još uvek *živi*! Preživeli smo!

```
hong({eyes:"surprise"});
bb({eyes:"normal"});
```

h: ?

(#act4b)

# act4a_worst

`bb({eyes:"normal_d"});`

b: Ali ipak...

h: Hm?

`bb({eyes:"surprise"});`

b: Preživeli smo!

(#act4b)

# act4a_right

`bb({eyes:"normal_d"});`

b: Ali... i ti si bila u pravu.

`hong({eyes:"surprise"});`

h: Hm?

`bb({eyes:"normal"});`

b: Ja sam *zaista* bio kao dečak koji je vikao "vuk". Kada je došla *prava* opasnost, ti mi - sa pravom - nisi poverovala.

`bb({eyes:"surprise_r"});`

b: Ali ipak, preživeli smo!

(#act4b)

# act4b

```
bb({eyes:"normal", mouth:"normal"});
hong({eyes:"normal", mouth:"normal"});
```

b: Uprkos svemu, još uvek smo ovde.

`hong({eyes:"suspect"});`

{{if _.INJURED}}
h: Činiš mi se poprilično mirno s obzirom na to da smo zamalo umrli.
{{/if}}

{{if !_.INJURED}}
h: Činiš mi se poprilično mirno s obzirom na to da smo *zamalo* zamalo umrli.
{{/if}}

```
hong({eyes:"normal"});
bb({eyes:"annoyed_d", mouth:"narrow"});
```

b: Pa, u poređenju sa svim ostalim to čini stvari manje strašnima. Nateralo me je na razmišljanje.

`bb({eyes:"normal", mouth:"normal"});`

b: Ako je loše kada se ja borim protiv tebe, zato što te to ne štiti...

h: Ali je loše i kada se ti boriš protiv mene, zato što samo glasnije vičeš...

`bb({eyes:"normal_r"})`

b: Onda možda...

`bb({eyes:"normal"})`

h: Možda ne moramo da se borimo.

```
Game.FORCE_CANT_SKIP = true;
Game.clearText();
```

(...301)

`publish("smash",[0]);`

(...2001)

```
publish("smash",[1]);
sfx("smash_glass");
```

(...2601)

```
publish("smash",[2]);
bb({eyes:"normal", mouth:"normal"});
hong({eyes:"normal", mouth:"normal"});
```

(...2001)

`Game.FORCE_CANT_SKIP = false;`

(#act4b_2)

# act4b_2

```
music('dontfight',{fade:5, volume:0.6});
bb({eyes:"annoyed_d"});
```

b: Ja nisam Veliki Zli Vuk. Ali nisam ni vuk-čuvar.

`bb({eyes:"sad_d"})`

b: Ja sam pretučeni pas lutalica.

`bb({eyes:"sad"})`

b: Preživeo sam loše stvari. Možda traumu ili zanemarivanje. Zato nekada preterano reagujem i krenem sa:

```
sfx("yaps", {volume:0.6});
bb({body:"yap_1"});
Game.FORCE_CANT_SKIP = true;
Game.WORDS_HEIGHT_BOTTOM = 215;
Game.FORCE_TEXT_DURATION = 90;
Game.FORCE_NO_VOICE = true;
```

b: AV AV AV AV AV

(...1884)

```
Game.WORDS_HEIGHT_BOTTOM = -1;
Game.FORCE_CANT_SKIP = false;
bb({body:"normal", mouth:"scream", eyes:"scream_sad"});
```

b: Ali ja *ne želim* da budem kukavički pas! Želim da te štitim! Želim da budem dobar pas!

`bb({eyes:"sad", mouth:"normal"});`

b: Osobo...hoćeš li pomoći da se ovaj vuk pripitomi?

`hong({eyes:"sad"})`

h: Pa...Pokušaću.

`hong({eyes:"normal_l", body:"chin", mouth:"narrow"})`

h: U redu. Zdrav odnos sa osećanjima. Odnosima treba komunikacija. Hajde da komuniciramo.

`hong({eyes:"normal", body:"hands_1", mouth:"normal"})`

h: Narednih pet minuta će zvučati jako otrcano, ali probajmo da lažiramo dok ne uspemo.

```
hong({body:"hands_2", mouth:"normal"});
```

h: Dragi unutrašnji vuče... kako se *ti* osećaš?

n2: STRAHOVI KORIŠĆENI:

n2: *POVREĐIVANJE* {{_.attack_harm_total}}, *NEVOLJEN* {{_.attack_alone_total}}, *LOŠA OSOBA* {{_.attack_bad_total}}

n2: O KOM STRAHU ŽELIŠ DA PRIČAŠ PRVO? (O OSTALIM ĆEŠ MOĆI KASNIJE)

```
_.a4_fears_discussed = 0;
_.num_thanks = 0;
hong({body:"normal"});
bb({eyes:"normal"});
```

[Plašim se da ćemo se povrediti.](#act4_harm)

[Plašim se da ćemo biti sami.](#act4_alone)

[Plašim se da smo loši ljudi.](#act4_bad)

# act4_harm

```
_.a4_talked_about_harm = true;
_.a4_fears_discussed += 1;
```

`bb({eyes:"normal_d"})`

b: Želim da sačuvam tvoju fizičku sigurnost,

`bb({eyes:"sad_d"})`

b: Ali je *ceo svet* toliko opasan. Pun tragedije i zla.

`bb({eyes:"sad"})`

{{if _.a4_fears_discussed==1}}
b: Nemam pojma, *ja* sam za sad rekao dovoljno. Šta *ti* imaš da kažeš, osobo?
{{/if}}

{{if _.a4_fears_discussed==2}}
b: U redu, sad ponovo ti, osobo. Šta misliš?
{{/if}}

{{if _.a4_fears_discussed==3}}
b: Još neka misao, osobo?
{{/if}}

`Game.OVERRIDE_CHOICE_SPEAKER = "h"`

[U pravu si. Hajde onda da se zaštitimo.](#act4_harm_skills)

[Izložimo se opasnosti *još više*.](#act4_harm_exposure)

[Hvala ti.](#act4_thanks) `_.thanks_for = "moju fizičku sigurnost";`

# act4_harm_skills

`bb({eyes:"look_down", body:"paw"})`

b: Ali... kako? Imam očnjake i kandže, ali ja sam samo metafora.

```
bb({ body:"normal", eyes:"normal" });
hong({ body:"one_up", eyes:"surprise" });
```

h: Mogli bismo da naučimo samoodbranu? Da se pridružimo zajednici u kojoj članovi čuvaju jedni druge? Generalno poboljšamo naše zdravlje i lične granice?

```
bb({ eyes:"annoyed_r" });
hong({ body:"normal", eyes:"normal" });
```

b: Možda, ali...

[Kako da krenemo sa tim?](#act4_harm_skills_start)

[Šta ako to ipak ne uspe?](#act4_harm_skills_work)

[Šta ako preteramo u "sigurnosti"?](#act4_harm_skills_overboard)

# act4_harm_skills_start

`bb({ eyes:"sad_d" })`

b: Imamo toliko stvari da radimo, toliko stvari koje treba da propravimo kod sebe. Kako uopšte da *počnemo*?

`hong({ body:"shrug", eyes:"surprise" })`

h: Odmah ćemo početi?

`bb({ eyes:"normal", mouth:"narrow" })`

b: Hm?

```
bb({ body:"normal", mouth:"normal" });
hong({ body:"normal", mouth:"normal", eyes:"normal"});
```

h: Upravo sad vežbamo dobru komunikaciju. Koja ćenam pomoći da bolje otkrivamo opasnost, sa manje lažnih pozitivnih,

`hong({ eyes:"surprise" });`

h: I *to* će nam pomoći da se zaštitimo!

`hong({ eyes:"normal", mouth:"normal" });`

h: Dakle: ovo *jeste* trening samoodbrane.

`bb({ eyes:"normal_r" })`

b: Ha. Očekivao sam više ovoga:

```
Game.FORCE_CANT_SKIP = true;
Game.clearText();
hong({ eyes:"sad", mouth:"smile" });
bb({ body:"karate_1" });
sfx("hiya");
```

(...1001)

`Game.FORCE_CANT_SKIP = false;`

(#act4_something_else)

# act4_harm_skills_work

`bb({ eyes:"normal" });`

h: Tačno, ne postoji način da se 100% zaštitimo...

`hong({ body:"one_up" });`

h: Ali čak i 1% poboljšanja vredi nešto, zar ne?

```
bb({ eyes:"annoyed" });
hong({ normal:"one_up" });
```

b: Vidiš čašu ne kao 99% praznu, nego 1% punu?

`bb({ eyes:"normal" });`

h: I to je vrlo značajno ako si izgubljen u pustinji.

`bb({ eyes:"closed" });`

b: Ha. Živeli, onda.

(#act4_something_else)

# act4_harm_skills_overboard

`bb({ body:"chest", eyes:"annoyed" })`

b: Mislim, čitav razlog zašto si ignorisala moja upozorenja bio je što sam *ja* preterao sa sigurnošću! 

`bb({ body:"normal", eyes:"normal" })`

h: Ne, u pravu si. Želimo da budemo umereno sigurni. Treba biti umeren u svemu.

`bb({ eyes:"suspect" })`

b: Izvini, umereni u *SVEMU*?

`hong({ eyes:"annoyed" })`

h: Umereni u *umerenom broju stvari*.

```
bb({ eyes:"closed" });
hong({ eyes:"normal" });
```

b: Hvala ti što održavaš svoje izjave samodoslednima.

(#act4_something_else)


# act4_harm_exposure

`bb({ mouth:"scream_talk", eyes:"scream", MOUTH_LOCK:true });`

b: *ŠTA*

```
bb({ mouth:"narrow", eyes:"suspect" });
hong({ body:"one_up" });
```

h: Mislim, recimo da se pas boji grmljavine.

`hong({ body:"hands_1" });`

h: Jedan od trikova koje koriste treneri je da puštaju snimak grmljavine tiho, pa daju psu poslasticu jer je ostao miran.

`hong({ body:"hands_2" });`

h: Tokom nekoliko dana, trener pojačava snimak, dok pas ne pobedi svoj strah od grmljavine.

```
hong({ body:"normal", eyes:"surprise" });
bb({ mouth:"normal", eyes:"normal" });
```

h: To je terapija izlaganja!

`hong({ body:"point", eyes:"normal" });`

h: Pošto si ti pas, trebalo bi da radi i na tebi, zar ne? Svi sisari imaju borba-beg reakciju.

`hong({ body:"normal" });`

[Šta ako se *previše* izložimo?](#act4_harm_exposure_overboard)

[Šta ako smo izloženi *pravoj* opasnosti?](#act4_harm_exposure_hurt)

[Ja sam vuk, ne pas.](#act4_harm_exposure_dog) `bb({ eyes:"suspect" })`

# act4_harm_exposure_dog

h: Ja ću biti dobra i strpljiva dok te ne pripitomim u slatku malu kucu.

`bb({ MOUTH_LOCK:true })`

b: ...

`bb({ eyes:"sad", mouth:"smile" })`

b: Aww

(#act4_something_else)

# act4_harm_exposure_overboard

`bb({ eyes:"annoyed" })`

b: *Upravo* smo videli šta se dogodi ako ugasiš svoj strah - staviš sebe u *prave* opasne situacije.

`bb({ eyes:"angry_r", body:"one_up" })`

b: Sem toga, zar nas neće previše desentizacije pretvoriti u psihopate?

`bb({ mouth:"scream", eyes:"scream", body:"two_up" })`

b: Uskoro ćemo davati sebi poslastice dok gledamo ilegalne porniće sa ubijanjem!

`hong({ eyes:"annoyed" })`

h: Mislim... mislim da postoji linija između toga i grmljavine.

`bb({ body:"normal", mouth:"normal", eyes:"suspect" })`

b: Ali *gde* je ona, osobo? *Gde?!*

`hong({ eyes:"surprise", body:"one_up" })`

h: Ne znam. Ali *ti* možeš da mi pomogneš!

`hong({ eyes:"normal", body:"normal" })`

h: Dok radim i pregovaram sa tobom, nacrtaćemo tu liniju.

`bb({ body:"paw", mouth:"narrow", eyes:"closed" })`

b: Okej. Ali ja nemam suprotne palčeve, tako da ćeš ti morati da crtaš.

(#act4_something_else)

# act4_harm_exposure_hurt

`bb({ body:"two_up", eyes:"angry_r" })`

{{if _.INJURED}}
b: Na primer: skočili smo sa prokletog *krova!*
{{/if}}

{{if !_.INJURED}}
b: Na primer: zamalo smo skočili sa prokletog *krova!*
{{/if}}

```
hong({ eyes:"annoyed" });
bb({ body:"normal", eyes:"annoyed" });
```

h: Ne u pravu si. *Može* da se ode predaleko.

`hong({ eyes:"normal" });`

h: Ali baš zato, ako krenemo sa terapijom izlaganja, krećemo od malih stvari i pravimo male korake ka napred.

h: Pre nego što dođemo do *prave* opasnosti, prestaćemo.

`bb({ eyes:"annoyed_r", mouth:"narrow" });`

b: E pa postavljam granicu između slušanja jake grmljavine i stojanja sa visokom šiljatom kapom tokom oluje.

(#act4_something_else)

# act4_thanks

`_.num_thanks += 1`

{{if _.num_thanks==1}}
(#act4_thanks_1)
{{/if}}

{{if _.num_thanks==2}}
(#act4_thanks_2)
{{/if}}

{{if _.num_thanks==3}}
(#act4_thanks_3)
{{/if}}

# act4_thanks_1

`bb({ MOUTH_LOCK:true })`

b: ...

`bb({ eyes:"annoyed" })`

b: Čekaj, nemaš argumenata za ili protiv mojih osećanja? Samo... "hvala ti"?

`hong({ eyes:"surprise", body:"shrug" })`

h: Da! Hvala ti što se brineš za {{_.thanks_for}}.

```
bb({ eyes:"closed_annoyed", MOUTH_LOCK:true });
hong({ eyes:"normal", body:"normal" });
```

b: ...

h: Jesi li dobro?

`bb({ eyes:"super_sad", mouth:"narrow" });`

b: Nikada mi ranije nisi rekla *hvala*.

`hong({ mouth:"smile" });`

h: Ti veliki čupavi paničarski vuče.

(#act4_something_else)

# act4_thanks_2

h: Čak iako preterano odreaguješ, cenim što paziš na {{_.thanks_for}}.

`bb({ eyes:"annoyed" })`

b: Čekaj... ne ponavljaš to "hvala ti" kako ne bi pričala o svojim strahovima, zar ne?

```
bb({ eyes:"normal" });
hong({ eyes:"annoyed", body:"chin" });
```

h: Pa, to je komplikovano, a nemam uvek spreman odgovor.

`hong({ eyes:"annoyed_l", body:"one_up" })`

h: Život ti ne daje listu od tri isprogramirana izbora u dijalogu.

`hong({ eyes:"normal", mouth:"smile", body:"normal" })`

h: Ali za sada, mogu bar da se zahvalim.

b: Pa, hvala i tebi, što me strpljivo slušaš.

`bb({ eyes:"closed" });`

b: Ti mali mesnati sisaru.

(#act4_something_else)

# act4_thanks_3

h: Iako me tvoje lajanje plaši, ti samo pokušavaš da zaštitiš {{_.thanks_for}}.

`bb({ eyes:"smile_r" });`

b: Okej, ako nastaviš da mi laskaš, internet će dobiti neke čudne ideje o nama.

```
bb({ eyes:"smile" });
hong({ eyes:"annoyed" });
```

h: Ma 'ajde, ja sam samo ranjiva devojka sa faksa a ti si veliki, strašni vuk. Šta je najgore što m--

`hong({ eyes:"normal", body:"point" });`

h: Zapravo, ne odgovaraj na to.

(#act4_something_else)




# act4_alone

```
_.a4_talked_about_alone = true;
_.a4_fears_discussed += 1;
```

`bb({ eyes:"sad_d" });`

b: Želim da zadovoljiš tu duboku, ljudsku potrebu da pripadaš...

`bb({ eyes:"sad_u" });`

b: Ali brinem se da ako nas iko ikada upozna - *prave* nas - napustili bi nas.

`bb({ eyes:"sad" });`

{{if _.a4_fears_discussed==1}}
b: Nemam pojma, dovoljno sam *ja* pričao. Šta *ti* želiš da kažeš, osobo?
{{/if}}

{{if _.a4_fears_discussed==2}}
b: Ponovo, tvoj red, osobo. Šta ti misliš?
{{/if}}

{{if _.a4_fears_discussed==3}}
b: Još neka misao, osobo?
{{/if}}

`Game.OVERRIDE_CHOICE_SPEAKER = "h"`

[Slažem se: hajde da poradimo na našem socijalnom životu.](#act4_alone_skills)

[Mislim da nas ljudi vole. Hajde da otkrijemo jel' tako?](#act4_alone_experiment)

[Hvala ti.](#act4_thanks) `_.thanks_for = "moje socijalno pripadanje";`

# act4_alone_skills

```
bb({ eyes:"normal" });
hong({ body:"chin" });
```

h: Mogli bismo da vežbamo veštine kao što su postavljanje pitanja, slušanje i pokazivanje empatije, da se otvaramo i budemo ranjivi, itd?

`hong({ eyes:"normal_l" });`

h: Ili da stvorimo bolje socijalne navike, kao što su dogovaranje druženja sa prijateljima ili svakodnevni razgovor sa njima?

`hong({ body:"one_up" });`

h: Mogli bi i da se više navikenemo na odbijanje.

`hong({ eyes:"normal" });`

h: Ili naučimo da shvatimo kada nas ljudi zapravo *ne odbijaju*, nego su samo umorni ili jednostavno imaju takav izraz lica.

```
hong({ body:"normal" });
bb({ eyes:"annoyed_r" });
```

b: Ima dosta opcija. Ali, nešto o "učenju socijalnih veština"...

[Zar to nije *manipulativno?*](#act4_alone_skills_manipulative)

[Znar onda nećemo biti *laki za manipulisanje?*](#act4_alone_skills_manipulated)

[Šta ako ipak ne uspemo?](#act4_alone_skills_fail)

# act4_alone_skills_manipulative

`bb({ eyes:"suspect" });`

b: Zar nisu serijske ubice koje lako čitaju žrtvine emocije dobri u "empatiji"?

`bb({ eyes:"annoyed" });`

b: Zar nije Čarls Manson imao prijatelje i uticao na ljude?

`hong({ eyes:"annoyed", body:"chin" });`

h: Ne, u pravu si.

h: "Socijalne veštine" su ništa ako te *zapravo* nije briga za ljude.

`hong({ body:"normal" });`

h: U stvari, samo nemoj biti ^šupak^.

`bb({ eyes:"annoyed", mouth:"smile" });`

b: Kao tekst motivacionog postera.

`hong({ body:"shrug", mouth:"narrow" });`

h: “Nemoj Biti ^Šupak^™”

(#act4_something_else)

# act4_alone_skills_manipulated

`bb({ eyes:"angry" })`

b: Postaćemo otirač sa dobrodošlicom, govorićemo Molim te i Hvala dok ljudi brišu noge o nas!

`bb({ mouth:"scream", eyes:"scream" })`

b: Uvlačićemo se u toliko guzica da će izgledati kao da smo pocrneli na suncu!

```
bb({ mouth:"normal", eyes:"normal" });
hong( body:"chin" });
```

h: Ne, u pravu si. "Socijalne veštine" nisu samo zadovoljavanje drugih, nego i postavljanje *granica.*

`hong( body:"one_up" });`

h: Ne možemo zvati nekoga kući ako nemamo zidove koji se uzdižu iz temelja.

```
hong( eyes:"angry", mouth:"narrow" });
bb( eyes:"annoyed", mouth:"smile" });
```

h: Takođe... mentalna slika o uvlačenju... *fuj??*

(#act4_something_else)

# act4_alone_skills_fail

`bb({ eyes:"annoyed" });`

h: Možda će biti neuspešno. Zapravo, mi *nećemo* uspeti.

```
bb({ eyes:"normal" });
hong({ eyes:"surprise", body:"shrug" });
```

h: I to je u redu! Neuspeh je znak da učimo nešto novo!

`hong({ body:"normal", eyes:"normal" });`

h: Pa hajde da zajedno ne uspemo, zar ne?

`bb({ eyes:"normal_r" });`

b: Predpostavljam... najgori mogući scenario, preselimo se i imamo novi identitet.

`bb({ eyes:"normal" });`

h: Da ovih dana to košta smo dva bitkojna.

(#act4_something_else)

# act4_alone_experiment

```
hong({ body:"one_up" });
bb({ eyes:"normal" });
```

h: Mogli bi da eksperimentišemo!

`hong({ body:"chin" });`

h: Mogli bi da nazovemo prijatelja da se družimo, pričamo sa starim prijateljem, ili čak samo pričamo sa kasirkom.

`hong({ body:"normal" });`

h: Mislim da ćemo otkriti da smo voljeniji nego što nam se čini.

`bb({ eyes:"annoyed" });`

[Šta ako su ovo male, nevažne "pobede"?](#act4_alone_experiment_cheap)

[Šta ako je ovo teret ostalima?](#act4_alone_experiment_burden)

[Ali razgovor o vremenu nismo *pravi* mi!](#act4_alone_experiment_real_us)

# act4_alone_experiment_real_us

`bb({ eyes:"sad" });`

b: Ako se tek tako nasmešimo, nikad se nećemo zaista povezati sa nekim,

`bb({ eyes:"super_sad" });`

b: *Ali* ako se otvorimo, drugi će videti našu zamršenu unutrašnjost!

`hong({body:"chin", mouth:"narrow", MOUTH_LOCK:true})`

h: ...

```
hong({body:"normal", mouth:"normal"});
bb({eyes:"normal"});
```

h: Prevrni se.

b: Šta.

`hong({body:"hands_1"})`

h: Kada psi žele da pokažu ljubav i poverenje, pokažu svoju ranjivost tako što ti pokažu stomak.

`hong({body:"one_up"})`

h: Možda se *još* ne osećamo dovoljno sigurno da budemo ranjivi, ali sa dovoljno vežbe,

`hong({body:"normal", eyes:"surprise"})`

h: Jednog dana ćemo ljudima pokazati prave nas - zamršenu, ljudsku osobu.

```
hong({eyes:"normal"});
bb({ eyes:"super_sad", mouth:"smile", body:"chest" });
```

b: Prevrnuću se ako mi daš poslasticu.

`bb({ eyes:"normal", mouth:"normal" });`

h: Ne.

(#act4_something_else)


# act4_alone_experiment_cheap

b: Reći "zdravo" prodavačici nije baš socijalni preformans za zlatnu medalju.

```
hong({ body:"point", eyes:"surprise" });
bb({ eyes:"normal" });
```

h: To je za *nas!*

`hong({ body:"one_up", eyes:"annoyed" });`

h: U socijalnoj areni, mi nismo ni klasa težine pera, mi smo više kao... težina kvarka.

`hong({ body:"normal", eyes:"normal" });`

h: Ako treba da počnemo sa malim, nevažnim pobedama, neka tako bude. Moramo preći prvi stepenik pre hiljaditog.

b: Da! Možda posle "Zdravo" možemo da počnemo da govorimo...

`bb({ body:"two_up", mouth:"smile", eyes:"smile_u" });`

b: *"Kako ste?"*

`hong({ body:"shrug", mouth:"smile", eyes:"surprise_l" });`

h: *"Ništa specijalno!"*

(#act4_something_else)

# act4_alone_experiment_burden

`bb({ eyes:"suspect_r" })`

b: Možda prodavačica samo hoće da nam naplati, a ne da bude *eksperiment* da vidimo da li imamo socijalne veštine.

`bb({ eyes:"annoyed" })`

h: Pa, ako se ispostavi da *jesmo* teret...

```
hong({ eyes:"surprise" });
bb({ eyes:"normal" });
```

h: Dobro je da to saznamo!

`hong({ eyes:"normal" });`

h: Onda možemo da naučimo kako da sami shvatimo sa čim su drugi u redu, da znamo i poštujemo tuđe granice.

```
hong({ eyes:"annoyed_l", mouth:"narrow" });
bb({ eyes:"annoyed", mouth:"smile" });
```

h: Znaš, sva ta ^sranja^ o "inter-personalnim veštinama" koje viđamo na brošurama kod školskog psihologa.

(#act4_something_else)



# act4_bad

```
_.a4_talked_about_bad = true;
_.a4_fears_discussed += 1;
```

`bb({ eyes:"annoyed_r" })`

b: Želim da odbranim tvoje moralne potrebe koje te guraju da budeš bolja osoba,

`bb({ eyes:"sad_d" })`

b: Ali izgleda mi kao da smo duboko dole samo, u osnovi... oštećeni.

`bb({ body:"two_up", eyes:"angry" })`

{{if _.INJURED}}
b: I nemoj mi reći da *nismo* zamršeni. Skočili smo sa *krova*.
{{/if}}

{{if !_.INJURED}}
b: I nemoj mi reći da *nismo* zamršeni. Zamalo smo skočili sa *krova*.
{{/if}}

`bb({ body:"normal", eyes:"sad" })`

{{if _.a4_fears_discussed==1}}
b: Nemam pojma, dovoljno sam *ja* pričao. Šta *ti* želiš da kažeš, osobo?
{{/if}}

{{if _.a4_fears_discussed==2}}
b: Ponovo, tvoj red, osobo. Šta ti misliš?
{{/if}}

{{if _.a4_fears_discussed==3}}
b: Još neka misao, osobo?
{{/if}}

`Game.OVERRIDE_CHOICE_SPEAKER = "h"`

[So we're broken. Let's fix us.](#act4_bad_fix)

[So we're broken. Let's accept it.](#act4_bad_accept)

[Thank you.](#act4_thanks) `_.thanks_for = "moje moralno blagostanje";`

# act4_bad_fix

```
bb({eyes:"normal"});
hong({body:"chin"});
```

h: We could slowly build better habits, get our life more in line with what we value,

`hong({body:"one_up"});`

h: And if needed, we could get professional help – a therapist or counsellor.

`hong({body:"normal"});`

h: There's ways to fix us.

[What if we can't fix it all?](#act4_bad_fix_cant)

[What if we fix *too* much?](#act4_bad_fix_too_much)

[We can't afford professional help.](#act4_bad_fix_afford)

# act4_bad_fix_cant

`hong({eyes:"annoyed"});`

h: Nah, I guess you're right.

h: We can't fix it all.

`bb({mouth:"scream", eyes:"scream_sad"});`

b: Ahhh I knew it we'll always be broken!

`hong({eyes:"surprise"});`

h: But we can at least be *less* broken.

```
bb({mouth:"normal", eyes:"annoyed"});
hong({eyes:"sad", mouth:"smile"});
```

h: Scars heal with time, but they never go away. And that's okay.

`bb({eyes:"annoyed_r"});`

b: I guess. Besides,

```
Game.FORCE_TEXT_Y = 460;
Game.clearText();
publish("act4-sexy", [true]);
```

b: Scars are *sexy.*

```
Game.FORCE_TEXT_Y = -1;
Game.clearText();
publish("act4-sexy", [false]);
bb({body:"chest", mouth:"smile_talk", MOUTH_LOCK:true, eyes:"sexy"}, 0);
hong({eyes:"normal", mouth:"normal"}, 0);
```

h: Please do not do that.

(#act4_something_else)

# act4_bad_fix_too_much

`bb({ eyes:"angry_d" })`

b: This feels sick to admit, but... some part of me *wants* to have this disorder.

`bb({ eyes:"angry" })`

b: I mean, without it, won't we be *boring?*

`bb({ eyes:"sad_r", body:"one_up" })`

b: Without the disorder, won't our art become stale and bland?

`bb({ eyes:"sad_u", body:"two_up" })`

b: Without the disorder, won't we be unable to connect with our friends who have the disorder?

`bb({ eyes:"sad", body:"chest" })`

b: If we're ever content with life, won't we stop driving ourselves to do great things?

`hong({ MOUTH_LOCK:true })`

h: ...

h: If we even fear... "running out of fears"...

h: I don't think we're gonna run out of fears.

`bb({ eyes:"smile_u", body:"normal", mouth:"smile" })`

b: Oh, yeah! Whew! What a relief!

(#act4_something_else)

# act4_bad_fix_afford

`bb({ body:"one_up", eyes:"sexy", mouth:"normal" })`

b: "Doc, I'm anxious that I'm paying $100/hr just to hear you ask *how does that make you feel?*"

`bb({ body:"paw", eyes:"closed", mouth:"narrow" })`

b: "Mm-hmm. And how does that make you feel?"

```
bb({ body:"normal", eyes:"normal", mouth:"normal" });
hong({ eyes:"sad" });
```

h: Nah, that's a totally reasonable worry.

`hong({ eyes:"annoyed", mouth:"sad" });`

h: And it genuinely sucks that mental healthcare isn't affordable for lots of folks.

`hong({ eyes:"normal", mouth:"normal" });`

h: Still, there are some cheap or free options:

`hong({ body:"chin" })`

h: Support groups, online therapy, student/non-profit health centers...

`hong({ body:"hands_1" })`

h: Building habits like meditation, sleeping well, chatting regularly with friends, learning new things...

`hong({ body:"hands_2" })`

h: Going to a library to borrow workbooks for evidence-based psychotherapies...

`hong({ body:"one_up" })`

h: There's a full list of resources at the end of this game!

```
hong({ body:"normal" });
bb({ eyes:"annoyed", mouth:"narrow" });
```

b: Well *that* fourth wall didn't last long.

`hong({ body:"point" });`

h: Some things are more important than narrative convention. Such as mental health.

(#act4_something_else)


# act4_bad_accept

```
bb({ eyes:"normal" });
hong({ eyes:"normal_l", body:"one_up", mouth:"narrow" });
```

h: I mean, that's what therapists say right? Accept all your emotions, even the negative ones?

```
bb({ eyes:"annoyed" });
hong({ eyes:"normal", body:"normal", mouth:"normal" });
```

b: Wait.

["Accept" as in *give up*?](#act4_bad_accept_give_up)

["Accept" as in *approve*?](#act4_bad_accept_approve)

["Accept" as in *take literally*?](#act4_bad_accept_literally)

# act4_bad_accept_give_up

`bb({ eyes:"angry", body:"one_up" });`

b: Do you think Martin Luther King would've said, "Shucks we can't sit in the front of the bus, let's just *accept* it?"

`bb({ eyes:"angry_r", body:"two_up" });`

b: Why does the Self-Help Industrial Complex think waving the white flag is some *profound wisdom?*

`bb({ eyes:"annoyed", body:"normal" });`

h: I think therapists mean "accept" bad things as in: acknowledging they exist and are hard to change,

h: But not necessarily giving up a commitment to change.

`bb({ eyes:"suspect" });`

b: Then therapists should say *acknowledge*, not *accept*.

`hong({ body:"chin", eyes:"annoyed" });`

h: Yeah come to think of it, "accept" is kinda confusing.

`bb({ eyes:"closed", mouth:"narrow" });`

b: Well, I *acknowledge* that.

(#act4_something_else)

# act4_bad_accept_approve

`bb({ eyes:"angry" });`

b: Like it's *good* that we're broken or something? No!

`bb({ eyes:"angry_r", body:"one_up" });`

b: All those dang Hollywood screenwriters who romanticize mental illness are full of crud!

`bb({ eyes:"angry", body:"two_up" });`

b: Having a mental disorder *sucks!* It robs people of *lives!* Why should we "accept" that?!

`bb({ body:"normal" });`

h: I think therapists mean "accept" our emotions as in: be patient with them.

```
hong({ body:"one_up" });
bb({ eyes:"normal" });
```

h: Like how struggling in quicksand makes you sink faster, and the solution is to patiently lie flat,

`hong({ eyes:"surprise" });`

{{if _.INJURED}}
h: Fighting against you, my fear, led me to jump off a roof.
{{/if}}

{{if !_.INJURED}}
h: Fighting against you, my fear, almost led me to jump off a roof.
{{/if}}

`hong({ body:"normal", eyes:"normal" });`

h: Instead, the solution is to do what we're doing now – not to fight, but to patiently be with each other.

`bb({ eyes:"annoyed" });`

b: Then they should say *that* instead of some problematic word like "accept".

`hong({ body:"chin", eyes:"annoyed" });`

h: Yeah come to think of it, "accept" kind of sucks.

`bb({ eyes:"closed_annoyed", mouth:"narrow" });`

b: I do not accept "accept".

(#act4_something_else)

# act4_bad_accept_literally

`bb({ eyes:"sad", body:"one_up" });`

b: But we already *know* you shouldn't take me literally!

`bb({ eyes:"sad_u", body:"two_up" });`

b: The whole *problem* is that I want to help you, but I suck at using words to do so!

`bb({ eyes:"sad", body:"normal" });`

h: I think therapists mean "accept" your emotions as in: "don't fight or ignore them."

`hong({ eyes:"surprise", body:"one_up" });`

h: To listen to you, work *with* you, but not take what you say as 100% literal truth.

```
hong({ eyes:"normal", body:"normal" });
bb({ eyes:"annoyed", mouth:"normal" });`
```

b: Then therapists should say *that* instead of some vague confusing word like "accept".

`hong({ body:"chin", eyes:"annoyed" });`

h: I guess they suck at using words, too.

(#act4_something_else)




# act4_something_else

```
bb({ body:"normal", mouth:"normal", eyes:"normal" });
hong({ body:"normal", mouth:"normal", eyes:"normal" });
```

{{if _.a4_fears_discussed==1}}
h: Anyway, anything else you wanna chat about?
{{/if}}

{{if _.a4_fears_discussed==2}}
h: So, anything else on your heavy heart?
{{/if}}

{{if _.a4_fears_discussed==3}}
(#act4_something_else_2)
{{/if}}

{{if _.a4_talked_about_harm!=true}}
[I'm scared we'll be harmed.](#act4_harm)
{{/if}}

{{if _.a4_talked_about_alone!=true}}
[I'm scared we'll be alone.](#act4_alone)
{{/if}}

{{if _.a4_talked_about_bad!=true}}
[I'm scared we're bad people.](#act4_bad)
{{/if}}

[Nah, I'm good for now.](#act4c_prelude)

# act4_something_else_2

h: Okay, I think we've talked about all our fears now.

b: Yes, there are only three fears.

h: Yup, exactly three.

b: Convenient.

(#act4c)

# act4c_prelude

h: Good chat, team.

(#act4c)

# act4c

```
Game.clearText();
music(null,{fade:3});
bb({body:"normal", eyes:"normal", mouth:"normal", MOUTH_LOCK:true},0);
hong({body:"normal", eyes:"normal", mouth:"normal"},0);
```

b: ...

`hong({MOUTH_LOCK:true},0)`

h: ...

`bb({eyes:"annoyed_d"})`

b: This isn't some *game*, you know.

`bb({eyes:"angry_d", body:"one_up"})`

b: Building a healthy relationship with your emotions isn't as simple as clicking buttons on a screen.

`bb({eyes:"sad", body:"normal"})`

b: *Can* we really get along?

b: *Can* we work together, as a team?

`hong({eyes:"sad", body:"one_up"})`

h: Well,

```
hong({eyes:"surprise_l"});
bb({eyes:"normal"});
```

a: E-excuse me...

```
Game.clearText();
publish("act4-in-2");
music('campus', {volume:0.5, fade:1});
```

(...2101)

(#act4d)

# act4d

`Game.WORDS_HEIGHT_BOTTOM = 221;`

`publish("act4", ["alshire", 0]);`

a: W-wo-would you mind if I sat with you for lunch?

`publish("act4", ["alshire", 1]);`

{{if _.TOP_FEAR=="harm"}}
s: *This* is your crush? Why are they sitting alone like a psycho serial killer?
{{/if}}

{{if _.TOP_FEAR=="alone"}}
s: Asking your crush if you can sit with them? Do you know how *needy* we sound?!
{{/if}}

{{if _.TOP_FEAR=="bad"}}
s: *This* is your crush? We interrupted their peace and quiet! We're such a burden!
{{/if}}

`publish("act4", ["alshire", 2]);`

a: I- I mean- it's, it's okay if not, I just...

`publish("act4", ["alshire", 3]);`

`Game.OVERRIDE_CHOICE_SPEAKER = "h2"`

[Wait, didn't I see you at the party?](#act4d_recognition) `publish("act4", ["hong_to_alshire",1])`

[Yeah, of course! Come here.](#act4d_yes) `publish("act4", ["hong_to_alshire",2])`

[Sorry, I need alone time right now.](#act4d_no) `publish("act4", ["hong_to_alshire",8])`

# act4d_recognition

`publish("act4", ["hong_to_alshire",2]);`

h2: Yeah you were on the couch! At the first party I went to...

`publish("act4", ["hong_to_alshire",10]);`

{{if _.a2_ending=="fight"}}
h2: Where I had that panic attack and punched the host.
{{/if}}

{{if _.a2_ending=="flight"}}
h2: Where I had that panic attack and ran out crying.
{{/if}}

```
publish("act4", ["hong_to_alshire", 0]);
publish("act4", ["bb_to_alshire", _.INJURED ? 3 : 1]);
```

b: Hang on human, we may be making them uncomfortable.

```
publish("act4", ["hong_to_alshire", 3]);
publish("act4", ["bb_to_alshire", _.INJURED ? 2 : 0]);
```

h2: Ah, I don't mean to put you on the spot!

`publish("act4", ["hong_to_alshire",4]);`

h2: Just remembering a friendly face, is all.

```
publish("act4", ["hong_to_alshire",5]);
publish("act4", ["alshire", 4]);
```

{{if _.TOP_FEAR=="harm"}}
s: AHHHHH I KNEW IT! THEY'RE A DANGEROUS PANIC-DRIVEN PSYCHO!
{{/if}}

{{if _.TOP_FEAR=="alone"}}
s: AAHHH THE FIRST IMPRESSION WE MADE WAS "WITNESSED MY TRAUMA"! THAT MEANS THEY HATE US!
{{/if}}

{{if _.TOP_FEAR=="bad"}}
s: AAAHHH WE MADE SOMEONE REMEMBER A TRAUMATIC EVENT. OUR MERE PRESENCE HURTS OTHERS.
{{/if}}

(#act4e)

# act4d_yes

```
publish("act4", ["hong_to_alshire", 5]);
publish("act4", ["bb_to_alshire", _.INJURED ? 3 : 1]);
```

b: Hang on human, they seem uncomfortable.

```
publish("act4", ["hong_to_alshire", 6]);
publish("act4", ["bb_to_alshire", _.INJURED ? 2 : 0]);
```

h2: Ah, no pressure of course!

`publish("act4", ["hong_to_alshire", 4]);`

h2: Just saying, you can sit here if you want to.

```
publish("act4", ["hong_to_alshire", 5]);
publish("act4", ["alshire", 4]);
```

{{if _.TOP_FEAR=="harm"}}
s: THEY'RE BEING *TOO* FRIENDLY! LIKE TED BUNDY, THE SERIAL KILLER!
{{/if}}

{{if _.TOP_FEAR=="alone"}}
s: THEY'RE JUST ACTING NICE! NO ONE *REALLY* WANTS TO BE CLOSE TO US!
{{/if}}

{{if _.TOP_FEAR=="bad"}}
s: AHHH WE ALWAYS MAKE OTHERS FEEL AWKWARD! WE'RE A STAIN UPON THE EARTH!
{{/if}}

(#act4e)

# act4d_no

```
publish("act4", ["hong_to_alshire", 9]);
publish("act4", ["bb_to_alshire", _.INJURED ? 3 : 1]);
```

b: Hang on human, we may be making them uncomfortable.

```
publish("act4", ["hong_to_alshire", 3]);
publish("act4", ["bb_to_alshire", _.INJURED ? 2 : 0]);
```

h2: Ah, I don't mean to be rude!

`publish("act4", ["hong_to_alshire", 6]);`

h2: I just need some time to process my emotions. Please don't take it as a personal rejection.

```
publish("act4", ["hong_to_alshire", 7]);
publish("act4", ["alshire", 4]);
```

{{if _.TOP_FEAR=="harm"}}
s: WHAT SICK, TWISTED THOUGHTS ARE THEY PROCESSING?! WHAT DARK DESIRES FILL THIS PSYCHO'S HEART?!
{{/if}}

{{if _.TOP_FEAR=="alone"}}
s: WE'VE BEEN PERSONALLY REJECTED! WE'LL NEVER BE LOVED!
{{/if}}

{{if _.TOP_FEAR=="bad"}}
s: WE INTERRUPTED THEIR EMOTIONAL PROCESSING! NOW THEY'LL BE TRAUMATIZED FOREVER AND IT'S ALL OUR FAULT!
{{/if}}

(#act4e)

# act4e

```
Game.WORDS_HEIGHT_BOTTOM = 195;
publish("act4", ["alshire", 6]);
```

s: RUN RUN RUN RUN RUN RUN RUN RUN RUN RUN RUN RUN RUN RUN RUN

```
Game.clearText();
publish("act4", ["hong_to_alshire", 0]);
publish("act4", ["alshire", 10]);
sfx("pop");
```

(...1001)

```
publish("act4", ["alshire", 11]);
sfx("alshire_run");
```

(...2601)

```
publish("act4-out-3");
Game.WORDS_HEIGHT_BOTTOM = -1; /* reset */
```

(...1201)

`publish("act4-jumpcut-hong");`

h: Huh. That was weird. I wonder what was going on in their head.

`publish("act4", ["hong_closer", 2]);`

h: Anyway, you were saying?

```
publish("act4", ["hong_closer", 1]);
publish("act4", ["bb_closer", 6]);
```

b: Uh, I forget? Something about teams and work?

```
publish("act4", ["bb_closer", 0]);
publish("act4", ["hong_closer", 3]);
```

h: ¯\_(ツ)_/¯

```
publish("act4", ["hong_closer", 1]);
publish("act4", ["bb_closer", 4]);
```

b: They say you should "make peace" with your emotions, as if your emotions are *war criminals*.

`publish("act4", ["bb_closer", 7]);`

b: But I want us to make *more* than mere peace! I want us to be *allies!*

`publish("act4", ["bb_closer", 3]);`

b: I want to be a good guard-dog. Just like how hunger & thirst are alarms for your physical needs,

`publish("act4", ["bb_closer", 8]);`

b: I want to be the alarm for your *psychological* needs – your needs for safety, belonging, goodness.

`publish("act4", ["bb_closer", 1]);`

b: But... I suck at my job, so I need you to train me.

`publish("act4", ["bb_closer", 4]);`

b: I'm not "always valid," nor "always irrational." I'm just... trying my best. So, please,

`publish("act4", ["bb_closer", 30]);`

b: Help me help you!

`publish("act4", ["bb_closer", 6]);`

b: Though, teaching an old dog new tricks *will* take a while. Maybe *years.*

`publish("act4", ["bb_closer", 3]);`

b: And sometimes I'll relapse, I'll slip into my old habits.

`publish("act4", ["bb_closer", 2]);`

b: I'll bark at shadows. I'll scare you with words. I might even show you some intrusive images of... things.

`publish("act4", ["bb_closer", 9]);`

b: I'm sorry! I'm a battered shelter dog! Battered dogs poop on your bed sometimes!

`publish("act4", ["bb_closer", 4]);`

b: But if you're patient with me... and just stay and sit with me...

`publish("act4", ["bb_closer", 8]);`

b: Maybe you can tame this wolf.

`publish("act4", ["bb_closer", 0]);`

`Game.clearText();`

(...1000)

`Game.OVERRIDE_CHOICE_SPEAKER = "h"`

[Good dog.](#act4f-pat-bb) `Game.OVERRIDE_CHOICE_SPEAKER = "h"; publish("act4", ["hong_closer", 2]);`

`Game.OVERRIDE_CHOICE_SPEAKER = "b"`

[Good human.](#act4f-pat-hong) `Game.OVERRIDE_CHOICE_SPEAKER = "b"; publish("act4", ["bb_closer", 8]);`

# act4f-pat-hong

```
Game.clearText();
publish("hide_tabs");
Game.FORCE_CANT_SKIP = true;
music(null,{fade:0.5});
sfx("youbothwin");
```

```
publish("act4", ["hong_closer", 4]);
publish("act4", ["bb_closer", 13]);
```

(...501)

`publish("act4", ["bb_closer", 14]);`

(...501)

`publish("act4", ["bb_closer", 13]);`

(...501)

`publish("act4", ["bb_closer", 14]);`

(...501)

`publish("act4", ["bb_closer", 13]);`

(...501)

`publish("act4", ["bb_closer", 14]);`

(...6501)

`publish("act4", ["bb_closer", 15]);`

(...1001)

(#act4f)

# act4f-pat-bb

```
Game.clearText();
publish("hide_tabs");
Game.FORCE_CANT_SKIP = true;
music(null,{fade:0.5});
sfx("youbothwin");
```

```
publish("act4", ["hong_closer", 4]);
publish("act4", ["bb_closer", 10]);
```

(...501)

`publish("act4", ["bb_closer", 11]);`

(...501)

`publish("act4", ["bb_closer", 10]);`

(...501)

`publish("act4", ["bb_closer", 11]);`

(...501)

`publish("act4", ["bb_closer", 10]);`

(...501)

`publish("act4", ["bb_closer", 11]);`

(...6501)

`publish("act4", ["bb_closer", 12]);`

(...1001)

(#act4f)

# act4f

```
Game.FORCE_CANT_SKIP = false;
publish("act4", ["bb_closer", 16]);
publish("act4", ["hong_closer", 5]);
```

{{if _.fifteencigs}}
b: AAAAA YOU'RE STILL EATING ALONE FIFTEEN CIGARETTES AAAAA
{{/if}}

{{if _.parasite}}
b: AAAAA YOU'RE STILL NOT PRODUCTIVE WHILE EATING WE'RE SOCIETY-PARASITES AAAAA
{{/if}}

{{if _.whitebread}}
b: AAAAA YOU'RE EATING MORE WHITE BREAD AAAAA
{{/if}}

```
publish("act4", ["bb_closer", 18]);
publish("act4", ["hong_closer", 6]);
sfx("yaps", {volume:0.6});
Game.FORCE_CANT_SKIP = true;
Game.WORDS_HEIGHT_BOTTOM = 205;
Game.FORCE_TEXT_DURATION = 90;
Game.FORCE_NO_VOICE = true;
```

b: YAP YAP YAP YAP YAP

(#credits)
