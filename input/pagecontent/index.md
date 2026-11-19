<!--
  Schritt 7: Startseite des Implementation Guides
-->

### Use Case

Dieser Implementation Guide beschreibt die strukturierte Erfassung von Arzneimittelallergien in einer Hausarztpraxis. Eine Ärztin oder ein Arzt dokumentiert die Allergie einer Patientin oder eines Patienten anhand standardisierter FHIR-Daten. Die Notfallstation kann diese Informationen nutzen, um bekannte Allergien bei der Behandlung zu berücksichtigen und unerwünschte Arzneimittelreaktionen zu vermeiden.

### Scope

Dieses IG basiert auf CH Core und erweitert das bestehende Profil AllergyIntolerance für die Dokumentation von Arzneimittelallergien.

Es definiert Anforderungen an den klinischen Status, die verwendeten Allergiecodes, die Kritikalität, den Beginn der Allergie, die erfassende Person und mögliche Reaktionen.

Andere Allergiearten, beispielsweise Lebensmittel- oder Umweltallergien, sind nicht Bestandteil dieses IG.

### Artefakte

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): FHIR-Profil zur standardisierten Erfassung von Arzneimittelallergien mit definierten Pflichtfeldern, Codes und Validierungsregeln.
* [Penicillinallergie bei Anna Muster](AllergyIntolerance-PenicillinAllergieAnna.html): Beispiel einer bestätigten Penicillinallergie mit hoher Kritikalität und dokumentierter Reaktion (Urtikaria).

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

Enea Stähelin

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
