# A comparative analysis of three pairs of material blocks 

<img src="https://i.imgur.com/en1M9c2.png"  width="200" align="left">

The data comes from one of the companies in Poland: 
+ I cannot provide the name of the company, the type of material and the physical property that was measured,
+ the blocks of material are the same size, cut into the same shape, and the physical property that was measured has the same unit,
+ the blocks are divided into three categories: 11, 20 and 30. Each category corresponds to a value around which the average value of the physical property of the material under test should oscillate.

**-->** [**Link to analysis.**](https://github.com/m0gr1m/comparative_analysis_of_two_products/blob/main/main_analysis.ipynb)

------

# Main goal

+ Are blocks produced by the innovative method significantly different from blocks produced by the standard method?

------

# Quick summary

For each block, produced by the innovative method compared to the block produced by the standard method, it is found:
+ a lower mean value of the physical property tested,
+ smaller range of variation of the tested physical property,
+ less scatter in the results of the physical property.

*This means that the blocks produced by the innovative method are more homogeneous and thus have a better physical property.*

In addition, based on **Mann-Whitney U tests** at 5% level of significance, it is found that the blocks from category 11 and 20 are significantly different, while for the block from category 30 there is no evidence to reject the null hypothesis.

There is also an interesting relationship: the values of the test statistic for blocks 11, 20 and 30 are in ascending order, as is the p-value, which suggests that the higher the value around which the mean value of the physical characteristic tested should oscillate, the smaller the improvement in material properties. Further tests on a larger sample of blocks would be needed to investigate this further.
