# Arduino-Infrared-Car

Link YouTube: https://youtu.be/cOzx2q6Rw1U

Ce este?

Este o masinuta construita pe baza unei placute de Arduino care va comanda 2 motoare in functie de semnalele IR pe care le receptioneaza senzorul.

Cele 2 motoare se vor misca astfel in functie de ceea ce receptioneaza senzorul:
- pentru deplasarea inainte -> ambele motoare merg in aceeasi directie si inainte
- pentru deplasarea inapoi -> ambele motoare merg in aceeasi directie si inapoi
- pentru deplasarea in stanga -> motorul din dreapta se opreste si merge doar cel din stanga inainte
- pentru deplasarea in dreapta -> motorul din stanga se opreste si merge doar cel din dreapta inainte

Controlul prin telecomanda:
-> am memorat semnalele emise de telecomanda pentru butoanele 0, 2, 4, 5, 6 astfel:
                           - butonul 2 pentru mersul inainte
                           - butonul 4 pentru virajul la stanga
                           - butonul 5 pentru mersul inapoi
                           - butonul 6 pentru virajul la dreapta
                           - butonul 0 pentru a se opri masina
