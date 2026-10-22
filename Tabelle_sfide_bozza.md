# Bozza tabelle sfide non-combat

Bozza da approvare prima di toccare il codice. Le voci sono modificabili: dimmi cosa togliere, cambiare o aggiungere.

## 1. Tipo di scena (pesi iniziali, modificabili nelle Impostazioni)

| Tipo | Peso |
|---|---|
| Combattimento | 30% |
| Ostacolo / pericolo | 40% |
| Evento ambientale | 20% |
| Incontro sociale | 10% |

## 2. Meccaniche calcolate dal livello sfida (1–5)

Ogni sfida pericolosa ha una gravità: **Lieve**, **Pericolosa** o **Mortale**. Il programma calcola CD e danno dal livello sfida scelto nel menù (selettore limitato a 1–5).

**Danno per livello e gravità:**

| Livello | Lieve | Pericolosa | Mortale |
|---|---|---|---|
| 1 | 1d6 | 2d6 | 3d10 |
| 2 | 1d8 | 2d8 | 4d10 |
| 3 | 2d6 | 3d8 | 5d10 |
| 4 | 2d8 | 3d10 | 6d10 |
| 5 | 2d10 | 4d10 | 8d10 |

**CD per livello e gravità:**

| Livello | Lieve | Pericolosa | Mortale |
|---|---|---|---|
| 1 | 10 | 12 | 16 |
| 2 | 10 | 13 | 17 |
| 3 | 11 | 13 | 18 |
| 4 | 11 | 14 | 19 |
| 5 | 12 | 15 | 20 |

**CD di rilevamento** (prova di abilità facoltativa per accorgersi del pericolo): Lieve 13, Pericolosa 16, Mortale 19.

**Regole sul danno e sull'Affaticamento:** il rilevamento esiste solo per i pericoli nascosti (trappole, veleni, magie). I pericoli evidenti (ghiaccio sottile, tornado, parete) non hanno prova per notarli, ma solo una prova o salvezza per evitarne l'effetto. Le voci che danno Affaticamento seguono la gravità: Lieve e Pericolosa danno solo l'Affaticamento (nessun danno); Mortale dà danno più Affaticamento, e con la salvezza riuscita il danno è dimezzato senza Affaticamento.

**Sequenza di una sfida pericolosa:**
1. *Rilevamento (solo se il pericolo è nascosto, facoltativo):* se i giocatori cercano, prova con la CD di rilevamento. Se riesce, il pericolo si evita o si affronta in sicurezza.
2. *Prova o salvezza:* tiro salvezza (CD dalla tabella di livello e gravità) oppure prova di abilità, indicata nella voce. Con la prova di abilità fallita la conseguenza è diretta.
3. *Esito:* salvezza fallita = danno pieno ed effetto. Salvezza riuscita = metà danno o nessuno (come indicato). Nessun effetto dura meno di 1 ora, perché un esagono richiede almeno un'ora.

**CD sociali** (indipendenti dal livello): Facile 10, Media 15, Difficile 20.

Chi supera la prova evita o dimezza il danno, a seconda della sfida. Per i pericoli di gruppo (marcia, meteo) il programma propone una perdita di risorse invece del danno: 1 dado Salute per PG, razioni o tempo.

## 3. Ostacoli e pericoli non-combat

Colonne: nome, scena, rilevamento (CD per gravità: 13/16/19), prova o salvezza (CD da tabella), gravità, danno, se riesce la salvezza, effetto se fallisce (durata).

