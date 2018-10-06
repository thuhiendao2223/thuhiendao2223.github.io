
<!DOCTYPE html>
<html>
<title>HienDAO</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<style>
body {font-family: "Times New Roman", Georgia, Serif;}
h1,h2,h3,h4,h5,h6 {
    font-family: "Playfair Display";
    letter-spacing: 5px;
}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-padding w3-card" style="letter-spacing:4px;">
    <a href="#home" class="w3-bar-item w3-button">DATAHOLICS</a>
    <!-- Right-sided navbar links. Hide them on small screens -->
    <div class="w3-right w3-hide-small">
      <a href="#about me" class="w3-bar-item w3-button">About me</a>
      <a href="#achievements" class="w3-bar-item w3-button">Achievements</a>
	  <a href="#Little thing" class="w3-bar-item w3-button">Little thing</a>
      <a href="#contact" class="w3-bar-item w3-button">Contact</a>
    </div>
  </div>
</div>

<!-- Header -->
<header class="w3-display-container w3-content w3-wide" style="max-width:1600px;min-width:500px" id="home">
  <img class="w3-image" src="/w3images/hamburger.jpg" alt="Hamburger Catering" width="1600" height="800">
  <div class="w3-display-bottomleft w3-padding-large w3-opacity">
    <h1 class="w3-xxlarge">Le Catering</h1>
  </div>
</header>

<!-- Page content -->
<div class="w3-content" style="max-width:1100px">

  <!-- About me Section -->
  <div class="w3-row w3-padding-64" id="about me">
    <div class="w3-col m6 w3-padding-large w3-hide-small">
     <img src="C:\Users\thuhien.dao\Desktop\Dao Thu Hien -AAS1921581\Capture.PNG" class="w3-round w3-image w3-opacity-min" alt="About me" width="600" height="750">
    </div>

    <div class="w3-col m6 w3-padding-large">
      <h1 class="w3-center">About me</h1><br>
      <h5 class="w3-center">An awardee of Australian Award 2018</h5>
      <p class="w3-large">My name is Hien DAO, I am currently a student of the Business Information System Master program at College of Business and Economics (CBE) in Australian National University. My interest domain is about <span class="w3-tag w3-light-grey">database structure,</span> data analytics and machine learning. </p>
      <p class="w3-large w3-text-grey w3-hide-medium">I am also very keen on cooking and hiking, also I am a big fan of travelling.</p>
    </div>
  </div>
  
  <hr>
  
  <!-- Achievements Section -->
  <div class="w3-row w3-padding-64" id="achievements">
    <div class="w3-col l6 w3-padding-large">
      <h1 class="w3-center">My achievements</h1><br>
	  <h4>Australian Award Scholarships (2018)</h4>
      <p class="w3-text-grey">Offered by Australian Government. </p><br>
	  
	  <h4>The Orange Knowledge Program Fellowship(2018)</h4>
      <p class="w3-text-grey">Offered by the Dutch Ministry of Foreign Affairs. </p><br>
	  
      <h4>Orange Tulip Scholarships(2018)</h4>
      <p class="w3-text-grey">Offered by Dutch higher education institutions, multinationals and government institutes.</p><br>
    
      <h4>Master Mind Scholarships for International Students (2018)</h4>
      <p class="w3-text-grey">Offered by Government of Flanders (Belgium). </p><br>
	  
	  <h4>Government of Ireland Scholarships(2018) - Reserved List</h4>
      <p class="w3-text-grey">Offered by Department of Education and Skills and managed by the Council.</p><br>
    
	 
    </div>
    
    <div class="w3-col l6 w3-padding-large">
      <img src="C:\Users\thuhien.dao\Desktop\Dao Thu Hien -AAS1921581\Fully-Funded-Australia-Awards-Scholarships-2018-1.jpg" vspace=30 class="w3-round w3-image w3-opacity-min" alt="Scholarships" style="width:50%" />
	  
	  
	  <img src="C:\Users\thuhien.dao\Desktop\Dao Thu Hien -AAS1921581\download.jpg" vspace=30 class="w3-round w3-image w3-opacity-min" alt="Scholarships" style="width:50%" />
	  
	  
	  <img src="C:\Users\thuhien.dao\Desktop\Dao Thu Hien -AAS1921581\download2.jpg" vspace=30 class="w3-round w3-image w3-opacity-min" alt="Scholarships" style="width:50%" />
	  
	  
	  <img src="C:\Users\thuhien.dao\Desktop\Dao Thu Hien -AAS1921581\download.png" vspace=50 class="w3-round w3-image w3-opacity-min" alt="Scholarships" style="width:50%" />
    </div>
  </div>

  <hr>
  
  <!-- Contact Section -->
  <div class="w3-container w3-padding-64" id="contact">
    <h1>Contact</h1><br>
    <p>You can contact me via my website or my Gitlab <a href="https://gitlab.com/felicity2302">Click here</a> to exchange interest in data analytics and machine learning.</p>
    <p class="w3-text-blue-grey w3-large"><b>My address: Canberra, Australia</b></p>
    <p>Or just send me a message here:</p>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="My interest domain is" required name=" "></p>
      <p><input class="w3-input w3-padding-16" type="datetime-local" placeholder="Date and time" required name="date" value="2017-11-16T20:00"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Question" required name="Message"></p>
      <p><button class="w3-button w3-light-grey w3-section" type="submit">SEND MESSAGE</button></p>
    </form>
  </div>
  
<!-- End page content -->
</div>

<!-- Footer -->
<footer class="w3-center w3-light-grey w3-padding-32">
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>

</body>
</html>
