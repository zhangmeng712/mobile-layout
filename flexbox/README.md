 #flexbox layout

 ##reference
 - https://github.com/philipwalton/solved-by-flexbox
 - https://blog.isotoma.com/2010/08/css3-flexbox/
 - https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Flexible_boxes


 ## standard
  - http://www.w3.org/html/ig/zh/wiki/Css3-flexbox/zh-hans

 ## prefix tools
 - http://simevidas.jsbin.com/gufoko/quiet

 ## old and new version of flex-box

 ### old
     //old version
      display: -webkit-box;
      display: -moz-box;
      display: box;


 ### new
     display: -webkit-flex;
     display: flex;
     display: -moz-flex;


 ### compact
     display: -webkit-box;
     display: -moz-box; //2009
     display: -ms-flexbox;//2011
     display: -webkit-flex;
     display: flex; //now

 ## details
 ### flex type
     - display: inline-flex (make element inline-block)
     - display: flex (make element block)
     - demo: http://codepen.io/zhangmeng712/pen/pveaxK?editors=110

 ### direction

     - flex-direction:row row-reverse column column
     - box-orient:horizontal vertical

 ### wrap

     - flex-wrap: nowrap | wrap | wrap-reverse (should not use in mobile safari)

 ### justify-content
     - justify-content: flex-start | flex-end | center | space-between | space-around;(should not use in mobile safari)
 ###



