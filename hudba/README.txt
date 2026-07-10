Sem patří skladby na pozadí (audio soubory).

Postup:
1) Nakopíruj sem audio, např.  skladba1.mp3 , skladba2.mp3 ...
2) V aplikaci (dvacitka_index.html) najdi v <script> pole TRACKS a přidej položky:

   const TRACKS = [
     { name: "Název první skladby",  src: "./hudba/skladba1.mp3" },
     { name: "Název druhé skladby",  src: "./hudba/skladba2.mp3" },
   ];

Dokud je TRACKS prázdné, ovladač hudby je zašedlý/neaktivní.
Tlačítko ▶/⏸ = přehrát/zastavit, ⏭ = další skladba (cyklicky).
