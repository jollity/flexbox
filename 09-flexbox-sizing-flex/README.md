# flex

## flex-grow
*How to distribute the available free-space into the flex-items.*  
Or rather, how do the **items grow** when there is **free-space available** in the flex-container.

## flex-shrink
In what **ratio**, the flex-item's size **shrinks** or give up its space when there is **not enough space** for them to accomodate all of the items at one-go.

## flex-basis
The term **enough-space** that I am talking about consistently refers to the value of **flex-basis property**.  
That is, if the flex-container has space **greater** than the value of flex-basis, then **flex-grow** will be used to accomodate that space.  
Else, if the space is **less** than the value of flex-basis, then **flex-shrink** will be used to decide the ratio at which the items get shrink.

## Shorthand notation

  flex: flex-grow flex-shrink flex-basis;
