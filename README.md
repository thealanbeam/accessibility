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


