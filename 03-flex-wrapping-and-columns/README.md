# Flex-wrapping and columns

##### How flex-box works normally?  (with flex-wrap: nowrap (default value))
If you **specify the dimensions** for the flex items, then flexbox will try to **adjust the items with the respective dimensions** that you have provided.  

But in case, **flexbox is not able to follow** the dimensions that you give it, then it will make sure to **evenly spread/distribute the space available into the items**.

## All about flex-wrap

The **flex-wrap** property is a **sub-property** of the ***Flexible Box Layout module***.

*It defines whether the flex items are forced in a single line or can be flowed into multiple lines. If set to multiple lines, it also defines the cross-axis which determines the direction new lines are stacked in*.

##### Reminder: the cross axis is the axis perpendicular to the main axis. Its direction depends on the main axis direction.

The flex-wrap property accepts 3 different values:
1. **nowrap (default)**: single-line which may cause the container to overflow
2. **wrap**: multi-lines, direction is defined by flex-direction
3. **wrap-reverse**: multi-lines, opposite to direction defined by flex-direction.

##### P.S. wrap-reverse property changes the direction of cross-axis by 180 degrees. 
