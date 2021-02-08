# 实时荧光定量PCR具体实验步骤

来自公众号「转录组」

https://mp.weixin.qq.com/s/08YFwfUiQWfKpXIBQUuQ1A

【表格没有整理完】

##**1 样品RNA的抽提** 

①取冻存已裂解的细胞，室温放置5分钟使其完全溶解。

②两相分离

每1ml的TRIZOL试剂裂解的样品中加入0.2ml的氯仿，盖紧管盖。手动剧烈振荡管体15秒后，15到30℃孵育2到3分钟。4℃下12000rpm离心15分钟。离心后混合液体将分为下层的红色酚氯仿相，中间层以及无色水相上层。RNA全部被分配于水相中。水相上层的体积大约是匀浆时加入的TRIZOL试剂的60%。

③RNA沉淀

将水相上层转移到一干净无RNA酶的离心管中。加等体积异丙醇混合以沉淀其中的RNA，混匀后15到30℃孵育10分钟后，于4℃下12000rpm 离心10分钟。此时离心前不可见的RNA沉淀将在管底部和侧壁上形成胶状沉淀块。

④RNA清洗

移去上清液，每1mlTRIZOL试剂裂解的样品中加入至少1ml的75%乙醇（75%乙醇用DEPC H~2~O配制），清洗RNA沉淀。混匀后，4℃下7000rpm离心5分钟。

> DEPC H~2~O：https://baike.baidu.com/item/DEPC%E6%B0%B4/10110676?fr=aladdin
>
> DEPC水是用DEPC（diethyl pyrocarbonate，焦碳酸二乙酯）处理过并经高温高压灭菌的超纯水（一级水），无色液体。经检测不含杂质RNA、DNA和蛋白质。
>
> DEPC水可以用于RNA沉淀的溶解，含有RNA的各种反应体系如反转录、siRNA的退火等，以及其它各种要求无RNase、DNAase和proteinase的反应体系。

⑤RNA干燥

小心吸去大部分乙醇溶液，使RNA沉淀在室温空气中干燥5-10分钟。

⑥溶解RNA沉淀

溶解RNA时，先加入无RNA酶的水40μl用枪反复吹打几次，使其完全溶解，获得的RNA溶液保存于-80℃待用。

##**2 RNA质量检测** 

###1）紫外吸收法测定

先用稀释用的TE溶液将分光光度计调零。然后取少量RNA溶液用TE稀释（1:100）后，读取其在分光光度计260nm和280nm处的吸收值，测定RNA溶液浓度和纯度。

① 浓度测定

A260下读值为1表示40 µg RNA/ml。样品RNA浓度(µg/ml)计算公式为：A260 ×稀释倍数× 40 µg/ml。

具体计算如下：RNA溶于40 µl DEPC水中，取5ul，1:100稀释至495µl的TE中，测得A~260~ = 0.21RNA 浓度= 0.21 ×100 ×40 µg/ml = 840 µg/ml 或 0.84 µg/µl

取5 µl用来测量以后，剩余样品RNA为35 µl，剩余RNA总量为：35 µl × 0.84 µg/µl = 29.4 µg

②纯度检测

RNA溶液的A~260~/A~280~的比值即为RNA纯度，比值范围1.8到2.1。

###2）变性琼脂糖凝胶电泳测定

①制胶

取1g琼脂糖溶于72ml水中，冷却至60℃，10 ml的10× MOPS电泳缓冲液和18 ml的37% 甲醛溶液(12.3 M)。

10×MOPS电泳缓冲液：

| 浓度  | 成分         |
| ----- | ------------ |
| 0.4M  | MOPS，pH 7.0 |
| 0.1M  | 乙酸钠       |
| 0.01M | EDTA         |

灌制凝胶板，预留加样孔至少可以加入25 µl溶液。胶凝后取下梳子，将凝胶板放入电泳槽内，加足量的1×MOPS电泳缓冲液至覆盖胶面几个毫米。

> MOPS：https://en.wikipedia.org/wiki/MOPS
>
> MOPS (3-(*N*-morpholino)propanesulfonic acid) is a buffer introduced by Good et al. in the 1960s. It is a structural analog to MES. Its chemical structure contains a morpholine ring. HEPES is a similar pH buffering compound that contains a piperazine ring. With a pKa of 7.20, MOPS is an excellent buffer for many biological systems at near-neutral pH.
>
> <!--Good, Norman E.; Winget, G. Douglas; Winter, Wilhelmina; Connolly, Thomas N.; Izawa, Seikichi; Singh, Raizada M. M. (1966). "Hydrogen Ion Buffers for Biological Research". Biochemistry. 5 (2): 467--77. doi:10.1021/bi00866a011. PMID 5942950-->

②准备RNA样品

取3 µg RNA，加3倍体积的甲醛上样染液，加EB于甲醛上样染液中至终浓度为10µg/ml。加热至70℃孵育15分钟使样品变性。

③电泳

上样前凝胶须预电泳5min，随后将样品加入上样孔。5–6V/cm电压下2h，电泳至溴酚兰指示剂进胶至少2–3cm。

