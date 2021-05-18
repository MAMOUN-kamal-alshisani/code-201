~~## Read-14: CSS~~

## Transforms :
***With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements
. All of these new techniques are made possible by the transform property. The transform property comes in two different settings, two-dimensional and three-dimensional.
Each of these come with their own individual properties and values.***

## Transform Syntax :
___The actual syntax for the transform property is quite simple, including the transform property followed by the value. 
The value specifies the transform type followed by a specific amount inside parentheses.___

***div {
  -webkit-transform: scale(1.5); .
     -moz-transform: scale(1.5); .
       -o-transform: scale(1.5); .
          transform: scale(1.5); .
}***

## 2D Transforms:
*__Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes.
Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element,__*

## 3D Transforms:
***Working with two-dimensional transforms we are able to alter elements on the horizontal and vertical axes, however there is another axis along which we can transform elements.
Using three-dimensional transforms we can change elements on the z axis, giving us control of depth as well as length and width.***

# Transitions & Animations :
***With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs,
such as when it is hovered over,focused on, active, or targeted.
Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes.Transitions provide a change from one state to another,
while animations can set multiple points of transition upon different keyframes.***

## Transitions:
**As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state.
The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.***

### There are four transition related properties in total:
1. including transition-property.
2. transition-duration.
3. transition-timing-function.
4.  and transition-delay.   
  Not all of these are required to build a transition, with the first three are the most popular.
