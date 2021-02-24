# Cluster Coordinates

Given ia longitude, and latitude, cluster_coords will create a new latitude and longitude randomly placing it anywhere between 5 and 25 meters from the original longitude and latitude.

```python
from cluster_coords import RandomCoord

coords = RandomCoord(<lomgitude>,<latitude>).randomize_coords()
new_lat = coords.lat
new_lng = coords.lng
```

# Installation
```pip install cluster_coords```
