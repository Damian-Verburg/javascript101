labje 1 en 2:
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














labje 3:
<!DOCTYPE html> 
<html lang="en">
<head>
    <meta charset= "UTF-8">
    <meta name= "viewport" content= "width=device-width, initial- scale=1.0">


</head>
<body>
    <script>                                                                //Damian Verburg, Software Developer
    var number;                                                             //Je maakt een variabele
    alert("van welk nummer wil de tafel?");                                 //Dit vraag welk tafel je wilt hebben
    number = prompt("typ hier een nummer");                                 //Hier zet je het nummer in
    
    let str= ' ';                                                           //Dit maakt een string

    for (let i= 0; i < 11; i++) {                                           //Dit wordt een loop
        str = number * i;                                                   //De uitkomst van het number in de string
        document.write("<h1>" + i + "x" + number + "=" + str + "</h1>");    //Hier krijg je het te zien
    }
</script>
</body>
</html>
































pizza calculator:

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
