#flexbox layout

##

##reference
 
 - https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Flexible_boxes
 - https://github.com/philipwalton/flexbugs
 - https://github.com/philipwalton/solved-by-flexbox


## standard
 
  - 2009: http://www.w3.org/TR/2009/WD-css3-flexbox-20090723/
  - 2011: http://www.w3.org/TR/2011/WD-css3-flexbox-20110322/
  - 2015: http://www.w3.org/TR/2014/WD-css-flexbox-1-20140925/

## prefix tools to solve old and new
 - http://simevidas.jsbin.com/gufoko/quiet

## old and new version of flex-box

### *old
 
      display: -webkit-box;
      display: -moz-box;
      display: box;


### *new
     display: -webkit-flex;
     display: flex;
     display: -moz-flex;


### *compact
     display: -webkit-box;
     display: -moz-box; //2009
     display: -ms-flexbox;//2011
     display: -webkit-flex;
     display: flex; //now

## details

   - DEMO: http://codepen.io/zhangmeng712/pen/pveaxK?editors=110

### flex type
     
   - display: inline-flex (make element inline-block)
   - display: flex (make element block)

### direction

   - flex-direction:row row-reverse column column
   - box-orient:horizontal vertical

### wrap
     
   - flex-wrap: nowrap | wrap(if not enough place will put content to the next row/column ) | wrap-reverse (should not use in mobile safari)

### flex-flow(direction wrap)
   - flex-flow: row nowrap;

### justify-content(horizontal distribution)
   - justify-content: flex-start | flex-end | center | space-between | space-around;(should not use in mobile safari)
   - horizontal center:
   
         -webkit-box-pack:center;
         -webkit-justify-content:center;
         -ms-flex-pack:center;
         justify-content:center;

### align-items (vertical distribution)
   -  align-items: flex-start | flex-end | center | baseline | stretch
   -  https://developer.mozilla.org/en-US/docs/Web/CSS/align-items

        -webkit-box-align:center;
        -webkit-align-items:center;
        -ms-flex-align:center;
        align-items:center;

###  align-self
   - used for flex items to change its align-items
   - align-items used for flex container

### flex-grow flex-shrink

### flex
  - flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]
  - flex-grow: width: *grow
  - flex-shrink: width: /shrink
  - flex-basis: the initial width of the div

### order
   - used for flex items; flex: 2
   - order of the flex items


## demos
   - detail examples:http://codepen.io/zhangmeng712/pen/pveaxK?editors=110
   - holy grail layout:
   - some classic layout like follows
   
![](../image/flex-box-app.jpg)


## bugs

   - https://github.com/philipwalton/flexbugs






