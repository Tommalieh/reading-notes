## CSS

### Transforms

* Transform is a new CSS3 technique for an alternative ways to size, position, and change elements.

* The transform property comes in two different settings, **two-dimensional** and **three-dimensional**. Each of these come with their own individual properties and values.

* Two-dimensional transforms work on the x and y axes, known as **horizontal** and **vertical axes**.

* Three-dimensional transforms work on both the **x and y axes, as well as the z axis**. These three-dimensional transforms help define not only the length and width of an element, but also the **depth**.

* The transform property accepts a handful of different values. The **rotate** value provides the ability to rotate an element **from 0 to 360 degrees**. Using a **positive** value will rotate an element **clockwise**, and using a **negative value** will rotate the element **counterclockwise**. The **default point of rotation is the center of the element**, 50% 50%, both horizontally and vertically.

* Example:

```
  .box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}

```

* Using the **scale** value within the transform property allows you to **change the appeared size of an element**. The **default scale value is 1**, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.

* With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.

* There are four transition related properties in total, including **transition-property**, **transition-duration**, **transition-timing-function**, and **transition-delay**. Not all of these are required to build a transition, with the first three are the most popular.

* The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. By default, all of the properties within an element’s different states will be altered upon change. However, only the properties identified within the transition-property value will be affected by any transitions.

* The transition-timing-function property is used to set the speed in which a transition will move. Knowing the duration from the transition-duration property a transition can have multiple speeds within a single duration. A few of the more popular keyword values for the transition-timing-function property include linear, ease-in, ease-out, and ease-in-out.

* To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.
