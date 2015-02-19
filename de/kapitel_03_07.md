##Tabelle ”teams” 

Die Tabelle wird dann benötigt, wenn Wettkämpfe ausgetragen werden, bei denen nur Mannschaftsergebnisse und keine Einzelergebnisse gewertet werden. (siehe [sub:Mannschaft])

Die Mannschaften werden beschrieben (Verein, Kategorie) und die einzelnen Mitglieder in der Tabelle ”teammembers” aufgeführt.

Mitglieder einer Mannschaft werden nicht zuätzlich in der Tabelle ”individuals” aufgeführt.

**Schüsselfelder**

* event_id (Fremdschlüssel [sub:Tabelle-”events”])
* team_id ([sub:team_id])

**Felder**

* title_short