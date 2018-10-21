# AmbientCivilians.Tanoa
For Arma 3 APEX

Set of scripts that automatically populate civilians and vehicles near the initialized object(s).

- Populates civlians in buildings and nearby open spaces
- Empty vehicles are spawned in tight spaces and alleyways near buildings, along fences, by parking meters, etc.
- Populates AI-driven vehicles on nearby roads
- Civilians automatically enter/exit buildings, sit on benches, walk to new destinations, etc.
- Drivers automatically drive around any nearby roads, selecting their own destinations
- Drivers will stop and honk at any vehicles or people that block their path
- Civilians and drivers are automatically despawned when far away for performance
- The number of cars, civilians, and drivers scales with the number of nearby buildings. So, cities will have higher populations while rural areas will see less cars and people.
- The ambient effect "follows" the initialized object, so if added to player for instance, civilians and vehicles etc. will be placed wherever the player goes, while despawning civilians from previously visited locations.
- Empty ambient vehicles are NOT despawned - this is intentional so that the map slowly becomes populated with empty vehicles that do not have to be spawned again. Performance here relies on Arma 3's "Dynamic Simulation" feature which is enabled for all empty vehicles.
