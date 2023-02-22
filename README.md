<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Element with class selector
		
	</title>
	<style>
		/*all h2 element */
		h2{
			color: red;
			text-align: center;
		}

		/*all with class="highlight" */
		 .highlight {
			font-size: 20px;
			font-weight: bold;
			font-style: italic;
			background-color:green;
			opacity: .6;
		}
		/* element with id="mainpoint" */
		#mainpoint{
			font-size: 24px;
			font-weight: bold;
			background-color: red;
			opacity: .7;
		}
		/* all p AND h1 elements */
		p, h1{
			color:blue;
			text-align: center;
		}
		
	</style>
    </head>
    <body>
         <h1>simple selectors (h1)</h1>
         <h2>subheading 1 (h2)</h2>
         <p class="highlight">dhamaan koodhka kor kahusan waa inaad <br>
         	sifican u qortaa waxaa uu ku saabasan yahay sida waxa 
         	loo kala bedelo Oo ah kalarada iyo qoraalada farta cabirkeeda <br>
         	wax welbo Oo kusaabsan HTML iyo CSS bilowgooda ahna dhaxda casjharka html iyo css
         	maxime quos?
         	 </p>
         	 <p class="highlight">paragraph with
         	 attribute class="higlight". lorem ipsum
         	 dolor sit amet, consectetur adipisicing
         	elit.</p>
         	<h2>subheading 2 (h2)</h2>
         	<p>koodkan wuxuu anfacayaa nolashaada inta kadhiman<br>
         	 waad isticmalikarta casharadan waxay kaa caawinaya 
         	 inaad dhisto wabsaayd adiga leedaha Oo Aad kuraaxaysato dhisidiisa <br>
         	BARO WAX BADAN WAXA QORAY OMAR HUSSEIN AADAN </p>
         	<div>this is the main point of the entire
         		article.so, attribute
         		<span id="mainpoint">id="mainpoint".</span
         	</div>

         <p>
			Let's Link to a website fan page I created for this course!
			<!-- link to website page with target-->
			<a href="Images.html"
			target="_blank" title="like our page!">course website page</a>
		</p>
    </body>
    </html>
