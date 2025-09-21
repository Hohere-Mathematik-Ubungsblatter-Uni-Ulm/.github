# .github
Hier findet ihr die LaTeX Dateien der Übungsblätter, welche ich im Wintersemester 24/25, in der Höheren Mathematik I an der Uni Ulm, bearbeitet habe.

# Aufbau der Dokumente:
## Aufgaben Ordner
Hier sind Unterordner zu den einzelnen Aufgaben. In diesen Unterordnern ist immer eine task.tex und evtl andere genutzte Mittel. 
Die task.tex beinhaltet die bearbeitete Aufgabe.
## main.tex
Hier steht Kurs, Semester und unter \supervisor der Eigene Name. Bei \title das richtige Blatt angeben und \setboolen{showsolutions}{\true} so lassen, sonst werden die Lösungen nicht angezeigt.
Im Dokument selber dann per \addtask{./PATH/TO/TASK.TEX}{task}{} die einzelnen Lösungen einfügen.
