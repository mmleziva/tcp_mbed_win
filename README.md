
Soubor 2kanaly_2sek.bin je sestaven v Arduinu/Sketch/Exportovat...    
Pomocí Python skriptů lssz.py a bin2ota.py ho nejlépe v linuxu převedu na 2kanaly_2sek.ino.ota       
Ten F.Opta zkouší stáhnout a updatovat svůj firmware a to po přenosu do influxdb(každých 10 minut) aspoň hodinu od resetu
(dříve je tento update možno vyvolat stisnutím  tlačítka na F. Opta, 2x, 3-6 s po sobě) 
Soubor 2kanaly_2sek.ino.ota je pak třeba vymazat, aby se update zbytečně neopakoval. 
