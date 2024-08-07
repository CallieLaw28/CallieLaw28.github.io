---
layout: project
type: project
image: img/projectdesign.avif
title: "ProjectDesign"
date: 2024-08-06
labels:
  - Web Design
  - Langugage
  - C++
summary: "ProjectDesign is to help people design websites, for either their jobs or for personal use."
---



The goal for this project is to teach people how to design websites. But it will also be used to desig other things like their social media accounts, and other things. We would love to have people discover their passion for this field as well as maybe one day working in the field as well. 

Our project is projectDesign which is not just for making websites but we will cater to whatever you would want to design.It will allow your creative juices flowing and with our team of expects you can not go wrong with that combination.

Here is some code that illustrates how we read values from the line sensors:

```cpp
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

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
