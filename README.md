### Interactive maps of new windmills in Bayern and Germany

Keywords, tags: windpower windmill windturbine Germany Bayern maps

For maps of new windmills in Bayern and Germany, go to \
https://denis-bz.github.io/New-Windmills-in-Bayern/ or \
https://denis-bz.github.io/New-Windmills-in-Bayern/newwindmills-DE.html \
These maps show windmills running since 2024, or planned: in Bayern 333, in all Germany 8263.
The data is from 1 January 2026,
https://www.marktstammdatenregister.de/MaStR  Gesamtdatenexport_20260101_25.2.zip .
Files `BY-*.csv` and `DE-*.csv` under https://github.com/denis-bz/New-Windmills-in-Bayern
have 1 line for each windmill, like
```
 AGS State   MW     Lat     Lon Thi Rotor       Date     Lkr  Place            Type
9184    BY 5.56 47.9519 11.6891 167   160 2025-05-28 München  Sauerlach  E-160_EP5_E3
9184    BY 5.56  47.938 11.7195 167   160 2025-07-07 München  Aying      E-160_EP5_E3
9184    BY 5.56 48.0216 11.7651 167   160 2026-11-18 München  Höhenkirchen-Siegertsbrunn E-160
...
```

These new windmills are BIG, around 250m:
e.g. 167m turbine height `Thi` + 80m Rotor diameter / 2.
Zoom in on ones in your area.


#### How profitable are windmills in Germany, from EEG tax money ?

"Installed power",
[Installierte Leistung](https://de.wikipedia.org/wiki/Installierte_Leistung)
is the *maximum* a windmill can generate, at windspeeds around 40 km/h.
Over a whole year, the electricity actually generated might be 20 % to 40 % of the maximum.
This is called "yield" (Ertrag) or "capacity factor".
It depends on actual windspeeds at a given site, and on turbine type and height.

In Germany, wind power, solar power etc. are subsidized with around
€20.000.000.000 per year out of the Federal Budget, tax money; see
[Erneuerbare Energien Gesetz](https://de.m.wikipedia.org/wiki/Erneuerbare-Energien-Gesetz#EEG-Konto_seit_dem_1._Juli_2022)
. New onshore wind turbine owners get about €70 per MWh from the EEG,
guaranteed for 20 years.
As I understand it, if the market price is 1/4 of that, the taxpayer pays the remaining 3/4.
But only the windmill owners (and a few politicians)
know how much EEG tax money each windmill gets.
This makes intelligent planning impossible.


#### Links
https://wind-data.ch/tools/powercalc.php shows interactively
how power production MWh/year can be calculated from windspeed distribution
and a power curve for a given turbine type.
Run some examples, with Weibull parameters `A = 1.127` * average windspeed and `k = 2.5`.


#### Comments welcome
Click on "Discussions" above.

cheers \
  &mdash; denis  2026-01-23 January

