# CiArpeSDS 0.9.5 Beta

Aggiornamento della beta gratuita (14 giorni). Sostituisce la 0.9.0.

## Novità
- Display SDS200: lo schermo dello scanner dal vivo, con simbolo grafico del gruppo.
- Scheda Scanner USB: «Leggi» e «Scrivi» entrano da soli in modalità USB (Mass Storage).
- Audio: ricampionamento 8->48 kHz polifase, niente più timbro metallico in ascolto e riascolto.
- Scansione: al massimo 20 s sui canali voce e 2 s sui segnali digitali non decodificati; i canali con un
  decoder attivo non vengono tagliati; AVOID e salto per 5 minuti con ritorno automatico.
- Avviso se lo scanner non risponde per oltre 30 s, senza insistere con i comandi.
- Decoder sempre in ascolto e avvio automatico sull'audio di rete (nella beta: DSC; POCSAG/FLEX/APRS con
  multimon-ng installato a parte).
- Schede canale con categoria, uso e banda dei canali pubblici.
- Tolta la scheda TETRA didattica (lo SDS200 non decodifica TETRA).

## Limiti noti
- Provato su un solo SDS200 (firmware 1.23.15). Lo scanner accetta un solo programma sull'audio.
- L'audio di rete dello SDS200 è in qualità telefonica (8 kHz): è un limite dello scanner.
