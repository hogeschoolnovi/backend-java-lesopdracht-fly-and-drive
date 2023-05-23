# backend-java-lesopdracht-fly-and-drive

- Maak een nieuw Console project aan in IntelliJ.
- Voeg een Main class toe met een main() methode.

- Maak een abstracte class _Vehicle_ aan met de volgend velden en (abstract) methods:
    - _speed (integer_
    - _weight (float)_
    - _startEngine()_
    - _turnOffEngine()_

- Maak de volgende interfaces:
    - _Flyable_ met methods: _takeOff(), land(), changeHeight()_.
    - _Driveable_ met methods: _accelerate(), brake(), changeGear()_.

- Maak de volgende afgeleide subclasses en gebruik de juiste interfaces:
    - _Car_
    - _Plane_
    - _FlyingCar_

- Instantieer objecten voor deze subclasses vanuit _main()_ en laat ze rijden en vliegen.

Bonus: Voeg een Aiport class toe met een lijst van voertuigen die kunnen vliegen. Genereer random de vulling voor de lijst.
