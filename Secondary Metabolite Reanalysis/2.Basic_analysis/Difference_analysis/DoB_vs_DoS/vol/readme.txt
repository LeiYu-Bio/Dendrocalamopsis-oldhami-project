vol-----------------------------------------------对应分组火山图
├── group-ID*_vs_group-ID*_vol.*------------------客户指定筛选条件下对应分组差异代谢物火山图（pdf文件或png文件或交互式html文件）
├── group-ID*_vs_group-ID*_*Pvalue_vol.*----------不同筛选条件下对应分组差异代谢物火山图，仅供参考（pdf文件或png文件或交互式html文件）
└── readme.txt

注：客户指定差异代谢物筛选条件为VIP + FC （+ Pvalue/FDR）时，展示以下2种筛选条件下的火山图
1. VIP + FC + Pvalue/FDR
2. VIP + FC
即：
如果客户指定筛选条件为VIP和差异倍数FC，
group-ID*_vs_group-ID*_vol.*----------------------筛选条件为客户指定的VIP和FC
group-ID*_vs_group-ID*_withPvalue_vol.*-----------筛选条件为客户指定的VIP和FC，以及常用的P值阈值（t-test，p < 0.05）

如果客户指定筛选条件为VIP和FC和P值/FDR，
group-ID*_vs_group-ID*_vol.*----------------------筛选条件为客户指定的VIP、FC和P值/FDR
group-ID*_vs_group-ID*_noPvalue_vol.*-------------筛选条件为客户指定的VIP和FC
