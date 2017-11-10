# Sticky-Fingers
main page
<!DOCTYPE html>
<html>
	<head>
		<link href="css/main.css" type="text/css" rel="stylesheet" />
		
		<!-- Kodowanie strony -->
		<meta charset="utf-8" />

		<!-- Znaczniki meta pod SEO -->
		<meta name="description" content="Strona poświęcona australijskiemu zespołowi Sticky Fingers" />
		<meta name="keywords" content="muzyka, zespół, autralijski zespół, Sticky Finegrs" />
		<meta name="author" content="Irena" />

		<!-- Wspomaganie responsywności strony -->
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />

		<title> Strona zespołu Sticky Fingers</title>

	</head>
	<body>
		<div id="menu">
			<div class="sub-box">
				<a href="kontakt.html"><div class="item">Kontakt</div></a> <!-- jeżeli chcemy aby odnośnik obowiązywało cały przycisk, a nie tylko tekst -->
				<a href="ozespole.html"><div class="item">O zespole</div></a>
				<div class="item"><a href="trasa.html">Trasa</a></div>
				<div class="item"><a href="muzyka.html">Muzyka</a></div>
			</div>
		</div>
		<div id="content">
			<form action="test.html" method="GET">
				<!-- Formularz wyrównanie w tabeli -->
				<table>
					<tr>
						<th scope="row"><label>Login:</label></th><td><input type="text" name="asd" value="login" /></td>
					</tr>
					<tr>
						<th scope="row"><label>Hasło:</label></th><td><input type="password" name="pass" /></td>
					</tr>
					<tr>
						<th scope="row"><label>E-mail:</label></th><td><input type="email" name="email" /></td>
					</tr>
					<tr>
						<td colspan="2">
							<textarea name="tekst">Pytanie do zespołu</textarea>
						</td>
					</tr>
				</table>

				<!-- Formularz -->
				<div>
					<input type="radio" name="Pytanie1" value="odp1" checked /> Kobieta
					<input type="radio" name="Pytanie1" value="odp2" /> Mężczyzna
				</div>
				<div>
					<select id="kraj" name="kraj" multiple>
						<option value="australia">Australia</option>
						<option value="austria">Austria</option>
						<option value="czechy">Czechy</option>
						<option value="niemcy">Niemcy</option>
						<option value="francja">Francja</option>
						<option value="polska">Polska</option>
						<option value="usa">USA</option>
						<option value="kanada">Kanada</option>
					</select>
				</div>
				<!-- Akceptacja regulaminu -->
				<div>
					<p>
						<input type="checkbox" name="regulamin" value="jeden" /> Akceptuję regulamin strony.
					</p>
				</div>

				<!-- Wyślij -->
				<div>
					<input type="submit" value="Wyślij" />
				</div>
			</form>
		</div>

		<!-- O zespole -->
		<h1 id="australijski">Australijski zespół Sticky Fingers</h1>
		<p class="sticky">Zespół Sticky Fingers powstał w Sydney w 2008 roku. Zagrali pierwszy koncert w 2009 roku. Dotychczas  wydali trzy albumy. 
		Do ich największych przebojów zalicza się: "Caress Your Soul", "How to fly", "Cyclone" and "Australia Street"</p>
		<a href="https://en.wikipedia.org/wiki/Sticky_Fingers_(band)">O Zespole</a>
		<p><span>Członkowie zespołu:</span></p>
		
		<ul>
			<li>Dylan Frost</li>
			<li>Paddy Cornwall</li>
			<li>Seamus Coyle</li>
			<li>Beaker Best</li>
			<li>Freddy Crabs</li>
		</ul>

		<!-- Zdjęcia zespołu -->
		<div class="team-photo">
			<a href="http://www.stickyfingerstheband.com/" target="blank">
				<img src="http://theinterns.net/wp-content/uploads/2015/09/StickyFingers.jpg" alt="Zespół Sticky Fingers" class="wszyscy" />
			</a>
		</div>

		<div class="muzycy">
			<div class="row">
				<div class="teammate-photo">
					<h3>Dylan Frost - wokalista i gitarzysta zespołu</h3>
					<img src="http://i.dailymail.co.uk/i/pix/2016/12/05/21/3B1354E700000578-4003208-image-a-12_1480973777752.jpg" 
					alt="Dylan Frost - wokalista i gitarzysta" class="teammate" />
				</div>
				<div class="teammate-photo">
					<h3>Paddy Cornwall - basista</h3>
					<img src="http://media.gettyimages.com/photos/paddy-cornwall-of-sticky-fingers-performs-on-day-5-of-the-rbc-royal-
					picture-id480559442?s=594x594" alt="Paddy Cornwall - basista" class="teammate" />
				</div>
			</div>
			<div class="row">
				<div class="teammate-photo">
					<h3>Seamus Coyle - gitarzysta</h3>
					<img src="https://s-media-cache-ak0.pinimg.com/736x/90/c0/67/90c0677a61b8a871e1bf8edbc41ccc53.jpg" 
					alt="Seamus Coyle - gitarzysta" class="teammate" />
				</div>
				<div class="teammate-photo left">
					<h3>Beaker Best - perkusista</h3>
					<img src="http://wpmedia.ottawacitizen.com/2015/07/beaker-best-of-sticky-fingers-performs-at-rbc-ottawa-blue1.
					jpg?quality=55&strip=all&w=840&h=630&crop=1" alt="Beaker Best - perkusista" class="teammate" />
				</div>
			<div class="row">
				<div class="teammate-photo">
					<h3>Freddy Crabs - klawisze</h3>
					<img src="http://wpmedia.ottawacitizen.com/2015/07/freddy-crabz-of-sticky-fingers-performs-at-rbc-ottawa-blues1.
					jpg?quality=55&strip=all&w=840&h=630&crop=1" alt="Freddy Crabs - klawisze" class="teammate" />
				</div>
			</div>
		</div>
		<div id="cookies-info">
			Cookies info
		</div>
		<div id="foot">
			Copyright &copy; 2017
		</div>
	</body>
</html>
