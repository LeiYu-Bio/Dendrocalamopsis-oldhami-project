enrichment------------------------------------------------------------差异富集分析目录
├── Graph-------------------------------------------------------------差异富集通路图目录
├── group-ID*_vs_group-ID*_filter_anno.xlsx---------------------------差异显著代谢物KEGG注释表
├── group-ID*_vs_group-ID*.KEGG.barplot.*-----------------------------KEGG差异富集分类图（png文件或pdf文件）
├── group-ID*_vs_group-ID*.KEGG.heatmap.Compounds.*-------------------KEGG通路的差异代谢物聚类热图，展示物质名称（png文件或pdf文件或交互式html文件）
├── group-ID*_vs_group-ID*.KEGG.heatmap.Index.*-----------------------KEGG通路的差异代谢物聚类热图，展示迈维ID（png文件或pdf文件或交互式html文件）
├── group-ID*_vs_group-ID*.KEGG.Enrichment.*--------------------------KEGG差异富集气泡图（png文件或pdf文件）
├── group-ID*_vs_group-ID*.KEGG.DA_score.*----------------------------KEGG差异丰度得分图（png文件或pdf文件）
├── group-ID*_vs_group-ID*_KEGG.xls-----------------------------------KEGG差异富集统计表
├── group-ID*_vs_group-ID*_KEGG_DA_score.xlsx-------------------------KEGG差异丰度得分统计表
├── group-ID*_vs_group-ID*_KEGG_stat.xlsx-----------------------------KEGG差异富集分类统计表
└── readme.txt

表格：
差异显著代谢物KEGG注释表
注：
Index：迈维ID
Formula：物质分子式
Compounds：物质英文名称
物质：物质中文名称
Class I：物质英文一级类别
物质一级分类：物质中文一级类别
Class II：物质英文二级类别
物质二级分类：物质中文二级类别
CAS：物质CAS号
Level：物质鉴定级别（1：样本物质二级质谱、RT与数据库物质匹配得分为0.7分以上；2：样本物质二级质谱、RT与数据库物质匹配得分为0.5-0.7分；3：样本物质Q1、Q3、RT、DP、CE与数据库物质核对一致）
VIP：变量重要性投影
p_value：显著性检验p值
FDR：多重假设检验验证后的错误发现率
Fold_Change：差异倍数
Log2FC：差异倍数以2为底取对数
Type：类型
cpd_ID：物质在KEGG数据库上的ID号
kegg_map：KEGG数据库信号通路编号

KEGG差异富集统计表
注：
KEGG_n：差异显著且被KEGG注释到的代谢物个数
KEGG_N：所有测到的代谢物中被KEGG注释到的代谢物个数
#Pathway：通路的名称
ko_ID：通路在KEGG数据库中的ko号;
Unique compound：在该通路中被注释到的差异显著代谢物个数
compound;所检测到的代谢物中属于该通路的代谢物个数
Uni_all：差异显著且被KEGG注释到的代谢物个数
compound_all：所有测到的代谢物中被KEGG注释到的代谢物个数

KEGG差异丰度得分统计表
注：
Kegg_level_1：通路分类
Kegg_pathway：通路的名称
ko_id：通路在KEGG数据库中的ko号
Metabolome_frequency：所检测到的代谢物中属于该通路的代谢物个数占所有测到的代谢物中被KEGG注释到的代谢物个数
P_value：KEGG差异富集的超几何分布p值
DA_score：差异丰度得分，即 (该通路上调差异代谢物个数 - 该通路下调差异代谢物个数) / 注释到该通路的所有代谢物个数
Up_num：该通路上调差异代谢物个数
Down_num：该通路下调差异代谢物个数

KEGG差异富集分类统计表
注：
Kegg_pathway：通路的名称
ko_id：通路在KEGG数据库中的ko号
Cluter_frequency：在该通路中被注释到的差异显著代谢物个数占异显著且被KEGG注释到的代谢物个数比例
Metabolome_frequency：所检测到的代谢物中属于该通路的代谢物个数占所有测到的代谢物中被KEGG注释到的代谢物个数
P-value：超几何分布p值
Corrected_P-value：校正p值


