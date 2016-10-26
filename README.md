# ResearchThesisMediatechnologies
Thesis voor de studie Mediatechnologie

# Hoofdvraag
De hoofdvraag van deze scriptie is: Hoe realiseren we een ontwikkelomgeving waarin niet-programmeurs, zoals 3D modellers en level designers, een efficiënte unieke Virtual Reality ervaring kunnen creëren in de Unreal Engine 4.

# Abstract 
Door de groeiende vraag naar virtual reality omgevingen zijn er steeds meer bedrijven gespecialiseerd in 3D visualisatie die met virtual reality aan de slag willen. Omdat deze bedrijven weinig tot geen ervaring met programmeren hebben en het programmeren van interactie in virtual reality momenteel een complexe taak is, word in deze scriptie gezocht naar een ontwikkelomgeving waarin niet-programmeurs die wel ervaring hebben met 3D ontwikkeling interactieve virtual reality omgevingen kunnen maken. Deze ontwikkelomgeving word gerealiseerd door de VRInteractions plugin voor de Unreal Engine 4. De plugin implementeert de virtual reality gerelateerde logica en koppelt deze aan een visuele programmeer taal. De plugin is ontwikkeld met een workflow die zich focust op gebruiksgemak en vrijheid voor de niet-programmeurs. Door middel van workshops en een gebruikstest word de conclusie getrokken dat niet-programmeurs zelfstandig omgevingen kunnen opzetten en interactief kunnen maken mits zij hulp kunnen krijgen van een programmeur.

# Inleiding
In een periode van 18 weken zijn er een reeks van basis componenten voor de \gls{ue4} ontwikkeld met als doel niet-programmeurs efficiënt interactie aan \gls{vr} demo’s te laten toevoegen.

De UE4 is gebruikt omdat deze een uitgebreid VS systeem heeft die het makkelijk maakt om simpele logica eenvoudig uit te drukken. Het VS systeem maakt het mogelijk voor niet-programmeurs om simpele logica toe te voegen zonder dat een programmeur nodig is. Dit zorgt voor een hogere productiviteit en kwaliteit.

# Conclusie
Om het ontwikkelen van interactieve 3D omgevingen mogelijk te maken voor niet-programmeurs is de VRInteractions plugin ontwikkeld. De plugin maakt het mogelijk om met een aantal simpele stappen VR omgevingen op te zetten en om bestaande omgevingen werkend te krijgen in VR.

Door het ontwikkelen met een workflow die prioriteit geeft aan vrijheid, experimenten en gebruiksgemak zijn de componenten iteratief ontwikkeld in samenwerking met de niet-programmeurs. Hierdoor is een intuïtieve koppeling gemaakt tussen Blueprints en VS.

Op basis van de gemaakte projecten en de taken van een programmeur hierin zijn de volgende componenten ontwikkeld:

* Een game mode voor een demo waarin de speler kan rondlopen en een voor een fly-through demo
* Een speler klasse per game mode
* Een component die verantwoordelijk is voor de input van de speler
* Een component die verantwoordelijk is voor de camera van de speler
* Een component die events afvuurt als er naar een object gekeken word
* Een HUD die het mogelijk maakt om op basis van de look events informatie te tonen
* Een 3D menu die zijn opties in een cirkel toont
* Een object wat verplaats kan worden door middel van ernaar te kijken.

Door de interactie te beperken tot kijken naar objecten is er voor gezorgd dat alle componenten in de VRInteractions plugin werken op de Oculus, Vive en de GearVR.

Met behulp van de plugin zijn meerdere projecten ontwikkeld door niet-programmeurs wat aantoont dat er succesvol een ontwikkelomgeving gerealiseerd is waarin niet-programmeurs in UE4 unieke virtual reality ervaring kunnen creëren.