| # | Nome | Scena | Rilevamento | Prova | Gravità | Danno | Se riesce | Effetto se fallisce |
|---|---|---|---|---|---|---|---|---|
| 1 | Ponte pericolante | assi marce e corde sfilacciate su un burrone | — | Salvezza Des | Pericolosa | Contundente | Metà | Il PG cade; 1 ora per risalire o aggirare |
| 2 | Parete da scalare | roccia umida alta quindici metri | — | Prova Atletica | Pericolosa | Contundente | — | Caduta a metà; 1 ora persa per ritentare |
| 3 | Trappola a pressione | lastra nascosta su un sentiero in rovina | Indagare o Percezione | Salvezza Des | Pericolosa | Perforante | Nessuno | — |
| 4 | Liane strangolanti | rampicanti che si stringono a chi passa | Natura o Percezione | Prova Atletica o Acrobazia | Lieve | Contundente | — | Afferrato; 1 ora persa a liberarsi |
| 5 | Tempesta improvvisa | pioggia, vento e fulmini senza riparo | — | Salvezza Cos | Lieve | Nessuno | Nessuno | Affaticamento 1 (fino al riposo lungo) |
| 6 | Sabbie mobili | terreno traditore in palude | Sopravvivenza | Prova Atletica | Pericolosa | Contundente | — | Trattenuto; 1 ora per liberarsi |
| 7 | Frana di sassi | il versante cede sopra il sentiero | Percezione | Salvezza Des | Pericolosa | Contundente | Metà | Sentiero bloccato; 1 ora per aggirare |
| 8 | Ghiaccio sottile | lago gelato da attraversare | — | Prova Acrobazia o Sopravvivenza (restare in piedi) | Lieve | Nessuno | Nessuno | Affaticamento 1 (fino al riposo lungo) |
| 9 | Guado in piena | fiume alto e veloce | — | Prova Atletica | Lieve | Contundente | — | Trascinati a valle in un esagono adiacente |
| 10 | Nebbia densa | nessuna visibilità | — | Prova Sopravvivenza | Lieve | Nessuno | — | Il gruppo si perde; 1 ora persa |
| 11 | Gas di palude | bolle di gas velenoso | Percezione o Natura | Salvezza Cos | Lieve | Veleno | Nessuno | Avvelenato 1 ora |
| 12 | Spore velenose | funghi che rilasciano nubi | Natura | Salvezza Cos | Pericolosa | Veleno | Nessuno | Avvelenato 4 ore |
| 13 | Fosse mimetizzate | buche coperte da fogliame | Percezione | Salvezza Des | Lieve | Contundente | Nessuno | 1 ora per risalire |
| 14 | Rete di rami e campanelli | trappola di cacciatori | Indagare | Salvezza Des | Lieve | Nessuno | Nessuno | Trattenuti; 1 ora persa; i cacciatori sono allertati |
| 15 | Terreno scivoloso | pendio di fango o ghiaia | — | Salvezza Des | Lieve | Contundente | Nessuno | Prono; 1 ora persa a risistemarsi |
| 16 | Calore soffocante | ore di marcia sotto un sole cocente | — | Salvezza Cos | Pericolosa | Nessuno | Nessuno | Affaticamento 1 (fino al riposo lungo) |
| 17 | Freddo mortale | notte gelida | — | Salvezza Cos | Pericolosa | Nessuno | Nessuno | Affaticamento 1 (fino al riposo lungo); niente benefici dal riposo breve |
| 18 | Foresta di rovi | sentiero chiuso da spine | — | Prova Atletica | Lieve | Perforante | — | 1 ora per aprirsi un passaggio |
| 19 | Cunicolo che si restringe | passaggio sempre più angusto | — | Prova Acrobazia o Atletica | Lieve | Contundente | — | Incastrato; 1 ora per liberarlo |
| 20 | Albero cavo con api | favo gigante nel tronco | Natura o Percezione | Salvezza Cos | Lieve | Veleno | Metà | Avvelenato 1 ora |
| 21 | Statua che osserva | sembra seguire il gruppo con lo sguardo | Arcano o Indagare | Salvezza Car | Pericolosa | Necrotico | Metà | Maledetto: svantaggio ai tiri salvezza fino al riposo lungo |
| 22 | Cerchio di pietre che sussurra | voci che confondono | Arcano | Salvezza Sag | Pericolosa | Psichico | Metà | Spaventato 1 ora: svantaggio a prove e tiri per colpire |
| 23 | Rovine instabili | un soffitto che cede | Percezione | Salvezza Des | Pericolosa | Contundente | Metà | Via sbarrata; 1 ora per liberarla |
| 24 | Cancello rugginoso | chiuso, ma serve passare | — | Prova Strumenti da scasso o Forza | Lieve | Nessuno | — | 1 ora persa; il rumore attira attenzione |
| 25 | Pozzo avvelenato | acqua apparentemente buona | Natura o Medicina | Salvezza Cos | Pericolosa | Veleno | Nessuno | Avvelenato 8 ore |
| 26 | Fuoco di bosco | l'incendio avanza | — | Salvezza Des | Pericolosa | Fuoco | Metà | 1 ora per aggirare; il gruppo finisce in un esagono adiacente |
| 27 | Caverna con aria viziata | poco ossigeno, torce che si spengono | Sopravvivenza | Salvezza Cos | Lieve | Nessuno | Nessuno | Avvelenati 1 ora |
| 28 | Cadavere con trappola | oggetto prezioso su un cadavere sospetto | Indagare | Salvezza Cos | Pericolosa | Veleno | Metà | Avvelenato 8 ore |
| 29 | Albero caduto | strada bloccata | — | Prova Atletica o Strumenti da falegname | Lieve | Nessuno | — | 1 ora persa |
| 30 | Ponte di corda ingannevole | trucco ottico, il passaggio non è dove sembra | Intuizione o Percezione | Salvezza Des | Lieve | Contundente | Nessuno | Caduta; 1 ora persa |
| 31 | Vento allucinogeno | odori che alterano la mente | — | Salvezza Sag | Pericolosa | Psichico | Metà | Confuso 1 ora: svantaggio a prove e tiri per colpire |

