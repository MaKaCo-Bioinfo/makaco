---
title: '<span style="display:none">Services</span>'
output: 
  html_document:
    includes:
      after_body: footer.html
    css: figures.css

---
<style type="text/css">
input[type="submit"]:hover {
background-color: #33B8FF;
color: white;

}
</style>
<script src="https://kit.fontawesome.com/0af1a424a5.js"></script>

To contact us for information about an analysis, fill out the form bellow.

<div rows=3>
<form name="makaco_contactform" method="POST" data-netlify="true">

<label >
    Your name: </label>  
    <input type="text" name="name" required/>
  
<label>
    Your e-mail: </label>  
    <input type="email" name="_replyto" required/>
   
<input type="hidden" name="_subject" value="MaKaCo contact" />

<label>
    Your message: </label> 
   
   <textarea name="message" style="padding: 5em; border-radius: 50px;" required></textarea>
 
<input type="hidden" name="_gotcha" />
    
<center>
<input type="submit" value="Send message" required/>
</center>
</form>

</div>
<br>

<br>
