---
title: '<span style="display:none">MaKaCo</span>'
output: 
    html_document:
      include:
        after-body: footer.html
---

<script src="https://kit.fontawesome.com/0af1a424a5.js" crossorigin="anonymous"></script>
<meta charset="UTF-8">
<style>

.main-container {
  max-width: 1600px;
  margin-left: auto;
  margin-right: auto;
}

img {
  margin-left: auto; 
  margin-right:auto
  width: 100%;
  height: 100%;
  border: none;
}
figcaption {
margin-left: auto; 
margin-right:auto
width: 100%;
border: none;
text-aling: center;
}
table {
border: none;
margin-left: auto; 
margin-right:auto
text-aling: center;
}

td {
padding-left: 15px;
padding-right: 15px;
text-aling: center;
}

footer {
   left: 0;
   bottom: 0;
   width: 100%;
   background-color: white;
display: block;
   text-align: center;
}

.header {
  float: left;
  width: 15%;
  margin-left: auto; 
  margin-right: auto; 
  display: block; 
  font-size:3em; 
  text-align: center;
}

.body {
  float: left;
  width: 70%;
  margin-left: auto; 
  margin-right: auto; 
  display: block; 
  text-align: center;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 1000px) {
  .header, .body {
    width: 100%;
    height: auto;
  }
}
</style>

<div class="header">
 ![We analyze your data **_for_** you, **_with_** you](images/logo.png) 
</div>

<div class="body">
<div style="display: block; padding-top: 40px; font-size:2em;"> 
**What we do**
</div>

<table>
<tr>


<td>
<figure>
<img style="float:left; width: 300px;" src="images/TrinityCompositeLogo.png" alt="Trulli">
<figcaption>
<center>
Transcriptome assembly with [Trinity](https://github.com/trinityrnaseq/trinityrnaseq/wiki)
</center>
</figcaption>
</figure>
</td>

<td>
<figure>
<img style="float:left;  width: 300px;" src="images/TrinotateLogo.png" alt="Trulli">
<figcaption>
<center>
Transcriptome annotation with [Trinotate](https://github.com/trinotate/trinotate.github.io/wiki)
</center>
</figcaption>
</figure>

</center>
</td>

<td>
<figure>
<img style="float:left;width: 300px; " src="images/read_alignment.png" alt="Trulli">
<figcaption>
<center>
Read alignment and counting

<p style="font-size:0.75em"> Source: [JBrowse](https://jbrowse.org/docs/alignments.html)</p>
</center>
</figcaption>
</figure>
</td>
</tr>


<tr>
<td>
<figure>
<img style="float:left;width: 300px; " src="images/Transcriptomes_heatmap_example.png" alt="Trulli">
<figcaption>
<center>
Differential expression analysis


<p style="font-size:0.75em"> Source: [Wikipedia](https://commons.wikimedia.org/wiki/File:Transcriptomes_heatmap_example.svg) <p>
</center>
</figcaption>
</figure>
</td>

<td>
<figure>
<img style="display: inline; float: left;width: 300px; " src="images/pca.png" alt="Trulli">
<figcaption>
<center>
Principal component analysis
<p style="font-size:0.75em"> Source: [Wikipedia](https://en.wikipedia.org/wiki/Principal_component_analysis) <p>
</center>
</figcaption>
</figure>
</td>

<td>
<figure>
<img style="display: inline; float: left;width: 300px; " src="images/hclust.png" alt="Trulli">
<figcaption>
<center>
Hierarchical clustering
<p style="font-size:0.75em"> Source: [Wikipedia](https://en.wikipedia.org/wiki/Hierarchical_clustering) <p>
</center>
</figcaption>
</figure>
</td>

</tr>
</table>


<footer>
&nbsp;
<hr />
<!-- <p style="text-align: center;">Copyright &copy; 2020 MaKaCo, Inc. All rights reserved.</p> -->


<p style="text-align: center;">Get in touch with MaKaCo</p>
<p style="text-align: center;font-size: 2em">[<i class="fab fa-github"></i>](https://github.com/makacom)     [<i class="fab fa-twitter"></i>]()     [<i class="fab fa-linkedin-in"></i>]()  </p>
&nbsp;

</footer>
</div>
