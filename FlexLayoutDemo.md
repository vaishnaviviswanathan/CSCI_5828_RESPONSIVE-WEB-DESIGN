###Example:
<p>The HTML and CSS snippet for a flexible layout would be as follows:</p>
<p><b>HTML</b></p>
<pre><code> 
  \<div class="container"\>
  \<section\>...\</section\>
  \<aside\>...\</aside\>
  \</div\>
</pre></code>
<p><b>CSS for fixed layout</b></p>
<pre><code> 
 .container {
  width: 538px;
}
section,
aside {
  margin: 10px;
}
section {
  float: left;
  width: 340px;
}
aside {
  float: right;
  width: 158px;
}
</pre></code>

<p><b>Output for fixed layout</b></p>
<img src=https://cloud.githubusercontent.com/assets/14301140/11171945/40c61e44-8bba-11e5-9cf6-7da85b2493e9.JPG></img>






