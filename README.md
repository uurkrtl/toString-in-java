Die equals() Methode ist eine in der Java-Standardbibliothek definierte Methode, die von der Object Klasse geerbt wird und verwendet wird, um zu überprüfen, ob zwei Objekte inhaltlich gleich sind. Die Standardimplementierung der equals() Methode in der Object Klasse vergleicht Objekte nach ihrer Referenz, dh sie gibt true zurück, wenn die beiden Objekte dasselbe Speicherobjekt referenzieren.

In den meisten Fällen müssen Sie die equals() Methode in Ihren eigenen Klassen überschreiben, um die semantische Gleichheit Ihrer Objekte festzulegen.

Die hashCode() Methode ist eine Methode der Object Klasse, die einen ganzzahligen Hash-Code für ein Objekt berechnet. Der Hash-Code ist eine numerische Darstellung des Objekts, die normalerweise verwendet wird, um Objekte in Sammlungen zu organisieren und zu suchen. In vielen Sammlungen, insbesondere HashMap und HashSet, wird der hashCode() Wert verwendet, um die schnelle Suche und den Zugriff auf Objekte zu ermöglichen.

Wenn Sie die equals() Methode überschreiben, sollten Sie auch die hashCode() Methode überschreiben, um sicherzustellen, dass Objekte, die als gleich betrachtet werden (laut Ihrer equals()-Implementierung), denselben Hash-Code haben. Dies ist wichtig, damit die Sammlungen ordnungsgemäß funktionieren.

Mein Artikel: https://www.linkedin.com/pulse/ist-equals-und-hashcode-java-ugur-kartal
