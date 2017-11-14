# Perseus-Cicero
Conversion des textes de Cicéron de PerseusDL/canonical-latinLit

Référent : Thibault Clérice, @ponteineptique

- Difficulté : 8/10
- Répétitivité : 9/10
- Schéma à utiliser : Epidoc (en mode édition)
- Minimum à convertir : 7
- Source du corpus : https://github.com/PerseusDL/canonical-latinLit
- Visualisation existante du corpus : https://cts.dh.uni-leipzig.de


Schéma : 

```xml
<?xml-model href="http://www.stoa.org/epidoc/schema/8.19/tei-epidoc.rng"	schematypens="http://relaxng.org/ns/structure/1.0"?>
<?xml-model href="http://www.stoa.org/epidoc/schema/8.19/tei-epidoc.rng"	schematypens="http://purl.oclc.org/dsdl/schematron"?>
```

Modèle pour les change log ([Exemple](https://github.com/PerseusDL/canonical-latinLit/blob/master/data/phi1294/phi002/phi1294.phi002.perseus-lat2.xml#L60-L62): 

```xml
<change when="2017-11-01" who="Thibault Clérice">Correction des milestones sections en div</change>
```
