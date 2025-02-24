# Microprocessor-based-Microsystem-Design
PM prj

Tema Proiectului
Să se proiecteze un microsistem cu următoarea structură:
● unitate centrală cu microprocesorul 8086;
● 256 KB memorie EPROM, utilizând circuite 27C2048;
● 64 KB memorie SRAM, utilizând circuite 62512;
● interfață serială, cu circuitul 8251, plasată în zona 0AF0H – 0AF2H sau 0BF0H – 0BF2H, în funcție
de poziția microcomutatorului S1;
● interfață paralelă, cu circuitul 8255, plasată în zona 0D70H – 0D76H sau 0C70H – 0C76H, în funcție
de poziția microcomutatorului S2;
● o minitastatură cu 12 contacte;
● 10 led-uri;
● un modul de afișare cu 7 segmente, cu 6 ranguri;

Toate programele în limbaj de asamblare vor fi concepute sub formă de
subrutine. Programele necesare sunt:
-rutinele de programare ale circuitelor 8251 şi 8255;
-rutinele de emisie/ recepţie caracter pe interfaţa serială;
-rutina de emisie caracter pe interfaţă paralelă;
-rutina de scanare a minitastaturii;
-rutina de aprindere/ stingere a unui led;
-rutina de afişare a unui caracter hexa pe un rang cu segmente.
