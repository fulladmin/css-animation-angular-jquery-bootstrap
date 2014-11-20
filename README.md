nganimate
=========

140 awesome CSS3 animation classes, compatible with angular and natively jQuery and bootstrap

***
Commonly the ngAnimate module provides support for JavaScript, CSS3 transition and CSS3 keyframe animation hooks within existing core and custom directives.

The directives that support animation automatically are: ngRepeat, ngInclude, ngIf, ngSwitch, ngShow, ngHide, ngView and ngClass. Custom directives can take advantage of animation by using the $animate service.

HOW COMPATIBLE WITH jquery

Like ngAnimate which module of angular.js we developed native jquery plugin named jquery.ngAnimate.
jquery.ngAnimate has approximately the same functionality with ngAnimate
***
UnLike ngAnimate it don't automatically enable angularAnimation.css effects. Because, it is possible that, if it enabled automatically It will effect some of other plugins in your project and couse performance problems. For this reason, you should indicate that, if enable animation or not.
It doesn't have any new method or required new learning. Just sets of overwritten some common existing jquery methods.
You can enable animations by using below method, with enable animation true: 

.show(true), .hide(true), .toggle(true) If you don't set true argument, animation would not be enabled. 

.addClass('yourClassName', true), .removeClass('yourClassName', true), .toggleClass('yourClassName', true) If you don't add true argument, animation would not be enabled. 

.appendTo(container, true) .prependTo(container, true) .insertBefore(element, true) .insertAfter(element, true) If you don't add true argument, animation would not be enabled. and .detach(true) If you don't add true argument, animation would not be enabled. 
Namely, when one of above method called, jquery.ngAnimate look at the element has animation css class or not. If true, it enables the animation. that is all.
