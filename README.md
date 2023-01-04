# 3D Mapping with ZED2i using vSLAM 
## Allgemeine Bemerkungen

Dieses Github-Repository ist eine Lernumgebung, die von türkisch-deutschen Universitätsstudenten 
für den Projektkurs Mec319 Mechatronics erstellt wurde. Diese Studien sind die Studien des 3D-Mapping-Projekts mit der ZED2i-Kamera.
Die in diesem Arbeitsarchiv eingereichten Studien gehören nicht uns. Die Werke stammen von verschiedenen
lizenzierten Seiten und sind nicht urheberrechtlich geschützt. <br/>

![3D-Rekonstruktion eines
Gebäudes auf dem Campus der Türkisch-Deutschen Universität.](https://user-images.githubusercontent.com/105494761/210575748-67df850f-04ab-43e3-8694-ac58407fdbe6.png)

Die im Rahmen dieses Kursprojekts durchgeführten Studien werden unter der folgenden Überschrift erläutert. Bitte melden Sie unklare Teile.

## ZED2i Kamera mit MATLAB  

Sie werden einige Quellcodezeilen unter Matlab-Dateien sehen.
Wie aus ihren Namen hervorgeht, handelt es sich um die Codezeilen, mit denen über Matlab auf die Kamera zugegriffen wird.
Entsprechend dem aktuellen Stand wird auch die Readme-Datei aktualisiert.
Die Videoaufnahme der ZED2i-Kamera und die sensor.m-Dateien stammen von der Stereolabs-Website.
Andere Matlab-Codezeilen wurden jedoch basierend auf Informationen aus verschiedenen Quellen für die Verwendung in unserem eigenen Projekt angepasst.
Wenn es ein Problem mit diesen gibt, lassen Sie es mich bitte wissen.
Wenn Sie mehr über die Verwendung der ZED2i-Kamera auf MATLAB erfahren möchten, können Sie [diesen Link](https://www.stereolabs.com/docs/matlab/) verwenden.


## ZED2i mit Python API 
Natürlich ist MATLAB nicht die einzige Möglichkeit, auf die ZED2i-Kamera zuzugreifen.
Eine der verschiedenen Möglichkeiten, dies zu tun, besteht darin, die Kamera zu steuern und mit Python auf die Kameradaten zuzugreifen.
Wir haben versucht, die Python-API von Zeit zu Zeit im Rahmen dieses Projekts zu verwenden, aber um ehrlich zu sein, haben wir sie nicht oft verwendet. 
Basierend auf den Informationen, die wir nach unserer Recherche erhalten haben, haben wir es jedoch nicht versäumt,
ein paar Zeilen Quellcode als Python-API unter dieser Datei hinzuzufügen.
Ich hoffe, Sie finden nützliche Informationen. Vergessen Sie nicht, die Dinge zu melden, die Ihrer Meinung nach fehlen oder falsch sind.
Wenn Sie mehr über die Steuerung der ZED2i-Kamera mit der Python-API erfahren möchten,
klicken Sie auf [diesen Link](https://www.stereolabs.com/docs/app-development/python/install/).
