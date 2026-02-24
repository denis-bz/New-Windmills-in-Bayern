### Interactive maps of new windmills in Bayern and Germany

Keywords, tags: wind-power windmill windi-turbine Germany Bayern maps

For maps of new windmills in Bayern and Germany, go to \
https://denis-bz.github.io/New-Windmills-in-Bayern/ or \
https://denis-bz.github.io/New-Windmills-in-Bayern/newwindmills-DE.html \
These maps show windmills running since 2024, or planned: in Bayern 333, in all Germany 8263.
Looking at these sites is more interesting than looking everywhere &mdash; importance weighting.
The data is from 1 January 2026,
https://www.marktstammdatenregister.de/MaStR  Gesamtdatenexport_20260101_25.2.zip .

These new windmills are BIG, around 250m:
e.g. 167m turbine height `Thi` + 80m Rotor diameter / 2.
Zoom in on ones in your area.

Files `BY-*.csv` and `DE-*.csv` under https://github.com/denis-bz/New-Windmills-in-Bayern
have 1 line for each windmill, like
```
Cosmowind175 Cosmocap175  AGS State   MW     Lat     Lon Thi Rotor       Date             Lkr
5.79         29          9371    BY 4.26 49.5114 11.9894 160   138 2027-12-31 Amberg-Sulzbach
...
5.69         28          9679    BY    6 49.7377 9.69521 162   175 2026-05-18        Würzburg
```
Here `Cosmocap175` is calculated
from hourly windspeed data from https://opendata.dwd.de/.../cosmo_rea6.)
and a power curve for wind turbine type E-160/5560.


#### How profitable are windmills in Germany, from EEG tax money ?

"Installed power",
[Installierte Leistung](https://de.wikipedia.org/wiki/Installierte_Leistung)
is the *maximum* a windmill can generate, at windspeeds around 40 km/h.
Over a whole year, the electricity actually generated might be 20 % to 50 % of the maximum.
This is called "yield" (Ertrag) or "capacity factor".
It varies a lot, depending on actual windspeeds at a given site, and on turbine type and height.

In Germany, wind power, solar power etc. are subsidized with around
€20.000.000.000 per year out of the Federal Budget, tax money; see
[Erneuerbare Energien Gesetz](https://de.m.wikipedia.org/wiki/Erneuerbare-Energien-Gesetz#EEG-Konto_seit_dem_1._Juli_2022)
. New onshore wind turbine owners get about €70 per MWh from the EEG,
guaranteed for 20 years.
As I understand it, if the market price is 1/4 of that, the taxpayer pays the remaining 3/4.
But only the windmill owners (and a few politicians)
know how much EEG tax money each windmill gets.
This makes intelligent planning &mdash; more wind power where there's more wind,
more solar power where more sun &mdash; difficult.


#### Links
https://wind-data.ch/tools/powercalc.php shows interactively
how power production MWh/year can be calculated from windspeed distribution
and a power curve for a given turbine type.
Run some examples, with Weibull parameters `A = 1.127` * average windspeed and `k = 2.5`.


#### Comments welcome
Click on "Discussions" above.

cheers \
  &mdash; denis \
  2026-02-24 February  (v0 23jan)

