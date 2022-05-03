# J296-Final-Project---Data-Journalism-
By Vera Watt 

Story 800-1000 words 

## "Ukrainian refugee crisis 2022"

### Data Analysis Process
I used data of countries that accepted more than 10 thousand Ukrainian refugees by April 9, 2022.

I downloaded the data from [here](https://www.google.com/url?q=https://databank.worldbank.org/indicator/NY.GDP.MKTP.CD/1ff4a498/Popular-Indicators&sa=D&source=docs&ust=1651611829608631&usg=AOvVaw12VStu5enxiblZPvcq51A6) (countries’ GDP for 2020 the most recent year). Upload it to Google Drive, and open it with Google Sheets.
 

Also I  collect data from different resources: 

https://www.unrefugees.org/

https://cis.org/

https://www.npr.org/

https://www.usatoday.com/in-depth/graphics/2022/03/19/millions-ukrainian-refugees-fleeing-where-they-going-ukraine-war/7034809001/

https://www.npr.org/2022/04/13/1092091451/ukrainians-have-arrived-at-the-u-s-mexico-border-by-the-thousands

https://data2.unhcr.org/en/situations/ukraine

https://user-images.githubusercontent.com/99926461/166569859-d5a17b8d-4909-403a-9ed6-b3e55e2daf9e.png

 
#### The following are five questions and step-by-step answers based on the data sets:
 
 
## Questions: 
 
### 1. What is the max and min GDP number (in USD) of the countries that accept refugees, and what was the average number? I was trying to determine if there was a positive correlation between a country’s wealth and the amount of refugees it would accept.
 
Sort the column "GDP” in the data sheet from A->Z
 
            Explanation: First I did this formula : =MIN(E2:E34) and =MAX(E2:E34)
            Max number: $21 (trillion) USA 
            Min Number : $12 (billion)  Moldova 
 
After I  did this formula to find the average number : =AVERAGE(E2:E34)
Average GDP number: $1,293 billion

![Screenshot for min and max GDP](/Q1.png) 

 
 ###     2. Which country had more and less refugees per 1,000 citizens that were accepted?  
        
        I use this formula to find that number. 
         =H34/J34*1000
(Column H number of refugees that left to country / Column J Population of the country )
Moldova has the most refugees
USA has least refugees  

![Screenshot that shows country with less refugees](/Q2.png)  


 
###     3. What factor, distance from Ukraine or wealth of a host country was most important in determining how many refugees would be accepted?
 
Sort the column "GDP RANK" in the data sheet from Z->A (or greatest to smallest), like so:
 
        =RANK.AVG($E$2:$E$34,$E$2:$E$34,0)
        =MIN(E2:E34)
        =MAX(E2:E34)
        =AVERAGE(E2:E34)
        
        
![Screenshot that shows GDP RANK ](/Q3.png)        



###     4. In which countries do most people go NATO or non-NATO; EU/non-EU?
 
       Pivot table : Sheet1!A2:M34 with NATO or EU in the row section and the metrics in the values section
 
Most people go to NATO and EU countries 

        
 ![Screenshot that shows country Nato/not-nato ; EU/Not EU numbers of people](/Q4.png)    
 
 
 ###    5. Given the data at hand, which factor drove the influx of the biggest number of refugees to neighboring countries, distance from Ukraine or a country’s wealth?
  Refugees as a percentage of GDP: 
 
       Formula =H2/E2 
       (Column H is refugees and Column E is GDP) 
       
 ![Screenshot that shows percentage of GDP](/Q5.png)  
 
 
  
 ![Screenshot of countrys with the most number of refugees](/Q5-2.png) 
  
  
 
  

 
### Story sumary : 
 
## "Ukrainian refugee crisis 2022"

More than five million people left Ukraine after the Russian armed Invasion on February 24th. This is the most massive crisis in Europe since the Second World War. Most of the refugees - about three million people - were accepted by Poland. 
Two-thirds of Ukrainian children left their homes. This number includes both those who left the country and internally displaced persons. Refugees are primarily women and children. The Ukrainian government does not release men aged 18 to 60 from the country as subject to mobilization. The majority of the people are trying to escape to neighboring countries: Poland, Moldova, Hungary. The main factor is distance because people hope to return home very soon. Another more significant factor is the friendly nature of the country that could provide food and a place to stay. Countries with the smallest GDP, like Moldova, accept more people from Ukraine than countries with very high GDB.  

At the same time, according to the UN, 870,000 refugees who left Ukraine after the Russian invasion returned to their homeland. It is not reported whether they are included in the latest updated statistics of the organization. The UN has data only for those European countries where refugees have crossed the border. But this does not mean that people escaping from the war are accommodated only in Poland, Romania, Moldova, Hungary, and Slovakia. For example, more than 200 thousand people have already arrived in Germany. Tens of thousands - France. Refugees are being hosted by other countries, particularly the Czech Republic and Ireland, as well as the United Kingdom, which has left the European Union.

According to UN estimates, at least 10 million people have left their homes and will leave Ukraine in the future. This is the most significant number of refugees in Europe in post-war history. For comparison: during the migration crisis of the mid-2010s, less than 1.5 million people arrived in the European Union.
Before the invasion, Ukraine had a population of 37 million in the regions under government control, excluding Russia-annexed Crimea and the pro-Russian separatist-controlled areas in the east.

And another tragic indicator: two-thirds of Ukrainian children were forced to leave their homes.
“This war has caused one of the fastest large-scale children's movements since World War II,” said UNICEF Executive Director Katherine Russell.

According to the Office of the Prosecutor General of Ukraine, on March 24, 128 children have died in the country since the beginning of the war, and more than 170 have been injured. The Office of the UN High Commissioner for Human Rights on March 23 reported the death of 81 children in Ukraine.

Here is a breakdown of how many Ukrainian refugees have fled to neighbouring countries:

### Poland
Nearly six out of 10 Ukrainian refugees -- 2,720,622 so far -- have crossed into Poland, according to the UN.
Many people who go to Ukraine's immediate western neighbours travel on to other states in Europe's Schengen open-borders zone.
The World Health Organization said Poland had made 7,000 hospital beds available for the sick and wounded from Ukraine, of which 20 percent were currently in use.
Some 652,000 people have crossed from Poland into Ukraine since the war began.
Before the crisis, Poland was already home to around 1.5 million Ukrainians, chiefly migrant workers.

### Romania
A total of 726,857 Ukrainians entered the EU member state, including a large number who crossed over from Moldova, wedged between Romania and Ukraine.
The vast majority are thought to have gone on to other countries.

### Russia
Another 484,725 refugees have sought shelter in Russia.
In addition, 105,000 people crossed into Russia from the separatist-held pro-Russian regions of Donetsk and Lugansk in eastern Ukraine between February 18 and 23.

### Hungary
A total of 447,053 Ukrainians have entered Hungary.

### Moldova
The Moldovan border is the closest to the major port city of Odessa. A total of 419,499 Ukrainians have crossed into the non-EU state, one of the poorest in Europe. Most of those who have entered the former Soviet republic of 2.6 million people have moved on but an estimated 100,000 remain, including 50,000 children -- of whom only 1,800 are enrolled in schools. "Refugee children from Ukraine have fled a brutal war and have arrived dispossessed and traumatised in Moldova. They are very vulnerable and need immediate support," said Yasmine Sherif, Director of Education Cannot Wait. "Public schools are open to refugee children; however, the capacity is over-stretched and there is a need for urgent mental health and psycho-social services, sanitation, and teachers."

### Slovakia
A total of 329,597 people crossed Ukraine's shortest border into Slovakia.

### Belarus
Another 22,827 refugees have made it north to Russia's close ally Belarus.

### USA 
The initial U.S. response was to provide people fleeing Ukraine with economic and humanitarian assistance where they are in neighboring European countries and consider for resettlement into the United States only those Ukrainians who are “unsafe” in the countries they fled to (which is, in essence, the real purpose of refugee resettlement).
One month into the conflict, President Biden, under pressure from refugee advocates, committed in Brussels to resettling 100,000 Ukrainians in the United States. Those with family members already living here will be given priority.
Ukrainians fleeing the war have been arriving at Mexico's northern border cities by the thousands. There, they are presenting themselves to U.S. border agents and asking for temporary admission to the United States on humanitarian grounds. Thousands of Ukrainians have been let in — availing themselves of the avenues that the Biden administration has opened to ease their admission into the U.S. faster than people who have come from other countries.




### Sources:

#### Katherine Russell, UNICEF Executive Director

#### Mark Danner, War Journalist   

#### Michelle Bachelet, UN High Commissioner for Human Rights 

#### Iryna Venediktova, General Prosecutor of Ukraine

#### Okana and Oleg Matiaschuk, Ukrainian Refugees in USA 


### Other sources: 

https://cis.org/

https://www.unrefugees.org/

https://www.npr.org/

https://www.usatoday.com/in-depth/graphics/2022/03/19/millions-ukrainian-refugees-fleeing-where-they-going-ukraine-war/7034809001/

https://www.npr.org/2022/04/13/1092091451/ukrainians-have-arrived-at-the-u-s-mexico-border-by-the-thousands

https://data2.unhcr.org/en/situations/ukraine

https://ru.wikipedia.org/wiki/%D0%9C%D0%B8%D0%B3%D1%80%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D1%8B%D0%B9_%D0%BA%D1%80%D0%B8%D0%B7%D0%B8%D1%81,_%D0%B2%D1%8B%D0%B7%D0%B2%D0%B0%D0%BD%D0%BD%D1%8B%D0%B9_%D0%B2%D1%82%D0%BE%D1%80%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%D0%BC_%D0%A0%D0%BE%D1%81%D1%81%D0%B8%D0%B8_%D0%BD%D0%B0_%D0%A3%D0%BA%D1%80%D0%B0%D0%B8%D0%BD%D1%83#cite_note-%D0%B0%D0%B2%D1%82%D0%BE%D1%81%D1%81%D1%8B%D0%BB%D0%BA%D0%B06-1 

https://www.dw.com/en/germany-agrees-2-billion-in-financial-support-for-ukrainian-refugees/a-61402717 

https://www.reuters.com/world/europe/tale-cruelty-ukraine-refugee-exodus-nears-36-million-2022-03-23/

https://www.schengenvisainfo.com/news/110000-refugees-have-arrived-from-ukraine-in-spain-until-now-spanish-pm-reveals/

https://www.interno.gov.it/it/notizie/85057-i-profughi-arrivati-finora-italia-dallucraina

https://www.hurriyetdailynews.com/some-58-000-ukrainians-take-shelter-in-turkey-says-minister-172411

https://kurier.at/politik/inland/42000-ukraine-gefluechtete-mit-vertriebenenstatus-in-oesterreich/401958248 

https://www.dnoticias.pt/2022/4/5/304977-portugal-aceita-mais-de-28-mil-pedidos-de-proteccao-temporaria/ 

https://user-images.githubusercontent.com/99926461/166575068-921d6b8a-240c-4a83-adcc-b08027fefdd4.png 


