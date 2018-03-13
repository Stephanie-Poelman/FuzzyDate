- tests

- na maand datum weergeven numeriek

- attribuut toevoegen waarmee je aantal dagen/maanden die worden weergegeven kan kiezen

- zorgen dat locale(talen) werkt. 

- checken of Date een echt een datum is (is NAN)


Locale based:
- Hoe weet onze javascript wat de locale (bvb en-GB) is(je kan opvragen aan browser) = navigator.language
- Een attribute/property maken zodat de gebruiker een andere locale kan kiezen (bvb locale="nl")
- Een "object" in onze javascript maken waar locales (die wij ondersteunen) in staan en de vertalingen die we willen (voor nu alleen maanden)

- Zorgen dat onze tweede formatter  (die nu Date.toDateString() is) de locale maanden gebruikt in dit formaat: 31 Januari 2018
- Zorgen dat elke locale een eigen default formaat heeft (zodat het er in het engels bvb Januari 31 2018 is)
- Zorgen dat er een attribute/property is zodat de bruiker een andere locale kan kiezen (bvb localeFormat="%m %y")


