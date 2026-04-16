# 段永平投资问答录（商业逻辑篇）—— 反例提取

```yaml
- id: ce01
  title: 追求性价比的陷阱
  type: counter-example
  source_chapter: 第1节-三/第7节-10
  source_quote: |
    "说追求'性价比'的公司大多是在为自己的低价找借口。长寿公司大概是不太强调'性价比'这个概念的，老百姓心里有杆秤。好货不便宜啊。"
  failure_mode: |
    企业以"性价比"为口号走低价路线，本质上是产品性能不够好而找借口。追求性价比的公司既没有长长的坡，也没有厚厚的雪，长期无法建立品牌溢价和护城河。
  mechanism: |
    低价策略导致利润微薄，无法投入足够的资金进行产品研发和创新，产品品质无法提升，陷入"低价-低质-更低价"的恶性循环，最终被市场淘汰。
  warning_signs:
    - 公司频繁宣传"性价比"概念
    - 产品价格持续走低但品质无提升
    - 以低价抢占市场份额为核心策略
    - 利润率远低于行业优秀企业
  bound_to:
    - "差异化评估"
    - "商业模式评估"
    - "护城河分析"
  tags: [counter-example, pricing, differentiation, low-end-trap]

- id: ce02
  title: 低价是最容易的路也是最难的路
  type: counter-example
  source_chapter: 第2节-16
  source_quote: |
    "低价是条最容易的路，也是一条最难的路。"
  failure_mode: |
    以低价切入市场看似门槛低、见效快，但一旦陷入低价竞争，就极难翻身。靠低价获得的份额不是真正的竞争优势，而是"阴影本身"。
  mechanism: |
    低价模式压缩利润空间，无法支撑持续的产品迭代和品质提升。消费者对低价产品缺乏忠诚度，一旦竞争对手价格更低，客户立即流失。低价获得的规模不等于盈利能力。
  warning_signs:
    - 管理层以"薄利多销"为荣
    - 市场份额增长但利润不增长甚至下滑
    - 频繁推出更低端的产品线
    - 靠降价维持销量
  bound_to:
    - "差异化评估"
    - "定价权评估"
    - "商业模式评估"
  tags: [counter-example, pricing, low-price-trap, market-share]

- id: ce03
  title: 没有差异化的产品无法长期赚钱
  type: counter-example
  source_chapter: 第2节-二
  source_quote: |
    "没有差异化的产品是很难长期赚到大钱的。""产品差异化程度越低，行业内的企业越难赚到钱。航空公司是极致，就是因为产品差异化小。"
  failure_mode: |
    在差异化极小的行业中，企业只能靠价格竞争，最终所有参与者都无法获得好的利润。航空公司、光伏组件、太阳能硅片等行业是典型例子。
  mechanism: |
    产品无差异化意味着消费者只关注价格，企业被迫进入价格战。价格战导致利润消失，利润消失导致无力创新，无力创新导致产品更加无差异化，形成死亡螺旋。
  warning_signs:
    - 消费者选择产品时只比较价格
    - 行业内频繁爆发价格战
    - 企业利润率持续低于资本成本
    - 行业整体长期无法获得合理回报
  bound_to:
    - "差异化评估"
    - "商业模式评估"
    - "行业选择"
  tags: [counter-example, differentiation, commoditization, price-war]

- id: ce04
  title: 成本优势不能构成护城河
  type: counter-example
  source_chapter: 第2节-三/17
  source_quote: |
    "还没见过成本优势可以成'护城河'的，很少有企业能长期维持低成本的，制造业好像没见过。而且靠自己产品卖低价的企业就很难有长久的，至少我没见过。"
  failure_mode: |
    企业将低成本作为核心竞争优势，认为可以通过效率优势长期取胜。但成本优势极其脆弱，竞争对手可以通过规模、技术或更低的人工成本来复制甚至超越。
  mechanism: |
    低成本优势来源于特定时期的条件（如低人工成本、规模效应、技术代差），这些条件会随时间被侵蚀。一旦优势消失，企业没有差异化产品作为壁垒，将迅速被淘汰。
  warning_signs:
    - 公司核心卖点始终是"成本更低"
    - 利润增长主要依赖成本削减而非产品溢价
    - 在低人工成本地区设厂是核心策略
    - 无法提价，只能跟随市场价格
  bound_to:
    - "护城河分析"
    - "差异化评估"
    - "定价权评估"
  tags: [counter-example, cost-advantage, moat, manufacturing]

- id: ce05
  title: 靠低价获得的份额是阴影本身
  type: counter-example
  source_chapter: 第2节-17
  source_quote: |
    "靠低价得到的份额实际就是阴影本身，很难走出来的。看看诺基亚就明白了。"
  failure_mode: |
    企业通过低价策略获得大量市场份额，以为规模就是优势，但实际上低价获得的用户缺乏忠诚度，品牌形象被固化在低端，极难向上突破。
  mechanism: |
    低价份额建立的品牌认知是"便宜"而非"好"，当企业试图提升品质和价格时，原有用户因价格敏感而流失，高端用户因品牌认知不买账。联想收购IBM PC后靠低价走量就是此模式。
  warning_signs:
    - 管理层以市场份额排名为主要KPI
    - 销量增长但利润率持续走低
    - 品牌在消费者心中等于"便宜"
    - 试图做高端产品但市场不认可
  bound_to:
    - "品牌评估"
    - "定价权评估"
    - "差异化评估"
  tags: [counter-example, market-share, low-price, brand-trap]

- id: ce06
  title: 多元化是失败的捷径
  type: counter-example
  source_chapter: 第6节-二
  source_quote: |
    "很少有公司能够做好'多元化'的，尤其是那些为了多元化而多元化的公司。""有很多公司在经历一段不错的发展后，为了分散风险，开始搞起了多元化，结果其中有些公司很快就不用再担心风险的问题了。"
  failure_mode: |
    企业在某一个领域成功后，认为自己能力可以复制到其他领域，开始盲目多元化。由于新领域缺乏核心竞争力和文化积累，不仅新业务失败，还拖累原有优势业务。
  mechanism: |
    多元化分散了管理注意力和资源，导致每个业务都无法做到极致。不同业务的企业文化难以兼容，管理复杂度指数级上升。GE曾是多元化成功的唯一例外，但最终证明时间长了也不行。
  warning_signs:
    - 公司同时经营多个不相关的业务
    - 管理层频繁谈论"新增长点"
    - 原有主业增速放缓后急于寻找新赛道
    - 并购成为主要增长方式
  bound_to:
    - "聚焦原则"
    - "商业模式评估"
    - "企业文化评估"
  tags: [counter-example, diversification, focus, acquisition]

- id: ce07
  title: 成功是失败之母——被过去成功模式困住
  type: counter-example
  source_chapter: 第2节-7
  source_quote: |
    "成功是失败之母。微软陷在过去的成功模式中出不来，估计以后也很难出来了。"
  failure_mode: |
    企业因过去的成功而固守原有商业模式，无法适应市场变化。过去的成功经验成为变革的阻碍，管理层无法放弃已经验证过的路径。
  mechanism: |
    成功模式产生的现金流和利润使企业没有紧迫感进行变革。组织内部形成利益格局，任何改变现有模式的尝试都遭到阻力。微软在移动互联网中坚持收费模式就是典型。
  warning_signs:
    - 公司核心业务收入占比持续超过80%且没有下降趋势
    - 管理层频繁强调"我们一直这么做"
    - 新业务始终无法获得足够资源
    - 对行业变化趋势的回应总是"这不影响我们"
  bound_to:
    - "企业文化评估"
    - "商业模式评估"
    - "管理层评估"
  tags: [counter-example, innovation, success-trap, organizational-inertia]

- id: ce08
  title: 利润导向导致不择手段
  type: counter-example
  source_chapter: 第1节/第3节
  source_quote: |
    "如果没有'取之有道'的约束，利润导向很容易不择手段。国内现在这个问题实际上非常严重。"
  failure_mode: |
    企业将利润作为唯一目标，在短期业绩压力下做出损害消费者利益、违反诚信原则的行为。这种做法短期内可能获利，但长期必然导致品牌崩塌和业务失败。
  mechanism: |
    利润导向使企业放弃原则，在"赚钱"和"做对的事"之间总是选择前者。一次不诚信的行为可能带来短期利益，但破坏了消费者信任这一最宝贵的无形资产。一旦信任丧失，重建几乎不可能。
  warning_signs:
    - 管理层只关注季度业绩和市值目标
    - 产品质量问题被忽视或掩盖
    - 对消费者的投诉不重视
    - 过度追求短期利润牺牲长期品牌
  bound_to:
    - "企业文化评估"
    - "诚信评估"
    - "长期主义"
  tags: [counter-example, profit-driven, integrity, short-termism]

- id: ce09
  title: 高负债的死亡螺旋
  type: counter-example
  source_chapter: 第2节-23/第7节-3
  source_quote: |
    "多数企业最后都是死在资金链断裂上。""我个人一般对有负债的公司不太愿意重仓，另外就是无论多有把握也绝对不要用margin。"
  failure_mode: |
    企业为了快速发展大量借贷，在经济好的时候一切正常，但一旦遇到经济周期下行或经营困难，债务变成致命的枷锁，最终导致资金链断裂而倒闭。
  mechanism: |
    高负债增加了固定成本（利息支出），降低了企业抵御风险的能力。经济周期下行时收入减少但债务不变，企业被迫出售资产或借新还旧，形成恶性循环。巴菲特比喻为"方向盘上装匕首"。
  warning_signs:
    - 负债率持续高于行业平均水平
    - 借新债还旧债
    - 利息支出占经营利润比例过高
    - 在行业下行期仍大举借债扩张
  bound_to:
    - "财务安全评估"
    - "商业模式评估"
    - "风险控制"
  tags: [counter-example, debt, leverage, financial-risk]

- id: ce10
  title: 没有愿景的公司走不远
  type: counter-example
  source_chapter: 第3节-一
  source_quote: |
    "没有愿景的公司容易陷入利润导向，最后容易被眼前利益诱惑而犯大错，从而导致公司寿命缩短。"
  failure_mode: |
    企业缺乏清晰的愿景和使命，在日常经营中只关注赚钱，遇到短期诱惑时无法做出正确判断，最终因一系列短期决策的累积而走向衰亡。
  mechanism: |
    没有愿景就没有判断对错的标准，管理层在决策时只能以短期利润为导向。短期利润导向必然导致牺牲长期利益的决策（如降低品质、削减研发、进入不熟悉的领域），这些决策累积起来最终致命。
  warning_signs:
    - 公司没有清晰的使命和愿景声明
    - 有愿景但只是挂在墙上没有落地
    - 领导层决策标准只有"赚不赚钱"
    - 员工不知道公司为什么要做某些事
  bound_to:
    - "企业文化评估"
    - "长期主义"
    - "管理层评估"
  tags: [counter-example, vision, corporate-culture, short-termism]

- id: ce11
  title: 空降CEO的高失败率
  type: counter-example
  source_chapter: 第3节-四
  source_quote: |
    "空降兵不是一定不行，但由于文化冲突的问题，空降兵的成功率非常低。""雅虎这么老从外面找CEO的办法说明美国雅虎董事会确实很烂啊。"
  failure_mode: |
    公司从外部聘请CEO，由于新CEO不认同或不理解公司企业文化，导致文化冲突、决策失误，最终不仅空降CEO失败，还严重损害了公司原有的文化基础。
  mechanism: |
    外部CEO缺乏对公司文化的深入理解，其管理风格和价值观可能与原有团队严重不匹配。文化冲突导致中层流失、执行力下降、战略摇摆。惠普聘请菲奥莉娜、雅虎频繁换CEO都是典型。
  warning_signs:
    - 董事会频繁从外部聘请CEO
    - 新CEO上任后大量更换管理层
    - 公司战略每隔几年就大幅调整
    - 员工对新领导层的认同度低
  bound_to:
    - "管理层评估"
    - "企业文化评估"
    - "继任计划"
  tags: [counter-example, CEO-selection, corporate-culture, succession]

- id: ce12
  title: 狼性文化的长期代价
  type: counter-example
  source_chapter: 第3节-四
  source_quote: |
    "狼性文化最终会输给人性文化。""兴奋剂当然是有用的。"
  failure_mode: |
    企业以狼性文化驱动，通过高压、高强度、竞争淘汰的方式追求业绩。短期内可能获得高速增长，但长期来看导致人才流失、创新力下降、企业文化畸形。
  mechanism: |
    狼性文化将员工视为消耗性资源，通过不断施压和淘汰来保持"战斗力"。这种模式下，员工只会执行指令不敢创新，优秀人才因无法获得尊重和成长而离开。如同兴奋剂，短期有效但长期摧毁身体。
  warning_signs:
    - 企业以"狼性""奋斗"为文化标签
    - 强制加班和高淘汰率
    - 员工年龄结构偏年轻，缺乏资深人才
    - 员工对公司缺乏归属感和认同感
  bound_to:
    - "企业文化评估"
    - "人才评估"
    - "长期主义"
  tags: [counter-example, wolf-culture, talent, sustainability]

- id: ce13
  title: 收购兼并的低成功率
  type: counter-example
  source_chapter: 第6节-一
  source_quote: |
    "收购的成功率一般都很低。只有具有很强企业文化的公司收购的成功概率才可能比较高点。"
  failure_mode: |
    企业通过收购来追求规模扩张或进入新领域，但由于文化整合困难、管理层能力不匹配、估值过高等原因，收购往往无法达到预期效果，甚至成为沉重的负担。
  mechanism: |
    收购最大的挑战是文化整合。两家公司的管理风格、决策方式、价值观不同，导致被收购公司的核心人才流失、运营效率下降。此外，收购时的高溢价需要多年才能消化。GE多元化最终失败证明了即使是管理最强的公司也难以持续做好收购。
  warning_signs:
    - 公司频繁进行收购
    - 收购价格明显高于被收购公司的内在价值
    - 收购的业务与原有业务无关联
    - 被收购公司的核心团队在收购后迅速离职
  bound_to:
    - "管理层评估"
    - "企业文化评估"
    - "资本配置评估"
  tags: [counter-example, acquisition, M&A, culture-clash]

- id: ce14
  title: 销售导向替代产品导向的衰落
  type: counter-example
  source_chapter: 第1节（乔布斯引述）
  source_quote: |
    "像IBM或微软这样的公司为什么会衰落...这些公司开始重视优秀的销售人员，因为是他们在推动销售、改写了收入数字...做销售的人经营公司，做产品的人就不再那么重要，其中很多人就失去了创造的激情。"
  failure_mode: |
    公司从产品驱动转向销售驱动，管理层由销售人员主导而非产品人员。产品品质下降，创新停滞，最终被产品导向的竞争对手超越。
  mechanism: |
    销售导向的管理层关注短期收入数字而非产品品质，资源分配向销售端倾斜，研发投入减少。产品人员失去话语权和激情，优秀的产品人才流失。公司靠渠道和营销维持增长，但产品竞争力持续下降。苹果的斯卡利时代和微软的鲍尔默时代都是此模式。
  warning_signs:
    - CEO出身销售而非产品
    - 公司奖励机制偏向销售而非产品创新
    - 产品迭代速度明显慢于竞争对手
    - 研发投入占比持续下降
  bound_to:
    - "管理层评估"
    - "企业文化评估"
    - "产品评估"
  tags: [counter-example, sales-driven, product-culture, innovation-decline]

- id: ce15
  title: 为做大而做大的并购陷阱
  type: counter-example
  source_chapter: 第6节-一
  source_quote: |
    "如果当有人本着'大不一定强，不大则一定不强。所以要做强则先做大。'的想法去并购的话，那结局一定是很难看的。"
  failure_mode: |
    企业以"先做大再做强"为理念进行并购扩张，追求规模而非质量。并购后整合不力、管理失控，规模越大问题越多，最终"大而不强"走向衰亡。
  mechanism: |
    "先做大"的思维导致在并购中忽视文化匹配和业务协同，盲目追求规模数字。整合过程中文化冲突、管理稀释、资源分散等问题累积爆发。规模带来的复杂性超过了管理能力的增长。
  warning_signs:
    - 管理层以"行业第一""全球最大"为目标
    - 并购速度明显超过整合消化能力
    - 公司业务跨度大但各业务间缺乏协同
    - 并购后管理费用大幅上升
  bound_to:
    - "管理层评估"
    - "企业文化评估"
    - "资本配置评估"
  tags: [counter-example, scale-obsession, M&A, management-capacity]

- id: ce16
  title: 弯道超车的翻车风险
  type: counter-example
  source_chapter: 第7节-13
  source_quote: |
    "Alaska有句话，shortcut is the fastest way to get lost（捷径是迷路的最快的办法）。不存在什么弯道超车的事情，关注本质最重要！不然即使超过去，也会被超回来。""提高翻车率的有效办法。"
  failure_mode: |
    企业试图通过投机取巧的方式快速超越竞争对手，而不是踏踏实实地做好产品和积累能力。短期内可能看似成功，但因为根基不牢，很快被竞争对手反超。
  mechanism: |
    弯道超车本质上是在基础不牢的情况下追求速度。企业在核心竞争力（产品、文化、品牌）未建立时就追求规模和速度，地基不稳导致后续发展无法持续。捷径看似节省时间，实际增加翻车风险。
  warning_signs:
    - 管理层热衷于谈论"弯道超车""颠覆式创新"
    - 公司增长速度远超同行但利润率很低
    - 大量依赖营销而非产品力驱动增长
    - 核心技术依赖外部而非自主研发
  bound_to:
    - "长期主义"
    - "企业文化评估"
    - "产品评估"
  tags: [counter-example, shortcut, fundamental, sustainable-growth]

- id: ce17
  title: 不懂不碰——投资能力圈之外的陷阱
  type: counter-example
  source_chapter: 第2节-9
  source_quote: |
    "对自己不够了解的公司，涨了也想卖跌了也想卖。"
  failure_mode: |
    投资者在没有真正理解公司商业模式的情况下买入，无论涨跌都无法安心持有。涨了担心回调想卖出，跌了恐慌割肉，最终在反复交易中亏损。
  mechanism: |
    不理解公司意味着没有判断其内在价值的能力，股价波动成为唯一的决策依据。当股价上涨时怀疑是否高估，下跌时担心是否有未知的利空，情绪波动导致频繁交易。段永平清空FB就是因为他不用FB的产品，对FB理解不够透彻。
  warning_signs:
    - 需要问别人"该不该买"才敢下手
    - 持有期间频繁关注股价变动
    - 无法用一句话说清楚公司的赚钱模式
    - 买入理由是"别人推荐"或"看起来便宜"
  bound_to:
    - "能力圈原则"
    - "商业模式理解"
    - "投资纪律"
  tags: [counter-example, circle-of-competence, understanding, investment-discipline]

- id: ce18
  title: 过度关注短期业绩的短视
  type: counter-example
  source_chapter: 第1节/第2节
  source_quote: |
    "多数人在投资时很习惯去看有没有'把事情做对'这点，从而会很容易掉进短期表现当中。"
  failure_mode: |
    投资者或管理层过度关注一两个季度的短期业绩表现，忽视了长期商业模式的健康度。短期业绩波动被误读为趋势，导致错误的投资或经营决策。
  mechanism: |
    短期业绩受多种因素影响（季节性、一次性事件、会计处理），不代表长期趋势。过度关注短期数据导致忽视根本性的商业模式问题。伟大的企业在"做对的事情"过程中也会犯错，短期表现不佳不代表方向错误。
  warning_signs:
    - 投资决策主要基于最近一两个季度的财报
    - 管理层为了季度业绩做损害长期利益的事
    - 因为一个季度业绩不达预期就否定公司
    - 频繁根据短期数据调整投资组合
  bound_to:
    - "长期主义"
    - "商业模式评估"
    - "投资纪律"
  tags: [counter-example, short-termism, quarterly-obsession, long-term-thinking]

- id: ce19
  title: 价格战的死亡螺旋
  type: counter-example
  source_chapter: 第7节-9
  source_quote: |
    "没有差异化的工业品往往容易有价格战。""价格战的最后结果往往是优不胜，比如汽车业和航空业。""除非不得已，用价格武器总是错的。"
  failure_mode: |
    企业主动发起或被动卷入价格战，以为通过降价可以扩大市场份额。结果是价格降了但份额没变，所有参与者的利润都被压缩到无法维持正常运营的水平。
  mechanism: |
    价格战的逻辑是"降价→抢份额→规模效应→成本降低→盈利"。但现实中，竞争对手也会跟进降价，最终结果是份额不变但价格更低。利润消失后无力投入研发和创新，产品竞争力进一步下降，形成恶性循环。
  warning_signs:
    - 管理层以"薄利多销"为经营策略
    - 行业内频繁出现"降价促销"
    - 利润率持续走低但市场份额无显著变化
    - 企业因价格战被迫削减研发或品质投入
  bound_to:
    - "差异化评估"
    - "定价权评估"
    - "行业竞争格局"
  tags: [counter-example, price-war, commoditization, differentiation]

- id: ce20
  title: 不诚信的必然恶果
  type: counter-example
  source_chapter: 第3节-三/第7节-7
  source_quote: |
    "不诚信公司大概率不会有好下场。""做对的事情就是--当发现错了就尽快改，不管多大的代价都是最小的代价。"
  failure_mode: |
    企业在经营中不守诚信（如欺骗消费者、拖欠供应商货款、对投资者不透明），短期可能获利，但长期必然导致信任崩塌、合作伙伴远离、消费者流失。
  mechanism: |
    诚信是商业合作的基石。一次不诚信的行为会通过口碑传播放大，合作伙伴和消费者一旦失去信任就不会再回来。建立信誉需要多年，毁掉信誉只需一次。卫哲事件中阿里巴巴B2B平台的欺诈问题就是典型。
  warning_signs:
    - 公司历史上存在欺诈或虚假宣传
    - 对消费者的投诉处理敷衍
    - 管理层在公开场合说的话前后不一致
    - 财务数据存在可疑之处
  bound_to:
    - "诚信评估"
    - "企业文化评估"
    - "管理层评估"
  tags: [counter-example, integrity, trust, reputation]

- id: ce21
  title: 诺基亚的低端机战略失误
  type: counter-example
  source_chapter: 第2节-14
  source_quote: |
    "这是诺基亚的大错之一。从他们推出低端机开始我就猜他们会有今天了。"
  failure_mode: |
    诺基亚通过推出低端机抢占市场份额，牺牲了品牌价值和产品差异化。低端策略导致品牌形象下降，创新能力被稀释，最终在智能手机时代被彻底淘汰。
  mechanism: |
    低端机策略分散了公司的研发资源和管理注意力，品牌从"高端品质"降格为"大众廉价"。当市场向智能手机转型时，诺基亚已经习惯了低价竞争模式，无法做出有足够差异化的高端产品。
  warning_signs:
    - 品牌公司推出明显低于品牌定位的产品线
    - 产品线过度丰富但缺乏明星产品
    - 研发资源被分散到大量低端产品上
    - 品牌溢价能力持续下降
  bound_to:
    - "品牌评估"
    - "产品策略"
    - "差异化评估"
  tags: [counter-example, nokia, low-end-strategy, brand-dilution]

- id: ce22
  title: 靠低价获得的霸主地位是假象
  type: counter-example
  source_chapter: 第2节-17
  source_quote: |
    "当个不那么赚钱的霸主味道不太好哦。"
  failure_mode: |
    企业通过低价策略获得市场份额第一的位置，但利润微薄甚至亏损。规模虽大但盈利能力差，一旦竞争对手推出更好的产品（而非更便宜的），市场份额迅速崩溃。
  mechanism: |
    不赚钱的市场份额不构成竞争优势，反而需要大量资源维持。当市场技术变革时，缺乏利润积累的企业无力进行战略转型。惠普在PC和平板市场的"霸主"地位就是此模式。
  warning_signs:
    - 公司市场份额第一但利润率远低于同行
    - 管理层以市场份额而非利润为核心指标
    - 行业第一的地位是靠低价维持的
    - 行业技术变革时无力投入研发
  bound_to:
    - "商业模式评估"
    - "盈利能力评估"
    - "竞争优势评估"
  tags: [counter-example, market-leader, profitability, competitive-advantage]

- id: ce23
  title: 资本支出黑洞——重资产行业的陷阱
  type: counter-example
  source_chapter: 第2节-24
  source_quote: |
    "资本支出大的行业不容易出现好企业。""最差的一种公司是那种发展很快，并需要大量资本投入来维持其发展，但利润却少得可怜甚至根本赚不到钱的公司。"
  failure_mode: |
    重资产行业需要不断投入大量资本来维持运营和增长，但利润微薄。企业赚的钱必须重新投入设备更新和扩张，股东实际上永远看不到现金回报。
  mechanism: |
    重资产行业的资本需求导致两个问题：一是利润被持续再投资吞噬，自由现金流为零甚至为负；二是资产贬值和淘汰风险高，技术变革可能让整个工厂变废铁。航空公司、航运业、光伏组件都是典型。
  warning_signs:
    - 资本支出占经营现金流的比例持续高于50%
    - 利润增长需要几乎等量的资本投入
    - 设备和技术更新速度极快
    - 自由现金流长期为负
  bound_to:
    - "商业模式评估"
    - "自由现金流评估"
    - "资本效率评估"
  tags: [counter-example, capital-intensive, free-cash-flow, asset-heavy]

- id: ce24
  title: 用margin（杠杆）投资的风险
  type: counter-example
  source_chapter: 第7节-3
  source_quote: |
    "贷款和用margin，赚的时候快，赔的时候更快。常在河边走，哪能不湿鞋，湿一回鞋就湿一辈子，为什么要冒这个险呢？"
  failure_mode: |
    投资者使用杠杆（margin）来放大投资收益，在市场下跌时被迫平仓，即使持有的公司本身没有问题，也可能因暂时的价格波动而永久性亏损。
  mechanism: |
    杠杆放大了收益也放大了风险。市场短期波动可能触发强制平仓，导致投资者在最不该卖出的时候被迫卖出。巴菲特说的"人生只需富一次"就是警告不要因为贪心而冒失去一切的风险。
  warning_signs:
    - 使用融资账户进行投资
    - 借钱来买股票
    - 投资收益中包含利息成本
    - 在市场下跌时焦虑不安
  bound_to:
    - "风险控制"
    - "投资纪律"
    - "长期主义"
  tags: [counter-example, margin, leverage, risk-management]

- id: ce25
  title: 强势领导下的组织僵化
  type: counter-example
  source_chapter: 第3节-四
  source_quote: |
    "凡是员工见到领导就战战兢兢的公司，时间长了都会出问题的。因为这种公司员工大多都会慢慢变得没有担待，凡事希望交给上级去决定，效率慢慢会降低。"
  failure_mode: |
    在强势领导的管理下，员工不敢提出不同意见，不敢自主决策，所有事情都等领导拍板。组织效率低下，创新停滞，一旦强势领导不在或判断失误，公司迅速衰败。
  mechanism: |
    强势领导导致"一言堂"文化，员工为自保只做被吩咐的事。决策权高度集中使公司成为"一个人的公司"，规模越大决策瓶颈越严重。乔布斯式的强势虽然有效但不可持续，最终拖垮领导者。
  warning_signs:
    - 员工在领导面前不敢表达真实想法
    - 所有关键决策都由一人做出
    - 领导不在时公司运转明显受影响
    - 员工只执行不思考，缺乏主动性
  bound_to:
    - "管理层评估"
    - "企业文化评估"
    - "组织效率"
  tags: [counter-example, authoritarian-leadership, organizational-rigidity, innovation]

- id: ce26
  title: 聚焦份额目标而非产品本质
  type: counter-example
  source_chapter: 第7节
  source_quote: |
    "我们公司不会把追求干倒谁作为目标，也不会把市场份额、销售数量及排名作为我们的追求目标的。我们追求的就是改善用户体验，做出最好的产品。"
  failure_mode: |
    企业将市场份额、排名、销售数量作为核心目标，而非专注于做好产品。这种目标导向导致企业做出损害用户体验和品牌价值的决策（如向经销商压货、降低品质抢市场）。
  mechanism: |
    以份额为目标时，决策标准从"什么对用户最好"变成"什么能提升份额"。这导致向渠道压货、过度促销、推出不成熟产品等短视行为。这些行为短期内提升份额，长期损害品牌和用户信任。
  warning_signs:
    - 管理层公开宣布市场份额或排名目标
    - 为达标而向渠道压货
    - 以"行业第一"为主要宣传点
    - 追求规模增速而非利润率和用户满意度
  bound_to:
    - "产品评估"
    - "消费者导向"
    - "管理层评估"
  tags: [counter-example, market-share-obsession, consumer-orientation, short-termism]

- id: ce27
  title: 没有利润之上追求的企业难以长久
  type: counter-example
  source_chapter: 第1节
  source_quote: |
    "多数公司碰到问题时讨论的都是有没有钱赚的问题，而有利润之上追求的公司碰到问题时可能会先问一句，这是对的事情吗？这是应该赚的钱吗？其实差别很小，但20年后差别很大。"
  failure_mode: |
    企业没有超越利润的使命和追求，在遇到决策时只看"赚不赚钱"。这种思维导致企业在面对原则性问题时做出错误选择，短期看似合理，长期累积成致命问题。
  mechanism: |
    缺乏利润之上的追求意味着企业没有判断"该不该做"的标准。在短期诱惑面前（如赚快钱的机会、降低品质降低成本），没有原则约束的企业会选择眼前的利益。每个小选择的偏差累积20年，就是伟大公司和普通公司的差距。
  warning_signs:
    - 管理层从不讨论"这是不是对的事"
    - 决策标准只有ROI（投资回报率）
    - 企业没有明确的使命和价值观
    - 遇到原则性问题时优先考虑经济利益
  bound_to:
    - "企业文化评估"
    - "长期主义"
    - "价值观评估"
  tags: [counter-example, profit-driven, purpose, corporate-culture]

- id: ce28
  title: 产品品种过多的渠道灾难
  type: counter-example
  source_chapter: 第2节（苹果案例）
  source_quote: |
    "那时很多做游戏机的都喜欢做很多品种，最后下场都不太好。"
  failure_mode: |
    企业推出过多的产品品种，试图覆盖所有市场细分。产品线过长导致资源分散、库存积压、渠道压力巨大，每个产品都做不到极致，最终全线溃败。
  mechanism: |
    产品品种过多分散了研发资源，每个产品的投入都不足以做出差异化。渠道被迫承担大量库存，资金链承压。消费者面对过多选择反而困惑，品牌定位模糊。苹果的单一产品策略恰恰证明了"少即是多"。诺基亚一年出40个品种是反面教材。
  warning_signs:
    - 产品线持续扩张，品种数量远超竞争对手
    - 每个产品品类都有多个SKU但缺乏明星产品
    - 渠道库存持续攀升
    - 研发资源被分散到太多产品上
  bound_to:
    - "产品策略"
    - "差异化评估"
    - "渠道管理"
  tags: [counter-example, product-proliferation, focus, channel-pressure]

- id: ce29
  title: 卫哲事件——短视职业经理人的破坏力
  type: counter-example
  source_chapter: 第3节
  source_quote: |
    "看起来在上市公司的业绩的压力下，要坚持做对的事情不容易。从卫哲以前说的一些话来看，此人有点虚荣，犯这种错误恐怕也不是偶然。"
  failure_mode: |
    职业经理人在短期业绩压力下，对违背价值观的行为视而不见甚至默许，导致公司出现系统性诚信问题。短视的管理不仅造成直接经济损失，更严重破坏了企业文化。
  mechanism: |
    职业经理人关注季度业绩和个人声誉（"有点虚荣"），在利润和原则冲突时倾向于选择前者。这种行为如果在公司内部被容忍，会形成"业绩至上"的文化，诱发更多违反价值观的行为。
  warning_signs:
    - CEO过度关注短期市值和排名
    - 管理层对违规行为睁一只眼闭一只眼
    - 业绩压力下放宽合规标准
    - 企业文化宣导与实际行为脱节
  bound_to:
    - "管理层评估"
    - "企业文化评估"
    - "诚信评估"
  tags: [counter-example, professional-manager, integrity, short-termism]

- id: ce30
  title: 为分散风险而多元化的悖论
  type: counter-example
  source_chapter: 第6节-二
  source_quote: |
    "有很多公司在经历一段不错的发展后，为了分散风险，开始搞起了多元化，结果其中有些公司很快就不用再担心风险的问题了。"
  failure_mode: |
    企业在主业成功后，出于"分散风险"的考虑进入多个不相关领域。本意是降低单一业务的风险，但实际上因为每个新业务都缺乏竞争力，总体风险反而增加了。
  mechanism: |
    分散风险的多元化看似合理，但忽视了企业能力圈的局限。每个新领域都需要不同的核心能力、行业知识和企业文化，原有优势无法迁移。新业务不仅不能分散风险，反而消耗原有业务的资源和管理精力，导致"两个都做不好"。盛大从游戏向多个方向扩张就是反面教材。
  warning_signs:
    - 管理层以"分散风险"为多元化理由
    - 同时进入多个不相关行业
    - 新业务与原有用户群没有关联
    - "没有焦点的公司早晚会有麻烦"
  bound_to:
    - "聚焦原则"
    - "能力圈原则"
    - "多元化评估"
  tags: [counter-example, diversification, risk-paradox, focus]
```
