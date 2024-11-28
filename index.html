<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>sprawdz PESEL</title>
</head>
<body>
    <h1>Sprawdź PESEL</h1>
    <script>
        function checkPesel() {
           
            let pesel = prompt('Podaj swój numer PESEL:');
           
           
            if (pesel.length !== 11 || !/^\d+$/.test(pesel)) {
                alert("Błąd: PESEL musi składać się z 11 cyfr.");
                return;
            }
 
         
            let year = parseInt(pesel.substring(0, 2));
            let month = parseInt(pesel.substring(2, 4));
            let day = parseInt(pesel.substring(4, 6));
            const gender = parseInt(pesel.charAt(9)) % 2 === 0 ? "Kobieta" : "Mężczyzna";
 
           
            const months = ["styczeń", "luty", "marzec", "kwiecień", "maj", "czerwiec", "lipiec", "sierpień", "wrzesień", "październik", "listopad", "grudzień"];
            if (month >= 1 && month <= 12) {
                year += 1900;
            } else if (month >= 21 && month <= 32) {
                month -= 20;
                year += 2000;
            } else if (month >= 41 && month <= 52) {
                month -= 40;
                year += 2100;
            } else if (month >= 61 && month <= 72) {
                month -= 60;
                year += 2200;
            } else {
                alert("Błąd: Nieprawidłowy miesiąc w PESEL.");
                return;
            }
 
           
            const daysInMonth = [31, (isLeapYear(year) ? 29 : 28), 31, 30, 31, 30, 31, 31, 30, 31, 30, 31];
            if (day < 1 || day > daysInMonth[month - 1]) {
                alert("Błąd: Nieprawidłowy dzień w PESEL.");
                return;
            }
 
           
            document.write('Rok: ', year, "<br>");
            document.write('Miesiąc: ', months[month - 1], "<br>");
            document.write('Dzień: ', day, "<br>");
            document.write('Płeć: ', gender, "<br>");
        }
 
       
        function isLeapYear(year) {
            return (year % 4 === 0 && (year % 100 !== 0 || year % 400 === 0));
        }
    </script>
 
    <button onclick="checkPesel()">Sprawdź PESEL</button>
</body>
</html>
