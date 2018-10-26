# DCdensity
来自：**https://eml.berkeley.edu/~jmccrary/DCdensity/**

Type **`github install iphone7725/DCdensity`** to download the ado file. It will be saved as **D:\stata15\ado\plus\d\dcdensity.ado**. 

This subdirectory contains 5 files:

1. **DCdensity.ado**  
 Put this file in your ado directory.  To find out where this is, issue -sysdir- at the Stata prompt.  Brian Kovak did the heavy lifting on writing the code.  Neither Brian nor I provide any support for the file.  If you believe you have found a conceptual mistake in the code,however, I would like to hear about it.  In that case, please send along documentation of how you know it is getting the wrong answer. 

2. **DCdensity_example.do**  
 This file gives example syntax for DCdensity and should be self-explanatory. 

3. **DCdensity_example.log**  
 The log file for DCdensity_example.do. 

4. **DCdensity_example.eps**  
 An encapsulated postscript graph that gets generated by DCdensity_example.do.  It shows the histogram and estimated density, based on a sample of size 10,000 from the standard normal distribution, where it has been pretended that the true density has a break at 0. 

5. **DCdensity.pdf**  
 This is a pdf file that describes the standard error bands displayed in the plots for DCdensity.  In particular, the standard errors are presented everywhere on the curve, not just on the boundary.  These are derived under the same assumptions as those involved in the Proposition of McCrary (2008).  It assumes you have read McCrary (2008) and looked pretty carefully at the proof of the Proposition. 

 JRM, 9/2008 
