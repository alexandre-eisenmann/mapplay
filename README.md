# Map Test

This snippet renders some localities across the world over a mapbox instance using d3. The code was based on the http://bl.ocks.org/enjalot/0d87f32a1ccb9a720d29ba74142ba365 example and the data from http://enjalot.github.io/wwsd/data/world/ne_50m_populated_places_simple.geojson

## Setup

```
git clone https://github.com/alexandre-eisenmann/mapplay.git
cd mapplay
open index.html
```


## Task

Your task is to update index.html enhancing this example trough the following steps:

1) Make the radius of the dots proportional to the population of the locality (pop_max attribute)
2) Add an extra panel to present the name of the locality and some extra info you choose. The panel should be updated when the user hover a particular location. 
3) Change the way the dots are rendering adding a time delay proportinal to the distance from Sydney in a way that localities closer to Sydney will be rendered first. Feel free to add a button to trigger this process.
4) Add some extra feature that you think would be nice :)

