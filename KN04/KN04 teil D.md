
| Volume | Typ | Persistenz |
| - | - | - |
|EBS Root|Hot|Nein|
|EBS Zusätzliches Volumen|Hot|Ja|
|S3|Warm|Ja|

EBS Root:

Ist im dauerbetrieb was beteutet das es Hot ist. 
Es zeigt eine hohe Persistenz, da es gleichzeitig mit einer Instanz gelöscht wird,
wenn diese Instanz gelöscht wird.



EBS Zusätzliches Volumen:

Ist hot, da es die zusätzlichen Elemente zu EBS root darstellt,
was das Betriebssystem ist. Es zeigt sich durch Persistenz aus,
da Volumen nicht gelöscht werden.


S3:

Warm passt, da das Bild nur manchmal aufgerufen wird. Es zeigt Persistenz, da das Bild weiterhin existiert, solange es nicht gelöscht wird.
