- id: v01
  title: 市场失败律先验
  type: mental-model
  source_candidates: [f01, f02, p01, p02, g01, g04, g05, ce01, ce02]
  V1_cross_domain:
    passed: true
    evidence:
      - "第1章: 新可乐、水晶百事、迪士尼和谷歌产品失败案例说明强资源仍不能免疫失败。"
      - "第1章: 作者在谷歌访谈失败项目, 将失败归因到启动、运营和前提。"
      - "结语: 作者将市场失败律作为六个硬事实之首再次复述。"
  V2_predictive_power:
    passed: true
    novel_question: "一个大厂有强工程团队和成熟渠道, 是否可以跳过早期市场验证直接开发 AI 硬件?"
    derived_answer: |
      不能。市场失败律把失败设为默认先验, 强执行只能提高交付质量, 不能证明市场前提成立。团队仍需先收集能抵消负先验的 YODA。
  V3_exclusivity:
    passed: true
    why_not_common: |
      常识会说"创业有风险"; 作者的独特之处是把失败视为默认基线, 并指出即使执行到位也不能避免前提失败。
  outcome: 进入阶段 2

- id: v02
  title: 区分正确的它与错误的它
  type: decision-framework
  source_candidates: [f03, f04, f21, f22, p26, g02, g03, g04, g05, ce02]
  V1_cross_domain:
    passed: true
    evidence:
      - "第2章: 作者定义正确的它和错误的它, 并提出先构建正确的它。"
      - "第1章: FLOP 访谈把启动、运营、前提失败分开。"
      - "结语: 七步流程最终落到争取、放弃、调整三个行动分支。"
  V2_predictive_power:
    passed: true
    novel_question: "一个产品 beta 版留存低, 团队应该先加功能还是重做市场假说?"
    derived_answer: |
      先诊断失败类型。如果问题是启动或运营, 可以改善触达或体验; 如果目标用户根本不愿投入切身利益, 就是前提失败, 应调整或放弃创意而非继续堆功能。
  V3_exclusivity:
    passed: true
    why_not_common: |
      常识会把失败归因于执行不足; 本框架要求先判断是不是"即使执行到位也会失败"的错误前提。
  outcome: 进入阶段 2

- id: v03
  title: 逃离空想之地证据
  type: reasoning-method
  source_candidates: [f05, f06, p03, p04, p05, p07, p08, g06, g07, g09, g10, ce03, ce04, ce05, ce06, ce09, ce10, ce18]
  V1_cross_domain:
    passed: true
    evidence:
      - "第2-3章: LadyLike、Webvan 和谷歌早期判断分别展示假阳性与假阴性。"
      - "第3章: OPD 与意见被定义为不能替代当前创意的一手数据。"
      - "结语: 作者再次强调数据胜过意见, 需要收集自己的数据 YODA。"
  V2_predictive_power:
    passed: true
    novel_question: "用户访谈里 80% 受访者说愿意试用新功能, 这是否足以进入开发?"
    derived_answer: |
      不足以。访谈表态仍可能处在空想之地, 只能作为线索。下一步应设计让用户付出行为代价的测试, 例如预约、付款、导入数据或邀请同事。
  V3_exclusivity:
    passed: true
    why_not_common: |
      常识会说"多做调研"; 作者反而提醒调研、专家意见和二手数据可能像意见一样误导, 必须逃向真实市场行为。
  outcome: 进入阶段 2

- id: v04
  title: 用 MEH 明确市场参与前提
  type: framework
  source_candidates: [f07, p06, g11, g12, ce11]
  V1_cross_domain:
    passed: true
    evidence:
      - "第4章: 作者用廉价寿司、Webvan、霍华德鸭和奈飞示范 MEH。"
      - "第8章: BusU 案例先写市场参与假说再进入 XYZ 和试验。"
      - "结语: 七步流程把确定市场参与假说列为第二步。"
  V2_predictive_power:
    passed: true
    novel_question: "团队说'我们要做一款更好的知识管理工具', 下一步怎么处理?"
    derived_answer: |
      先写 MEH: 哪类人会在什么场景下以何种方式参与这个工具, 是了解、导入资料、付费、日活还是团队协作。没有 MEH 就无法判断该测什么。
  V3_exclusivity:
    passed: true
    why_not_common: |
      常识会要求写目标用户或价值主张; MEH 特别聚焦市场将如何与创意互动, 是后续 XYZ 和预型的桥。
  outcome: 进入阶段 2

