###Aspect Ratio Feature:
<p>The <code>aspect-ratio</code> and <code>device-aspect-ratio</code> features specify the width/height pixel 
ratio of the targeted rendering area ie. the output device. The min and max qualifiers can be use to set thresholds 
here as well. The value for the aspect ratio is specified by two integers w and h separated by a forward
slash<code>w/h</code> where <code>w</code> is the width in pixels and <code>h</code> is height in pixels. </p>

<b>Example</b>
<pre><code>@media all and (min-device-aspect-ratio: 16/9) {...}</pre></code>

