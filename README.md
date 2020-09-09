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
