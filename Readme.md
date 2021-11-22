# Rövarspråket

Övningsuppgift i programmering för måndag.

## Instruktioner

Skriv ett java-program som läser in en text och översätter den till rövarspråket. Presentera den
översatta texten för användaren. Du kan använda dialogrutor (showInputDialog och showMessageDialog)
eller terminalen (new Scanner(System.in) och System.out.println()). Du behöver iterera igenom den
inlästa strängen och bygga upp resultatet allt eftersom. Tänk på att du inte vet hur lång översättningen
blir innan den är klar. Ett alternativ är att bygga upp den översatta strängen genom att konkatenera
(addera) de nya tecknen allt eftersom.

## Rorövovarorsospoproråkoketot

Efter varje konsonant så lägger du till ett o och sedan konsonanten igen.
[Wiki](https://sv.wikipedia.org/wiki/R%C3%B6varspr%C3%A5ket)

## Mer

- låt användaren välja om den vill översätta mer text efter den första inmatningen är klar.
- Låt användaren översätta en fil (se sid 217 i boken hur en Scanner kan läsa från en fil).
- Skriv din översättare som en metod (public static String translate(String text){})
- Spara resultatet i en fil istället för att skriva ut det på skärmen (Se avsnitt 10.2).
- Översätt till andra språk?