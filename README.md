# Python-Visual-Vocabulary
**使用Python 实现常见的50个可视化作品.作为字典供大家参考,具体下载 notebook 享用吧**

<h1>整体目录<span class="tocSkip"></span></h1>
<div class="toc"><ul class="toc-item"><li><span><a href="#01-关联(Correlation)" data-toc-modified-id="01-关联(Correlation)-1"><span class="toc-item-num">1&nbsp;&nbsp;</span>01 关联(Correlation)</a></span><ul class="toc-item"><li><span><a href="#1.-散点图（Scatter-plot）" data-toc-modified-id="1.-散点图（Scatter-plot）-1.1"><span class="toc-item-num">1.1&nbsp;&nbsp;</span>1. 散点图（Scatter plot）</a></span></li><li><span><a href="#2.-带边界的气泡图（Bubble-plot-with-Encircling）" data-toc-modified-id="2.-带边界的气泡图（Bubble-plot-with-Encircling）-1.2"><span class="toc-item-num">1.2&nbsp;&nbsp;</span>2. 带边界的气泡图（Bubble plot with Encircling）</a></span></li><li><span><a href="#3.-带线性回归最佳拟合线的散点图（Scatter-plot-with-linear-regression-line-of-best-fit）" data-toc-modified-id="3.-带线性回归最佳拟合线的散点图（Scatter-plot-with-linear-regression-line-of-best-fit）-1.3"><span class="toc-item-num">1.3&nbsp;&nbsp;</span>3. 带线性回归最佳拟合线的散点图（Scatter plot with linear regression line of best fit）</a></span></li><li><span><a href="#4.-抖动图（Jittering-with-stripplot）" data-toc-modified-id="4.-抖动图（Jittering-with-stripplot）-1.4"><span class="toc-item-num">1.4&nbsp;&nbsp;</span>4. 抖动图（Jittering with stripplot）</a></span></li><li><span><a href="#5.-计数图（Counts-Plot）" data-toc-modified-id="5.-计数图（Counts-Plot）-1.5"><span class="toc-item-num">1.5&nbsp;&nbsp;</span>5. 计数图（Counts Plot）</a></span></li><li><span><a href="#6.-边缘直方图（Marginal-Histogram）" data-toc-modified-id="6.-边缘直方图（Marginal-Histogram）-1.6"><span class="toc-item-num">1.6&nbsp;&nbsp;</span>6. 边缘直方图（Marginal Histogram）</a></span></li><li><span><a href="#7.-边缘箱形图（Marginal-Boxplot）" data-toc-modified-id="7.-边缘箱形图（Marginal-Boxplot）-1.7"><span class="toc-item-num">1.7&nbsp;&nbsp;</span>7. 边缘箱形图（Marginal Boxplot）</a></span></li><li><span><a href="#8.-相关图（Correllogram）" data-toc-modified-id="8.-相关图（Correllogram）-1.8"><span class="toc-item-num">1.8&nbsp;&nbsp;</span>8. 相关图（Correllogram）</a></span></li><li><span><a href="#9.-矩阵图（Pairwise-Plot）" data-toc-modified-id="9.-矩阵图（Pairwise-Plot）-1.9"><span class="toc-item-num">1.9&nbsp;&nbsp;</span>9. 矩阵图（Pairwise Plot）</a></span></li></ul></li><li><span><a href="#02-偏差（Deviation）" data-toc-modified-id="02-偏差（Deviation）-2"><span class="toc-item-num">2&nbsp;&nbsp;</span>02 偏差（Deviation）</a></span><ul class="toc-item"><li><span><a href="#10.-发散型条形图（Diverging-Bars）" data-toc-modified-id="10.-发散型条形图（Diverging-Bars）-2.1"><span class="toc-item-num">2.1&nbsp;&nbsp;</span>10. 发散型条形图（Diverging Bars）</a></span></li><li><span><a href="#11.-发散型文本（Diverging-Texts）" data-toc-modified-id="11.-发散型文本（Diverging-Texts）-2.2"><span class="toc-item-num">2.2&nbsp;&nbsp;</span>11. 发散型文本（Diverging Texts）</a></span></li><li><span><a href="#12.-发散型包点图（Diverging-Dot-Plot）" data-toc-modified-id="12.-发散型包点图（Diverging-Dot-Plot）-2.3"><span class="toc-item-num">2.3&nbsp;&nbsp;</span>12. 发散型包点图（Diverging Dot Plot）</a></span></li><li><span><a href="#13.-带标记的发散型棒棒糖图（Diverging-Lollipop-Chart-with-Markers）" data-toc-modified-id="13.-带标记的发散型棒棒糖图（Diverging-Lollipop-Chart-with-Markers）-2.4"><span class="toc-item-num">2.4&nbsp;&nbsp;</span>13. 带标记的发散型棒棒糖图（Diverging Lollipop Chart with Markers）</a></span></li><li><span><a href="#14.-面积图（Area-Chart）" data-toc-modified-id="14.-面积图（Area-Chart）-2.5"><span class="toc-item-num">2.5&nbsp;&nbsp;</span>14. 面积图（Area Chart）</a></span></li></ul></li><li><span><a href="#03-排序（Ranking）" data-toc-modified-id="03-排序（Ranking）-3"><span class="toc-item-num">3&nbsp;&nbsp;</span>03 排序（Ranking）</a></span><ul class="toc-item"><li><span><a href="#15.-有序条形图（Ordered-Bar-Chart）" data-toc-modified-id="15.-有序条形图（Ordered-Bar-Chart）-3.1"><span class="toc-item-num">3.1&nbsp;&nbsp;</span>15. 有序条形图（Ordered Bar Chart）</a></span></li><li><span><a href="#16.-棒棒糖图（Lollipop-Chart）" data-toc-modified-id="16.-棒棒糖图（Lollipop-Chart）-3.2"><span class="toc-item-num">3.2&nbsp;&nbsp;</span>16. 棒棒糖图（Lollipop Chart）</a></span></li><li><span><a href="#17.-包点图（Dot-Plot）" data-toc-modified-id="17.-包点图（Dot-Plot）-3.3"><span class="toc-item-num">3.3&nbsp;&nbsp;</span>17. 包点图（Dot Plot）</a></span></li><li><span><a href="#18.-坡度图（Slope-Chart）" data-toc-modified-id="18.-坡度图（Slope-Chart）-3.4"><span class="toc-item-num">3.4&nbsp;&nbsp;</span>18. 坡度图（Slope Chart）</a></span></li><li><span><a href="#19.-哑铃图（Dumbbell-Plot）" data-toc-modified-id="19.-哑铃图（Dumbbell-Plot）-3.5"><span class="toc-item-num">3.5&nbsp;&nbsp;</span>19. 哑铃图（Dumbbell Plot）</a></span></li></ul></li><li><span><a href="#04-分布（Distribution）" data-toc-modified-id="04-分布（Distribution）-4"><span class="toc-item-num">4&nbsp;&nbsp;</span>04 分布（Distribution）</a></span><ul class="toc-item"><li><span><a href="#20.-连续变量的直方图（Histogram-for-Continuous-Variable）" data-toc-modified-id="20.-连续变量的直方图（Histogram-for-Continuous-Variable）-4.1"><span class="toc-item-num">4.1&nbsp;&nbsp;</span>20. 连续变量的直方图（Histogram for Continuous Variable）</a></span></li><li><span><a href="#21.-类型变量的直方图（Histogram-for-Categorical-Variable）" data-toc-modified-id="21.-类型变量的直方图（Histogram-for-Categorical-Variable）-4.2"><span class="toc-item-num">4.2&nbsp;&nbsp;</span>21. 类型变量的直方图（Histogram for Categorical Variable）</a></span></li><li><span><a href="#22.-密度图（Density-Plot）" data-toc-modified-id="22.-密度图（Density-Plot）-4.3"><span class="toc-item-num">4.3&nbsp;&nbsp;</span>22. 密度图（Density Plot）</a></span></li><li><span><a href="#23.-直方密度线图（Density-Curves-with-Histogram）" data-toc-modified-id="23.-直方密度线图（Density-Curves-with-Histogram）-4.4"><span class="toc-item-num">4.4&nbsp;&nbsp;</span>23. 直方密度线图（Density Curves with Histogram）</a></span></li><li><span><a href="#24.-Joy-Plot" data-toc-modified-id="24.-Joy-Plot-4.5"><span class="toc-item-num">4.5&nbsp;&nbsp;</span>24. Joy Plot</a></span></li><li><span><a href="#25.-分布式包点图（Distributed-Dot-Plot）" data-toc-modified-id="25.-分布式包点图（Distributed-Dot-Plot）-4.6"><span class="toc-item-num">4.6&nbsp;&nbsp;</span>25. 分布式包点图（Distributed Dot Plot）</a></span></li><li><span><a href="#26.-箱形图（Box-Plot）" data-toc-modified-id="26.-箱形图（Box-Plot）-4.7"><span class="toc-item-num">4.7&nbsp;&nbsp;</span>26. 箱形图（Box Plot）</a></span></li><li><span><a href="#27.-包点+箱形图（Dot+Box-Plot）" data-toc-modified-id="27.-包点+箱形图（Dot+Box-Plot）-4.8"><span class="toc-item-num">4.8&nbsp;&nbsp;</span>27. 包点+箱形图（Dot+Box Plot）</a></span></li><li><span><a href="#28.-小提琴图（Violin-Plot）" data-toc-modified-id="28.-小提琴图（Violin-Plot）-4.9"><span class="toc-item-num">4.9&nbsp;&nbsp;</span>28. 小提琴图（Violin Plot）</a></span></li><li><span><a href="#29.-人口金字塔（Population-Pyramid）" data-toc-modified-id="29.-人口金字塔（Population-Pyramid）-4.10"><span class="toc-item-num">4.10&nbsp;&nbsp;</span>29. 人口金字塔（Population Pyramid）</a></span></li><li><span><a href="#30.-分类图（Categorical-Plots）" data-toc-modified-id="30.-分类图（Categorical-Plots）-4.11"><span class="toc-item-num">4.11&nbsp;&nbsp;</span>30. 分类图（Categorical Plots）</a></span></li></ul></li><li><span><a href="#05-组成（Composition）" data-toc-modified-id="05-组成（Composition）-5"><span class="toc-item-num">5&nbsp;&nbsp;</span>05 组成（Composition）</a></span><ul class="toc-item"><li><span><a href="#31.-华夫饼图（Waffle-Chart）" data-toc-modified-id="31.-华夫饼图（Waffle-Chart）-5.1"><span class="toc-item-num">5.1&nbsp;&nbsp;</span>31. 华夫饼图（Waffle Chart）</a></span></li><li><span><a href="#32.-饼图（Pie-Chart）" data-toc-modified-id="32.-饼图（Pie-Chart）-5.2"><span class="toc-item-num">5.2&nbsp;&nbsp;</span>32. 饼图（Pie Chart）</a></span></li><li><span><a href="#33.-树形图（Treemap）" data-toc-modified-id="33.-树形图（Treemap）-5.3"><span class="toc-item-num">5.3&nbsp;&nbsp;</span>33. 树形图（Treemap）</a></span></li><li><span><a href="#34.-条形图（Bar-Chart）" data-toc-modified-id="34.-条形图（Bar-Chart）-5.4"><span class="toc-item-num">5.4&nbsp;&nbsp;</span>34. 条形图（Bar Chart）</a></span></li></ul></li><li><span><a href="#06-变化（Change）" data-toc-modified-id="06-变化（Change）-6"><span class="toc-item-num">6&nbsp;&nbsp;</span>06 变化（Change）</a></span><ul class="toc-item"><li><span><a href="#35.-时间序列图（Time-Series-Plot）" data-toc-modified-id="35.-时间序列图（Time-Series-Plot）-6.1"><span class="toc-item-num">6.1&nbsp;&nbsp;</span>35. 时间序列图（Time Series Plot）</a></span></li><li><span><a href="#36.-带波峰波谷标记的时序图（Time-Series-with-Peaks-and-Troughs-Annotated）" data-toc-modified-id="36.-带波峰波谷标记的时序图（Time-Series-with-Peaks-and-Troughs-Annotated）-6.2"><span class="toc-item-num">6.2&nbsp;&nbsp;</span>36. 带波峰波谷标记的时序图（Time Series with Peaks and Troughs Annotated）</a></span></li><li><span><a href="#37.-自相关和部分自相关图（Autocorrelation-(ACF)-and-Partial-Autocorrelation-(PACF)-Plot）" data-toc-modified-id="37.-自相关和部分自相关图（Autocorrelation-(ACF)-and-Partial-Autocorrelation-(PACF)-Plot）-6.3"><span class="toc-item-num">6.3&nbsp;&nbsp;</span>37. 自相关和部分自相关图（Autocorrelation (ACF) and Partial Autocorrelation (PACF) Plot）</a></span></li><li><span><a href="#38.-交叉相关图（Cross-Correlation-plot）" data-toc-modified-id="38.-交叉相关图（Cross-Correlation-plot）-6.4"><span class="toc-item-num">6.4&nbsp;&nbsp;</span>38. 交叉相关图（Cross Correlation plot）</a></span></li><li><span><a href="#39.-时间序列分解图（Time-Series-Decomposition-Plot）" data-toc-modified-id="39.-时间序列分解图（Time-Series-Decomposition-Plot）-6.5"><span class="toc-item-num">6.5&nbsp;&nbsp;</span>39. 时间序列分解图（Time Series Decomposition Plot）</a></span></li><li><span><a href="#40.-多个时间序列（Multiple-Time-Series）" data-toc-modified-id="40.-多个时间序列（Multiple-Time-Series）-6.6"><span class="toc-item-num">6.6&nbsp;&nbsp;</span>40. 多个时间序列（Multiple Time Series）</a></span></li><li><span><a href="#41.-使用辅助-Y-轴来绘制不同范围的图形（Plotting-with-different-scales-using-secondary-Y-axis）" data-toc-modified-id="41.-使用辅助-Y-轴来绘制不同范围的图形（Plotting-with-different-scales-using-secondary-Y-axis）-6.7"><span class="toc-item-num">6.7&nbsp;&nbsp;</span>41. 使用辅助 Y 轴来绘制不同范围的图形（Plotting with different scales using secondary Y axis）</a></span></li><li><span><a href="#42.-带有误差带的时间序列（Time-Series-with-Error-Bands）" data-toc-modified-id="42.-带有误差带的时间序列（Time-Series-with-Error-Bands）-6.8"><span class="toc-item-num">6.8&nbsp;&nbsp;</span>42. 带有误差带的时间序列（Time Series with Error Bands）</a></span></li><li><span><a href="#43.-堆积面积图（Stacked-Area-Chart）" data-toc-modified-id="43.-堆积面积图（Stacked-Area-Chart）-6.9"><span class="toc-item-num">6.9&nbsp;&nbsp;</span>43. 堆积面积图（Stacked Area Chart）</a></span></li><li><span><a href="#44.-未堆积的面积图（Area-Chart-UnStacked）" data-toc-modified-id="44.-未堆积的面积图（Area-Chart-UnStacked）-6.10"><span class="toc-item-num">6.10&nbsp;&nbsp;</span>44. 未堆积的面积图（Area Chart UnStacked）</a></span></li><li><span><a href="#45.-日历热力图（Calendar-Heat-Map）" data-toc-modified-id="45.-日历热力图（Calendar-Heat-Map）-6.11"><span class="toc-item-num">6.11&nbsp;&nbsp;</span>45. 日历热力图（Calendar Heat Map）</a></span></li><li><span><a href="#46.-季节图（Seasonal-Plot）" data-toc-modified-id="46.-季节图（Seasonal-Plot）-6.12"><span class="toc-item-num">6.12&nbsp;&nbsp;</span>46. 季节图（Seasonal Plot）</a></span></li></ul></li><li><span><a href="#07-分组（Groups）" data-toc-modified-id="07-分组（Groups）-7"><span class="toc-item-num">7&nbsp;&nbsp;</span>07 分组（Groups）</a></span><ul class="toc-item"><li><span><a href="#47.-树状图（Dendrogram）" data-toc-modified-id="47.-树状图（Dendrogram）-7.1"><span class="toc-item-num">7.1&nbsp;&nbsp;</span>47. 树状图（Dendrogram）</a></span></li><li><span><a href="#48.-簇状图（Cluster-Plot）" data-toc-modified-id="48.-簇状图（Cluster-Plot）-7.2"><span class="toc-item-num">7.2&nbsp;&nbsp;</span>48. 簇状图（Cluster Plot）</a></span></li><li><span><a href="#49.-安德鲁斯曲线（Andrews-Curve）" data-toc-modified-id="49.-安德鲁斯曲线（Andrews-Curve）-7.3"><span class="toc-item-num">7.3&nbsp;&nbsp;</span>49. 安德鲁斯曲线（Andrews Curve）</a></span></li><li><span><a href="#50.-平行坐标（Parallel-Coordinates）" data-toc-modified-id="50.-平行坐标（Parallel-Coordinates）-7.4"><span class="toc-item-num">7.4&nbsp;&nbsp;</span>50. 平行坐标（Parallel Coordinates）</a></span></li></ul></li><li><span><a href="#致谢" data-toc-modified-id="致谢-8"><span class="toc-item-num">8&nbsp;&nbsp;</span>致谢</a></span></li></ul></div>
