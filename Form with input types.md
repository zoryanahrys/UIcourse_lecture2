<!Doctype html>
<html>
	<head>
		<meta charset="utf8"/>
		<title>Form with input types</title>
		<style>
			body {background-color: #ffbaba}
		</style>
		<meta name="author" lang="en" content="Zoriana Grys">
		</head>
	<body>
		<header>
<img src="http://www.itjam.com.ua/wp-content/themes/html5blank-stable/img/Logos_for_Web%20Page/Lviv_IT_School_www.lits.com.ua.JPG">
		</header>
<h1><b>HTML5. Form with all possible input types</b></h1>
<p><strong>Input Type: text</strong></p>
		   <form>
				First name:<br>
				<input type="text" name="firstname">
				<br>
				Last name:<br>
				<input type="text" name="lastname">
			</form>
			<br>
<p><strong>Input Type: password</strong></p>
			<form>
				User name:<br>
				<input type="text" name="username">
				<br>
				User password:<br>
				<input type="password" name="psw">
			</form>
			<br>
<p><strong>Input Type: submit</strong></p>
			<form action="action_page.php">
				First name:<br>
				<input type="text" name="firstname" value="Santa">
				<br>
				Last name:<br>
				<input type="text" name="lastname" value="Claus">
				<br><br>
				<input type="submit" value="Submit">
			</form>
			<br>
<p><strong>Input Type: radio</strong></p>
			<form>
				<input type="radio" name="sex" value="male" checked> Male
				<br>
				<input type="radio" name="sex" value="female"> Female
			</form>
			<br>
<p><strong>Input Type: checkbox</strong></p>
			<form>
				<input type="checkbox" name="vehicle1" value="Bike"> I have a bike
				<br>
				<input type="checkbox" name="vehicle2" value="Car"> I have a car 
				</form>
				<br>
<p><strong>Input Type: button</strong></p>
			<form>
				<input type="button" onclick="alert('Hello LITS!')" value="Click Me!">
			</form>
			<br>
<p><strong>Input Type: number</strong></p>
			<form>
  				Quantity (between 1 and 5):
  				<input type="number" name="quantity" min="1" max="5">
			</form>
			<br>
<p><strong>Input Restrictions</strong></p>
			<form>
  				Quantity:
  				<input type="number" name="points" min="0" max="100" step="10" value="30">
			</form>
			<br>
<p><strong>Input Type: date</strong></p>
			<form>
  				Birthday:
  				<input type="date" name="bday">
			</form>
			<br>
<p><strong>Input Type: color</strong></p>
			<form>
  				Select your favorite color:
  				<input type="color" name="favcolor">
			</form>
			<br>
<p><strong>Input Type: range</strong></p>
			<form>
  				<input type="range" name="points" min="0" max="10">
			</form>
			<br>
<p><strong>Input Type: month</strong></p>
			<form>
  				Birthday (month and year):
  				<input type="month" name="bdaymonth">
			</form>
			<br>
<p><strong>Input Type: week</strong></p>
			<form>
  				Select a week:
  				<input type="week" name="week_year">
			</form>
			<br>
<p><strong>Input Type: time</strong></p>
			<form>
  				Select a time:
  				<input type="time" name="usr_time">
			</form>
			<br>
<p><strong>Input Type: datetime</strong></p>
			<form>
  				Birthday (date and time):
  				<input type="datetime" name="bdaytime">
			</form>
			<br>
<p><strong>Input Type: datetime-local</strong></p>
			<form>
  				Birthday (date and time):
  				<input type="datetime-local" name="bdaytime">
			</form>
			<br>
<p><strong>Input Type: email</strong></p>
			<form>
  				E-mail:
  				<input type="email" name="email">
			</form>
			<br>
<p><strong>Input Type: search</strong></p>
			<form>
  				Search Google:
  				<input type="search" name="googlesearch">
			</form>
			<br>
<p><strong>Input Type: tel</strong></p>
			<form>
  				Telephone:
  				<input type="tel" name="usrtel">
			</form>
			<br>
<p><strong>Input Type: url</strong></p>
			<form>
  				Add your homepage:
  				<input type="url" name="homepage">
			</form>
			<br>
<footer>
  <p><strong>By Zoriana Grys</strong></p>
 </footer>
	</body>
</html>
