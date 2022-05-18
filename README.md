# Sånger

Detta repo innehåller

- [Sånghäftet](./sanghafte/) – en LaTeX-mall
- [Sjungboken](./sjungbok/) – också en LaTeX-mall samt förkompilerade versioner av sjungboken
- [Sångtexter](./texter/) – texter som kan användas i sånghäftet och sjungboken

## Använda mallarna

Skapa först en kopia av [Overleaf-projektet](https://www.overleaf.com/read/hfrdcszwfcsy) till ditt eget Overleafkonto.

### Sånghäftet

I din kopia av Overleaf-projektet bör du i dokumentets meny välja att kompilera `sanghafte/main.tex`. Det är också i detta dokument du redigerar för att ändra innehållet i sånghäftet:

1. Ändra titel, värdar, meny o.s.v. i `sanghafte/main.tex`
1. Ändra logga genom att ladda upp en egen fil till `sanghafte/logo.png`
1. Lägg in dina låtar i ordning med `\inputsong{...}` (vilka sånger som finns tillgängliga ser du i mappen [`texter`](./texter/))
1. Lägg in `\newpage` om en rubrik fastnar på föregående sida
1. Kompilera!
1. Skriv ut (dubbelsidigt längsmed långsidan)!

### Sjungboken

Sjungboken finns tillgänglig som pdf här:

- [Digital version](./sjungbok/sjungboken.pdf)
- [Tryck-version (A6)](./sjungbok/sjungboken-print.pdf)
- [Omslag för tryck (A6)](./sjungbok/framsida-print.pdf)

För instruktioner i hur sjungboksmallen avänds, se READMEn i [sjungbok](./sjungbok).

## Ändringar och tillägg

Det finns olika sätt att göra ändringar (ordnat utifrån smidighet):

- [Skicka ändrigsförslag direkt till Sångförmännen](mailto:sangforman@ftek.se)
- Gör en fork av projektet, och skapa en pull-requests, se [GitHubs dokumentation](https://docs.github.com/en/get-started/quickstart/contributing-to-projects)

**OBS** Ändringar skall inte göras i Overleaf-projektet.