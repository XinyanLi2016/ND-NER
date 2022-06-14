# ND-NER
ND-NER is a named entity recognition (NER) dataset for OSINT towards the national defense domain.

ND-NER_nested is the full version of dataset, annotating the nest structure.

ND-NER_flat is for flat NER, and we only preserved the outmost entities annotation.

The entity types of ND-NER with detailed explanation is shown in the table.

| Type  | Explanation |
|  ----  | ----  |
| O | The organization entity is the name and abbreviation of the social and political organization, such as military enterprise organization, military-related schools, military administrative units, government agencies and combat units or organizations.|
| C | The country entity is the name and abbreviation of a country, such as 美(America) and 华(China). |
| P | The person entity is the name of person and the nicknames of person. |
|T |The time entity is the date or precise time the event occurred. |
|L | The location entity is the name and abbreviation of a geographical location and administrative area. |
|F | The facility entity is the name and abbreviation of buildings, sites and facilities for military purposes. |
|E | The event entity is the name and abbreviation of military operations and political events. |
|R | The role entity is the name of the government job title and military ranks. |
|ARTILLERY | The artillery entity contains howitzers, rocket launchers, anti-tank guns, etc.|
|EXPLOSIVE| The explosive entity contains mines, grenades, blasting explosives, etc.|
|AIRCRAFT | The aircraft entity contains fighter aircraft, transport aircraft, drones, etc. |
|SHIP	|The ship entity contains frigates, destroyers, cruisers, etc. |
|MISSILE	|The missile weapon entity contains sea-based missiles, land-based missiles, air-based missiles, cruise missiles, etc.|
|SPACE	|The space-based equipment entity contains military satellites, spaceships, launch vehicles, etc.|
|TANK|The tank armored vehicle entity contains minesweeper, main battle tank, armored transport vehicle, infantry fighting vehicle, etc.|
|FIREARM	|The firearms and individual combat equipment entity contains pistols, rifles, submachine guns, knives, etc.|
|ELECTRONIC|The electronic equipment entity contains radar, combat command system, communication equipment, military computer, etc.|
|MASS\_DESTR	|The Weapons of Mass Destruction entity contains nuclear weapons, chemical weapons, biological weapons, etc.|
|NEW	|The New Concept Weapon entity contains directed energy weapons, kinetic energy weapons, genetic weapons, etc.|

The dataset is distributed under CC BY-SA 4.0 license.
