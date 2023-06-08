# intro

`SceneSetup.intro();`

# intro-play-button

(...51)

[IGRAJ!](#intro-start) `publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;`

# intro-start

(...500)

`clearText()`

n3: Pre nego što krenemo, kako bi *ti* hteo/la da čitaš?

`publish("show_options_bottom")`

# intro-start-2

n3: Sad, nek priča počne...

```
publish("hide_tabs");
clearText();
```

(...1000)

`publish("intro-to-game-2")`

n2: OVO JE OSOBA

(...600)

`clearText()`

(...300)

`publish("intro-to-game-3")`

# act1

```
SceneSetup.act1();
publish("hide_tabs");
music('battle', {volume:0.5});
```

(...300)

n: A OVO JE NJENA ANKSIOZNOST

n: _TI_ SI ANKSIOZNOST

(#act1_normal)


# act1_normal

```
hong({body:"putaway"});
sfx("rustle");
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Ne. Ne, ne, ne slušam. Proveravam telefon.

```
sfx("rustle2");
hong({body:"phone1", mouth:"neutral", eyes:"neutral"})
```

n: TVOJ POSAO JE DA ŠTITIŠ SVOJU OSOBU OD *OPASNOSTI*

`bb({eyes:"look", mouth:"small_lock", body:"fear"})`

b: Ha! Trošiš život na Tviteru! Ponovo!

```
bb({eyes:"normal", mouth:"normal", body:"normal"});
hong({eyes:"annoyed"});
```

h: Da pitam se zašto ne sedim i ne slušam svoje misli češće.

`hong({eyes:"neutral"});`

n: BRZO, UPOZORI IH O *OPASNOSTI!*

```
bb({eyes:"look"});
```

[O ne, pogledaj te užasne vesti!](#act1d_news)

[O ne, da li je taj tvit potajno o *nama?*](#act1d_subtweet)

[Hej, GIF mačke koja pije mleko](#act1d_milk)

# act1d_milk

`hong({mouth:"smile", eyes:"surprise"});`

h: Hah da to je slatko, ja--

```
hong({mouth:"shock", eyes:"shock"});
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.8;
```

b: MAČKE NE VARE MLEKO I MI SMO UŽASNI LJUDI ŠTO UŽIVAMO U ZLOSTAVLJANJU ŽIVOTINJA

(...200)

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
attack("20p", "bad");
publish("hp_show");
```



