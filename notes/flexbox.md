<h2>Flexbox</h2>

<h3>What is Flexbox</h3>

<img src="https://github.com/antonio-datahack/dev-html-css-course/blob/main/img/flexbox/what-is-flexbox.png"/>


<h3>Flex container -Flex items</h3>

<img src="https://github.com/antonio-datahack/dev-html-css-course/blob/main/img/flexbox/flex-container-flex-items.png">

<h3>The <code>flex-direction</code> property</h3>

<p>The <code>flex-direction</code> shows the direction on which the contents will be aligned.</p>

<img src="https://github.com/antonio-datahack/Ironhack-Web-Developer-Bootcamp/blob/main/img/flexbox-directions.png" width="500">
<p><img src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_ecf32476fd55b14b23626f070dc18ce0.gif" alt="" class="raw md-image" width="500">
<img src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_e9e1a52befe234c06ab093f7e83b85e9.gif" alt="" class="raw md-image" width="500"></p>

<h3>The <code>justify-content</code> property</h3>

<p>With <code>justify-content</code> we can <strong>horizontally</strong> arrange the items inside the flex container.</p>
</div>

<img src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_8d83d09f81ac2e495fca787946133020.gif" alt="" class="raw md-image" width="500">

<ul>
<li><code>flex-end</code>: items are positioned on the end of the flex-direction line</li>
<li><code>center</code>: items are centered along the line</li>
<li><code>space-between</code>: items are evenly distributed in the line; the first item is on the start line, last item on the end line</li>
<li><code>space-around</code>: items are evenly distributed in line with equal space around them. Note that visually the spaces aren’t equal since all the items have equal space on both sides. The first item will have one unit of space against the container edge, but two units of space between the next item because that next item has its own spacing that applies.</li>
<li><code>space-evenly</code>: items are distributed so that the spacing between any two items (and the space to the edges) is equal.</li>
</ul>

<h3>The <code>align-items</code> property</h3>

<p>This one is a lifesaver. Remember how hard it was to align the elements <strong>vertically</strong>? With <code>align-items</code> you can easily do this. Be careful with this one. If you don’t assign any value to this property, it is <strong>default value will be <code>stretch</code> which stretches the children to fill the whole container</strong>.</p>

<img src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_7166b023c79602acf89600997bf32acb.gif" alt="" class="raw md-image" width="500">

<ul>
<li><code>flex-start</code>: cross-start margin edge of the items is placed on the cross-start line</li>
<li><code>flex-end</code>: cross-end margin edge of the items is placed on the cross-end line</li>
<li><code>center</code>: items are centered in the cross-axis</li>
<li><code>baseline</code>: items are aligned such as their baselines align</li>
</ul>

<p>:exclamation: If you have an image as a flex item(a direct child of the flex container), it will be distorted by the automatic sizing and aligning. To “protect” the dimensions of an image, we need to put it inside a div.</p>

<img src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_572b2b1f546ded288cd7592cabf403a1.gif" alt="" class="raw md-image" width="500">

<p>There are <em>many</em> more things you can do with Flexbox. Check out <strong><a href="https://css-tricks.com/snippets/css/a-guide-to-flexbox/" target="_blank" rel="noopener noreferrer">CSS Trick’s Guide</a></strong> and take a look at all the possibilities you have.</p>

<p>To give you some experience with Flexbox and get acquainted with the newly discovered properties, go to <a href="https://flexboxfroggy.com/" target="_blank" rel="noopener noreferrer">Flexbox Froggy</a> and put your knowledge to practice.</p>

<h3>Extra Resources</h3>

<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/position" target="_blank" rel="noopener noreferrer">MDN <code>position</code> property</a> - See all the detailed information about the property on its documentation.</li>
<li><a href="https://medium.freecodecamp.org/how-to-use-the-position-property-in-css-to-align-elements-d8f49c403a26" target="_blank" rel="noopener noreferrer">How to use the position property in CSS to align elements + video</a></li>
<li><a href="http://alistapart.com/article/css-positioning-101" target="_blank" rel="noopener noreferrer">CSS Positioning 101</a></li>
<li><a href="https://www.youtube.com/watch?v=JJSoEo8JSnc" target="_blank" rel="noopener noreferrer">Flexbox - more than basics - video</a></li>
<li><a href="https://github.com/ohansemmanuel/Understanding-Flexbox" target="_blank" rel="noopener noreferrer">Understanding Flexbox: Everything you need to know</a></li>
<li><a href="https://flexboxfroggy.com/" target="_blank" rel="noopener noreferrer">Flexbox Froggy</a></li>
</ul>
