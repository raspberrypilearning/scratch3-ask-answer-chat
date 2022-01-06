
Je kunt de `vraag`{:class="block3sensing"} en `antwoord`{:class="block3sensing"} blokken uit het `Waarnemen`{:class="block3sensing"} blokkenmenu gebruiken om een gesprek te voeren.

![Dialoog vragen met ja als invoer](images/ask-answer.png)

Voeg blokken toe aan een script op de sprite die een `vraag`{:class="block3sensing"} wil stellen:

```blocks3
ask [Did you find everything you wanted today?] and wait
if <(answer) = [yes]> then
say [That's fantastic!] for [2] seconds
else
say [Maybe I should add more items to my shop] for [2] seconds
end
```

**Fouten opsporen:** Controleer of je de opties in je code en in je antwoord correct hebt gespeld. Het is niet erg als je hoofdletters gebruikt, dus "Ja" en "JA" zullen overeenkomen met "ja".

Voeg meerdere vragen toe om een chatbot of een "niet-speler karakter" te maken waarmee je kunt praten.

**Tip:** Als je de sprite die een vraag stelt op `verdwijn`{:class="block3looks"} instelt, dan verschijnt de vraag in het invoerveld in plaats van als een tekstballon.

![Vraagdialoog met een erin een vraag](images/ask-hidden-sprite.png)

