###Height and width media features:
 <p>The height and width of the viewport can be found by using the <code>height</code> and <code>width</code>, 
 media features. 
 Each of these media features can be prefixed with the <code>min</code> or <code>max</code> qualifiers to obtain 
 minimum and maximum widths of the viewport or device. 
 Similarly, the <code> device-height</code> and <code>device-width</code> features are based off the height and 
 width of the output device.Values for these height and width media features may be relative or absolute units.</p>
 <p><b>Example</b></p>
<pre><code>@media all and (min-width: 320px) and (max-width: 780px) {...}</code></pre>
