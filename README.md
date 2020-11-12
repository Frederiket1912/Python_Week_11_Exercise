# Python_Week_11_Exercise

Data: https://api.statbank.dk/console#data

*Kort resume af brug af api'et:*  
Vælg "Hent data"  
Vælg type af kald "GET"  
Insæt i Tabel-id: "KVUARNY1" (Handler om forskellige aldersgruppers brug af forskellige former for nyheder)  
Vælg format "CSV"  
Vælg adskiller "Semikolon"  
Klik på "Variabel- og værdikoder" for at udvælge data.

Brug kun data for 2019 i alle opgaverne.

1) Brug api'et til finde ud af hvor meget 16-24 årige benytter sig af de forskellige nyhedsformer.  
Vis resultatet i et sorteret søjlediagram.

2) Lav en klasse der har fields "age", "news_data", "most_used_news_type" and "least_used_news_type". (vælg selv navn til klassen)  
"age" er aldersgruppen.  
"news_data" er en liste af tupler med (nyhedsform, procent brugt af den aldersgruppe)
"most_used_news_type" er en tuple fra listen "news_data" med højest procent.  
"least_used_news_type" er en tuple fra listen "news_data" med lavest procent.  
Lav getters til de forskellige fields.

3) Lav en metode i klassen der kan skrive til en fil. Kald filen den værdi der er i "age" fieldet.  
Skriv "most_used_news_type" på første linje af filen, skriv "least_used_news_type" på anden linje.


 


