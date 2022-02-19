# User interfaces (UI)

Användargränssnitt kan bestå av bilder, text, knappar med mera. De behöver ligga på ett canvas för att dyka upp på skärmen.

![bild](https://user-images.githubusercontent.com/70745846/154728712-12d4babe-7ec0-4718-8e64-36f3723c2d91.png)

För att se hur gränssnittet ser ut i spelet kan du trycka på "game" ovanför 3D-vyn.

### Game over skärm

Skapa ett nytt canvas och kalla det något i form av "GameOverCanvas". Lägg in någon text och kanske en bild som bakgrund. När du är nöjd med hur den ser ut så ska du inaktivera canvasen enligt nedan:

![bild](https://user-images.githubusercontent.com/70745846/154729466-7d2dc010-7580-452b-854d-ee0155bb0bb5.png)

Till sist behöver ni ordna så att canvasen dyker upp när man förlorar.

![bild](https://user-images.githubusercontent.com/70745846/154729927-5225fd07-7954-4756-9b68-d8ecd6eaf4ac.png)

I objektet "Player" och under "On Fail" lägger du till en ny händelse. Den ska referera till din game over canvas som går att hitta under fliken "Scene". Funktionen som ska köras finns vid Gameobject -> SetActive, och rutan ska vara ibockad.

### Startskärm

För att göra en startskärm krävs en knapp, och gärna någon bild och text i bakgrunden för att göra den intressant.

![bild](https://user-images.githubusercontent.com/70745846/154799374-383e31b7-1f09-4b2b-87a7-0ac56295e15f.png)

Håll sedan ner ctrl och välj alla objekt som hör till startmenyn, högerklicka och välj "Create Empty Parent". Det gör att de objekten hamnar tillsammans under samma objekt, som sedan enkelt kan visas och döljas. Kalla det nya objektet "StartScreen" eller nåt liknande.

![bild](https://user-images.githubusercontent.com/70745846/154799499-71233402-1a52-41ae-93d6-38e698fd147d.png)

Sen ska knappen på startskärmen dölja skärmen. Markera knappen och skrolla ner till "On Click" i inspectorn. Gör en ny händelse och välj det nya parent-objektet under fliken "Scene". Funktionen som ska köras finns vid Gameobject -> SetActive, och rutan ska vara avbockad.
