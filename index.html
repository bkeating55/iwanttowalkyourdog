
<?php
	if (isset($_POST["submit"])) {
		$name = $_POST['name'];
		$email = $_POST['email'];
		$message = $_POST['message'];
		$human = intval($_POST['human']);
		$from = 'Demo Contact Form';
		$to = 'bam326@gmail.com';
		$subject = 'Test';

		$body = "From: $name\n E-Mail: $email\n Message:\n $message";

		// Check if name has been entered
		if (!$_POST['name']) {
			$errName = 'Please enter your name';
		}

		// Check if email has been entered and is valid
		if (!$_POST['email'] || !filter_var($_POST['email'], FILTER_VALIDATE_EMAIL)) {
			$errEmail = 'Please enter a valid email address';
		}

		//Check if message has been entered
		if (!$_POST['message']) {
			$errMessage = 'Please enter your message';
		}
		//Check if simple anti-bot test is correct
		if ($human !== 5) {
			$errHuman = 'Your anti-spam is incorrect';
		}

// If there are no errors, send the email
if (!$errName && !$errEmail && !$errMessage && !$errHuman) {
	if (mail ($to, $subject, $body, $from)) {
		$result='<div class="alert alert-success">Thank You! I will be in touch</div>';
	} else {
		$result='<div class="alert alert-danger">Sorry there was an error sending your message. Please try again later</div>';
	}
}
	}
?>
<!DOCTYPE html>
<html lang="en">
<head>

  <title>Arlington Dog Walking Services</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <style>
  body {
      font: 20px Montserrat, sans-serif;
      line-height: 1.8;
      color: #f5f6f7;
  }
  p {font-size: 16px;}
  .margin {margin-bottom: 45px;}
  .bg-1 {
      background-color: #1abc9c; /* Green */
      color: #ffffff;
  }
  .bg-2 {
      background-color: #474e5d; /* Dark Blue */
      color: #ffffff;
  }
  .bg-3 {
      background-color: #ffffff; /* White */
      color: #555555;
  }

  .container-fluid {
      padding-top: 70px;
      padding-bottom: 70px;
  }
  .navbar {
      padding-top: 15px;
      padding-bottom: 15px;
      border: 0;
      border-radius: 0;
      margin-bottom: 0;
      font-size: 12px;
      letter-spacing: 5px;
  }
  .navbar-nav  li a:hover {
      color: #1abc9c !important;
  }
  #about p{
    text-align: left;
    font-size: 18px;
  }
  .form-group{
    text-align: center;
  }
  </style>
</head>
<body>
  <body data-spy="scroll" data-target=".navbar" data-offset="0">

<!-- Navbar -->
<nav class="navbar navbar-inverse navbar-fixed-top">
  <div class="container">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#">Bryan McCarthy - Iwanttowalkyourdog.com</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- First Container -->
<div id="about">
<div class="container-fluid bg-1 text-center">
  <h3 class="container-fluid bg-1">Affordable Dog Walking/Day Care in Arlington, Va.</h3>
  <img src="images/image.jpeg" class="img-responsive" style="display:inline" alt="Bryan" width="550" height="350">
  <p>As a nearly lifelong Arlington resident, I grew up a dog person. My first dog Jack came from the Vola-Lawson ASPCA. Honestly, he was always my dad's dog just like Annabelle in these pictures but I care for her as though I was first in her mind. This brings me to why I want to walk your dog. Arlington is an expensive place to live. I want to build a business that I can be proud of in order to support myself and one day a dog of my own. I look forward to meeting you and yours in order to build a trusted relationship and keep your dog happy in during the most boring time of his or her life (while you're away).</p>
</div>
</div>


<!-- Second Container (Grid) -->
<div id="services">
<div class="container-fluid bg-2 text-center">
  <h3 class="margin">Services</h3><br>
  <div class="row">
    <div class="col-sm-6">
      <p>Dog Walking</p>
      <img src="images/dog 2.jpg" class="img-responsive margin" style="width:100%" alt="Image">
      <p> 10 minute walk - $10 </p>
      <p> 20 minute walk - $15 </p>
      <p> 30 minute walk - $20 </p>
    </div>
    <div class="col-sm-6">
      <p>Doggy Day Care</p>
      <img src="images/Daycare.jpg" class="img-responsive margin" style="width:100%" alt="Image">
      <p>Need someone to keep your pet busy all day?  I will watch your dog while you are at work or if you need to get out of town.</p>
    </div>
  </div>
</div>
</div>

<!-- Third Container  -->
<div id="contact">
<div class="container-fluid bg-3 text-center">
  <h3 class="margin">Contact</h3><br>
  <div class="row text-center">
    <div class="span-sm-12">
      <p>(703) 371-2415</p>
      <p>Or you can send me a message here</p>

      <form class="form-horizontal" role="form" method="post" action="index.php">
      	<div class="form-group">
      		<label for="name" class="col-sm-2 control-label">Name</label>
      		<div class="col-sm-10">
      			<input type="text" class="form-control" id="name" name="name" placeholder="First & Last Name" value="<?php echo htmlspecialchars($_POST['name']); ?>">
      			<?php echo "<p class='text-danger'>$errName</p>";?>
      		</div>
      	</div>
      	<div class="form-group">
      		<label for="email" class="col-sm-2 control-label">Email</label>
      		<div class="col-sm-10">
      			<input type="email" class="form-control" id="email" name="email" placeholder="example@domain.com" value="<?php echo htmlspecialchars($_POST['email']); ?>">
      			<?php echo "<p class='text-danger'>$errEmail</p>";?>
      		</div>
      	</div>
      	<div class="form-group">
      		<label for="message" class="col-sm-2 control-label">Message</label>
      		<div class="col-sm-10">
      			<textarea class="form-control" rows="4" name="message"><?php echo htmlspecialchars($_POST['message']);?></textarea>
      			<?php echo "<p class='text-danger'>$errMessage</p>";?>
      		</div>
      	</div>
      	<div class="form-group">
      		<label for="human" class="col-sm-2 control-label">2 + 3 = ?</label>
      		<div class="col-sm-10">
      			<input type="text" class="form-control" id="human" name="human" placeholder="Your Answer">
      			<?php echo "<p class='text-danger'>$errHuman</p>";?>
      		</div>
      	</div>
      	<div class="form-group">
      		<div class="col-sm-10 col-sm-offset-2">
      			<input id="submit" name="submit" type="submit" value="Send" class="btn btn-primary">
      		</div>
      	</div>
      	<div class="form-group">
      		<div class="col-sm-10 col-sm-offset-2">
      			<?php echo $result; ?>
      		</div>
      	</div>
      </form> 



</body>
</html>
