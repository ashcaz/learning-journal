## Design web pages with CSS

### Duckett Ch. 10 Introducing CSS

**Understanding CSS**

- The key to undertsnading how CSS works is to imagine that there is an invisible box around ebery HTML element.
- CSS allows you to create rules that determines what each individual box is presented
- CSS associates the rules you create with the HTML element. A CSS rule has two parts a **selector** - indicates which element the rule applies to, and a **declaration** -indicates how the elements referred to in the selector should be styled

p (selector){
    font-family (property); Arial (value); (everything inside curly brackets = decllaration)
}

- Declarations sit inside of curly brackets
- Declarations are made up of two parts: a **property** - indicates the aspect of the element you want to change, and a **value** - specify settings you want to use for the chosen property.
- Several properties in one declaration can be specified when seperated by a semi-colon

**Using External CSS**

- You can use the link element in an HTML document to tell the browser where to find the CSS file used to style the page

link href="css/styles.css" type="text/css" rel="stylesheet"

- href specifies the path to the CSS file
- The type attribute  tells you the type of document
- rel specifies the relationship between the HTML page and the file it is linked to

**Using Internal CSS**

- you can style within the HTML document using the style element

**CSS Selectors**

- universal selector :  *{}
- type selector :  h1, h2, h3 {}
- class selector : .note {} or p.note - targets on p elements with that class attribute
- ID selector : #introduction {}
- Child selector : li>a {} - targets any a elements that are children of li
- adjacent sibling selector : h1+p {} - targets first element after any h1 element but no othe p element

CSS works in cascading rules - goes from top to bottom, if two rules are identical for one selector the latter of the two with take precedence over the first

**Advantages of External Style Sheet**

- All your web pages can share the same style sheet
- When making a change to all h1 elements you dont have to individually change every element. You only need to change one css style sheet.

### Duckett Ch.11 - Color

**Foreground Color**

- To change forground color use property color in your declaration.
- You can provied the value (color you want) by color name, hex code or RGB value

h1{
    color: DarkCyan (color name) / #ee3e80 (hex code) /rgb(100,100,900);
}

**Background Color**

-To change the background color use the property background-color in your declaration.
Same rules apply as forground color for your value selection.

**Understanding Color**

- RGB values: values for red, green, and blue are expressed as numbers between 0 and 255. rgb(102[red], 205[green], 170[blue])
- Hex Codes: hex values represent values for red, green, and blue in hexadecimal code.
- Color Names: colors represented by printed name. Very limited in number
- Saturation: referts to the amount of gray in a color
- Brightness: refers to how much black is in a color. Max brightness - no black in color

**Opacity**

-using rgba (0,0,0,.5) as a value in your declaration provides opacity. Value is between 0-1 representing 0-100% opacity.

p{
    color: rgba(0,0,0, .25)
}


[Back to Home Page](https://ashcaz.github.io/learning-journal/)