- id: v05
  title: XYZ 假说去模糊器
  type: reasoning-method
  source_candidates: [f08, p11, p12, g13, g14]
  V1_cross_domain:
    passed: true
    evidence:
      - "第4章: 污染监测器、洗衣服务、狗用啤酒等多个例子被改写为 XYZ。"
      - "第8章: BusU 创意被合并并转写成 XYZ 假说。"
      - "结语: 作者将 MEH 转为'至少 X% 的 Y 会 Z'列入总流程。"
  V2_predictive_power:
    passed: true
    novel_question: "有人说'很多家长会喜欢 AI 家教', 如何变成可测试判断?"
    derived_answer: |
      改写为: 至少 X% 的 Y 会 Z, 例如'至少 8% 的上海初中生家长会为一次 99 元 AI 数学诊断课付款'。这样团队可以争论 X、Y、Z 并设计试验。
  V3_exclusivity:
    passed: true
    why_not_common: |
      常识会说"目标要量化"; XYZ 独特在于固定三元结构, 同时逼出目标比例、目标市场和可观察行为。
  outcome: 进入阶段 2

- id: v06
  title: 将 XYZ 缩进为可测试 xyz
  type: reasoning-method
  source_candidates: [f09, p13, p14, g15, g16]
  V1_cross_domain:
    passed: true
    evidence:
      - "第4章: 污染监测器从全球污染城市缩进到城市 A 一所幼儿园家长。"
      - "第5章: Fold4U 从大市场缩进到伦尼投币洗衣店顾客。"
      - "第8章: BusU 从湾区通勤学习需求缩进到具体邮件名单和通勤人群。"
  V2_predictive_power:
    passed: true
    novel_question: "想验证全国职场人是否愿意买 AI 简历教练, 但预算只有 500 元怎么办?"
    derived_answer: |
      不测全国市场。缩进为一个代表性且可触达的 y, 如某求职社群的应届生; Z 缩成一次低价诊断付款或预约; 时间缩成一周内完成。
  V3_exclusivity:
    passed: true
    why_not_common: |
      常识会说"先小范围测试"; 作者给出从范围、空间、时间缩进且保持代表性的具体推理规则。
  outcome: 进入阶段 2

- id: v07
  title: 设计预型试验收集 YODA
  type: decision-framework
  source_candidates: [f10, f11, f12, p15, p16, g17, g18, g19, ce12]
  V1_cross_domain:
    passed: true
    evidence:
      - "第5章: IBM、Fold4U、PalmPilot、假门、CarsDirect 等案例展示不同预型。"
      - "第5章: 作者明确区分预型问'是否应该构建', 原型问'能否构建'。"
      - "结语: 使用预型技术运行试验并收集 YODA 是总流程第五步。"
  V2_predictive_power:
    passed: true
    novel_question: "尚未开发 AI 会议秘书, 如何知道用户是否会依赖它?"
    derived_answer: |
      先做预型: 用人工整理会议纪要或半自动流程伪装成服务, 要求目标用户付费、上传真实会议或在团队内试用, 以观察真实行为。
  V3_exclusivity:
    passed: true
    why_not_common: |
      常识会建议做 MVP; 作者区分预型和原型, 主张在构建能力前先验证是否应该构建。
  outcome: 进入阶段 2

- id: v08
  title: 按创意形态选择预型技术
  type: decision-framework
  source_candidates: [g20, g21, g22, g23, g24, c07, c08, c09, c10, c11, c12, c13, c15, c16, c17, c18, c19]
  V1_cross_domain:
    passed: true
    evidence:
      - "第5章: 土耳其机器人、匹诺曹、假门、假面、YouTube、潜入者、改标签等技术分别对应不同创意形态。"
      - "第5章: IBM、PalmPilot、CarsDirect、Walhub 和隔日寿司展示从软件到硬件到零售的跨场景应用。"
      - "结语: 作者鼓励修改、调适和组合基础预型技术。"
  V2_predictive_power:
    passed: true
    novel_question: "一个线下新食品、一款纯软件工具和一本书分别应优先选什么预型?"
    derived_answer: |
      线下食品可用改标签或潜入者; 软件工具可用假门、假面或土耳其机器人; 书可用假门页面、预售或连载。选择依据是最低成本地产生带切身利益的行为。
  V3_exclusivity:
    passed: true
    why_not_common: |
      常识只会泛泛说"做测试"; 作者给出一组命名技术, 并把技术选择绑定到创意形态和 YODA 类型。
  outcome: 进入阶段 2

