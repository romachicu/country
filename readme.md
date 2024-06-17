1. Initirea unui fiser HTML:
   <!DOCTYPE html>
2. Structura unui fiser HTML:
   ![alt text](..//images/structura-html.png)
3. Partea vizibila/invizibila [head/body]
4. Crearea unui Liste:
   <ul> - Unordered List
   Tag-ul <ul> este folosit pentru a defini o listă neordonată, adică o listă în care ordinea elementelor nu este importantă. Elementele dintr-o listă neordonată sunt de obicei marcate cu bullet points (puncte).

   <li> - List Item
   Tag-ul <li> este folosit pentru a defini un element dintr-o listă, fie ea neordonată (<ul>) sau ordonată (<ol>).
5. Crearea unui tabel:
   <table border="1">: Creează un tabel și setează o bordură pentru acesta.
   <tr>: Definește un rând în tabel. Fiecare rând din tabel este plasat între tag-urile <tr>...</tr>.
   <th>: Definește o celulă de antet (header) în tabel. Antetele sunt de obicei afișate cu text îngroșat și aliniat la centru.
   <td>: Definește o celulă de date în tabel. Fiecare celulă de date este plasată între tag-urile <td>...</td>.

   <!DOCTYPE html>
   <html>
   <head>
       <title>Exemplu Tabel HTML</title>
   </head>
   <body>

   <h2>Exemplu de Tabel</h2>

   <table border="1">
       <tr>
           <th>Nume</th>
           <th>Vârstă</th>
           <th>Oraș</th>
       </tr>
       <tr>
           <td>Maria Popescu</td>
           <td>28</td>
           <td>București</td>
       </tr>
       <tr>
           <td>Ion Ionescu</td>
           <td>34</td>
           <td>Cluj-Napoca</td>
       </tr>
       <tr>
           <td>Elena Vasilescu</td>
           <td>25</td>
           <td>Timișoara</td>
       </tr>
   </table>

   </body>
   </html>
