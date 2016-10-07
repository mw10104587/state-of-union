# Computational Journalism HW1
[iPython Notebook]()


## LSI Annotation

(19, '0.209*"soviet" + -0.158*"job" + 0.132*"democraci" + -0.127*"japanes" + -0.114*"program" + -0.112*"1942" + -0.093*"hitler" + 0.085*"savag" + -0.084*"nurs" + 0.081*"tonight"')
I think this one is pretty clear that they are talking something Japanese, Hitlar and Soviet are all involved and happened between 1939-1945.

(35, '-0.129*"democraci" + 0.115*"wool" + -0.096*"1892" + -0.089*"seminari" + 0.087*"missil" + -0.085*"california" + 0.085*"..." + -0.084*"1890" + 0.076*"savag" + 0.071*"sheep"')
This one seems to care a lot about sheep and wool. I searched and found his name -- Grover Cleveland, he indeed cares a lot about farmers and veterans.

(0, '-0.093*"program" + -0.079*"upon" + -0.066*"tonight" + -0.066*"help" + -0.062*"territori" + -0.061*"mexico" + -0.060*"job" + -0.060*"bank" + -0.058*"indian" + -0.058*"subject"')
Most of them are negative and a lot of documents seems to have a large probability of dropping into this topic, this might just be a topic that's really far away from other topics.

(17, '-0.119*"kansa" + 0.117*"job" + 0.108*"oil" + -0.099*"communist" + -0.093*"1890" + 0.090*"speci" + 0.090*"1869" + 0.088*"enemi" + -0.088*"1892" + -0.088*"democraci"')
I guess this kind of speech mentioned a lot of data or historical events during the State of the union speech. 

(64, '-0.096*"cabl" + -0.083*"1973" + 0.083*"soviet" + -0.081*"..." + 0.071*"eight-hour" + 0.068*"exchequ" + 0.067*"battleship" + 0.062*"scout" + 0.060*"submarin" + 0.058*"1888"')
I am guessing this is during the war since it's related to soviet, battleship, submarine and cables. I looked for speeches that has higher than 20% probability of being categorized in this topic, it's an event about going to WWI.