## 4. Eventi ambientali (status e perdita di tempo)

Stesse colonne degli ostacoli. Quasi tutti senza danno: contano lo status e il tempo perso.

| # | Nome | Scena | Prova | Gravità | Danno | Se riesce | Effetto se fallisce |
|---|---|---|---|---|---|---|---|
| 1 | Nebbia disorientante | il gruppo perde la rotta | Prova Sopravvivenza | Lieve | Nessuno | — | Spostati in un esagono adiacente a caso; 1 ora persa |
| 2 | Tempesta violenta | vento e pioggia battente | Salvezza Cos | Pericolosa | Nessuno | Nessuno | Affaticamento 1 (fino al riposo lungo) |
| 3 | Fuochi fatui | luci che attirano nel bosco | Salvezza Sag | Lieve | Nessuno | Nessuno | Affascinati 1 ora; il gruppo viene condotto in un esagono adiacente |
| 4 | Caldo soffocante | marcia sotto il sole | Salvezza Cos | Lieve | Nessuno | Nessuno | Affaticamento 1 (fino al riposo lungo) |
| 5 | Gelo improvviso | temperatura in picchiata | Salvezza Cos | Lieve | Nessuno | Nessuno | Affaticamento 1 (fino al riposo lungo) |
| 6 | Nube di polline | aria carica di allergeni | Salvezza Cos | Lieve | Nessuno | Nessuno | Avvelenati 1 ora |
| 7 | Sciami di insetti | fastidio costante | Salvezza Cos | Lieve | Nessuno | Nessuno | Svantaggio a Percezione e Furtività fino al prossimo riposo |
| 8 | Frana sul sentiero | la strada è bloccata | Prova Atletica o Sopravvivenza | Lieve | Nessuno | — | 1 ora persa; il gruppo finisce in un esagono adiacente |
| 9 | Pioggia di cenere | aria irrespirabile | Salvezza Cos | Pericolosa | Nessuno | Nessuno | Accecati 1 ora |
| 10 | Brezza stregata | voci che confondono | Salvezza Sag | Lieve | Nessuno | Nessuno | Spaventati 1 ora: svantaggio a prove e tiri per colpire |
| 11 | Oscurità innaturale | cala il buio all'improvviso | Salvezza Sag | Pericolosa | Nessuno | Nessuno | Spaventati 1 ora: svantaggio a prove e tiri per colpire |
| 12 | Fiume in piena | il guado non è praticabile | Prova Sopravvivenza | Lieve | Nessuno | — | 1 ora persa; il gruppo finisce in un esagono adiacente |
| 13 | Sentiero che inganna | la strada sembra tornare allo stesso punto | Prova Indagare o Sopravvivenza | Lieve | Nessuno | — | 1 ora persa; tornano all'esagono precedente |
| 14 | Pollini narcotici | sonnolenza improvvisa | Salvezza Cos | Pericolosa | Nessuno | Nessuno | Affaticamento 1 (fino al riposo lungo) |
| 15 | Vento allucinogeno | odori che alterano la mente | Salvezza Sag | Pericolosa | Nessuno | Nessuno | Confusi 1 ora: svantaggio a prove e tiri per colpire |
| 16 | Fango profondo | ogni passo costa fatica | Prova Atletica | Lieve | Nessuno | — | 1 ora persa; Affaticamento 1 (fino al riposo lungo) |
| 17 | Branco in fuga | stampede che travolge il gruppo | Salvezza Des | Lieve | Contundente | Nessuno | 1 ora persa a riorganizzarsi |
| 18 | Acqua stagnante | sete e acqua sospetta | Salvezza Cos | Lieve | Nessuno | Nessuno | Avvelenati 8 ore se si beve |
| 19 | Sonno spezzato | notte disturbata da rumori e incubi | Salvezza Sag | Lieve | Nessuno | Nessuno | Il riposo lungo recupera solo metà PF e slot |
| 20 | Cielo che si oscura | giorno che diventa notte | Salvezza Sag | Lieve | Nessuno | Nessuno | Spaventati 1 ora: svantaggio a prove e tiri per colpire |
| 21 | Tempesta di fulmini | un cataclisma di nubi nere e saette: bisogna mettersi in salvo | Salvezza Des (mettersi in salvo) | Mortale | Fulmine | Metà | Affaticamento 1 (fino al riposo lungo) |
| 22 | Tornado di fuoco | una colonna di fiamme e vento che avanza: bisogna scappare | Salvezza Des (scappare in tempo) | Mortale | Fuoco | Metà | Affaticamento 1 (fino al riposo lungo) |

