# Varför Flexbox
Flexbox passar för aktivitetskorten då ska ligga på en rad (endimensionellt), med luft, och bryta när de inte får plats. Med Flexbox behöver man inte manuellt räkna ut width of margins för korten, vilket också behöver ändras när man tar bort eller lägger till mer kort.

`.kort-rad` är klassen med flex (bokhyllan), alla `article.kort` är flex-items (böckerna). Korten ligger på en rad, och bryter när de inte får plats (`flex-wrap`), med luft emellan (`gap`).

Grid är till för tvådimensionella layout:er, när man behöver rader och kolumner samtidigt.

# Feedback
FEEDBACK: div istället för semantiska taggar på korten -> ändra till `article`.
FEEDBACK: inline stil (`style=""`) -> ny klass och ny regel i CSS fil.
FEEDBACK: margin i .card stilen -> gap på förälder div:en.