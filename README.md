# mapPY
A procedural 2D map generator. 

### Terrain generation
The terrain elements that will be integrated are:
- Land (e.g. prairie, desert)
- Mountains
- Rivers
- Lakes
- Woods
- Sea
- Cities*
- Roads*

The generation of the map will be based on probability distributions configured with a set of parameters (e.g. from a config file), using a random seed that identifies the specific map (i.e. using the same seed, the same map will be generated).

### Technologies
Python 3 + Pygame + various libs

### Goals
- Custom generating algorithm that:
  - generates the entire map
  - generates different terrains randomly (i.e. without using predefined patterns)
- Visualization of the map via Pygame
- Different levels of zoom that display different levels of detail*

### TODO:
- [ ] build a basic representation of the `Map` object (+ `Terrain`s and everything)
- [ ] build a basic tools (e.g. based on [Pillow](https://pillow.readthedocs.io/en/5.3.x/) that displays a `Map` (useful for quick testing)
- [ ] Devise generating algorithms for map-level terrains
- [ ] Devise generating algorithms for terrain-level visual representations
- [ ] Integrate all of the above with Pygame


---
\* Nice to have's
