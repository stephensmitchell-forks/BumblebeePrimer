# 4.4.0 (2) Color Scale Formatting

(2) Color Scale Formatting allows you to set up a formatting condition that will evaluate a range of numbers and then based on some simple rules will color all of the values with an appropriate color defined in a two color gradient.

![](2color1.png)

### 4.4.1 Define Min and Max Value Types

You can define rules of how this color gradient will be applied to range of numbers by specifying Min and Max value types. This can either be as simple as "automatic" or as custom as inputting an actual number for a min/max value. 

Let's have a quick look at available options and their meaning. 

![](2color12png.png)

<blockquote>
<p><b> LowestValue:</b> If you chose this option, Excel will automatically chose the lowest value in the specified range and use that as a Minimum. Chosing this option means that you DO NOT have to supply MinValue. </p>
<p><b> Number: </b> If you chose this option, you will have to also supply MinValue input that will determine the minimum number. 
<p><b>Percent:</b> If you chose this option you will have to supply MinValue and it will have to be between 0-100. </p>
<p><b> Formula: </b> You can use a Formula to determine a MinValue. If you chose to use the formula then, you have to supply it to MinValue input. Something to keep in mind when using Formulas with 2-Color Formatting is that they cannot be referencing other cells. That means that a formula like this: =1, will work just fine while something like this: =$B1=1, will not.</p>
<p><b> Percentile:</b> If you chose this option you will have to supply MinValue and it will have to be between 1-99. </p> 
<p><b> HighestValue:</b> If you chose this option, Excel will automatically choose the highest value in the specified range and use that as a Minimum/Maximum. Choosing this option means that you DO NOT have to supply MinValue/MaxValue. </p>
<p><b> AutomaticMax:</b> This option is NOT available for use with (2) Color Scale Formatting. </p>
<p><b> AutomaticMin:</b> This option is NOT available for use with (2) Color Scale Formatting. </p>
<p><b> None:</b> This option is NOT available for use with (2) Color Scale Formatting. </p>
</blockquote>