## 5. Incontri sociali

Formato: **Chi**: situazione. *Prove* · CD · cosa si ottiene o si perde.

1. **Mercante in difficoltà**: carro rotto sul sentiero. *Persuasione o Strumenti* · Media · ricompensa o informazioni
2. **Pellegrini**: gruppo di fedeli in marcia. *Religione o Persuasione* · Facile · benedizione o notizie
3. **Esattore di pedaggio**: posto di blocco con una tassa discutibile. *Persuasione, Inganno o Intimidire* · Media · passare gratis o pagare
4. **Cavaliere errante**: sfida a una gara non letale. *Atletica o Intrattenere* · Media · onore e un favore
5. **Guaritore ambulante**: offre rimedi. *Medicina o Intuizione* · Facile · cure o imbroglio
6. **Spirito gentile / raggirevole**: fantasma che chiede un favore o ne cerca l'inganno. *Religione, Intuizione o Persuasione* · Media · benedizione o maledizione

## 6. Situazioni dei mostri (si applicano ai combattimenti)

1. **Dormono**: possibile aggirarli o colpire di sorpresa. *Furtività*.
2. **In caccia**: puntano un'altra preda, il gruppo può intervenire o evitare.
3. **A difesa di qualcosa**: cuccioli, tesoro o territorio.
4. **Disposti a trattare**: parlare è un'opzione concreta. *Persuasione o Intuizione*.
5. **Stanno mangiando**: distratti, svantaggio alle prove di Percezione.
6. **In movimento**: stanno per attraversare il sentiero.
7. **Tendono un'imboscata**: sorpresa contro il gruppo (prova di Percezione passiva).
8. **In fuga**: scappano da qualcosa di più grosso.
9. **Affamati e disperati**: attaccano subito, ma accettano cibo.

## 7. Pericoli ambientali per il combattimento

1. **Nebbia**: copertura leggera, nessuno vede a più di 6 m.
2. **Terreno instabile**: terreno difficile e possibili cadute.
3. **Pioggia battente**: svantaggio alle prove di Percezione basate sull'udito.
4. **Rovi**: terreno difficile con danno minore a chi lo attraversa.
5. **Vento forte**: svantaggio agli attacchi a distanza.
6. **Acqua alta**: chi cade rischia di essere trascinato.
7. **Fuoco di bosco**: l'incendio si propaga ogni round.
8. **Pozza di fango**: Destrezza per non rimanere bloccati.
