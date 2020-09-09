B1W2L1 en B1W3L2:
<html>    
    <body>
        <script type="text/javascript"> //Damian Verburg, Software developer 
            var firstname;                                                                       //maakt variabelen voornaam
            var lastname;                                                                        //maakt variablen achternaam
            var age;                                        //maakt variablen leeftijd
            firstname   = prompt ("wat is je voornaam?");                                        //stelt vraag voor voornaam
            lastname    = prompt ("wat is je achternaam?");                                      //stelt vraag voor achternaam
            age         = prompt ("wat is je leeftijd?");                                        //stelt vraag voor leeftijd
            document.write("<h1>" + firstname + " " + lastname + "<br>" + age + "</h1>");        //zet antwoorden op site
        </Script>
    </body>
</html>













B1W3L3:

<!DOCTYPE html> 
<html lang="en">
<head>
    <meta charset= "UTF-8">
    <meta name= "viewport" content= "width=device-width, initial- scale=1.0">
</head>
<body>
    <script type="text/javascript">
        document.write("tafels van 3 en 6:" + "<br>");
        for(i = 1; i < 11; i++) {
            var tafelVan3 = i*3;                                               //dit geeft de tafel van 3 aan
            var tafelVan6 = i*6;
            document.write(tafelVan3 + "      ");
            document.write(tafelVan6 + "<br>");
        }
                                                                               //Damian Verburg, Software devloper 
        var num = 12;
        var num2 = 6;
        num = Math.abs(num2 + num);
        document.write("<br>" + "12=6=" + num + " ");
        num = Math.abs(num * 10);
        document.write("18x10=" + num + " ");
        num = Math.abs(num / 5);
        document.write("180:5=" + num + " ");
        num = Math.abs(num - 12);
        document.write("36-12=" + num);


        var start = 12;
        var nummer = prompt("vul hier uw nummer in:");
        nummer = Math.abs(start + nummer);

        var nummer2 = prompt("vul hier uw nummer in:");
        nummer= Math.abs(nummer + nummer2);

        var nummer3 = prompt("vul hier uw nummer in:");
        nummer = Math.abs(nummer / nummer3);

        var nummer4 = prompt("vul hier uw nummer in:");
        nummer= Math.abs(nummer - nummer4);
        document.write("<br>" + "<br>" + "uw berekening:" + nummer);

    </script>
    </body>
</html>

















B1W3O1:

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Datatype voorbeeld</title>
    </head>
    <body>
        <script type="text/javascript">

            var SmallPizza = prompt("hoeveel small pizza's wil je hebben?");
            var MediumPizza = prompt("hoeveel medium pizza's wil je hebben?");
            var LargePizza = prompt("hoeveel large pizza's wil je hebben?");

            const SMALLPIZZAPRICE = 1
            const MEDIUMPIZZAPRICE = 12
            const LARGEPIZZAPRICE = 26

            totalPrize = Number(SmallPizza) * Number(SMALLPIZZAPRICE) + Number(MediumPizza) * Number(MEDIUMPIZZAPRICE) + Number(LargePizza) * Number(LARGEPIZZAPRICE);
            document.write("<h1>" + "je heeft:" + SmallPizza + "Small pizza's gekozen" + "<br>" + "</h1>");
            document.write("<h1>" + "je heeft:" + MediumPizza + "Medium pizza's gekozen" + "<br>" + "</h1>");
            document.write("<h1>" + "je heeft:" + LargePizza + "Large pizza's gekozen" + "<br>" + "</h1>");
            document.write("<h1>" = "het totaal bedrag is" + "€" + TotalPrize + ",-" + "</h1>");
        </script>
        </body>
    </html>
