<!DOCTYPE html>
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<title></title>
	<link rel="stylesheet" href="">
<script>
	day=new Date()     //..get the date

	x=day.getHours()    //..get the hour

	if(	x>=6 && x<12 ) {

   document.write('<style type="text/css">body{background: white url(images/coffee.jpg);background-size:cover}"></style>')

	} else if(x>=12 && x<16) {

   document.write('<style type="text/css">body{background: white url(images/day.jpg);background-size:cover}</style>')

	} else if(x>=16 && x < 19) {

   document.write('<style type="text/css">body{background: white url(images/ninja.jpg);background-size:cover}</style>')

	} else if (	x>=19 && x<6) {

   document.write('<style type="text/css">body{background: white url(images/night.jpg); background-size:cover}</style>')
	}
</script>
</head>
<body style="
    text-align: center;
    margin: 20% auto;
    font-family: Helvetica;
    color: darkgray;
    font-size: 70px;
    //background: rgba(0,0,0,0.74);
">
<a  style="font-size:20px;
			float:right;
			text-decoration:none;
			color:lightblue;
			margin-right:2%;
			margin-top:-18%;
			padding:2%;
			"
	href="javascript:location.reload(true)">
	Reload This Page
</a>
<script>
var Quotation=new Array() // do not change this!

// Set up the quotations to be shown, below.
// To add more quotations, continue with the
// pattern, adding to the array.  Remember
// to increment the Quotation[x] index!

Quotation[0] = "“ Any code of your own that you haven't looked at for six or more months might as well have been written by someone else. ” - Eagleson's law";
Quotation[1] = "“ Programs must be written for people to read, and only incidentally for machines to execute. ” - Abelson / Sussman";
Quotation[2] = "“Trying to become something in a world where everyone wants to become something is a thing that needs God's programming.” ― Michael Bassey Johnson";
Quotation[3] = "“Think like a fundamentalist, code like a hacker.”― Erik Meijer";
Quotation[4] = "“Any fool can write code that a computer can understand. Good programmers write code that humans can understand.” ― Martin Fowler";
Quotation[5] = "“Enlightenment is the unprogrammed state.” ― Jed McKenna";
Quotation[6] = "O! Youth! What a pain in the backside.";
Quotation[7] = "“Truth can only be found in one place: the code.”― Robert C. Martin,";
Quotation[8] = "“Talk is cheap. Show me the code.” ― Linus Torvalds";
Quotation[9] = "Invention is the mother of too many useless toys.";
Quotation[10] = "“I'm not a great programmer; I'm just a good programmer with great habits.” ― Kent Beck";
Quotation[11] = "“Some of the best programming is done on paper, really. Putting it into the computer is just a minor detail.” ― Max Kanat-Alexander";
Quotation[12] = "“Simplicity is prerequisite for reliability.” ― Edsger W. Dijkstra" ;

// ======================================
// Do not change anything below this line
// ======================================
var Q = Quotation.length;
var whichQuotation=Math.round(Math.random()*(Q-1));
function showQuotation(){document.write(Quotation[whichQuotation]);}
showQuotation();
</script>

</body>
</html>
