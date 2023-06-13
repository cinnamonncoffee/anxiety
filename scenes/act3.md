# act3

```
SceneSetup.act3();
Game.WORDS_HEIGHT_BOTTOM = 205;
sfx("cheers");
```

r: Živeli!

```
publish("act3",["roofhunter",1]);
publish("act3",["roofhong",1]);
sfx("drinking");
```

(...4001)

```
publish("act3-alpha", ["dizzyhunter",1]);
publish("act3-alpha", ["dizzyhong",1]);
publish("act3",["roofhunter",3]);
publish("act3",["roofhong",3]);
```

h2: *Ah* to pogađa u metu.

```
publish("act3",["roofhunter",2]);
publish("act3",["roofhong",2]);
```

r: Znaš, srećo...

```
publish("act3",["roofhunter",3]);
publish("act3",["roofhong",6]);
```

h2: Konkretno, pogođene mete su moja leva i desna amigdala.

```
publish("act3",["roofhunter",8]);
publish("act3",["roofhong",5]);
```

r: Podsećaš me na mene kada sam bila mlađa. Kada je i mene mučila životinja u glavi.

```
publish("act3",["roofhunter",9]);
publish("act3",["roofhong",2]);
```

r: Tako sam zahvalna što to mogu da prosledim dalje, i pomognem ti da ubiješ zver kao što sam ja ubila svoju.

```
publish("act3",["roofhunter",2]);
```

r: Ej, brzo pitanje: istina ili iz--

```
publish("act3",["roofhunter",3]);
publish("act3",["roofhong",7]);
publish("act3-alpha", ["dizzyhong",0]);
```

h2: IZAZOV!

```
publish("act3-alpha", ["dizzyhong",1]);
publish("act3",["roofhunter",10]);
publish("act3",["roofhong",2]);
```

r: Haha! Super.

```
publish("act3",["roofhunter",21]);
publish("act3",["roofhong",4]);
```

r: Okej. Vidiš li taj svetloplavi bazen dole?

```
publish("act3-alpha", ["dizzyhong",0]);
publish("act3",["roofhunter",11]);
publish("act3",["roofhong",9]);
```

h2: Da? Šest spratova ispod?

```
publish("act3",["roofhunter",10]);
publish("act3",["roofhong",8]);
```

r: Uskoči u njega.

```
publish("act3",["roofhunter",11]);
publish("act3",["roofhong",10]);
```

h2: ...

```
publish("act3",["roofhong",11]);
```

h2: Ček, šta?

```
publish("act3",["roofhong",10]);
publish("act3",["roofhunter",2]);
```

r: Životinja je krenula da cvili, zar ne?

```
publish("act3",["roofhunter",23]);
```

r: *O neeeeee opasno je, ne radi tooooo.*

```
publish("act3",["roofhunter",22]);
```

r: Ali baš zato nam trebaju uzbuđenja koja prkose smrti! Žurka do jutra! Carpe diem! Šmrkaj kokain sa ^dupeta^ prostitutke, #YOLO!

```
publish("act3",["roofhunter",10]);
```

r: Pokaži životinji da nam trne *^kurac^* što je ^pička^! Uskači.

```
publish("act3",["roofhunter",11]);
publish("act3",["roofhong",13]);
```

h2: Ovaj, ali nekada, pa... strah ima poentu...

```
publish("act3",["roofhunter",5]);
publish("act3",["roofhong",12]);
music(null, {fade:2});
```

r: ...

```
publish("act3-alpha", ["dizzyhunter",0]);
publish("act3",["roofhunter",6]);
publish("act3",["dd",1]);
```

r: Izvini, ali jesi li pala na tu propagandu samosvesnosti koja govori da je *dobro* što se osećaš loše?

```
publish("act3",["roofhunter",17]);
```

r: ^Šupci^ koji upravljaju svetom *nama* prave anksioznost i depresiju,

```
publish("act3",["roofhunter",18]);
```

r: A onda prave TED razgovore da nam kažu da "prihvatimo" što smo sjebani, i "prihvatimo" tog sadističnog demona u našim glavama!

```
publish("act3",["roofhunter",6]);
```

r: Srećo, znam da *ti* znaš da ta životinja *povređuje* ljude kao što smo mi. Ona *muči* ljude kao što smo mi.

```
publish("act3",["roofhunter",19]);
```

r: Ona nije naš prijatelj. To je besna zver, koja ili treba da uzme *tabletu za smirenje*,

```
publish("act3",["roofhunter",20]);
```

r: ili da usadi sebi *metak u lobanju*.

```
publish("act3",["roofhunter",27]);
```

