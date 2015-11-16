###Example for Media Queries:
<p>Consider the example mentioned in flexible layouts section. Sometimes, the aside tab can become
too small in smaller viewports as follows:</p>
<img src = https://cloud.githubusercontent.com/assets/14301140/11173016/e95065ac-8bcd-11e5-8751-933d4aefe4cd.JPG>

<p>We can add a media query for viewports less than 420 pixels wide and change 
the layout by turning off the floats and changing the widths of the section and aside tabs.</p>
<p><b>CSS Media Query</b></p>
<pre><code>@media all and (max-width: 420px) {
  section, aside {
    float: none;
    width: auto;
  }
}</pre></code>

<p><b>Ouput after adding the CSS Media Query</b></p>
<p>The media queries allow the section and aside tabs to span the entire viewport 
and create room for other content.</p>
<p><img src = https://cloud.githubusercontent.com/assets/14301140/11173037/3c7a1016-8bce-11e5-9711-18cef615c099.JPG></p>

[<img align="left" alt="left" src="https://cloud.githubusercontent.com/assets/14101008/11165526/091b197c-8acf-11e5-8ac1-3a1e5042ed78.png" width="70" height="70"></img>](https://github.com/vaishnaviviswanathan/CSCI_5828_RESPONSIVE-WEB-DESIGN/blob/master/MQResoln.md)
[<img align="right" alt="right" src="https://cloud.githubusercontent.com/assets/14101008/11165527/0a4289a2-8acf-11e5-8378-c5e3a55ab4dc.png" width="70" height="70"></img>](https://github.com/vaishnaviviswanathan/CSCI_5828_RESPONSIVE-WEB-DESIGN/blob/master/Breakpoints.md)

