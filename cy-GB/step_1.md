
Galli di ddefnyddio'r blociau `gofyn`{:class="block3sensing"} ac `ateb`{:class="block3sensing"} o'r ddewislen blociau `Synhwyro`{:class="block3sensing"} i gael sgwrs.

![Deialog gofyn gyda do fel mewnbwn](images/ask-answer.png)

Ychwanega'r blociau i sgript ar y corlun fydd yn `gofyn`{:class="block3sensing"} cwestiwn:

```blocks3
ask [Ddes di o hyd i bob dim roeddet ti eisiau heddiw?] and wait
if <(answer) = [do]> then
say [Mae hynny'n wych!] for [2] seconds
else
say [Falle ddylwn i ychwanegu mwy o eitemau i fy siop] for [2] seconds
end
```

**Difa chwilod:** Gwna'n siŵr dy fod wedi sillafu'r opsiynau yn gywir yn dy god ac yn dy ateb. Mae'n iawn os wyt ti'n defnyddio priflythrennau, felly bydd "Do" a "DO" yn cyfateb i "do".

Ychwanega fwy nag un cwestiwn i greu bot sgwrsio neu gymeriad nad yw'n chwaraewr y galli di siarad ag ef.

**Awgrym:** Os wyt ti'n `cuddio`{:class="block3looks"} y corlun sy'n gofyn cwestiwn, yna bydd cwestiwn yn ymddangos y tu mewn i'r blwch mewnbwn yn lle fel swigen siarad.

![Deialog gofyn gyda cwestiwn ynddo](images/ask-hidden-sprite.png)