r: Inače, pustićeš je da pobedi.

```
publish("act3",["roofhunter",31]);
publish("act3",["roofhong",14]);
publish("act3",["dd",2]);
```

h2: Ne. Nisi u pravu.

```
publish("act3",["roofhunter",13]);
publish("act3",["roofhong",15]);
music('battle_dark', {volume:1.0}, function(){
	music('battle_dark_loop');
});
```

h2: Neću je pustiti da pobedi.

```
publish("act3",["roofhunter",25]);
publish("act3-alpha", ["roofhong",0]);
publish("act3-alpha", ["transition",1]);
publish("act3",["dd",6]);
```

r: Idemooo! Verujem u tebe, ljubavi! Ubij je! <3

(#act3a)



# act3a

```
Game.clearText();
publish("act3-out");
Game.WORDS_HEIGHT_BOTTOM = -1; /* reset */
_.act3_bb_body = 1;
```

(...1500)

```
publish("hp_show");
```

b: ne ne ne ne ne ne

n: OVO POGLAVLJE IMA DVA MOGUĆA KRAJA. JEDAN JE *VRLO, VRLO LOŠ.*

b: NE NE NE NE NE NE NE NE NE NE NE NE NE NE

n: PAŽLJIVO BIRAJ IZBORE. SAČUVAJ SVOJU OSOBU

`bb({ eyes:"oh_crap", mouth:"normal_talk", MOUTH_LOCK:true });`

b: AAAAAAAAAAAAAAAAAA

`bb({ mouth:"normal" });`

n: SREĆNO

```
Game.clearText();
bb({ eyes:"start" });
```

[Osobo, ovde bi STVARNO mogla da umreš!](#act3a_harm) `Game.OVERRIDE_CHOICE_LINE=true`

[Ovo je glupo i samodestruktivno!](#act3a_bad) `Game.OVERRIDE_CHOICE_LINE=true`

[Ovi bolesnici ti nisu stvarno prijatelji!](#act3a_alone) `Game.OVERRIDE_CHOICE_LINE=true`

# act3a_harm

`bb({ MOUTH_LOCK:true, mouth:"normal_talk" });`

b: O--

(#act3a_after)

# act3a_alone

`bb({ MOUTH_LOCK:true, mouth:"normal_talk" });`

b: O--

(#act3a_after)

# act3a_bad

`bb({ MOUTH_LOCK:true, mouth:"normal_talk" });`

b: O--

(#act3a_after)

# act3a_after

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

h: Znaš, možda bih ti i poverovala... da nisi pokušao isto zilion puta ranije.

h: Kao ona basna o dečaku koji je vikao "vuk".

```
bb({ eyes:"sad" });
```

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_harm"`

[](#act3_fork) `_.SPECIAL_ATTACK="harm"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_alone"`

[](#act3_fork) `_.SPECIAL_ATTACK="alone"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_bad"`

[](#act3_fork) `_.SPECIAL_ATTACK="bad"; Game.OVERRIDE_CHOICE_LINE=true`


# act3_fork

```
Game.clearText();
bb({body:"special_attack"});
sfx("charging");
Game.FORCE_CANT_SKIP = true;
```

(...1001)

```
Game.FORCE_CANT_SKIP = false;
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

h: I to si pokušao.

b: osobo, molim te...

`hong({ eyes:"look_right" });`

h: O *žao mi je* što doktori ne podržavaju moj način lečenja.

h: Vidi ^šupku^, *svi* imamo način da te nateramo da ^jebeno^ začepiš.

`hong({ body:"look_up", eyes:"look_up" });`

h: Neki ljudi rade bez prestanka.

`hong({ body:"look_down", eyes:"look_down" });`

h: Neki ljudi se koriste seksom, drogama, i refrešovanjem fida na Fejsu.

`hong({ body:"normal", eyes:"look_right" });`

h: Neki ljudi se bacaju na druge ljude. 

`hong({ eyes:"angry" });`

h: Ja ću se baciti u taj bazen.

[Pijana si i NA ŠESTOM SI SPRATU](#act3_bad_1_harm)

[Stvarno, ovo je zahvalnost koju dobijam?!](#act3_bad_1_insult) `bb({eyes:"angry"});`

[Okej, priznajem. Zeznuo sam.](#act3_good_1) `bb({mouth:"sorry", eyes:"sorry_down"});`

# act3_bad_1_harm

b: Čak i da upadneš u vodu, površinski napon će ti slomiti rebra i napraviti potres mozga *u najboljem slučaju!*

h: Eh.

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

h: Videla sam Rusa kako radi isto na Jutjubu.

(#act3_bad_2)

# act3_bad_1_insult

`hong({ eyes:"look_right" });`

h: Št- Izvini, *zahvalnost?*

`bb({ eyes:"angry" });`

b: Ovo je baš zašto *postojim!* Zato što ljudi ne mogu da zaštite sami sebe!

b: Pokušavao sam da zaštitm tvoju glupavu glavu čitav svoj život a sad ćeš samo--

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

(#act3_bad_2)

# act3_good_1

`hong({ body:"laugh_1" })``

h: heh.

`hong({ body:"laugh_2" })``

h: hahahaha

`hong({ body:"laugh_3" })``

h: HAHAHAHAHAHA

```
bb({ eyes:"sorry"});
hong({ body:"yell_1", mouth:"yell", eyes:"blank" });
```

h: O VAU to je najveće *^jebe^no* podcenjivanje veka!

`hong({ body:"yell_2" });`

h: Da, ti trula, krvava kretenčino! ^Jebeno^ si zeznuo!

`hong({ body:"normal", mouth:"angry", eyes:"angry" });`

h: Imaš još neku napomenu, Kolumbo?

[Ako se osvetiš meni to neće rešti problem!](#act3_good_1_fail_revenge) `bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });`

[Ali ovaj put sam *zapravo* u pravu!](#act3_good_1_fail_harm) `bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });`

[Povredio sam te.](#act3_good_2a)


# act3_good_1_fail_revenge

b: Moraš da imaš zdraviji odnos sa svojim emocijama, a ne da ih rešav--

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

(#act3_bad_2)



# act3_good_1_fail_harm

b: Tako da molim te, spusti flašu i hajd--

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

(#act3_bad_2)




# act3_bad_2

`bb({ eyes:"sad" });`

b: molim te... nemoj...

h: Energija ti izgleda strašno nisko, vuče.

h: Da sam na tvom mestu, pažljivo bih birala sledeće reči.

`bb({ eyes:"normal" });`

[Dobro. Neću te štititi više.](#act3_bad_2_jump) `bb({ mouth:"ignore", eyes:"ignore" });`

[Bio sam u pravu sve vreme.](#act3_bad_2_right)

[Žao mi je.](#act3_good_2b) `bb({mouth:"sorry", eyes:"sorry_down"});`


# act3_bad_2_jump

b: Pa, hajde, skoči. Nije me briga.

`hong({ eyes:"look_right", mouth:"normal", MOUTH_LOCK:true });`

h: ...

```
hong({ eyes:"less_angry", mouth:"normal" });
bb({ eyes:"ignore_oh_crap" });
```

h: Okej onda. Vidimo se.

```
bb({ mouth:"normal", eyes:"oh_crap" });
Game.OVERRIDE_TEXT_SPEED = 2;
```

b: NE ČEKAJ TO JE OBRNUTA PSIHOLOGIJA TREBAŠ DA URADIŠ *SUPROTNO* OD ONOG ŠT--

(#act3_bad_3)



# act3_bad_2_right

`bb({ eyes:"angry" });`

b: *Ti* stavljaš sebe u opasnost. Tvoji takozvani prijatelji koriste *tebe*. I *ti* koristiš svoje takozvane prijatelje.

`bb({ eyes:"sad" });`

b: So please, human... why don't you believe me?!

h: Because you never believed in *me*.

(#act3_bad_3)


# act3_bad_2_terrible

`bb({ eyes:"angry" });`

b: Other guard-wolves have humans who actually take time to patiently train them, to *learn* to work together,

b: Rather than hate the guard-wolves for trying to protect them! So why can't you jus--

`bb({ eyes:"normal" });`

h: Wrong ^fuck^ing answer.

(#act3_bad_3)



# act3_bad_3

```
music(null);
hong({body:"drink"});
bb({body:"attacked"});
publish("bb_STOP_VIBRATING");
attackBB("100p");
```

(...2000)

```
hong({ body:"normal", mouth:"normal", eyes:"normal" });
bb({ body:"dead" });
```

(...999)

h: *"The only thing to fear is fear itself."*

`hong({ body:"look_up", mouth:"happy", eyes:"blank" });`

h: *"Don't worry, be happy!"*

`hong({ body:"normal", mouth:"normal", eyes:"normal" });`

h: All the wise folk of our time agree: negative emotions are *bad!*

`hong({ eyes:"less_angry" });`

h: Duh! That's why they're called *negative!*

b: human... please...

`hong({ eyes:"normal" });`

h: A while back, I said: “I just want to be free from all this pain.”

h: I got my wish. I no longer feel pain, or fear, or anxiety...

h: I don't feel anything at all.

`_.a3_ending = "jump";`

(#act3_end)



# act3_good_2a

`bb({mouth:"sorry", eyes:"sorry_down"});`

b: I was so obsessed with making sure nothing else hurt you, that I didn't realize *I* was creating the hurt.

```
bb({ eyes:"sorry"});
hong({ body:"yell_2", mouth:"yell", eyes:"blank" });
```

h: NO. S^HIT^.

`hong({ body:"yell_1" });`

h: ^GODDAMN^. It really took you this long to finally figure it out?!

`hong({ body:"cry", mouth:"cry", eyes:"blank" });`

h: You could've saved us so much trouble, you big fluffy dumb^ass^. Why didn't you realize this sooner?...

`_.apologized_for_hurt = true;`

(#act3_good_2q)



# act3_good_2b

`hong({ body:"normal", mouth:"angry", eyes:"look_right" });`

h: ...you're *sorry.*

`hong({ eyes:"angry", MOUTH_LOCK:true });`

h: ...

h: Sorry for *what*?

(#act3_good_2q)


# act3_good_2q

`bb({mouth:"sorry", eyes:"sorry"});`

{{if _.apologized_for_hurt}}
(#act3_good_2q_already_apologized)
{{/if}}

{{if !_.apologized_for_hurt}}
(#act3_good_2q_not_already_apologized)
{{/if}}


# act3_good_2q_already_apologized

`hong({ body:"normal", mouth:"angry", eyes:"less_angry" });`

[I'm sorry I wasn't a good protector.](#act3_good_3_protector)

[I'm sorry I didn't respect you.](#act3_good_3_respect)

[I'm sorry.](#act3_good_4)


# act3_good_2q_not_already_apologized

`hong({ body:"normal", mouth:"angry", eyes:"angry" }, 0);`

[I'm sorry I have a terrible human!](#act3_bad_2_terrible) `bb({mouth:"normal", eyes:"normal"})`

[I'm sorry I didn't respect you.](#act3_good_3_respect)

[I'm sorry I hurt you.](#act3_good_3_hurt)



# act3_good_3_protector

`bb({eyes:"sorry_down"});`

b: It's my duty to warn you against *real* danger, but I kept barking at cars and the mailman.

`bb({eyes:"sorry_up"});`

b: Barking at shadows. Barking so much.

`bb({eyes:"sorry"});`

b: It only makes sense that you'd want to muzzle me.

`bb({eyes:"sorry_down"});`

b: I'm sorry.

(#act3_good_4)



# act3_good_3_respect

`bb({eyes:"sorry_down"});`

b: I was supposed to be *your* loyal guard-dog, but I acted as if you were supposed to obey *me*.

`bb({eyes:"sorry_up"});`

b: There's a difference between a protector and a prison warden, and I crossed the line.

`bb({eyes:"sorry_down"});`

b: I'm sorry.

(#act3_good_4)



# act3_good_3_hurt

`bb({eyes:"sorry_down"});`

b: I was so obsessed with trying to protect you from being hurt, I never stopped to realize *I* was hurting you.

`bb({eyes:"sorry_up"});`

b: I was a bad dog.

`bb({eyes:"sorry_down"});`

b: I'm sorry.

(#act3_good_4)


# act3_good_4

```
music(null,{fade:3});
hong({ eyes:"less_angry", MOUTH_LOCK:true },0);
```

h: ...

```
hong({ body:"stop", mouth:"stop", eyes:"blank" });
```

h: Yeah, well, this was a dumb idea anyway.

h: I only did this to mess you up, and, well, I messed you up.

h: Let's just call this round a tie, okay?

```
bb({ mouth:"sorry", eyes:"sorry" });
bb({ MOUTH_LOCK:true });
```

b: ...

b: Okay.

h: Okay.

n: *TIE*

`_.a3_ending = "walkaway";`

(#act3_end)









# act3_end

```
Game.clearText();
publish("act3-in");
publish("hp_hide");
Game.FORCE_CANT_SKIP = true;
```

{{if _.a3_ending=="walkaway"}}
(#act3_walkaway)
{{/if}}

{{if _.a3_ending=="jump"}}
(#act3_jump)
{{/if}}






# act3_walkaway

```
publish("start-walkaway-anim");
Game.WORDS_HEIGHT_BOTTOM = 205;
```

(...3501)

```
sfx("bottle_toss");
publish('hong-next');
publish("act3",["roofhunter",7]);
```

(...667)

```
publish("act3",["dd",4]);
publish("act3",["roofhunter",26]);
publish('hong-next');
sfx("concrete_step1");
```

(...667)

```
publish('hong-next');
sfx("concrete_step2");
```

(...667)

```
publish('hong-next');
publish("act3",["roofhunter",27]);
```

`Game.FORCE_CANT_SKIP = false;`

r: Oh *come on*. After all that animal's done to you, you're just *giving up?*

r: What's the matter, kid? Are you *scared?*

```
publish('hong-next');
publish("act3",["roofhunter",26]);
```

h2: Yes.

h2: I'm scared.

`publish('hong-next')`

h2: And that's okay!

`publish('hong-next')`

h2: It's okay to be scared.

`publish('hong-next')`

(...500)

```
Game.clearText();
Game.FORCE_CANT_SKIP = true;
```

(...1167)

```
publish('hong-next');
```

(...833)

```
publish('hong-next');
sfx("rustle2");
```

(...1333)

```
publish('hong-next');
publish("act3",["dd",5]);
publish("act3",["roofhunter",31]);
sfx("concrete_step4");
```

(...667)

```
publish('hong-next');
sfx("concrete_step1");
```

(...667)

```
publish('hong-next');
sfx("door");
```

(...1333)

```
publish('hong-next');
sfx("concrete_step2");
```

(...501)

```
publish('hong-next');
Game.FORCE_CANT_SKIP = false;
sfx("lock_door");
publish("act3",["roofhunter",32]);
```

(...2001)

```
publish("act3",["roofhunter",33]);
```

r: Did they just lock the door?

```
Game.clearAll();
_.INJURED = false;
Game.WORDS_HEIGHT_BOTTOM = -1;
```

(...2000)

(#act4)




# act3_jump

```
publish("start-jump-anim");
Game.FORCE_TEXT_Y = 300;
```

(...2001)

```
publish('hong-next');
sfx("bottle_toss");
```

(...833)

```
sfx("concrete_step1");
sfx("claps");
publish('hong-next');
publish("act3",["dd",4]);
publish("act3",["roofhunter",28]);
```
(...125)

`publish("act3",["roofhunter",29]);`

(...125)

`publish("act3",["roofhunter",28]);`

(...125)

`publish("act3",["roofhunter",29]);`

(...125)

```
sfx("concrete_step2");
publish('hong-next');
publish("act3",["roofhunter",28]);
```

(...125)

`publish("act3",["roofhunter",29]);`

(...125)

`publish("act3",["roofhunter",28]);`

(...125)

`publish("act3",["roofhunter",29]);`

(...125)

```
sfx("concrete_step3");
publish('hong-next');
publish("act3",["dd",5]);
publish("act3",["roofhunter",34]);
```

(...1167)

```
sfx("rustle2");
publish('hong-next');
```

(...1001)

`publish('hong-next')`

b: no...

(...501)

`Game.clearText();`

`publish('hong-next')`

(...1333)

```
sfx("quack");
publish('hong-next');
```

(...1333)

`publish('hong-next')`

b: no no no

(...501)

`Game.clearText();`

`publish('hong-next')`

(...2001)

```
sfx("rustle2");
publish('hong-next')
```

(...501)

```
sfx("concrete_step1");
publish('hong-next');
publish("act3",["dd",4]);
publish("act3",["roofhunter",30]);
```

(...167)

```
sfx("concrete_step2");
publish('hong-next');
```

(...167)

```
sfx("concrete_step3");
publish('hong-next');
publish("act3",["dd",2]);
publish("act3",["roofhunter",15]);
```

(...167)

```
sfx("bottle_slip");
publish('hong-next');
publish("act3",["dd",3]);
publish("act3",["roofhunter",16]);
```

(...833)

```
sfx("rustle");
publish('hong-next');
```

(...167)

`publish('hong-next')`

(...167)

```
publish('hong-next');
Game.FORCE_TEXT_Y = 325;
Game.OVERRIDE_FONT_SIZE = 50;
```

b: NO!

(...400)

```
Game.WORDS_HEIGHT_BOTTOM = -1;
Game.FORCE_TEXT_Y = -1;
Game.clearText();
publish("act4-injury-show");
publish("hide_tabs");
```

(...2000)

```
sfx("hospital1");
publish("act4-injury", [1]);
```

(...4000)

```
stopAllSounds();
publish("act4-injury", [0]);
```

(...2000)

```
sfx("hospital2");
publish("act4-injury", [2]);
```

(...4000)

```
stopAllSounds();
publish("act4-injury", [0]);
```

(...2000)

```
sfx("hospital3");
publish("act4-injury", [3]);
```

(...8000)

```
stopAllSounds();
publish("act4-injury", [0]);
```

(...5500)

`_.INJURED = true;`

(#act4)
