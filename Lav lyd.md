# Guide til at Tilføje og Bruge Lyde i Roblox

Lyde kan tilføje en ekstra dimension til dit Roblox-spil ved at skabe stemning, baggrundsmusik eller effekter. Denne guide vil vise dig, hvordan du tilføjer og bruger lyde i dit Roblox-spil.

## Trin 1: Opret og Upload Lydfilen

Først skal du oprette eller finde en lydfil, som du ønsker at bruge i dit spil. Du kan oprette lyde ved hjælp af lydredigeringssoftware eller downloade lydeffekter eller musik fra pålidelige kilder på internettet.

Når du har din lydfil klar, skal du uploade den til Roblox ved at følge disse trin:

1. Åbn Roblox Studio.
2. Klik på "View" (Vis) i den øverste menu og sørg for, at "Explorer" (Udforsker) og "Properties" (Egenskaber) er markeret.
3. I "Explorer" (Udforsker) vinduet, højreklik på "Workspace" (Arbejdsområde) og vælg "Insert Object" (Indsæt objekt).
4. Vælg "Sound" (Lyd) og klik på "OK".
5. Dubliker lydobjektet ved at højreklikke på det i "Explorer" (Udforsker) og vælge "Duplicate" (Dupliker).
6. Vælg den duplikerede lyd og gå til "Properties" (Egenskaber) vinduet.
7. I "Properties" (Egenskaber) vinduet skal du ændre "SoundId" til URL'en for den uploadede lydfil. Du kan uploade lydfilen til Roblox ved at klikke på "Manage Audio" (Administrer lyd) under "Home" (Hjem) fanen på Roblox's hjemmeside.

## Trin 2: Tilføj Lyden til Spillet

Nu kan vi tilføje lyden til vores spil:

1. I "Explorer" (Udforsker) vinduet, find det objekt, du vil tilføje lyden til (f.eks. en trigger, et dørobjekt, en knap osv.).
2. Højreklik på objektet og vælg "Insert Object" (Indsæt objekt).
3. Vælg "Sound" (Lyd) og klik på "OK".
4. I "Properties" (Egenskaber) vinduet, find "SoundId" egenskaben og indtast URL'en for lydfilen.
5. Du kan justere andre lydegenskaber såsom "Volume" (Volumen), "PlaybackSpeed" (Afspilningshastighed) og "Looped" (Gentaget) efter behov.

## Trin 3: Kontrol af Lyden via Scripting

Hvis du ønsker mere kontrol over lyden, kan du bruge scripts til at programmere afspilning og manipulation af lydegenskaber. Her er et eksempel på, hvordan du kan afspille en lyd ved hjælp af Lua scripting:

```lua
local sound = workspace.Sound -- Erstat "Sound" med navnet på dit lydobjekt
sound:Play()
