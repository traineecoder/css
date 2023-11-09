# Notes:
## CSS
CSS can implemented in three ways:
<ul>
    <li>External</li>
    <li>Internal</li>
    <li>In-line</li>
</ul>
In External styling, the sheets are creating elswhere and linked to the html, Internal styling is implemented using 'style' tag inside 'head' of html and Inline styles are added by using style attribute on tags.<br>
Internal and External sheets override each other based on their placement in 'head' tag of html.<br>
Inline overrides both internal and External.<br>
It is best to Use External way of implementing styles, As it is more managable.<br>

# Rule Set
A rule set comprised of selector, property and property values.

# Selector
There are mainly three types: element, class and id selectors.<br>
we can use same names for classes in tags But id's must be unique. It is always best practice to use classes and elements for writing code in CSS. Class names preceed by a dot(.) in CSS.<br>
we can group multiple selectors with comma(,).<br>
we can style only nested selectors by putting space like 'h1 h2' says select on h2 which resides in h1.<br>
There is also a way to select every element from html, it is by *, also known as universal selector. This is commonly used for CSS reset.<br>
Specifity for selecters are: id > classes > elements.<br>
We can override the specificty by adding '!important' after a property value. But It is not recommended.<br>
Some properties are inherited by every elements  like if we mention body { font-size: 22px; } it will inherited by elements under body. by default, form elements doesn't inherit any things. Likewise if you want those non-inherited elements to be inherited we should mention property value 'inherited' for appropriate property.<br>

# color
We can set color with hex values like #FFFFFF, rgb(255,255,255), hsl(100%,100%,50%) etc., It is better to tweak with these to give a good combination of text and background color for our page to look attractive.

# CSS Units
There are different units to specify sizes in CSS like px,inches etc., pixels is the common one used for starters. It is better to avoid absolute values as it creates problems for other parts of CSS. Instead we should 'relative to parent' and 'relative to root' concepts for configuring sizes. And for somethings we can use absolute values like borders etc.,<br>
The rem units are relative to root.<br>
The em units are relative to font size of current if mentioned otherwise its relative to its parents font_size.<br>
We use em units for properties if font size is mentioned in our scope or according to our use-case.<br>
The ch units specifies the width of characters in lines.<br>
The usage of percentages is best for defining widths.<br>
We can select the whole body page by using 'min-height: 100vh;' and expand as the content goes on.<br>

# Box model
As the changes that are not specified by us in CSS, the browser will set up those valuse, To avoid this we use CSS reset which helps to reset everything from the start and apply our configurations to webpage.<br>
The content-box in box-sizing is applies to only content i.e., if we mention a width to content all space is used by content in addition to padding and border. The border-box in box-sizing is applies to content, padding and border. Hence, the width will be aggregated to all of those.<br>
In box model, we commonly consider padding,margin, borders, outlines etc.,<br>
The thing about the outline is, it doesn't consume space in box.<br>
We can change looks of box with box-radius property.<br>

# Typography
Typography is the way that text is arranged and presented.<br>
There are many ways we can manipulate text and can also import fonts from other resources on web.<br>

# Styling links
Links can be styled according to our needs, we can change the defaults to make our link look good.<br>
Pseudo-classes can be accessed by putting colon after the element.<br>
The order is important while using pseudoclasses.<br>

# List Styles




