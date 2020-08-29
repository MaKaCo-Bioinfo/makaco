---
title: '<span style="display:none">Contact us</span>'
output: 
  html_document:
    include:
      after_body: footer.html
    css: figures.css
---
<style type="text/css">
footer {
   bottom: 0;
   width: 50%;
   position: fixed;
   background-color: white;
display: block;
   text-align: center;
}

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

