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

1.	Logica proiectului impărțită in workflow-uri multiple (Sequences). Proiectul este alcătuit din mai multe fisiere xaml, fiecare fișier fiind invocat în Main cu Invoke Workflow.
   
2.	Se folosesc mai multe tipuri de variabile (String, Int, Double, List, Array, Datatable, Dictionary).

3.	Automatizare fișiere Excel (citire date/scriere date/procesare).
   
4.	Automatizare fișiere native PDF.
   
5.	Automatizare aplicație web - Google Calendar (folosind activități de UI cu selectori stabili și folosirea wildcard-urilor, click, type into).
   
6.	Tratare excepții de bază (validarea datelor extrase, verificarea incărcării paginii cu Element Exists) Tratare de excepții folosind Try/Catch, Throw, Rethrow.
   
7.	Automatizare Email (citire și trimitere email).
   
8.	Folosire fișier de configurare JSON.

## Cerințe pentru rulare 📌

🖇️Software necesar 

- UiPath Studio (versiunea 2022 sau mai nouă).

🖇️Librării și pachete 

- UiPath.Mail.Activities
  
- UiPath.Excel.Activities
  
- UiPath.PDF.Activities
  
- UiPath.System.Activities
  
- UiPath.UIAutomation.Activities
