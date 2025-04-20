# Mi hoja de trucos CSS
## Selectores

Universal Selector `* {}`  
Type Selector `h1,h2,h3 {}`  
Child Selector `ul > li {}`
Descendant Selector `p a {}`  
Class Selector `.class {}`  
ID Selector `#id {}`  
Adjacent Sibling Selector `h1 + p {}`  
General Sibling Selector `h1 ~ p {}`
Attribute Selector `[attribute="SomeValue"] {}`

## PseudoSelectores y elementos

Mouse Over Selector `a:hover {}`
Active Link Selector `a:active {}`
Focus Selector `input:focus {}`
Visited Links Selector `a:visited {}`
Link Selector `.class:link {}`  
First Line Selector `P::first-line {}`  
First Letter Selector      `P::first-letter {}`    
First Child Selector `P:first-child {}`  
Last Child Selector `P:last-child {}`  
Only Child Selector `P:only-child {}`  
:nth-Child Selector `P:last-child {}`  
First Element of its Parent   Selector `p:first-of-type {}`  
Checked elements selector `input:checked {}`  
Disabled elements selector `input:disabled {}`  
Enabled elements selector `input:enabled {}`  
Elements that hav no Children Selector (including text modes) `p:empty {}`   
Not a Specified Element Selector `:not(p) {}`    
Before Element `.class::before {}` 
After Element `.class::before {}` 

## Estilos de texto
Font style `font-style: normal | italic | oblique`  
Font variant `font-variant: normal | small-caps`  
Font weight `font-weight: normal | bold | bolder | lighter | 100-900`  
Vertical aligment `vertical-align: baseline | 10px | sub | super | top | text-top | middle | bottom | text-bottom | initial`  
Font size `font-size: 12px | 0.8em | 80%`  
Text transform `text-transform: capitalise | lowercase | uppercase`  
Space between characters `letter-spacing: normal | 4px`  
Line height `line-height: normal | 3em | 34%`  
Horizontal alignment `text-align: left | right | center | justify`  
Text align last `text-align-last: auto | left | right | center | justify | start | end | initial | inherit`  
Text decoration `text-decoration: none | underline | overline | line-throught` 
Indent First Line `text-indent: 25px`
Font Family `Font-family: 'Open Sans', sans-serif`  
Text justify `text-justify: auto | inter-word | inter-character | none | initial | inherit`  
Text overflow `text-overflow: clip | ellipsis | string | initial | inherit`  
Text shadow `text-shadow: h-shadow v-shadow blur-radius color | none | initial | inherit` 

## Posicion
Position `position: static | relative | absolute | fixed | sticky`  
Position properties `top | right | bottom | left `  
Float element  `float: left | right | none`    
Clear floating elements `clear: none | left | right | both`  
Z Index `z-index: 3 | auto | inherit`  

## Background
Backgroud image `background-image: url()`  
Backgroud repeat `background-repeat: repeat-x | repeat-y | repeat | sound | no-repeat |`     
Background color `background-color: #2AA9E0`      
Background position `background-position: top | right | bottom | left | center`  
Background attachment `background-attachment: scroll | fixed | local | initial | inherit`

## Box properties
Box sizing `box-sizing: border-box | content-box`  
Margin `margin: 2px 4px 6px 8px | 0 auto`  
Padding `padding: 2px 4px 6px 8px`  
Border color `border-color: #2AA9E0`  
Border style `border-style: none | hidden | dotted | dashed | solid | double | groove | ridge | inset | outset`  

## Estilos de lista
List type `list-style-type: disc | circle | square | none`  
List position `list-style-position: inside | outside`  
List image `list-style-image: url()`  

## Flexbox
Flex direction `flex-direction: row | row-reverse | column | column-reverse`  
Flex wrap `flex-wrap: nowrap | wrap wrap-reverse`  
Justify content `justify-content: flex-star | flex-end | center | space-between | space-around | space-evenly`  
Align items `align-items: flex-star | flex-end | center | baseline | space-around | stretch`  
Align content `align-content: flex-star | flex-end | center | space-between | space-around | stretch`
Order `Order: 0`  
Flex grow `flex-grow: 0`

## CSS grid
Grid template columns `grid-template-columns: 40px 50px auto 50px 40px`  
Grid template rows `grid-template-rows: 25% 100px auto`  
Grid template areas `grid-template-areas: "a b c" | none`  
Grid template `grid-template: "a a a" 20% "b b b" auto | 100px 1fr / 50px 1fr`  
Grid column gap `grid-column-gap: 10px`  
Grid row gap `grid-row-gap: 10px` 
justify items `justify-items: start | end | center | stretch`  
Align items `align-items: start | end | center | stretch`  
Justify content `justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly`  
Align content `align-content: flex-star | flex-end | center | space-between | space-around | stretch`  
Grid auto columns `grid-auto-columns: 100px | max-content | min-content`  
Grid auto rows `grid-auto-rows: 100px | max-content | min-content`  
Grid auto flow `grid-auto-flow: row | column | row dense | column dense`  
Grid column start `grid-column-start: 2 | areaname | span 2 | span areanname | auto`  
Grid column end `grid-column-end: 2 | areaname | span 2 | span areanname | auto`  
Grid row start `grid-row-start: 2 | areaname | span 2 | span areanname | auto`  
Grid row end `grid-row-end: 2 | areaname | span 2 | span areanname | auto`  
Grid column `grid-column: 3 /span 2`   
Grid row `grid-row: 3 /span 2`  
Justify self `justify-self: start | end | center | stretch`  
Align self `align-self: start | end | center | stretch`  

## Contenido dinamico
CSS variable `--variable-name: value`    
Variable usage `var(--variable-name)`  
Counter reset `counter-reset: name-of-counter`  
Counter increment `counter-increment: name-of-counter`    
Counter dynamic value `content: counter(name-of-counter)`      
Attribute dynamic value `content: attr(name-of-attribute)`














