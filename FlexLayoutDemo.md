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

<p><b>CSS for flexible layout</b></p>
<pre><code> 
section,
aside {
  margin: 1.858736059%; /*  10px ÷ 538px = .018587361 */
}
section {
  float: left;
  width: 63.197026%;    /* 340px ÷ 538px = .63197026 */   
}
aside {
  float: right;
  width: 29.3680297%;  /* 158px ÷ 538px = .293680297 */
}
</pre></code>


