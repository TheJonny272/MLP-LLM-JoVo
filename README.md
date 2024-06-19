# MLP/NLP-LLM-JoVo
Mistral wird in vier verschiedenen Szenarien des MLP/NLP verwendet und mit anderen Open- und Closed LLMs verglichen.

1) Aufgabe: Was wollen Sie testen (gerne mit Beispiel)?
  Mit dem Open LLM Mistral sollen vier verschiedene Satzvervollständigungsszenarien analysiert und mit einem anderen Open LLM (Llama) sowie einem Closed LLM (ChatGPT) verglichen werden. Hierbei teile ich die vierteilige Aufgabenstellung       mit meiner Kommilitonin Norma Katrin Wilcken. Modell und Datensatz werden sich jedoch unterscheiden. Die vier Aufgaben für das LLM lauten:
      1. Here is part of a comment. Complete the last sentence: ...
      2. Complete the second verse in a way that it rhymes with the first verse:... / Vervollständige den zweiten Vers so, dass er sich auf den ersten Vers reimt:...  [Hier wird sowohl mit englischen als auch deutschen Eingabedaten gearbeitet und diese im nachhinein verglichen]
      [3. Complete the input to create a joke with a punchline:...]
      [4. Rewrite the following sentence in a formal / colloquial way:...]
  Zum Schluss werden die Ergebnisse im Hinblick auf ihre Richtigkeit analysiert und unter den Modellen / Sprachen miteinander verglichen.

2) Datenbasis (Medium, Sprache, Quelle)

   Medium:
      Text
   
   Sprache:
      Englisch
   
   Quellen:
     1. Social Media Kommentare (z.B. von Youtube),
     2. diverse englische und deutsche Webseiten mit Reimen, aus denen dann nur ein Vers kopiert wird (Ausgabe des LLMs kann auch mit originalem Anschlussvers verglichen werden)
     [3. diverse englische und deutsche Webseiten mit Witzen, aus denen dann nur der erste Satz kopiert wird (Ausgabe des LLMs kann auch mit originaler Pointe verglichen werden)]
     [4. selbstgeschriebene Beispielsätze (eventuell auch Social Media Feeds)]

4) OpenLLM, das Sie nutzen wollen (muss nicht unbedingt das von Ihnen vorgestellte sein)
    Mistral in einer Version mit 7,2 oder 46,7 Billionen Parametern von Hugging Face:
    https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2
    [https://huggingface.co/mistralai/Mixtral-8x7B-Instruct-v0.1]

5) Experimentdesign - wie wollen Sie vorgehen und wie die Ergebnisse beurteilen? Testen Sie vielleicht, wie geläufige LLMs die Aufgaben erledigen?
    Alle originalen Daten, Inputdaten (mit Prompt und Blank), Outputdaten und die Korrektheit werden in einer Google Doc Tabelle festgehalten und später mit den anderen Modellen verglichen. Zusätzlich wird bei der 2. Aufgabe noch eine Unterteilung in englische und deutsche Iputs und Outputs erfolgen. Im Vergleich werden die Ergebnisse bzw. Ausgaben meines Modells Mistral mit denen von Llama und ChatGPT auf Richtigkeit / Logik hin verglichen und bewertet.
