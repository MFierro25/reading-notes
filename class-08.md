#### CH 15 CSS Layout

- Things to remember when editing th layout is that eacch element is treated as its own box. it can be block level or in-line.<br>
- block elements can contain one another, having a parent and child elements, (containing elements)

position : (position-type) 
#### Relative
  - moves element from normal position
#### absolute
  - moves element in relation to its containing element
  - does not affect surrounding elements
#### Fixed 
   - moves in relation to browser window
   - does not affect surrounding
   - does not move when user scrollls up or down
#### Floating
  - moves far left or far right of containg element
  - contents flows around it
> Z-index is used for overlapping, used to show elements sit on top of each other. ( higher the number the closer it appears to the front)

#### FIxed width vs Liquid Layouts

fixed do not change sizes as user increases or decrease size of browser. liquid strestches or contracts.
FIxed pixel values are accurate. can end up with gaps. Liquid can make pages look different than intended.
