#Hur lär sig en dator egentligen saker?

Nim är ett mattematiskt spel I vilket två spelare turas om att ta ett antal spelbrickor ifrån en uppbyggd rad. Antalet som spelaren kan ta under sin tur är 1, 2 eller 3. Den spelare som tar den sista spelbrickan förlorar.  En sak som gör NIM spelciellt lämpat för våra ändamål är att det alltid går att vinna NIM om en bara följer en viss algorithm.  

 

Exempel, vi startar med 13 spelbrickor och låter motspelaren börja. Vilket antal spelblirckor som motståndaren än väljer så ska du ta ett antal som gör att det totalt försvunnit fyra under den omgången. Exempelvis, motspelaren tar en så du tar tre. Motspelaren tar två så du tar också två.  

 

Den här strategin fungerar för 5, 9, 13 eller större antal brickor.  (4x + 1) 

 

Enklast kanske är att spela med 5 spelbrickor då detta kommer ge färre iterationer.  

 

Dela upp deltagarna I mindre grupper om fyra personer. I varje grupp ska en person vara den mänskliga spelaren och de övriga representera datorn.  

 

Mänskan ska helt enkelt försöka göra sitt bästa och dator spelarna ska helt enkelt spela genom slumpen på ett sätt som kommer att förklaras.  

 

Varje datorspelare har fått en mugg innehållandes ett antal olika godisar.  En blå godis som representerar att ta bort 3 spelbrickor, en orange som representerar att ta bort 2 och slutligen en gul som representerar att ta bort 1 godis. Varje datorspelare kommer att göra sitt drag beroende på hur många spelbrickor som ligger kvar. Det vill säga, en datorspelare gör sitt drag när det är 4 spelbrickor kvar, en annan när det är 3 och den sista när det är 2.  

 

Efter att den mänskliga spelaren har gjort sitt drag är det datorns tur att spela.  Säg att det då ligger 3 spelbrickor kvar på bordet. Den datorspelare som ska göra sitt drag när det är 3 spelbrickor på bordet drar nu en godis på måfå ur sin mugg och tar bort så många som godisens färg antyder. 

 

Och här kommer vi till det intressanta. Om godisens färg betyder att datorspelarna förlorar, det vill säga plockar upp den sista eller fler än det finns spelbrickor kvar får den spelaren om den vill äta upp! (Negative reinforcement för "datorn", ett dåligt val I en situation elimineras.) 

 

Om det slumpade valet däremot leder till att den mänskliga spelaren istället förlorar och får plocka upp den sista så lägger vi istället tillbaka godisen I glaset och lägger till ytterligare en av samma färg! (Positive reinforcement) 

 

Om spelet spelas tillräckligt länge och alla val görs kommer efter ett tag de olika muggarna endast innehålla de färger som leder till vinnande drag för sina respektive antal.  

 
