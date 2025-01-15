# Event Photo RPA Assistant 📷


## Descrierea proiectului 💡

Acest proiect automatizează procesul de gestionare a solicitărilor pentru fotografia de evenimente folosind tehnologia RPA. Robotul este dezvoltat pentru a:

- Citi emailurile primite de la clienți.
  
- Extrage informațiile relevante (nume, dată, tipul evenimentului).
  
- Genera o factură proformă în format PDF.
  
- Adăuga evenimentul în calendarul administratorului.
  
- Trimite un răspuns automat clienților, atașând documentul generat.

Scopul proiectului este de a reduce timpul necesar procesării solicitărilor, de a minimiza erorile umane și de a simplifica comunicarea cu clienții. Acest robot oferă o soluție eficientă și modernă pentru planificarea activității firmei de fotografie de eveniment.

## Funcționalități principale ⚙️

1.	Logica proiectului impartita in workflow-uri multiple (Flowchart + Sequence in functie de caz). Proiectul trebuie sa fie alcatuit din mai multe fisiere xaml, fiecare fisier fiind invocat in Main (Invoke Workflow)
   
2.	Folosirea mai multor tipuri de variabile (String, Int, Double, List, Array, Datatable, etc)

3.	Automatizare fisiere Excel (citire date/scriere date/procesare) 
   
4.	Automatizare fisiere PDF (native/image) 
   
5.	Automatizare aplicatii web/aplicatii desktop (folosirea de activitati de UI cu selectori stabili si folosirea wildcard-urilor, introducere date, extragere date, etc.)
   
6.	Tratare exceptii de baza (validarea datelor extrase/introduse, verificarea incarcarii paginilor/elementelor cu Element Exists, folosirea mecanismelor de Retry) Tratare de exceptii folosind Try Catch, Throw, Rethrow 

7. 	Functionarea proiectului la schimbarea datelor de test 
   
8.	Automatizare Email (citire sau trimitere email)
   
9.	Folosire fisier de configurare (json sau excel)

## Cerințe pentru rulare 📌

🖇️Software necesar 

- UiPath Studio (versiunea 2022 sau mai nouă).

🖇️Librării și pachete 

- UiPath.Mail.Activities
  
- UiPath.Excel.Activities
  
- UiPath.PDF.Activities
  
- UiPath.System.Activities
  
- UiPath.UIAutomation.Activities
