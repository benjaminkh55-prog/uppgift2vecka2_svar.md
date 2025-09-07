# Skillnaden mellan vattenfallsmodellen och agil metodik

## Vattenfallsmodellen
- Mer stabilitet, struktur och planering.
- Kraven och målet är tydliga och klara.
- Man gör allt i ordning, steg för steg:
  1. Plan
  2. Bygg
  3. Test
  4. Klart
- Passar när man vet exakt vad man vill ha och det inte ska ändras.
- **Exempel:** Bygga ett hus – man ändrar inte ritningen efter att huset är påbörjat.

## Agil metodik
- Mer flexibilitet och anpassning.
- Man jobbar i små delar, testar och ändrar längs vägen.
- Passar när man inte är helt säker på kraven eller när saker kan ändras snabbt.
- **Exempel:** Bygga en app – man kan släppa en första version och sedan förbättra den.

---

# Git-commit

## Vad är ett Git-commit?
Git-commit är en ögonblicksbild av ditt projekt vid en viss tidpunkt.  
När man gör ett commit sparas ändringarna i koden tillsammans med ett meddelande som beskriver vad man har gjort.  
Varje commit får ett unikt ID så att man kan spåra exakt vad som ändrats, när och av vem.

## Varför är det viktigt?
- **Historik:** Se hur projektet har utvecklats över tid.
- **Återställning:** Om något går fel kan du backa till en tidigare fungerande version.
- **Samarbete:** Flera personer kan arbeta på samma projekt utan att skriva över varandras kod.
- **Spårbarhet:** Förstå varför en viss ändring gjordes genom commit-meddelandet.

## Exempel
Jag jobbar på en webbsida tillsammans med min kollega:  
- Jag lägger till en ny funktion och gör ett commit: *"lagt till ny funktion i koden"*.  
- Min kollega gör ett commit: *"fixat designen på startsidan"*.  
- Vi slår ihop våra ändringar (merge) och allt fungerar bra.  
- Om en bugg uppstår kan vi återställa projektet till det senaste fungerande commitet, vilket sparar tid och minskar risker.

---

# Samarbete med GitHub

## Vad innebär samarbete med GitHub?
GitHub gör det möjligt för flera personer att arbeta på samma projekt samtidigt.

## Viktiga funktioner
- **Branch:** En separat version av koden där man kan utveckla nya funktioner utan att störa huvudkoden.
- **Pull request:** En förfrågan om att slå ihop (merge) sin branch med huvudbranchen, ofta med kodgranskning.
- **Merge:** Slår ihop en branch med huvudbranchen.
