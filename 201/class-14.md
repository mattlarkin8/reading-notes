# **CSS Transforms, Transitions, and Animations**

## **Transforms**

The transform property enables new ways to ways to size, position, and change elements using CSS3. There are two-dimensional and three-dimensional transforms, each doing something different and having individual properties and values.

2D transforms work using the X and Y axis to manipulate elements. You can use `rotate` to rotate an element either clockwise or counter-clockwise depending on the value given. The `scale` value allows you to resize the element, with the default size being `1`. `scaleX` and `scaleY` can be used individually to change only the width or height. `translate` can be used to position the element without interrupting the normal flow. You can move it just horizontally or vertically using `translateX` or `translateY` or both at once using `transform: translate(10px,-15px);`. The `skew` value is used to distort an element and follows the same syntax as translate, but is measured in degrees and not pixels or percentages. Multiple transforms can be combined at once and each value should be listed in the same transform statement **without** any separating elements like commas.

To use 3D transformations, the elements must be given a perspective from which to transform. The `perspective` is used for this purpose and can be set for either each element individually or all elements at once by setting it in the parent element. With the perspective set, we can now get into 3D transforms. You can now use `rotateZ` to rotate the element on its Z-axis. Likewise, `scaleZ` allows you to scale the element on its Z-axis, which should be like setting its depth. The `translateZ` element is pretty interesting because it has the effect of either pushing the element away from you or pulling it towards you. This will make the element appear larger or smaller as if you were scaling it, but it is different because it is working only on the Z-axis. `skew` is the only value that **cannot** be used on the Z-axis.

## **Transitions**

A transition allows you to alter an element whenever a state change occurs.

- `transition-property` determines what properties will be altered.
- `transition-duration` specifies the time taken to complete the transition.
- `transition-timing-function` is used to the speed the transition moves at.
- `transition-delay` can be used to delay the transition from starting.

## **Animations**

Animations allow an element to be altered in multiple keyframes. This is basically setting up multiple transitions to create the animation and setting keyframes that specify the time for each transition to take place. Keyframes are assigned to an `animation-name` property, which is then applied to the element that will be animated. You must also give the element an `animation-duration` property that tells the browser how long the full animation should take. You can also add the `animation-timing-function` and `animation-delay` properties that behave the same way as they work for transitions.

## **Things I want to know more about**

I think all of these operations are pretty cool, but my favorite is animations. Although it is the most complicated, it allows you do the most to an element. Being able to create some neat animations for elements in my page will be really cool. I'm looking forward to learning more about these operations and how I can use them to style up my web page.