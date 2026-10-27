dataset-chart.zip是<chart, insight>数据集，内含txt格式的insight文本和json格式的vega-lite图表，文件命名即为图表编号

dataset-chart.csv是<chart, insight>数据集的另一种保存形式，没有显式的图表编号，从1开始排序即得图表编号。
部分项含义：
sourceDataset：[two_col | multi_col]。表示来自Chart-to-Text数据集的哪类数据集，two_col为数据表只有两列的简单图表（柱状图、折线图、饼图……），multi_col为数据表有多列的复杂图表（堆叠柱状图、多折现图……）
dataId：在Chart-to-Text数据集中的原始ID
insightFrom：[data | chart-to-text | vistext]。表示insight的获取方法，data为通过算法从数据表中计算生成，chart-to-text、vistext表示取自Chart-to-Text数据集或VisText数据集



dataset-sketch.zip
是<sketched chart, insight>数据集，命名规则为“图表编号_同一图表的区分序号”，insight文件夹内含txt和json，txt为insight description（未修正），json为修正内容，需要人工在txt中修正