- id: v09
  title: 用切身利益卡尺校准证据强度
  type: decision-framework
  source_candidates: [f13, p09, p10, p17, g08, g25, ce07, ce13]
  V1_cross_domain:
    passed: true
    evidence:
      - "第6章: Tortell-o-matic 和团队 A/B 示例展示不同切身利益强度。"
      - "第5章: 谷歌眼镜案例说明浏览、点赞不等于长期需求, 付款和到场更强但仍需追踪。"
      - "结语: 切身利益卡尺被列为分析 YODA 的核心工具。"
  V2_predictive_power:
    passed: true
    novel_question: "落地页有 2000 次浏览、300 个点赞、20 个邮箱、3 个订金, 哪个最该影响决策?"
    derived_answer: |
      按切身利益排序: 订金最强, 有效邮箱次之, 点赞和浏览接近零。决策应更多依赖用户付出的真实成本, 而不是注意力指标。
  V3_exclusivity:
    passed: true
    why_not_common: |
      常识知道付款比点赞强; 卡尺的独特性在于把不同承诺量化校准, 并明确无切身利益不能算合格 YODA。
  outcome: 进入阶段 2

- id: v10
  title: 用 TRI 计量仪综合多次试验
  type: decision-framework
  source_candidates: [f14, f15, p23, p24, p25, g26, ce08, ce14, ce15]
  V1_cross_domain:
    passed: true
    evidence:
      - "第6章: 隔日寿司案例将试验结果映射到 TRI 计量仪。"
      - "第8章: BusU 多轮 YODA 和商业模型调整展示多箭头判断。"
      - "结语: TRI 被列为将 YODA 转化为争取、放弃或调整的核心工具。"
  V2_predictive_power:
    passed: true
    novel_question: "第一次预售结果很好, 是否可以立刻辞职创业?"
    derived_answer: |
      不应只看一次试验。把结果映射到 TRI 后, 还要用不同样本、不同 xyz 和更强切身利益再射几箭, 并按投资风险决定证据数量。
  V3_exclusivity:
    passed: true
    why_not_common: |
      常识会说"多测几次"; TRI 独特在于把市场失败律负先验、试验强度和多次证据方向放到同一决策仪表盘。
  outcome: 进入阶段 2

- id: v11
  title: 最小化数据距离、数据小时、数据美元
  type: decision-framework
  source_candidates: [f16, f17, f18, f19, p18, p19, p20, g27, ce16, ce17]
  V1_cross_domain:
    passed: true
    evidence:
      - "第7章: 全球化策划、本地化测试用 DTD 缩短到市场的距离。"
      - "第7章: 现在测试胜过以后测试用 HTD 约束拖延。"
      - "第7章: 便宜、更便宜、最便宜用数据美元约束试验成本。"
  V2_predictive_power:
    passed: true
    novel_question: "有三个试验方案: 全国广告、行业大会展台、已有社群预售, 应先选哪个?"
    derived_answer: |
      比较 DTD、HTD、$TD。若已有社群仍代表目标市场且能快速低成本收集切身利益, 应优先选它, 而不是更宏大但更远更慢更贵的方案。
  V3_exclusivity:
    passed: true
    why_not_common: |
      常识会说"低成本验证"; 作者把低成本拆成距离、时间和金钱三种可比较指标, 可直接指导试验排序。
  outcome: 进入阶段 2

- id: v12
  title: 先调整再翻转, 再谈放弃
  type: decision-framework
  source_candidates: [f20, p21, p22, p27, p28, g28, c21, c22, c23]
  V1_cross_domain:
    passed: true
    evidence:
      - "第7章: 作者提出不要被最初糟糕 YODA 过早打击, 先调整再翻转。"
      - "第8章: BusU 根据多轮 YODA 调整课程形式、价格和商业模型。"
      - "结语: 最终行动分支包括争取、放弃和调整, 并补充创意也要适合自己和世界。"
  V2_predictive_power:
    passed: true
    novel_question: "第一次预型显示用户不愿每月订阅, 是否说明创意该死?"
    derived_answer: |
      不一定。先看用户对哪个部分有反应, 微调价格、交付、目标人群或使用场景; 多轮调整仍无法产生强 YODA, 再翻转关键假说或放弃。
  V3_exclusivity:
    passed: true
    why_not_common: |
      常识在坏数据后容易二选一: 硬扛或放弃。作者的独特顺序是先小微调, 再关键翻转, 最后才放弃。
  outcome: 进入阶段 2
