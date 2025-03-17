
Firmware pro F.Opta byl volbou Arduino/Sketch/Exportovat... zkompilován a sestaven do binárního formátu  2kanaly_2sek.bin.      
Pomocí Python skriptů lssz.py a bin2ota.py se nejlépe v linuxu převede do souboru  2kanaly_2sek.ino.ota, který je zkopírován sem na github.       
F.Opta zkouší tento soubor stáhnout a updatovat jím firmware a to po každém přenosu dat do influxdb(tj. po 10 minutách) aspoň hodinu od resetu F. Opta
(dříve je tento update možno vyvolat stisnutím  tlačítka na F. Opta, 2x cca 3-6 s po sobě) 
Soubor 2kanaly_2sek.ino.ota je pak třeba vymazat, aby se update zbytečně neopakoval. 
