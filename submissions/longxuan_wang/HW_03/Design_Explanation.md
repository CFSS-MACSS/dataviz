Design Explanation
================
Longxuan Wang
May 9, 2017

Story
-----

In the summer of 2015, the Chinese stock market reached its highest level since the 2008 global financial crisis after a steep climb. However, the bull market was short-lived. Within two month after the peak on June 12th, CSI 300, one of the most widely quoted market indexes, would lose more than 40% of its peak value. Chinese regulators soon found a target of blame: the futures market. China Financial Futures Exchange (CFFEX), where stock market index futures were traded, has since put forward drastic measures to constrain trading activities in those futures contracts.

Detailed results and analysis are in the main html file. Briefly speaking, through this project, I want to show that this stock market crash lead to unprecedented level of deviations between the futures market prices and spot market prices of CSI 300 index, which measures the general price level of the entire Chinese financial market. Furthermore, by looking at the timing of regulatory policies and different market statistics, I show that the policies were not successful in achieving their intended goals.

Graphics
--------

For the first graph, I choose to use line plot to show the time trend of futures prices and spot prices. Line plot is usually the standard way of visualizing time series data, and using two thin lines of different colors make it easy for the reader to see the deviations between the two prices.

For the second graph, I use annotation to indicate the timing of various regulatory policies. By hovering their mouse on each point, the readers can see the exact date and content of those policies. The policies are layered onto a line plot to spot market prices, so that the readers will know the background of those policies. Furthermore, it shows that the policies were not implemented during the most tumultuous times. Rather, those polices came at a time when price drop had already slowed down significantly.

For the last graph, I use a bottom for the reader to select which market statistics to show, and I use bar charts for those statistics. In finance, statistics such as volume are usually shown with bar charts as the bars give the readers a feel of volume that is not present in line plots. Furthermore, the line plot to look very ugly because those statistics are not as smooth as prices and changes drastically from day to day, so a line plot will show congested lines and reader will have a hard time telling what is going on.

Interactivity
-------------

Interactivity is trememdously helpful in this project. First of all, as we can see in the first graph, we want to compare the deviation between the two lines before and after the market crash. At first sight, there seems to be no huge deviation because the deviations are relatively small compared with the price level. By using the interactive slider, we can focus on the range we are interested in and more closely examine the deviations. Before the market crash, even if we zoom in quite a lot, we see that the two lines are still overlapping. After the crash, we can see that the futures prices are generally lower than the spot price. Without this interactivity, the only alternative is to show two static images one of before the crash and one of after the crash. The two plots will likely be disconnected and not customizable.

Furthermore, interactivity is also crucial for the second plot. Without the hovering text, we have to put all the text onto the plot which will make it crowed and the text hard to read. Using interactivity, the plot is much more elegant and the reader can read the details and the exact date of each policy by hovering their mouse on the specific policy they are interested in. Without interactivity, the best way to show policies is to use a tablel; however, tables are not as beautiful and the readers will not be able to see the price level at the time of the policies.

Last but not least, the last plot uses interactivity to concisely combine three seperate plots into one. This saves a lot of space and adds more fun to the reading experience. Moreover, by putting them into the same interactive plot, the readers will gain a sense that those statistics belongs into the same category, i.e. the effects of regulatory policies, but at the same time those statistics each tells a unique story.
