# Kamen - Škare - Papir 🪨✂️📄

## O projektu

Projekt implementira klasičnu igru kamen-škare-papir protiv računala, s tekstualnim sučeljem koje se iscrtava izravno na Hack ekranu putem ugrađenih `Output` i `Screen` klasa Jack operacijskog sustava. Igrač bira potez pomoću tipkovnice, a rezultati partija prate se tijekom cijele sesije.

## Kako igra radi

1. Na početku svake runde ispisuje se zaglavlje s uputama i trenutnim rezultatom.
2. Igrač bira potez unosom tipke:
   - `1` — Kamen
   - `2` — Škare
   - `3` — Papir
   - `Q` — Izlaz iz igre
3. Potez računala generira se nasumično na temelju vremena reakcije igrača (brojač koji raste dok se čeka pritisak tipke).
4. Program uspoređuje poteze i određuje pobjednika runde (igrač, protivnik ili neriješeno).
5. Rezultat se ažurira i prikazuje, uz kratku animaciju pri pobjedi igrača.
6. Po izlasku iz igre ispisuje se konačan zbroj pobjeda, poraza i neriješenih partija.
   
## Pravila igre

- Kamen pobjeđuje škare
- Škare pobjeđuju papir
- Papir pobjeđuje kamen
- Isti potezi rezultiraju neriješenim ishodom

## Struktura projekta

| Datoteka | Opis |
|---|---|
| `Main.jack` / `Main.vm` | Ulazna točka programa |
| `Game.jack` / `Game.vm` | Sadrži svu logiku igre: ispis sučelja, obradu unosa, odabir poteza računala, suđenje rundi i praćenje rezultata. |

## Pokretanje

Potreban je Nand2Tetris VM Emulator. Učitaj sve .vm datoteke i pokreni.

