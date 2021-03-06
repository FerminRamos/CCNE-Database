# CCNE-Database
A program designed to extract specific data from the CCNE website (Accredited University, City, State, Degree-Types) as well as the latitude and longitude of each school through Google's Geocoding API.

Link: https://directory.ccnecommunity.org/reports/accprog.asp

## Format of Database
Databases last updated: 3/16/2022

Format of database:
* 1 School per line
* "1" = true // has degree
* "0" = false // does not offer degree
* Latitude and Longitude with values = 0, school not identified on google maps (rare)
* "NLN AD" & "NLN BSN" columns will always be zero, as information is ONLY checked for CCNE accreditation, not NLN
* Format of "noCoord": university;city;state;NLN_AD;NLN_BSN;CCNE_BSN;CCNE_MSN;CCNE_DNP
* Format of "Coord": latitude;longitude;university;city;state;NLN_AD;NLN_BSN;CCNE_BSN;CCNE_MSN;CCNE_DNP

## Databases
* Excel Spreadsheet (w/ Coordinates): [CollegesofNursing_Coord EXCEL]
* Text file (w/ Coordinates): [CollegesofNursing_Coord Plain text]

* Excel Spreadsheet (w/ no Coordinates): [CollegesofNursing_noCoord EXCEL]
* Text file (w/ no Coordinates): [CollegesofNursing_noCoord Plain text]


[CollegesofNursing_Coord EXCEL]: https://github.com/FerminRamos/CCNE-Database/blob/b638ea6733c34f7863b3a6ae15fdbc615c5ade7c/Colleges%20of%20Nursing_Coord.xlsx
[CollegesofNursing_Coord Plain text]: https://github.com/FerminRamos/CCNE-Database/blob/540420d6642d2d9fbb167bb47692470af7b80765/CollegesOfNursing_Coord.txt
[CollegesofNursing_noCoord EXCEL]: https://github.com/FerminRamos/CCNE-Database/blob/9db6346c45a7c241cc95485dbca6c600e7807be2/Colleges%20of%20Nursing_noCoord.xlsx
[CollegesofNursing_noCoord Plain text]: https://github.com/FerminRamos/CCNE-Database/blob/c0deea77ede2f193698581d70bb0fd78983b25b1/CollegeOfNursing_noCoord.txt
