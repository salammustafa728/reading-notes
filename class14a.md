# Read: 14a - CSS Transforms, Transitions, and Animations


**Transforms** It's a way to position and alter elements. It has two different settings:two-dimensional and three-dimensional.

Transform Syntax: it have the transform property followed by the value,the value specify the transform type followed by a specific amount inside parentheses.

````
Example of transform:
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
````
2D Transforms and Three-dimensional: it works on the x and y axes, Three-dimensional transforms work on both the x and y axes, as well as the z axis.
In 2D Transforms it has a 2D Rotate it has ability to rotate an element from 0 to 360 degrees,Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise.
```
Example of 2D Rotate:
.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}

```
And it has a 2D Scale it allows you to change the appeared size of an element. its default value is 1.
Also has 2D Translate: its like relative position.
And 2D Skew:is used to distort elements on the horizontal axis, vertical axis, or both.
also you can Combining Transforms It is common for multiple transforms like rotating and scaling. and the default transforms property is is the dead center you can change it by using Transform Origin.

Perspective:Its for 3D dimensional work, to work the elements need a perspective from which to transform
and it has Perspective Depth Value and can be set as none or a length measurement, also has 3D Rotate,3D Scale,3D Translate,3D Skew and it has Shorthand 3D Transforms These properties include rotate3d, scale3d, transition3d, and matrix3d.

[The example for transform from this link](https://learn.shayhowe.com/advanced-html-css/css-transforms/)

**Transitions & Animations** 

**Transitions** it use to take place like by using the :hover, :focus, :active, and :target pseudo-classes.
and has these four property including transition-property,transition-duration, transition-timing-function, and transition-delay. 
note the not all properties may be transitioned nly properties that have an identifiable halfway point. Colors, font sizes, and the alike may be transitioned.

And you can use Transition Duration its value set using general timing values, and Transition Timing
it use The transition-timing-function property is used to set the speed in which a transition will move.
also there is a Transition Delay you can set a delay with the transition-delay property. 

Shorthand Transitions: shorthand property, transition, capable of supporting all of these different properties and values.

Transitions there is a 8 really simple effects that will add life to your UI like Fade in, Change color,Grow & Shrink,Rotate elements, Square to circle, 3D shadow,Swing and Inset border. 

**Animations** it has a Animations Keyframes you can use it to set multiple points at which an element should undergo a transition. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

Animation Duration, Timing Function, & Delay it has also this properties its include a duration, timing function, and delay if desired.Also you can customizing animations it should has the ability  to further customize an element’s behavio, and it has animation iteration, animation direction, animation play state, animation fill mode and shorthand animations.  

[Home](README.md)