④紫外透射光下观察并拍照

28S和18S核糖体RNA的带非常亮而浓（其大小决定于用于抽提RNA的物种类型），上面一条带的密度大约是下面一条带的2倍。还有可能观察到一个更小稍微扩散的带，它由低分子量的RNA（tRNA和5S核糖体RNA）组成。在18S和28S核糖体带之间可以看到一片弥散的EB染色物质，可能是由mRNA和其它异型RNA组成。RNA制备过程中如果出现DNA污染，将会在28S核糖体RNA带的上面出现，即更高分子量的弥散迁移物质或者带，RNA的降解表现为核糖体RNA带的弥散。用数码照相机拍下电泳结果。 

##**3 样品cDNA合成**

①反应体系

序号 反应物 剂量1 逆转录buffer 2μl2 上游引物 0.2μl3 下游引物 0.2μl4 dNTP 0.1μl5 逆转录酶MMLV 0.5μl6 DEPC水 5μl7 RNA模版 2μl8 总体积 10μl

轻弹管底将溶液混合，6000rpm短暂离心。

②混合液在加入逆转录酶MMLV 之前先70℃干浴3分钟，取出后立即冰水浴至管内外温度一致，然后加逆转录酶0.5μl，37℃水浴60分钟。

③取出后立即95℃干浴3分钟，得到逆转录终溶液即为cDNA溶液，保存于-80℃待用。

## **4 梯度稀释的标准品及待测样品的管家基因（β-actin）实时定量PCR** 

①β-actin阳性模板的标准梯度制备

阳性模板的浓度为10^11^，反应前取3μl按10倍稀释（加水27μl并充分混匀）为10^10^，依次稀释至10^9^、10^8^、10^7^、10^6^、10^5^、10^4^，以备用。

②反应体系如下：

标准品反应体系

序号 反应物 剂量1  SYBR Green 1 染料 10μl2 阳性模板上游引物F 0.5μl3 阳性模板下游引物R 0.5μl4 dNTP 0.5μl5 Taq酶 1μl6 阳性模板DNA 5μl7 ddH2O 32.5μl8 总体积 50μl轻弹管底将溶液混合，6000rpm短暂离心。

管家基因反应体系

序号 反应物 剂量1 SYBR Green 1 染料 10μl2 内参照上游引物F 0.5μl3 内参照下游引物R 0.5μl4 dNTP 0.5μl5 Taq酶 1μl6 待测样品cDNA 5μl7 ddH2O 32.5μl8 总体积 50μl轻弹管底将溶液混合，6000rpm短暂离心。

③制备好的阳性标准品和检测样本同时上机，反应条件为：93℃2分钟，然后93℃ 1分钟，55℃ 2分钟，共40个循环。

##**5 制备用于绘制梯度稀释标准曲线的DNA模板**

①针对每一需要测量的基因，选择一确定表达该基因的cDNA模板进行PCR反应。

反应体系：

序号 反应物 剂量1 10× PCR缓冲液 2.5 ul2 MgCl2 溶液 1.5 ul3 上游引物F 0.5 ul4 下游引物R 0.5 ul5 dNTP混合液 3 ul6 Taq聚合酶 1 ul7 cDNA 1 ul8 加水至总体积为 25ul轻弹管底将溶液混合，6000rpm短暂离心。35个PCR循环（94℃1分钟；55℃1分钟；72℃1分钟）；72ºC延伸5分钟。

②PCR产物与 DNA Ladder在2％琼脂糖凝胶电泳，溴化乙锭染色，检测PCR产物是否为单一特异性扩增条带。

③将PCR产物进行10倍梯度稀释

设定PCR产物浓度为10^10^，依次稀释至10^9^、10^8^、10^7^、10^6^、10^5^、10^4^几个浓度梯度。

##**6 待测样品的待测基因实时定量PCR**

①所有cDNA样品分别配置实时定量 PCR反应体系。

体系配置如下：

序号 反应物 剂量1 SYBR Green 1 染料  10 ul2 上游引物 1ul3 下游引物 1ul4 dNTP  1ul5 Taq聚合酶 2ul6 待测样品cDNA 5ul7 ddH2O  30ul8 总体积 50 ul轻弹管底将溶液混合，6000rpm短暂离心。

②将配制好的PCR反应溶液置于Realtime PCR仪上进行PCR扩增反应。反应条件为：93℃ 2分钟预变性，然后按93℃ 1分钟，55℃ 1分钟，72℃ 1分钟，共40做个循环，最后72℃ 7分钟延伸。

##**7 实时定量PCR使用引物列表**

引物设计软件：Primer Premier 5.0，并遵循以下原则：

- 引物与模板的序列紧密互补
- 引物与引物之间避免形成稳定的二聚体或发夹结构
- 引物不在模板的非目的位点引发DNA 聚合反应(即错配)


##**8 电泳**

各样品的目的基因和管家基因分别进行Realtime PCR反应。

PCR产物与 DNA Ladder在2％琼脂糖凝胶电泳，==GoldView™染色==，检测PCR产物是否为单一特异性扩增条带。

