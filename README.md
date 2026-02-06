# Mitt-AI-projekt - Building AI course project
## Summary
Detta AI-projekt syftar till att analysera text och avgöra om en person uttrycker glädje eller nedstämdhet utifrån en mening. Byggt som ett Building AI course project, använder modellen nyckelord med positiv eller negativ laddning för att identifiera känslor. Projektet är inspirerat av behovet att förstå människors känslomässiga tillstånd genom text, något som kan vara användbart i allt från sociala medier och kundservice till psykisk hälsa.

Modellen fungerar genom att först definiera listor med ord som signalerar positiva och negativa känslor, exempelvis ord som “glad”, “älskar” eller “fantastiskt” för positiva uttryck och “ledsen”, “tråkigt” eller “sorgligt” för negativa uttryck. När en mening matas in, jämför AI:n orden i texten med dessa listor och avgör om övervägande positiva eller negativa ord förekommer. Resultatet visas sedan som “GLAD :)” eller “LEDSEN :(”, vilket gör det enkelt för användaren att tolka känslan.

Syftet med projektet är inte att skapa en perfekt känsloanalys, utan att demonstrera hur AI kan användas för att tolka text och ge en grundläggande känsloförståelse. Projektet är också ett exempel på hur enkelt data och enkla regler kan kombineras med programmering för att skapa användbara AI-lösningar.

Framtida förbättringar kan inkludera att använda mer avancerade AI-tekniker som maskininlärning eller neurala nätverk för att bättre förstå kontext, ironi och subtila känslor i text. Projektet erbjuder en praktisk introduktion till textanalys och visar på AI:s potential att analysera och tolka mänsklig kommunikation
## Bakgrund 
Det löser problemen att kunna identifiera om människor är glada eller ledsna. Men också: 
- AI att tolka text. 
## Hur det används 
 This is how you create code examples:
```python 
def main():
 glada_ord = ['glad', 'kul', 'älskar', 'fantastiskt']
 ledsna_ord = ['ledsen', 'tråkigt', 'hatar', 'sorgligt']

identifierat glada_ord = return "GLAD :)"
identifierat ledsna_ord = return "LEDSEN :("

# Testa programmet
mening = input "Skriv en mening")
print ("AI gissar") 

```
