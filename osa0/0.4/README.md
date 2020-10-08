title 0.4: uusi muistiinpano

selain->palvelin: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note Selain lähettää uuden muistiinpanon palvelimelle joka tallentaa sen
palvelin-->selain: Palvelin ohjaa selaimen takaisin osoitteeseen https://studies.cs.helsinki.fi/exampleapp/notes
selain->palvelin: HTTP GET https://studies.cs.helsinki.fi/exampleapp/notes
palvelin-->selain: HTML-koodi
selain->palvelin: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css
palvelin-->selain: main.css
selain->palvelin: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js
palvelin-->selain: main.js
selain->palvelin: HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json 
palvelin-->selain: data.json sisältää uuden muistiinpanon jonka JavaScript näyttää selaimessa 
selain->palvelin: HTTP GET https://studies.cs.helsinki.fi/exampleapp/favicon.ico 
palvelin-->selain: favicon.ico  
 
