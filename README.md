Download Link: https://assignmentchef.com/product/solved-stat215-assignment-4
<br>






<strong>Problem 1: </strong>Consider a Gaussian linear dynamical system (LDS),

[ ~<em>T                                                                                                          </em>] [ ii <em>T                                                                               </em>]

<em>p</em>(<em>x</em>1:<em>T </em>, <em><sub>y</sub></em><sub>1:</sub><em><sub>T</sub></em> ) = jV (<em>x</em>1 | 0, <em>q</em><sup>2</sup>)     jV (<em>x<sub>t</sub></em> | <em>ax</em><em>t</em>_1 + <em>b</em>, <em>q</em><sup>2</sup>)    jV (<em>y<sub>t</sub></em> | <em>x<sub>t</sub></em>, <em>r</em><sup>2</sup>) ,

<em> t</em>=2                                                   <em>t</em>=1

for <em>x<sub>t</sub></em>, <em>y<sub>t</sub></em> E R for all <em>t</em>, and parameters <em>a</em>, <em>b </em>E R and <em>q</em>2, <em>r</em><sup>2</sup> E R<sub>+</sub>. Compute the forward filtered distribution <em>p</em>(<em>x<sub>t</sub></em> | <em>y</em>1:<em>t</em>) in terms of the model parameters and the filtered distribution <em>p</em>(<em>x</em><em>t</em>_1 | <em>y</em>1:<em>t</em>_1). Solve for the base case <em>p</em>(<em>x</em>1 | <em>y</em>1). For reference, consult the state space modeling chapters of either the Bishop or the Murphy textbook.

Your solution here.




<strong>Problem 2: </strong>Sample a time series of length <em>T </em>= 30 from the Gaussian LDS in Problem 1 with param­eters <em>a </em>= 1, <em>b </em>= 0,<em>q </em>= 0.1, <em>r </em>= 0.3. Plot the sample of <em><sub>x</sub></em><sub>1:</sub><em><sub>T</sub></em> as a solid line, and plot the observed <em>y</em>1:<em>T </em>as +’s. Write code to compute the filtered distribution <em>p</em>(<em>x<sub>t</sub></em> | <em>y</em>1:<em>t</em>) you derived in Problem 1. Then plot the mean of the filtered distribution E[<em>x<sub>t</sub></em> | <em>y</em>1:<em>t</em>] over time as a solid line, and plot a shaded region encompassing the mean ±2 standard deviations of the filtered distribution. All plots should be on the same axis. Include a legend.

Write your code in a Colab notebook and include a PDF printout of your notebook as well as the raw .ipynb file.




<strong>Problem 3: </strong>Reproduce Figure 2.5 of Rasmussen and Williams, <em>Gaussian Processes for Machine Learn­</em><em>ing</em>, available at <a href="http://www.gaussianprocess.org/gpml/chapters/RW2.pdf">http://www.gaussianprocess.org/gpml/chapters/RW2.pdf</a>. Use a randomly generated dataset as described in the figure caption and surrounding text.

Write your code in a Colab notebook and include a PDF printout of your notebook as well as the raw .ipynb file.