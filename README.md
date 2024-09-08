# This is a page to introduce myself to you.

![personal-website](https://zxradrian.github.io/)


Education
======
* M.S. in Big Data project of Electronic Information major, Zhejiang University, 2026
* B.S. in Computer Science, Beijing Foreign Studies University, 2018

  
Work experience
======
* 2024.7 - : 字节跳动TikTok
  * Tiktok-data-video recommendation-消息推荐 算法实习生
  * 频次模型迭代:
    * 依据原频次模型uplift进行迭代，模型上将原有的T-Learner结构改进为DESCN和EFIN的算法结合体，数据上增加了关闭特征，过去的曝光，点击，关闭和宽点击序列特征，标签上拓展了多任务的标签宽点击标签，并修改上线。
  * 时机模型迭代:
    * 迭代原有的时机模型从多任务MLP为MMoE的版本。
  * 流控架构调整:
    * 增加关闭状态用户少发的逻辑，增加分层流控X+UV不涨的评判标准。
  * 端智能弹窗引导优化：
    * 控制不同场景下引导push打开弹窗的频次时间与退场时间，从原有的避让策略迁移到规则策略再最后迁移到端智能模型。
* 2024.3-2024.7: 哈啰出行
  * 人工智能部-基础算法-智能搜推组算法实习生
  * 流量货币化广告模型迭代:
    * 依据原效果广告模型进行迭代，将序列信息通过带有特殊position encoding和mask机制的transformer编码并使用target attention融合并改进了模型。具体负责了从调研，取数，训练到上线的全流程任务。经过线上ABTest证实CTR效果提升了3.7%，CVR效果提升了2.7%。
  * 流量货币化广告模型迭代:
    * 制作供给后端部门和算法部门每日自动更新的报表，根据曝光全链路之中抽取得到有效曝光，点击和转化信息制作对于ECPM排名偏差指标，CTR，CVR偏差，消耗和报价的相关报表，其中考虑了曝光链路里冷启流量等污染指标以及UV浏览等情况，依据此发现了空耗流量和预算超跑等相关问题。
  * 租车推荐业务协同过滤算法:
    * 用户点击某辆车后，下拉菜单所推荐的其他相近车型的推荐排序。具体方法是使用地理位置召回，Swing召回以及强制重排等逻辑，对原本简单的车辆召回逻辑做了改进。根据ABTest，CTR提升了0.5%左右。
* 2020.7 - 2021.9: 中国科学院
  * 信息工程研究所-科研助理
  * 文献调研:
    * ：翻译，综述文献等，主要方面是虚假信息检测及其他自然语言处理应用领域的文献翻译及文献综述撰写等。


Skills
======

  * Python
  * C++
  * TensorFlow
  * LaTex
* Language
  * TEM8
  * TEM4
  * CET6
  * CET4
  * Basic Spanish
* MultiMedia
  * PS
  * PR
 
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards
======
* 全国大学生数学能力挑战赛一等奖
* 美国大学生数学建模竞赛M 奖
* 北京市优秀毕业生
* 北京市优秀毕业论文
* 北京外国语大学优秀共产党员
* 北外一等奖学金（10%）
* 国家励志奖学金
* 优秀共青团员
