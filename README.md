# GenderClassification.github.io
Repository für unser Projekt: Gender Classification of Figurines 

Seminar: Künstliche Intelligenz und Cultural Heritage 
Dozent: Dr. Jan Wieners
Erstellt von: Katjana Johag, Marco Zeyen, Saim Kaan Simsek, Christoph Alexander


Reminder: Unser Ansatz
Wir möchten als Gruppe ein Programm entwickeln, das als Basis über eine Datenbank bestehend aus einer bestimmten Anzahl von Bildern verfügt. Wir möchten dem Programm beibringen das Geschlecht einer Statue zu erkennen. Wenn wir uns auf das Gesicht beschränken, benötigen wir erstmal eine Gesichtserkennung. 
Das könnten wir mit OpenCV realisieren. Dann müssten wir festhalten, welche Merkmale wir dem männlichen und welche Merkmale wir dem weiblichen Geschlecht zuordnen (Bart, markante Gesichtszüge etc). 
Wenn wir uns auf den Torso beschränken gilt die selbe Vorgehensweise. 
Die Merkmale benennen und dem jeweiligen Geschlecht zuordnen (muskulöser Oberkörper, weibliche Rundungen etc).


Was bisher geschah.. 

Wir haben uns einen Ordner „Artificial Intelligence“ in GoogleDrive erstellt um Dateien hochzuladen. Hier wird am Crawler gearbeitet. Zu Beginn hatten wir die Schwierigkeit, dass maximal 35 Bilder auf einmal gecrawlt werden können, das Problem wurde mittlerweile gelöst und wir haben Zugriff auf viele Bilder auf einmal um unseren Korpus aufzubauen.							
Wir wollten unsere Bilder, die den Korpus bilden in drei verschiedene Kategorien unterteilen. 
Zum einen die Kategorie „Frau“, zum Anderen die Kategorie „Mann“ und des Weiteren, um alle anderen Möglichkeiten abzudecken die Kategorie „Sonstiges“. 
Bekommt unser am Ende fertiggestelltes Programm also beispielsweise ein Bild von einem Kühlschrank übergeben, soll es dieses Bild als „Sonstiges“ erkennen.									
-> Wie viele Bilder werden benötigt, um ein aussagekräftiges Ergebnis zu erhalten? 			    
Wir haben pro Kategorie 1000 Bilder zur Verfügung. Der Korpus enthält damit 3000 Bilder.

Weiterhin zu besprechende Fragen:


Weitere Vorgehensweise
Tensorflow auf allen PC’s ans Laufen kriegen
Bildbearbeitung mit OpenCV
