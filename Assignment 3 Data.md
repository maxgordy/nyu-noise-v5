## Roles
- Margot in charge of
	- QGIS processing and mapping
	- editing/polishing graphics/maps
	- research/writing
- Max in charge of
	- R processing, graphics (and mapping maybe)
	- Datawrapper mapping?
	- writing/editing
## General Notes

MapPluto

- Field OwnerType
	- Value X
		- Description Fully tax-exempt property that may be owned by the city, state, or federal government; a public authority; or a private institution

241126 Lucy Meeting
- start early and test whether it is possible
	- proof of concept to prove it happens
- focus on targeted areas rather than trying to prove causation/close relationship
	- look at local news coverage around big new dorm
	- NYU Stuyvesant town agreement?
- ACRIS open data
	- real property parties
	- real property master has specific info about recorded documents
- maxwell austenson (JustFix) could help with pulling property/portfolio information
	- Maxwell@justfix.org
- DAP portal
- ZoLA
- Look at NYU dorms
- talk about why relationship between noise complaints and dorms matters
- look at demographic shifts in zip codes

# Plan

## Data
### property data
- building selection
	- criteria
		- move-in date post 2010
		- somewhat adjacent/within a residential neighborhood
	- options
		- Columbia
			- 600 west 125th street
		- NYU
			- Paulson
- Pluto
	- have list of NYU properties
		- no dates built
- **ACRIS Open Data**
	- Parties
		- looking up NYU, finding properties
			- plot on map, only take within village zip codes?
	- Master
		- pull recorded documents based on address list
		- filter for lease/deed?
		- map
- JustFix
	- Properties purchased since 20

*NYU NOHOSOHO PROPERTIES*

| Name                                                                                                                                                                    | Address              | Latitude | Longitude | BBL |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- | -------- | --------- | --- |
| Education Building (B-2)                                                                                                                                                | 35 West 4th Street   |          |           |     |
| Bookstore and Computer Store (B-2)  College of Arts and Science (B-2) (Interim)<br>Global Liberal Studies<br>Liberal Studies<br>Moses Center<br>Res Life<br>SHC<br><br> | 726 Broadway         |          |           |     |
| School of Global Public Health                                                                                                                                          | 708 Broadway         |          |           |     |
| 404 Fitness                                                                                                                                                             | 404 Lafayette        |          |           |     |
| NYU Shanghai                                                                                                                                                            | 14 E 4th Street      |          |           |     |
| Admissions Office                                                                                                                                                       | 383 Lafayette Street |          |           |     |
|                                                                                                                                                                         | 411 Lafayette Street |          |           |     |
|                                                                                                                                                                         | 20 Cooper Square     |          |           |     |
 
**Res Halls** (NYU in Manhattan)

| Building               | Address                | BBL   | Add 2                |
| ---------------------- | ---------------------- | ----- | -------------------- |
| Brittany Hall          | 55 East 10th Street    | 56230 | 787 BROADWAY         |
| Founders Hall          | 120 East 12th Street   | 55648 | 120 EAST 12 STREET   |
| Lipton Hall            | 33 Washington Square   | 55224 | 35 WASHINGTON SQ W   |
| Res College at Paulson | 181 Mercer Street      | 52466 | 100 BLEECKER STREET  |
| Rubin Hall             | 35 Fifth Street        | 4613  | 25 COOPER SQUARE     |
| Weinstein Hall         | 5 University Place     | 5484  | 5 UNIVERSITY PLACE   |
| Alumni Hall            | 33 Third Avenue        | 4651  | 31 3 AVENUE          |
| Broome Street          | 400 Broome Street      | 4811  | 400 BROOME ST        |
| Carlyle Court          | 25 Union Square West   | 84322 | 21 UNION SQUARE      |
| Coral Tower            | 129 Third Avenue       | 8961  | 125 3 AVENUE         |
| Gramercy Green         | 310 3rd Avenue         | 87944 | 318 3 AVENUE         |
| Greenwich Hall         | 636 Greenwich Street   | 60346 | 636 GREENWICH STREET |
| Lafayette Hall         | 80 Lafayette Street    | 17220 | 76 LAFAYETTE STREET  |
| Palladium Hall         | 140 East 14th Street   | 55922 | 126 EAST 14TH STREET |
| Second Street          | 1 East 2nd Street      | 4589  | 1 EAST 2 STREET      |
| Seventh Street         | 40 East Seventh Street | 46218 | 38 E 7 STREET        |
| Sixth Street           | 200 East 6th St        | 4616  | 35 COOPER SQUARE     |
| Third North            | 75 Third Avenue        | 4671  | 67 3 AVENUE          |
| University Hall        | 110 East 14th Street   | 55912 | 106 EAST 14 STREET   |

NOTE: GRAMERCY GREEN USES ADDRESS OF BUILDING NEXT TO IT BC NO ADDRESS IS LISTED FOR LOT

REMOVED ADDRESSES

| Clark Street  | 55 Clark Street |     | 51 CLARK |
| ------------- | --------------- | --- | -------- |
| STUY TOWN<br> |                 |     |          |
| WSV           |                 |     |          |
|               |                 |     |          |

DUPLICATE ADDRESSES IN MAPPLUTO
"35 WASHINGTON SQ W"   "400 BROOME ST"        "126 EAST 14TH STREET" "38 E 7 STREET"   

### noise/displacement data
- 311 data
	- filter for 
		- zip codes
		- relevant complaints
		- 2010-
	- create sub dataset
	- ![[Screenshot 2024-12-05 at 11.12.05 AM.png]]

new plan
- pull lot info of 7/8 nyu properties, put into data frame
	- ![[Screenshot 2024-12-05 at 11.12.15 AM.png]]
summary by address description
# Graphics

# Writing Portion
## Background
- Palladium 
	- https://en.wikipedia.org/wiki/Palladium_(New_York_City)#:~:text=The%20Palladium%20was%20converted%20from,Steve%20Rubell%20and%20Ian%20Schrager
	- https://www.artsy.net/article/artsy-editorial-6-iconic-new-york-artworks-that-were-destroyed
	- https://indypendent.org/2024/10/west-harlem-pushes-back-against-columbias-latest-manhattanville-campus-expansion/

