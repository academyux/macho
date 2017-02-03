# The Macho Framework

## Structuring your content

### Make any element flexy with `.flex`
+ Child elements will be displayed left to right in a row and not wrap

### Make a flexy element's children stack with `.stack`
+ Child elements will be displayed top to bottom in a column
+ Applied to the parent element

### You can stack and unstack child elements at defined viewport widths with `.stack-` and `.unstack-` 
+ The viewport breakpoints are: *384px*, *768px*, *1024px*, *1280px* and *1440px*
+ Example stacking at 768px: `.stack-768`
+ Example unstacking at 768px: `.unstack-768`
+ Applied to the parent element

### Make a flexy element's children fluid with `.fluid`
+ This will make the element span the full width of it's flexy parent container
+ If multiple fluid siblings exist, their widths will distributed equally inside the parent flexy container. Ex: four fluid elements will all have a width of 25%
+ Applied to a flexy elements children

## Laying out your content

<!-- explain main and cross axis -->

## Align child elements along the main axis 
+ `.child-main-center` children are centered on the main axis
+ `.child-main-end` children are packed towards the end of the main axis
+ `.child-main-space-around` children are evenly distributed on the main axis with equal space around them
+ `.child-main-space-between` children are evenly distributed on the main axis; first child is at the start, last child is at the end

## Align child elements along the cross axis
+ `.child-cross-start` children packed towards the start of cross axis
+ `.child-cross-center` children are centered on the cross axis
+ `.child-cross-end` children are packed towards the end of the cross axis

