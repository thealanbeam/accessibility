# Accessibility
Accessibility doesn't have to be difficult.

##Add ARIA roles
<code><pre>
`<div class="layerclassname" role="XXX" aria-lable="Description of div that serves as an alt text of the div"> __CONTENT__ </div>`
</pre></code>

The attribute "role" allows screen readers to know what the content represents and is serving as.

### Possible role paramters
* Alert
* Article
* Button
* Grid
* Heading
* Img
* Link
* Main

Comprehensive list of all roles. http://www.w3.org/TR/wai-aria/roles#role_definitions


## Making Images Accessible
Sometimes we use a background image in a div, it would be nice to communicate that image sometimes. Possible through use of Roles.
<code><pre>
    ``<div id="hero" role="img" aria-lable="Description of background image">
      <div class="panel">For instance, a panel box in middle</div>
    </div>``
</pre></code>


## Writing a good description
Screen readers interpret to the user a description about what is happening in the image. These descriptions need to be concise but yet convey actions and words portrayed.

### Do nots
* Be redundant
* Use the phrase "image of" or "graphic of"


### Do
* Images should be used when related to page copy and your alt text should show that
	- If the image is followed by a caption, the use of a verbose alt may not be needed
	- If the image is standing on it's own, it may need a full 
* show the content and role the image has on the page	
	
All images, decorative or not, needs an alt tag. Decorative images suffice with an empty tag i.e. <code>alt =""</code>	

To determine if an image is decorative or not, ask to question--If I didn't use this image, what would I put here?

### Complex figures
With the longdesc tag deprecating with the emergence of HTML5, the figure tag is quickly replacing it. It's purpose is to make a symantic connection between caption and the image.
<code><pre><figure>
<img src="company-logo.jpg">
<figcaption>Internet Connections Corporation</figcaption>
</figure></pre></code>
