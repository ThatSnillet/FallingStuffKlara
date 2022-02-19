# Nycklar och dörrar

![bild](https://user-images.githubusercontent.com/70745846/154798801-ea831a21-50e7-43d7-a7ee-d5f63d080f9c.png)

För att nycklarna och dörrarna ska fungera måste spelaren ha taggen "Player".

### Nycklar
![bild](https://user-images.githubusercontent.com/70745846/154798558-e71c0828-f37b-4c5b-88dc-07db946b2afc.png)

Börja med att dra ut en 3D-modell av en nyckel i världen. Det finns en redo i mappen "Models".

![bild](https://user-images.githubusercontent.com/70745846/154798698-a7afd34f-d41c-4cfa-a266-4742afd5ef8d.png)

Med objektet markerat, välj "Add Component" och välj "Key"

![bild](https://user-images.githubusercontent.com/70745846/154798774-10d83442-83ab-4a9b-a564-3604a1b48c33.png)

Till sist behövs en collider. Lägg till en box collider. Se till att fylla i "Is Trigger", det gör att den går att gå igenom men att den aktiveras då.

### Dörrar
![bild](https://user-images.githubusercontent.com/70745846/154798855-04fa6a22-ba4f-4b61-9216-7e3fa3d59f05.png)

Lägg till en modell som ska funka som dörr. Jag väljer att lägga in en ny kub enligt ovan.

![bild](https://user-images.githubusercontent.com/70745846/154798879-693185b8-42cc-4321-8b74-ada0503c2c35.png)

Jag byter namn och storlek på den, namnet gör det lättare att organisera och storleken gör att den faktiskt blockerar vägen.

![bild](https://user-images.githubusercontent.com/70745846/154798944-802e020c-2bf7-4440-93a3-bf885982b5e7.png)

Sen behöver det finnas en till collider. Den som är med från början ska vara kvar som den är. Sedan krävs en till som fungerar som trigger, och den måste vara större än den andra collidern så att spelaren kan ta sig in i den. Det är när spelaren kommer in i triggern som dörren öppnas (om de har plockat up en nyckel).
