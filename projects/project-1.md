---
layout: project
type: project
image: images/
title: 
permalink: projects/
# All dates must be YYYY-MM-DD format!
date: 2015-07-01
labels:
  - 
summary: 
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/">
</div>



Here is some code that illustrates how we read values from the line sensors:

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```



