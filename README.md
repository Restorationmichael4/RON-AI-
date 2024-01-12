# RON-AI-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RON AI - Your Ultimate AI Solution</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Header Section -->
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#pricing">Pricing</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
      <div class="login-signup">
        <button class="login-btn">Login</button>
        <button class="signup-btn">Sign Up</button>
      </div>
    </nav>
    <h1 class="logo">RON AI</h1>
  </header>
  
  <!-- Home Section -->
  <section id="home" class="home-section">
    <h2 class="section-title">Welcome to RON AI</h2>
    <p class="section-description">We provide cutting-edge AI solutions that revolutionize the way you work and live. Our AI technologies generate answers to your questions, images based on text prompts, movies and videos based on text prompts or scripts, music and music videos based on text or script, and enhance images based on text prompts. Our services are free for generating answers, but for generating images, movies, and videos more than twice a week, or for enhancing images more than once a month, you need to pay $5, $7, $6, respectively. For unlocking premium for everything, it costs $35 for a yearly subscription. If you want to pay for yearly subscription on a monthly basis, the prices will be divided by 10. The subscription will expire after a month.</p>
    <button class="get-started-btn">Get Started</button>
  </section>
  
  <!-- Services Section -->
  <section id="services" class="services-section">
    <h2 class="section-title">Our Services</h2>
    <div class="service-card">
      <img src="answer.png" alt="Answer Icon" class="service-icon">
      <h3 class="service-title">Answer Generation</h3>
      <p class="service-description">Our AI technologies generate accurate and detailed answers to your questions based on prompt.</p>
      <button class="copy-btn" disabled>Copy Answer</button>
    </div>
    <div class="service-card">
      <img src="image.png" alt="Image Icon" class="service-icon">
      <h3 class="service-title">Image Generation</h3>
      <p class="service-description">Our AI technologies generate high-quality images based on text prompts. You can generate images twice a week for free, or pay $5 to generate images as much as you want for a year.</p>
      <!-- Disabled Copy Button -->
      <!-- This button will be enabled when the user generates an image -->
      <!-- The image will be displayed next to this button -->
      <!-- The user can download the image by clicking the Download Button -->
      <!-- The Download Button will also be disabled until the user generates an image -->
      <!-- The user can also delete the image by clicking a Delete Button -->
      <!-- The Delete Button will also be disabled until the user generates an image -->  
      <!-- The user can also edit the image by clicking an Edit Button -->  
      <!-- The Edit Button will also be disabled until the user generates an image -->  
      <!-- When the user edits the image, they can use text prompts to change their clothes, hair , clothing accessories jewelleries, put the type of make up on their face , the type of shoe , the type and the items they are carrying infact it should be able to change anything about an image based on text prompt -->  
      <!-- When all these things are being done there should be an ad playing until everything is done editing thsi should be done always unless the user pays $1 per month -->  
    </div>  
    <!-- More Service Cards Here... -->  
  </section>  
  
  <!-- Pricing Section -->
  <section id="pricing" class="pricing-section">
    <!-- Pricing Table for Answer Generation -->  																										<div class="pricing-table answer-generation">  	<h3 class="pricing-title">Answer Generation</h3>  	<p class="pricing-description">Generate accurate and detailed answers to your questions based on prompt.</p>  	<ul class="pricing-features">  	<li><strong>&#8357;</strong>&nbsp;Free/Answer</li>  	<!-- This price will be displayed when generating answers for free -->  	<!-- When generating answers more than once in a day or more than twice in a week, this price will change to &#8357;5/Answer -->  	<!-- When generating answers more than twice in a week or more than once in a day for three consecutive days, this price will change to &#8357;7/Answer -->  	<!-- When generating answers more than once in a day or more than twice in a week for four consecutive days or more than twice in a week for two consecutive weeks, this price will change to &#8357;9/Answer -->  	<!-- When generating answers more than twice in a week for three consecutive weeks or more than twice in a week for four consecutive weeks, this price will change to &#8357;11/Answer -->  	<!-- When generating answers more than twice in a week for five consecutive weeks or more than twice in a week for six consecutive weeks, this price will change to &#8357;14/Answer -->  	<!-- When generating answers more than twice in a week for seven consecutive weeks or more than twice in a week for eight consecutive weeks, this price will change to &#8357;17/Answer -->  	<!-- When generating answers more than twice in a week for nine consecutive weeks or more than twice in a week for ten consecutive weeks, this price will change to &#8357;19/Answer -->  	<!-- When generating answers more than twice in a week for eleven consecutive weeks or more than twice in a week for twelve consecutive weeks, this price will change to &#8357;22/Answer -->  	<!-- When generating answers more than twice in a week for thirteen consecutive weeks or more than twice in a week for fourteen consecutive weeks, this price will change to &#8357;24/Answer -->  	<!-- When generating answers more than twice in a week for fifteen consecutive weeks or more than twice in a week for sixteen consecutive weeks, this price will change to &#8357;26/Answer -->  	<!-- When generating answers more than twice in a week for seventeen consecutive weeks or more than twice in a week for eighteen consecutive weeks, this price will change to &#8357;28/Answer -->  	<!-- When generating answers more than twice in a week for nineteen consecutive weeks or more than twice in a week for twenty consecutive weeks, this price will change to &#8357;30/Answer -->  	<!-- When generating answers more than twenty times consecutively without any break between them (i.e., without stopping using our services), this price will change to &#8357;32/Answer (the highest possible price) and you'll need to contact us at support@ronai.com to discuss your usage requirements and pricing options further. This is our fair usage policy which ensures that our services remain affordable and accessible to all our users while also allowing us to sustainably invest in research and development of our AI technologies. Based on your usage patterns over time (i.e., how many times you use our services per day/week/month), we may adjust your pricing accordingly (i.e., lower your pricing if you use our services less frequently or raise your pricing if you use our services more frequently). We reserve the right to modify our pricing policies at any time without prior notice. Please refer to our Terms of Service and Privacy Policy for further details regarding our pricing policies and usage restrictions. Thank you for choosing RON AI! We appreciate your business and look forward to serving you better every day! Based on your feedback and suggestions, we're constantly improving our AI technologies and expanding our services portfolio. Please don't hesitate to contact us at support@ronai.com if you have any questions or concerns regarding our pricing policies or if you'd like to request any new features or functionalities that would make our services even better suited to your needs. We're here to help! Best regards, RON AI Team." /> </ul>     </div><!-- End of Answer Generation Pricing Table --><!-- Pricing Table for Image Generation --><div class="pricing-table image-generation" style={{display: "none"}} >     <!-- This style is used because we don't want this pricing table to be displayed by default since it requires payment --><!-- We'll use JavaScript later on to show this pricing table when the user clicks on "Generate Images" button --><h3 class="pricing-title">Image Generation (Up To Twice A Week For Free)</h3><!-- This title will be displayed when generating images up to twice a week --><!-- When generating images three times within one week (i.e
