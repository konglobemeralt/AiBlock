# Lär godis och plastmuggar att spela nim! 

Egentligen behövs inte ens en dator för att göra den här typen av smarta saker, på samma sätt som används för att lära en dator att känna igen olika saker går det faktiskt att lära några plastmuggar och godisar att spela enkla spel! 


För att visa detta ska vi spela spelet Nim som går ut på att två spelare turas om att ta olika antal spelbrickor ifrån en rad av fem spelbrickor. Den spelare som tar den sista spelbrickan förlorar och under varje omgång får en spelare ta en, två eller tre spelbrickor.  

(Det sak som gör Nim spelciellt lämpat är att det alltid går att vinna nim om en bara följer en viss algorithm, det vill säga även om barnen inte kan eller kommer på den så kommer muggarna med godis efter några omgångar följa den till 100% och alltid vinna. Algoritmen är helt enkelt att vilket antal spelblirckor som motståndaren än väljer att ta så ska du ta ett antal som gör att det totalt försvunnit fyra under den omgången. Exempelvis, motspelaren tar en så du tar tre. Motspelaren tar två så tar du också två och så vidare. Den här strategin fungerar för 5, 9, 13 eller större antal brickor. (4x + 1) ) 

 

Vi delar upp oss i mindre grupper på fyra personer. I varje grupp ska en person vara "människan" och de andra ska tillsammans representera godis-plastmuggs-datorn.  

(Enklast är att spela med 5 spelbrickor då detta ger färre iterationer.)  
 
Varje datorspelare har fått en mugg innehållandes tre olika godisar. En blå godis som representerar att ta bort 3 spelbrickor ifrån planen, en orange som representerar att ta bort 2 och slutligen en gul som representerar att ta bort 1 godis. (Färgerna är givetvis godtyckliga) 

Datorspelarna börjar spelar efter människan har gjort sitt drag och vem av datorspelarna som kommer att göra ett drag under den turen beror på hur många spelbrickor som ligger kvar. Det vill säga, en av datorspelarna har ansvaret att slumpmässigt dra en godis ur sin mugg när det är 4 spelbrickor kvar, en annan när det är 3 och den sista när det är 2 kvar på spelplanen. Ingen behöver dra när det endast är en bricka kvar för i det fallet har datorn ändå förlorat.   

När en datorspelare drar en godis händer det intressanta. Om godisens färg betyder att datorspelarna förlorar, det vill säga plockar upp den sista spelbrickan eller fler än det finns spelbrickor kvar, får den spelaren om den vill äta upp den godisen! (Negative reinforcement för "datorn", ett dåligt val i en situation elimineras.) 

Om det slumpade valet däremot istället leder till att människospelaren får plocka upp den sista spelbrickan så lägger vi istället tillbaka godisen i glaset och lägger till ytterligare en av samma färg i den muggen! (Positive reinforcement) 


Om spelet spelas tillräckligt länge kommer efter ett tag de olika muggarna endast innehålla de färger som leder till vinnande drag för sina respektive antal. Vi har helt enkelt lärt godisarna att spela och vinna nim. Nu skulle du kunna utmana en kompis eller dina föräldrar att spela mot godisdatorn och alltid vinna! 

(Efter att barnen har spelat kanske man kan gå igenom vad den vinnande strategin i Nim är, beskriven ovan, och visa hur godisarna nu är en representation av detta, och kanske viktigast av allt, prata om att godisdatorn lärde sig detta utan att de kände till just den strategin. Här kan man kanske också prata lite om vikten av att lära datorn rätt saker. )

 

 
