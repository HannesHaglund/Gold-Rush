# Gold-Rush
The code for a Warcraft 3 map mod project. A collaboration between myself, and Adrian Lindblom, who worked on environment (placing of static objects in the so-called terrain editor), while I did the code you see now.

It is written in [WurstScript](https://github.com/peq/WurstScript). More information about the release of the map can be found on our [HiveWorkshop page](http://www.hiveworkshop.com/forums/maps-564/gold-rush-v1-1-a-269852/). Here's a [download link](http://www.hiveworkshop.com/forums/maps.php?p=download&id=v5erlj&toast=e08c899705f58a1138d37bb77fd95f57&dateline=1443702416).

Editor-only portions of the final map file has been removed, and it is thus not possible (or at least difficult) to open it in the editor. Sadly, much of the source code references id's of objects created in the Warcraft 3 World Editor so this code can't be used alone to easily develop forks. The portion of the WurstScript library that is able to generate in-editor object data was bleeding edge and therefore not used.
