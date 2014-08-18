---
title: ChartXAxisItemMajorTicks
---

# \Kendo\Dataviz\UI\ChartXAxisItemMajorTicks

A PHP class representing the majorTicks setting of ChartXAxisItem.


## Methods

### color
The color of the scatter chart x axis major ticks lines. Accepts a valid CSS color string, including hex and rgb.

#### Returns
`\Kendo\Dataviz\UI\ChartXAxisItemMajorTicks`

#### Parameters

##### $value `string`



#### Example 
    <?php
    $majorTicks = new \Kendo\Dataviz\UI\ChartXAxisItemMajorTicks();
    $majorTicks->color('value');
    ?>

### size
The length of the tick line in pixels.

#### Returns
`\Kendo\Dataviz\UI\ChartXAxisItemMajorTicks`

#### Parameters

##### $value `float`



#### Example 
    <?php
    $majorTicks = new \Kendo\Dataviz\UI\ChartXAxisItemMajorTicks();
    $majorTicks->size(1);
    ?>

### skip
The skip of the x axis major ticks.

#### Returns
`\Kendo\Dataviz\UI\ChartXAxisItemMajorTicks`

#### Parameters

##### $value `float`



#### Example 
    <?php
    $majorTicks = new \Kendo\Dataviz\UI\ChartXAxisItemMajorTicks();
    $majorTicks->skip(1);
    ?>

### step
The step of the x axis major ticks.

#### Returns
`\Kendo\Dataviz\UI\ChartXAxisItemMajorTicks`

#### Parameters

##### $value `float`



#### Example 
    <?php
    $majorTicks = new \Kendo\Dataviz\UI\ChartXAxisItemMajorTicks();
    $majorTicks->step(1);
    ?>

### visible
If set to true the chart will display the scatter chart x axis major ticks. By default the category axis major ticks are visible.

#### Returns
`\Kendo\Dataviz\UI\ChartXAxisItemMajorTicks`

#### Parameters

##### $value `boolean`



#### Example 
    <?php
    $majorTicks = new \Kendo\Dataviz\UI\ChartXAxisItemMajorTicks();
    $majorTicks->visible(true);
    ?>

### width
The width of the major ticks in pixels.

#### Returns
`\Kendo\Dataviz\UI\ChartXAxisItemMajorTicks`

#### Parameters

##### $value `float`



#### Example 
    <?php
    $majorTicks = new \Kendo\Dataviz\UI\ChartXAxisItemMajorTicks();
    $majorTicks->width(1);
    ?>
