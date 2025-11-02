


<html> 
	<head>
		<title>PHP Form Design</title>
		<link rel="stylesheet" href="css/style_form.css">
	</head>	
  <body>
	 
		 
    <h1>Brazil</h1>
	  
	  
	<div id = "main">
	
	    <hr>
		<?php
		//pull links from the nav.php page and places them in the navigation div
		require("nav.php") //'require' is %100 needed for the site to run 
		?>
		
		 <h2>Hola, Welcome to my brazilian travel blog</h2>
	
			<h2>Contact</h2>
		<?php
		//get the connection to the database in phpmyadmin
		require_once("PhpForm_mysqli.php");
		?>
		
		
<br>
		<!-- form starts here -->
		
		<div class="contact_container">
			<form action="connect.php" method="post">
		
	<!-- Name field -->
		<div class="row"> 	
	    <div class="column">
    	 <label for ="name">Full Name</label>
	   <!-- Lowercase "name" is the database feild name. keep all names lowercase in code + database to match. -->	
	   </div>
	   <div class="column2">
	    <input type="text" id="name" name="name" placeholder="your full name">	
	   </div>
	   </div>
		
			<!-- Email address field -->
		<div class="row"> 	
	    <div class="column">
    	 <label for ="email">Email Address</label>
	   <!-- Lowercase "name" is the database feild name. keep all names lowercase in code + database to match. -->	
	   </div>
	   <div class="column2">
	    <input type="text" id="email" name="email" placeholder="your email address">	
	   </div>
	   </div>
			
			<!-- Contact number field -->
	   <div class="row"> 	
	    <div class="column">
    	 <label for ="contactnumber">Contact Number</label>
	   <!-- Lowercase "name" is the database feild name. keep all names lowercase in code + database to match. -->	
	   </div>
	   <div class="column2">
	    <input type="text" id="phone" name="phone" placeholder="your contact number">	
	   </div>
	   </div>
			
		    <!-- message field -->
	   <div class="row"> 	
	    <div class="column">
    	 <label for ="message">message</label>
	   <!-- Lowercase "name" is the database feild name. keep all names lowercase in code + database to match. -->	
	   </div>
	   <div class="column2">
	    <textarea id="message" name="message" placeholder="write something..." style="height:200px"></textarea>	
	   </div>
	   </div>
			
	<br>
				
				
			<!-- submit Button -->
	   <div class="row">
	   <input type="submit" value="submit">
	   </div>
			
			</form>		
		</div>
		
		
	  </div>
	</body>
</html>		
