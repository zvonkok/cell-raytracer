Abstract
========

Viele Prozessorhersteller stossen mitlerweile and die Grenzen des machbaren um
die Performance eines Prozessors auf herkoemlichen Weg zu steigern. Um den grossen
Bedarf an Rechenleistung zu decken ziehen die Hersteller mitlerweile multi-core chips in Betracht.
Das Joint Venture aus IBM Sony und Toshiba entwickelten deshalb eine neue Prozessorarchitektur
die Cell Broadband Engine.
Die CBE vereint auf einem Chip einen DualThread faehigen 64-Bit-PowerPC kern und Acht sogenannte
SPUs. Sinergetic Processing Units sind RISC-Prozessoren mit einer 128-Bit-SIMD Einheit fuer
single und double precision Berechnungen.
Die CBE vereint eine Pipeline-Architektur, simultaneous
multithreadung und eine Multicore-Architektur auf einem highly integrated chip um ein hohes Mass an Parallelisierung
zu Erreichen.
(this not only results in regarding single problems but in ... as well)
Die Konsequenz aus dem ganzen besteht darin, dass fuer eine Aufgabe voellig neue Ansatze zur Loesung entwickelt
werden muessen die speziell and die Architektur der CBE angepasst sind. Durch die Vielfalt der Moeglichkeiten ein
Problem zu loesen ergeben sich mehrere Loesungen die genau abgewogen werden muessen um die beste Performance
zu erreichen.
In order to demonstrate
Die Problemstellung die sich damit ergibt wurde fuer einen Raytracer untersucht der auf die CBE
portiert werden soll.

Im Rahmen dieser Arbeit sollen unterschiedliche Ansätze untersucht und vorgestellt werden,
wobei die einzelnen Ansaetze hinsichtlich ihrer Performance und ihrer tauglickheit fuers
Raytracing untersucht werden. Ziel der Arbeit ist es eine optimale Architektur fuers
Raytracing auf der CBE mit Fokus auf Performance zu entwerfen.

As a result, this optimized Architecture for Raytracing will be able to render medium sized scenes
at rates far better than conventional Raytracer.