(93, '-0.099*"cabl" + 0.090*"wool" + -0.074*"eight-hour" + 0.071*"decre" + 0.063*"spanish" + -0.059*"seed" + -0.057*"hire" + 0.057*"democraci" + 0.057*"nomine" + 0.056*"1975"')
I searched for documents with probability higher than 15% being in this topic(since there's no document higher than 20% for this). This kind of documents might be talking about Europe governments and decrees.

(37, '0.113*"saddam" + 0.106*"1973" + 0.090*"iraq" + -0.087*"nuclear" + -0.085*"terrorist" + 0.084*"vietnam" + -0.073*"poverti" + 0.072*"atom" + -0.069*"seminari" + -0.068*"emancip"')
Speech about USA having problem with Iraq, Saddam and terrorist.

(70, '-0.108*"1973" + 0.092*"acr" + 0.080*"greytown" + 0.075*"nomine" + 0.069*"cyan" + -0.064*"1884" + 0.064*"1893" + -0.064*"decre" + -0.060*"polygami" + 0.058*"huerta"')
Speech about USA tackling Victoriano Huerta. It's still probably about war since Cyane seems to be a ship.

(77, '0.105*"wool" + -0.077*"texa" + 0.066*"disavow" + -0.064*"unrest" + -0.062*"eighti" + -0.062*"convent" + 0.058*"panama" + 0.055*"communist" + -0.055*"1878" + -0.055*"stipul"')
I guess there's an unrest in Panama? No not at all, I don't know what is this category about.

(66, '-0.096*"program" + 0.093*"inflat" + -0.078*"unrest" + 0.077*"democraci" + -0.075*"circuit" + -0.068*"democrat" + 0.068*"billion" + -0.064*"challeng" + -0.063*"panama" + -0.062*"1932"')
I think this kind of topic is also pretty general, billion might be speakers highlighting how much money they took or spent from the taxpayer.



# LDA Annotation
LDA doesn't have negative features which makes it a little more easier to understand intuitively. LDA has a minimum probability setting for features, making the result more cleaner. But LDA seems to take a little longer time on my laptop.


(111, '0.002*job + 0.002*iraq + 0.002*program + 0.002*today + 0.002*iraqi + 0.002*help + 0.001*tonight + 0.001*terrorist + 0.001*achiev + 0.001*communist')
This looks like a combination of a lot of general terms like "tonight, I am talking in front of you...", like we got to make more "jobs". But it also includes two iraq related terms.

(86, '0.002*mexico + 0.001*cabl + 0.001*mexican + 0.001*1847 + 0.001*1846 + 0.001*territori + 0.001*steamer + 0.001*indemn + 0.001*ironclad + 0.001*telegraph')
A topic about mexico(mexican, mexico) and cables(cable, telegraph).

(45, '0.002*sea-men + 0.001*natchez + 0.001*esq. + 0.001*commission + 0.001*cathol + 0.001*french + 0.001*majesti + 0.001*algier + 0.001*country-men + 0.001*regenc')
A topic of relatively old terms like sea-men and country-men. 

(4, '0.003*wool + 0.002*kid + 0.002*markwel + 0.002*tonight + 0.002*1911 + 0.001*statut + 0.001*panama + 0.001*anti-trust + 0.001*drug-fre + 0.001*today')
A topic about fighting drugs for kids. year: 1990

(21, '0.001*nontax + 0.001*mandamu + 0.001*royalti + 0.001*hinder + 0.001*bushel + 0.001*circuit + 0.001*valuat + 0.001*tariff + 0.001*centum + 0.001*reclam')
tax related, including nontax, tariff. I guess bushel comes along as well.

(25, '0.002*seventi + 0.002*clean + 0.002*program + 0.001*wool + 0.001*sheep + 0.001*tariff + 0.001*air + 0.001*today + 0.001*blame + 0.001*america')
farmer related topics. Wool, sheep, tariff. Also about environment, because of clean and air.

(87, '0.003*program + 0.002*communist + 0.002*atom + 0.001*1951 + 0.001*help + 0.001*laugh + 0.001*korea + 0.001*disarma + 0.001*curtain + 0.001*fight')
World War two related. Atom(nulcear), fight, communist, disarm

(66, '0.003*1973 + 0.002*soviet + 0.002*domingo + 0.002*program + 0.001*san + 0.001*goal + 0.001*spend + 0.001*texa + 0.001*plagu + 0.001*i.e.')
I don't think this means anything to me.

(27, '0.000*timidli + 0.000*label + 0.000*partit + 0.000*importantli + 0.000*rid + 0.000*arabl + 0.000*thirty-two + 0.000*paint + 0.000*blot + 0.000*178')
I don't think this means anything

(32, '0.002*unrest + 0.001*antagon + 0.001*dyestuff + 0.001*storag + 0.001*interst + 0.001*programm + 0.000*enmiti + 0.000*workman + 0.000*malevol + 0.000*shipment')
It feels like some pretty industrial topic, since it has storage, dyestuff, workman and shipment in it.


# How State of union speech has changed over time?
## Algorithm
I think my algorithm is really boring, it just sums up the probability of all ten (or more) years' topics. I considered normalizing, but I'm not sure on what, since document length is already removed from this feature. I think this algorithm has a really big problem, there are some common topics that almost every document includes, this sums them up and show them in the very front. 


## Observations
However, I think we can still see a little bit of pattern of chronological events in the result. For example, you see a lot more 18xx appearing in the several first decades. I also found that in the State of union speech, democracy gets mentioned less nowadays. Also it's quite obvious that this algorithm tend to group similary things together, for example ['lake','tribe','forest'], it sort of tells the latent semantic part, but it doesn't necessarily always match to a certain event, but a topic instead.


## Matching the historical events
We can find bank, deficit and unemployed around the time of 1931-1940, but also in 1921 and 1951. 
I think this showed WWII pretty clear that it showed plane, fighter, nazi and hitler and several war related terms.
It also uniquely showed al-qaida in the 2001-2010 period. 







