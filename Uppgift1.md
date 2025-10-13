# Uppgift 1 – Semantiska element och CSS intro

# Att göra 

1. Skriv en titel på sidan i <title> taggen
2. Skriv en lämplig rubrik, t.ex. hemsidans namn, i <header> med en <h1> tagg
3. I <nav> ska du lägga minst 2 relevanta länkar, detta kan vara länkar till .html sidor som du implementerar senare.
4. I <main> har du 2 sektioner. Välj vad dessa två ska innehålla.
5. I <footer> ska du skriva kontaktuppgifter till hemsidan. Dessa kan såklart vara fejkade.

# Följande styling ska finnas med external css
1. Ändra på hur <h1> ser ut
2. Se till att <header> har en bakgrund och eventuellt centrering av texten
3. Styla <footer>

# Anteckningar
Anteckna kort här vad du har gjort för förändringar på sidan i denna uppgift.


<!DOCTYPE html>

<html lang"sv">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device=device, initial-scale=1.0" />
  <title>StudyBoost</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
 

  <header>
    <h1>StudyBoost</h1>
  </header>   
  
  <nav>
    <a href="index.html">Start</a>
    <a href="kontakt.html">Kontakt</a>
  </nav>
  

  <main>
    <section>
      <h2>Om oss</h2>
      <p>Bättre än km.se och NOK</p>
    </section>


    <section>
      <h2>Nyheter</h2>
      <p>Här hittar du nyheter</p>

    </section>
   </main>


   <footer>
     <p>Kontakt: information.studyboost@gmail.com  Tel: 072-717 23 03</p>

   </footer>
</body>
</html>





    
     