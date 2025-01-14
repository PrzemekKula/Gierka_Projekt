**Działanie skryptu TerrainGenerator.cs**

  Na początku gry, skrypt generuje maxTerrainCount terenów, przy czym każdy z tych terenów pochodzi z losowego typu terenu z listy terrainDatas.

  W trakcie gry, po naciśnięciu przycisku W, generowany jest nowy teren, który może być jednym lub więcej terenów tego samego typu, a stary teren (najstarszy w liście) zostaje usunięty, aby liczba terenów nie przekroczyła maxTerrainCount.
