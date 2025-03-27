#Wiki 

This is an archive of some types of pages that have a more or less standardized format. Anything in double quotes is something that needs to be filled out with information. The only thing all pages must have as far as formatting is tags at the top, then a line break before anything else.
# City Page
(example: [[Gnin City Klan Bzaf]])
"#Location" "#City"

"city name", "territory name", "kingdom"
**Population:** "population" ... **Hot season:** "avg high" - "avg mean" - "avg low" ... **Cold season:** "avg high" - "avg mean" - "avg low"
**Elevation:** "elevation" m ... **Annual Rainfall:** "rainfall" mm ... **Biome:** "biome"
"**Location:**" "continent Mainland (or) island name" - "body of water Coast (or) Inland" - "longitude E/W latitude N/S"
**Neighbors:**  (distances rounded to nearest 5 km)
- "full city name" - "total distance" km "direction": "trail name" for "distance" km -> "left/right" onto "trail name" for "distance" km -> etc.
- etc.

"one paragraph about the city. known for, interesting features, etc"

"**City Map:** (interactive map link)"
"city map image from Procgen Arcana [[#Procgen Arcana City Map Style Guideline|formatted]] as SVG"

"# History"
"# Geography"
"# Economy"
"# Politics"
### Procgen Arcana City Map Style Guideline
- Graphics -> Thin lines, Tint districts
- Elements ->
	- Font size = Medium
	- Districts = Straight
	- Landmarks = hidden
	- Title, Scale bar, Grid, Compass
- Buildings -> 
	- Display mode = Complex
	- Processing = Offset
	- Roofs = Plain, Raised = no, Solids = no
- Outline -> Buildings, Water
- Misc -> 
	- Show alleys
	- Towers = Round
	- Farm fields = Hidden
- Colors: (json format) ![[silver_darkgrey_black 1.json]]
```json
{ "colorPaper": "#CCC5B8",
  "colorDark": "#1A1917",
  "colorRoof": "#A5A095",
  "colorWater": "#7F7A71",
  "colorGreen": "#A59F93",
  "colorRoad": "#CCC5B8",
  "colorWall": "#1A1917",
  "colorTree": "#7F7A71",
  "colorLabel": "#1A1917",
  "colorLight": "#CCC5B8",
  "tintMethod": "Spectrum",
  "tintStrength": "30",
  "weathering": "20"}
```

# Path Page
(example: [[Gnin Trail Bzaf]])
"#Location" "#Path" maybe "#Road" or "#Trail"

"path name" "route / pass / trail / road", "territory if starting point" "kingdom of starting point", "length" km (rounded to nearest 5 km)
> [!note] Path Types
> - Route: connects multiple cities together, often for the purpose of trade
> - Pass: connects usually one, but sometimes two or more cities as an offshoot from a more prominent path
> - Trail: connects a few cities together directly and is not large.
> - Road: made for high amounts of traffic, paved, and usually spanning large lengths

**Stops:**
- "starting point, most north west end of path", "length along road" km
- "next stop, etc...", "length along road" km
- "last stop, most south east end of path", "length along road" km

(stops include cities, landmarks, river crossings, etc.)

**Elevation Change:** "total elevation difference" m ("min elevation" m -> "max elevation" m)

"Introductory paragraph"

"# History"