
Firmware pro F.Opta byl volbou Arduino/Sketch/Exportovat... zkompilován a sestaven do binárního formátu  2k_2s_M1M2.ino.bin(2k_2s_M3M4.ino.bin, 2k_2s_M5M6.ino.bin)      
Pomocí Python skriptů lssz.py a bin2ota.py se nejlépe v linuxu převede do souboru  2k_2s_M1M2.ino.ota(2k_2s_M3M4.ino.ota, 2k_2s_M5M6.ino.ota), který je zkopírován sem na github.       
F.Opta zkouší tento soubor stáhnout a updatovat jím firmware a to po každém přenosu dat do influxdb(tj. po 10 minutách) aspoň hodinu od resetu F. Opta
(dříve je tento update možno vyvolat stisnutím  tlačítka na F. Opta, 2x cca 3-6 s po sobě) 
Soubor 2k_2s_M1M2.ino.ota(2k_2s_M3M4.ino.ota, 2k_2s_M5M6.ino.ota) je pak třeba vymazat, aby se update zbytečně neopakoval. 
