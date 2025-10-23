# Posta : Sistemet Inteligjente për Menaxhimin Fleksibël të Dërgesave (S.I.M.F.D.)

**Një prototip për të revolucionarizuar shërbimet postare, duke u dhënë klientëve kontroll të plotë mbi kohën dhe vendin e marrjes së dërgesave.**
## Problemi
Shërbimet aktuale postare shpesh detyrojnë klientin të jetë në shtëpi në një dritare kohore të madhe (p.sh., 8:00 - 17:00), duke shkaktuar humbje kohe dhe dorëzime të dështuara. Mungesa e transparencës mbi vendndodhjen e saktë të korrierit shton frustrimin.
## Zgjidhja (S.I.M.F.D.)
S.I.M.F.D. përdor teknologjinë e Gjeo-Lokalizimit (GPS) dhe Algoritme Prediktive (ML) për të ofruar:
1.  **Ora e Vlerësuar e Mbërritjes (O.V.M.):** Një dritare kohore e saktë (± 60 min) në kohë reale.
2.  **Fleksibilitet Dinamik:** Mundësinë për ri-drejtim (Reschedule), dërgim në pika lokale (Pick-up Points), apo Smart Lockers, direkt nga aplikacioni mobil.
3.  ## Arkitektura e Projektit

Projekti është i ndarë në këto komponentë:

1.  **Aplikacioni i Klientit (`src/client_app`):** (P.sh., I ndërtuar me Flutter) - Për ndërfaqen, ndjekjen në hartë dhe kërkesat e ri-drejtimit.
2.  **Backend & API (`src/backend`):** Menaxhon të dhënat, llogaritjen e O.V.M.-së, dhe komunikimin me sistemin e korrierit.
3.  **Sistemi i Korrierit:** (Mjet i simuluar) - Përdor GPS për të dërguar vendndodhjen në kohë reale.
