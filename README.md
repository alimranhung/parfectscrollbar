# parfectscrollbar

How to use css.
.your-element{
    position: relative;
    height: 400px;
    width: 500px
}

How to use scrollbar color change for css.
.ps--theme_green.ps--active-y.ps > .ps__scrollbar-y-rail > .ps__scrollbar-y {
    background: blue;
}

Color for any theme value.

.ps--theme_red.ps > .ps__scrollbar-y-rail > .ps__scrollbar-y {
    background-color: red;
}

How to use js.
jQuery(document).ready(function($){

     $("html").perfectScrollbar();
     
     $(".your-element").perfectScrollbar();
     
               /*or*/
               
     /*scrollbar color change for js*/
     $("html").perfectScrollbar({
     	theme:'green'
     });
     $(".section-bg-area").perfectScrollbar({
     	theme:'red'
     });
        
});
