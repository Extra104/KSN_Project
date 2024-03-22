# **&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;PlutoSDR für Frequenzanalyse &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**

# Inhaltsverzeichnis

1. [Ziel](#ziel)
2. [Hardware](#hardware)
   - [Allgemeine Beschreibung](#allgemeine-beschreibung)
   - [Technische Beschreibung](#technische-beschreibung)
3. [Entwicklungen](#entwicklungen)
   - [Verwendete Programme](#verwendete-programme)
   - [Allgemeine Beschreibung](#allgemeine-beschreibung-1)
   - [Installation des Treibers](#installation-des-treibers)
   - [Installation von GNU - Radio](#installation-von-gnu---radio)
4. [Software](#software)
5. [Resümee](#resümee)

---

## Ziel
Realisierung eines hochmodernen Software Defined Radio (SDR) Systems unter Einsatz der leistungsstarken PlutoSDR-Plattform, das sich auf die akkurate Analyse von Frequenzen sowie die ansprechende Visualisierung mittels Wasserfall-Darstellungen konzentriert.

## Hardware
   ### Allgemeine Beschreibung
   Das verwendete Hardwaregerät ist das PlutoSDR, eine erschwingliche Lösung für Software-Defined-Radio- 
   Anwendungen. Entwickelt von Analog Devices, bietet das PlutoSDR eine breite Palette von HF-Frequenzen und 
   ermöglicht die bidirektionale Kommunikation über USB. Mit integrierter Antenne und flexibler       
   Signalverarbeitung eignet es sich ideal für verschiedene Funkanwendungen, von der Frequenzanalyse bis hin 
   zur drahtlosen Kommunikationsexperimente. Seine hohe Abtastrate und einfache Bedienung machen es zu einer 
   beliebten Wahl für Bastler und Funkamateure.
   
   ### Technische Beschreibung
   Dieses Gerät passiert auf einem AD9 AD9363-Chip, der eine breite Palette von HF-Frequenzen abdeckt. Diese 
   liegen im Allgemeinen zwischen 70 MHz bis 6 GHz. Mit dem Host-Computer wird das Gerät über eine USB-      
   Schnittstelle verbunden.  Es ermöglicht eine bidirektionale Kommunikation, auch als zwei Wege Kommunikation 
   bekannt. 
   Zudem ist er mit integrierten Antennen ausgestattet. Sowie einer flexiblen Signalverarbeitung mit einer 
   maximalen Abtastrate von bis zu 52 MSPS.  Außerdem kann er sowohl als Empfänger und Sender agieren. 

   Zusammenfassend lässt sich sagen, dass zu den Hauptmerkmalen ein breiter Frequenzbereich, eine hohe 
   Abtastrate, flexible Signalverarbeitung, einfache Schnittstellen und integrierte Antennen sind. 

   ![ABbilung ](./img/adi-pluto-1.jpg)
   
## Entwicklungen
   ### Verwendete Programme
   GNU Radio Companion ist eine einfache Software, mit der du eigene Software Defined Radio (SDR)-Anwendungen erstellen kannst, indem du 
   Flussdiagramme erstellst, um Signalverarbeitungsschritte darzustellen.

   Der Treiber "PlutoSDR-M2k-USB-Drivers.exe" wird benötigt, um das PlutoSDR-Gerät unter Windows zu verwenden. Er ermöglicht die 
   Kommunikation zwischen dem Computer und dem PlutoSDR-Gerät, damit du es für verschiedene Funkanwendungen nutzen kannst.

   ### Allgemeine Beschreibung
   Der erste Schritt besteht darin, GNU Radio auf Ihrem Computer zu installieren. GNU Radio ist eine vielseitige Softwareplattform, die    speziell für die Entwicklung von Software Defined Radio (SDR)-Anwendungen entwickelt wurde. Sie können GNU Radio von der offiziellen     Website herunterladen und auf Ihrem System installieren [Link](https://wiki.gnuradio.org/index.php/InstallingGR)

Nach der Installation von GNU Radio müssen Sie den Treiber für das PlutoSDR-Gerät installieren. Dieser Treiber, der als "PlutoSDR-M2k-USB-Drivers.exe" bekannt ist, ermöglicht es Ihrem Betriebssystem, das PlutoSDR-Gerät zu erkennen und eine reibungslose Kommunikation damit zu gewährleisten. Die Installation dieses Treibers ist entscheidend, um sicherzustellen, dass Ihr Computer das PlutoSDR-Gerät korrekt erkennt und Sie es nahtlos mit GNU Radio verwenden können.

Durch die Installation von GNU Radio und des PlutoSDR-Treibers legen Sie den Grundstein für die Entwicklung und Umsetzung verschiedener Funkanwendungen mit dem PlutoSDR-Gerät. Diese Kombination aus leistungsstarker Software und einem zuverlässigen Treiber ermöglicht es Ihnen, die volle Bandbreite der Funktionen des PlutoSDR-Geräts zu nutzen und Ihre eigenen SDR-Projekte zu realisieren.
   ### Installation des Treibers
Um den Treiber für das PlutoSDR-Gerät zu installieren, muss man die entsprechende [Installationsdatei](https://wiki.gnuradio.org/index.php/InstallingGR) herunterladen. Diese Datei finden Sie auf der offiziellen Website von Analog Devices oder auf der Supportseite des PlutoSDR-Geräts. Stellen Sie sicher, dass Sie die richtige Version des Treibers für Ihr Betriebssystem auswählen.

Sobald die Installationsdatei heruntergeladen wurde, führen Sie sie aus, indem Sie darauf doppelklicken. Dadurch wird der Installationsassistent gestartet, der Sie durch den Installationsprozess führt. Folgen Sie den Anweisungen des Assistenten, um den Treiber auf Ihrem System zu installieren. Möglicherweise benötigen Sie Administratorrechte, um den Treiber erfolgreich zu installieren.

Nach Abschluss der Installation können Sie überprüfen, ob der Treiber ordnungsgemäß installiert wurde, indem Sie den Geräte-Manager auf Ihrem Computer öffnen. Suchen Sie nach dem PlutoSDR-Gerät unter den USB-Geräten. Wenn das Gerät dort angezeigt wird, wurde der Treiber erfolgreich installiert und das PlutoSDR-Gerät ist bereit zur Verwendung.

   ### Installation von GNU - Radio
Um GNU Radio zu installieren, besuchen Sie die [offizielle Website](https://wiki.gnuradio.org/index.php/InstallingGR) und laden Sie die passende Installationsdatei für Ihr Betriebssystem herunter. Führen Sie dann das Installationsprogramm aus und folgen Sie den Anweisungen. Stellen Sie sicher, dass alle erforderlichen Abhängigkeiten installiert sind. Öffnen Sie nach der Installation GNU Radio und konfigurieren Sie die Einstellungen nach Ihren Vorlieben. Überprüfen Sie abschließend, ob die Software ordnungsgemäß funktioniert, indem Sie eine Beispielanwendung ausführen oder ein neues Projekt erstellen und testen.

  ### Software
   ![ABbilung ](./img/GNU.pdf)


  ### Resümee
Dieses Projekt bietet eine breite Palette an Lernmöglichkeiten. Es können grundlegende Kenntnisse in den Bereichen Software und Hardware erlangt werden.
Der Schwerpunkt ist dabei auf der Frequenzanalyse und Signalverarbeitung. 
Zudem können die Fähigkeiten durch Funkanwendungen und Signalverarbeitungsblöcke in GNU Radio erlangt werden. 

Zusammenfassend lässt sich sagen, dass es ein spannendes Projekt ist. Welches durch seine gute Veranschaulichung heraussticht.  
