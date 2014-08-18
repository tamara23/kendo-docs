---
title: ChartYAxisItemMajorGridLines
---

# \Kendo\Dataviz\UI\ChartYAxisItemMajorGridLines

A PHP class representing the majorGridLines setting of ChartYAxisItem.


## Methods

### color
The color of the lines. Accepts a valid CSS color string, including hex and rgb.

#### Returns
`\Kendo\Dataviz\UI\ChartYAxisItemMajorGridLines`

#### Parameters

##### $value `string`



#### Example 
    <?php
    $majorGridLines = new \Kendo\Dataviz\UI\ChartYAxisItemMajorGridLines();
    $majorGridLines->color('value');
    ?>

### dashType
The dash type of the line.The following dash types are supported:

#### Returns
`\Kendo\Dataviz\UI\ChartYAxisItemMajorGridLines`

#### Parameters

##### $value `string`



#### Example 
    <?php
    $majorGridLines = new \Kendo\Dataviz\UI\ChartYAxisItemMajorGridLines();
    $majorGridLines->dashType('value');
    ?>

### skip
The skip of the y axis major grid lines.

#### Returns
`\Kendo\Dataviz\UI\ChartYAxisItemMajorGridLines`

#### Parameters

##### $value `float`



#### Example 
    <?php
    $majorGridLines = new \Kendo\Dataviz\UI\ChartYAxisItemMajorGridLines();
    $majorGridLines->skip(1);
    ?>

### step
The step of the y axis major grid lines.

#### Returns
`\Kendo\Dataviz\UI\ChartYAxisItemMajorGridLines`

#### Parameters

##### $value `float`



#### Example 
    <?php
    $majorGridLines = new \Kendo\Dataviz\UI\ChartYAxisItemMajorGridLines();
    $majorGridLines->step(1);
    ?>

### visible
If set to true the chart will display the x major grid liness. By default the x major grid liness are visible.

#### Returns
`\Kendo\Dataviz\UI\ChartYAxisItemMajorGridLines`

#### Parameters

##### $value `boolean`



#### Example 
    <?php
    $majorGridLines = new \Kendo\Dataviz\UI\ChartYAxisItemMajorGridLines();
    $majorGridLines->visible(true);
    ?>

### width
The width of the line in pixels. Also affects the major and minor ticks, but not the grid lines.
#### Example - set the scatter chart x major grid lines width

#### Returns
`\Kendo\Dataviz\UI\ChartYAxisItemMajorGridLines`

#### Parameters

##### $value `float`



#### Example 
    <?php
    $majorGridLines = new \Kendo\Dataviz\UI\ChartYAxisItemMajorGridLines();
    $majorGridLines->width(1);
    ?>
