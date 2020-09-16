# Design Web Pages with CSS

## Chapter 10: Introducing CSS

- CSS treats each HTML element as it appears inside its own box and uses rules to indicate how the element should look
 - Rules are made up of: 
    - Selectors specify the elements that the rule applies 
        **and** 
    - declararions indicte what these elements should look like
- different selector types  allow you to target rules at different elements
- Declarations are made of 2 parts
    - the prpoerties of the element that you want to change
    - the values of those properties
    - i.e. the font-family property sets the choice of font and the value arial specifies Arial as the preferred typeface
- CSS rules usually apper in a seperate document for scope of responsibility and scalability  easier to troubleshoot and make stylistic (logos and colors) changes across all the pages in a website

## Chapter 11: Color

- RGB 
- Hex Codes
- Color Names
- CSS3 has HSLA

- color picker can be used to find the right color mixture

- hue - color
- saturation - how much grey is in the color
- brightness - how much black is in the color

- Adding comments in CSS use /* and */ around comments
 - these are usefull for breaking the page into sections making it easier to read

### Properties 
- color ex {color: cyam} changes color of font
- background color ex {background-color: black}

    **Best Practice** no background color will = make the background page transparent and the user may set a background color that makes your text hard to read - remember to set background color everytime to prevent this issue
 
- Contrast
    - Low Contrast: hard to read avoid 
    - High Contrats: Easier to read but should be avoided for log bodies of text
    - Medium Contrast: Good for long spans of text

- Opacity available in CSS3 can beused to play with opacity of a background

- **Pro tip** When using CSS3, Opacity and HSL make sure to use a RGB or hex value for code first in case the user is using an older browser that doesn't read the newer code. use the older values first and newer code second 

 [<-- Back](README.md)