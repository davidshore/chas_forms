# Bygg ett Registreringsformulär

Dagens uppgift är att bygga ett registreringsformulär och layouta det med css grid. Du kommer också att skicka data från formuläret till en tjänst som kallas HTTPbin och den bör visa den data du har lagt in.

## Så slutför du denna uppgift

1. Gå online och hitta en sida med ett formulär som du gillar utseendet på och försök att återskapa stilen med hjälp av bland annat css grid. Det behöver inte bli exakt men försök att komma nära.

2. Bygg ett formulär som innehåller minst:

   - 2 x Textrutor
   - 1 x Lösenordsfält
   - 1 x Uppsättning radioknappar
   - 1 x Uppsättning checkboxar
   - 1 x Skicka-knapp

3. Sätt formulärets `action` till `https://httpbin.org/anything` och sätt `method="post"` på `<form>`. Detta innebär att httpbin kommer att visa dig hur datan skulle se ut om du skickade detta till en server. Försök skicka ditt formulär och se om du kan se svaret på httpbin.

4. Försök skicka ditt formulär för att se hur svaret från httpbin ser ut:

   - Hur ser textrutorna ut?
   - Vilket svar får du från lösenordsfältet?
   - Försök välja en eller ett par av radioknapparna och skicka igen. Vad ändras?
   - Välj inga av radioknapparna och skicka.
   - Markera kryssrutorna och skicka.
   - Lämna kryssrutorna obestämda och skicka.

### :books: Läslista

- [W3Schools - GET vs. POST](https://www.w3schools.com/tags/ref_httpmethods.asp)
- [W3Schools - Om HTML-formulär](https://www.w3schools.com/html/html_forms.asp)
- [W3Schools - Formulärelement](https://www.w3schools.com/html/html_form_elements.asp)
- [MDN - Styla HTML-formulär](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Styling_HTML_forms)

---

### :sos: Hur man får hjälp

Att lära sig att tänka som en webbutvecklare handlar om att lära sig att vara en expert på problemlösning. Så när du fastnar börja med steg 1 och fortsätt tills problemet är löst.

1. Googla! På engelska, skriv in felmeddelandet om det finns ett, sök inom det språk du använder (t.ex. CSS, JavaScript osv.).
2. Fråga dina kodkompisar i din grupp.
3. Fråga dina medstudenter i Slack.
4. Fråga David.

Kom ihåg att vi är en del av en delande gemenskap - dela svaret med dina kamrater!

---

### :boom: Success!

Efter att ha slutfört denna uppgift bör du känna dig bekväm med att bygga formulär i HTML och förstå vad som händer när formuläret skickas med POST-metoden. Du kommer också att veta hur data du skickar ser ut på serversidan för att senare kunna använda den till exempel för att skapa ett konto. Du kommer dessutum att ha fått öva på css grid.

---

### :runner: Extrauppgifter

Klar med huvuduppgiften? Här är några idéer för saker att fortsätta med:

1. Lägg till en fokuseffekt på input-taggar (använd CSS `:focus` pseudo-selector). Ändra fältets ram eller bakgrundsfärg och lägg till en ljuseffekt.
2. Använd lämpliga inmatningstyper och valideringar för fälten
   t.ex. med attributet required.
