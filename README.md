# Udacity--DataVisualization-Tableau
#### 使用Tableau对电影数据进行清洗并可视化
#### 详细清洗过程见 "movies_data_clean.ipynb" 文件
#### [Tableau可视化作品链接](https://public.tableau.com/profile/.37707676#!/vizhome/P3_23/Q1)

### 结论

问题1：电影类型是如何随着时代变化而变化的?
在二十世纪80年代以前，由于电影数量相对较少，电影类型也相对单一，在这个时期主要以Drama为主。
二十世纪80年代，Comedy异军突起，数量迅速增多超过Drama，并与80年代中后期成为发行量第一的电影类型。
二十世纪90年代，Thriller、Action以及Romance发行数量逐渐增多，日渐成为电影市场中不可取少的类型。
进入二十一世纪以后，Drama、Comedy、Thriller、Action都有较快发展，分列电影类型前四名。值得注意的是，Horror自2004年以后飞速发展，截至2015年末，以由2004年的第10名发展为第4名，超过Action并仅次于Comedy。
其他类型的电影由于相对小众，发展情况一直不温不火，较为稳定，只是随着电影发行总数的增多而增多。


问题2：环球影业和派拉蒙影业的电影之前数据指标有什么区别?
总体来看，环球影业的电影发行数量高于派拉蒙影业。但从单部影片的平均收益来看，派拉蒙影业要稍高于环球影业。进一步看，派拉蒙影业单部影片的平均预算及平均关注度均要高于环球影业。


问题3：和非小说改编的电影相比，基于小说改编的电影表现得怎么样?
从样本整体情况来看，基于小说改编的电影无论是从关注度方面、收益方面、预算收益比（来自预算与收益趋势线的比较）方面，似乎均要优于非小说改编的电影。但从历年的情况来看，选取了几个存在极端情况的年份进行细致分析发现，出现这种表面上非小说改编电影完败的原因是我们采取了平均值方法进行比较，由于非小说改编电影的数量巨大，从而存在大量低质量的片子拉低了整体水平；反观基于小说改编的电影，一般来说能够用于改编电影的小说均具有一定的名气，一旦上映会天然吸引一定的关注度和票房，且该类型电影数量相对少很多，从而无法有效消除极值影响。
然后，当我使用历年最赚钱、关注度最高的电影形成时间序列进行分析时发现，除个别年份，绝大多数年份当年最赚钱、关注度最高的电影均为非小说改编电影。
综上，和非小说改编的电影相比，基于小说改编的电影预算收益比较高，票房有一定的保证，但是不容易出现收益和关注度极高的电影。


问题4：电影评分、电影收益与关注度、预算之间的关系。
一般来说，关注度越高，电影评分和电影收益越高。预算越高，电影评分和电影收益越高。
在自己平时选择观看哪些电影时，多是先看哪些电影的讨论比较多（关注度），然后看评分高低，从而抉择到底选择观看哪部电影。再个就是如果电影的预算投入比较大的，多数制作较为精良，也能够吸引到很多眼球。
