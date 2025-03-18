
## City Page
**tags:** Location City
**full name:** "city name", "county name", "kingdom"
"**Location:**" "continent Mainland (or) island name" - "body of water Coast (or) Inland" - long E/W, latitude N/S
"**Neighbors:**  (distances rounded to nearest 5 km)"
- "full city name" - "total distance" km "direction": "trail name" for "distance" km -> "left/right" onto "trail name" for "distance" km -> etc.
- etc.

"Desctiption"

"**City Map:** (interactive map link)"
"city map image from Procgen Arcana formatted as SVG"
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
	- Roofs = Plain, Raised = no, Solids = yes
- Outline -> Buildings, Water, Roads
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

