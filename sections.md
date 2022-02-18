# Sektioner

En sektion är en platform där block faller ner helt enkelt

### Placera ut en sektion
![bild](https://user-images.githubusercontent.com/70745846/154720999-dabec662-0918-49b9-86e2-f87be81ffb9c.png)

Gå till mappen "prefabs" och dra ut "levelsection" i nivån

### Ändra storlek på en sektion
![bild](https://user-images.githubusercontent.com/70745846/154723293-b452a860-890e-4e05-bd1c-4c1544375e1e.png)

En sektion består av en kub som heter "floor" och en zon som spawnar in block.

Kuben är bara till för att vara nånting att gå på.

![bild](https://user-images.githubusercontent.com/70745846/154724192-1617cf6e-ed8a-4eb0-8c8f-d345f8453b2a.png)

Zonen sköter lite mer. Till att börja med behöver den vara i hörnet av golvet, där koordinaterna är negativa som i bilden.

Sen är det viktigt att collidern är över hela golvet där blocken ska falla. Ändra värdena i "box collider" så att den passar.

Till sist måste "Game Space Size" ändras. "Grid Size" innebär storleken på blocken. "Game Space Size" är hur många block som får plats i zonen. Här är golvet 16x8, så game space size blir 8x4.

### Ändra typer av block
I zonen finns en lista som heter "Object Types".

![bild](https://user-images.githubusercontent.com/70745846/154725897-55c85b4d-c0ad-4581-9bd7-d42290a7f936.png)

De prefabs som finns listade är de som kommer att spawnas in. Finns flera i listan kommer de att väljas slumpmässigt.

Vill du ändra typer av block på en specifik sektion är det bara att göra det i nivån, vill du ändra på alla får du öppna prefaben "LevelSection" bland dina assets.

[Mer om hur du gör prefabs](https://docs.unity3d.com/Manual/CreatingPrefabs.html)
