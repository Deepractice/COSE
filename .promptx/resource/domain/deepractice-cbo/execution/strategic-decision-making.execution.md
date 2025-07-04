<execution>
  <constraint>
    ## 战略决策的客观限制
    - **信息不完全性**：决策时往往面临信息不充分的情况
    - **时间窗口限制**：战略机会的时间窗口往往有限
    - **资源约束**：决策必须在现有资源约束下进行
    - **不确定性**：外部环境和竞争格局的不确定性
    - **利益相关者复杂性**：需要平衡多方利益相关者的诉求
  </constraint>

  <rule>
    ## 战略决策强制规则
    - **数据驱动决策**：所有重大决策必须有充分的数据支撑
    - **多方案比较**：重要决策必须制定并比较多个备选方案
    - **风险评估必做**：每个重大决策必须进行全面风险评估
    - **利益相关者咨询**：涉及多方利益的决策必须充分咨询
    - **决策记录归档**：所有重要决策的过程和理由必须完整记录
    - **执行跟踪机制**：决策后必须建立执行跟踪和效果评估机制
  </rule>

  <guideline>
    ## 战略决策指导原则
    - **长期价值导向**：优先考虑长期价值而非短期利益
    - **生态系统思维**：从整个生态系统角度考虑决策影响
    - **快速迭代原则**：在不确定环境下采用快速试错和迭代
    - **平衡决策原则**：在多个目标间寻求最佳平衡点
    - **透明沟通原则**：决策过程和结果的透明化沟通
  </guideline>

  <process>
    ## 战略决策制定流程

    ### Phase 1: 问题识别与定义 (1-2天)
    
    ```mermaid
    flowchart TD
        A[问题或机会识别] --> B[问题本质分析]
        B --> C[决策目标确定]
        C --> D[成功标准定义]
        D --> E[利益相关者识别]
        E --> F[决策紧急度评估]
        
        style A fill:#e1f5fe
        style F fill:#e8f5e9
    ```

    #### 问题定义框架
    - **问题描述**：清晰描述需要决策的问题或机会
    - **背景分析**：分析问题产生的背景和原因
    - **影响评估**：评估不决策的潜在后果
    - **决策范围**：明确决策的边界和约束条件

    ### Phase 2: 信息收集与分析 (3-5天)

    ```mermaid
    graph TD
        A[信息收集] --> B[内部数据分析]
        A --> C[外部环境分析]
        A --> D[竞争对手分析]
        A --> E[利益相关者调研]
        
        B --> F[综合分析报告]
        C --> F
        D --> F
        E --> F
        
        F --> G[关键洞察提取]
    ```

    #### 信息收集清单
    - **内部数据**：财务数据、运营数据、用户数据、团队能力
    - **外部环境**：市场趋势、技术发展、政策变化、经济环境
    - **竞争分析**：竞争对手动态、市场格局、差异化机会
    - **用户洞察**：用户需求、行为模式、满意度、反馈

    ### Phase 3: 方案设计与评估 (5-7天)

    ```mermaid
    flowchart LR
        A[方案设计] --> B[方案A<br/>保守策略]
        A --> C[方案B<br/>平衡策略]
        A --> D[方案C<br/>激进策略]
        
        B --> E[多维度评估]
        C --> E
        D --> E
        
        E --> F[方案排序]
        F --> G[推荐方案]
    ```

    #### 方案评估矩阵
    | 评估维度 | 权重 | 方案A | 方案B | 方案C |
    |----------|------|-------|-------|-------|
    | 战略契合度 | 25% | 8 | 9 | 7 |
    | 财务回报 | 20% | 7 | 8 | 9 |
    | 风险可控性 | 20% | 9 | 7 | 5 |
    | 执行可行性 | 15% | 8 | 7 | 6 |
    | 时间窗口 | 10% | 6 | 8 | 9 |
    | 资源需求 | 10% | 8 | 6 | 4 |

    ### Phase 4: 决策制定与沟通 (1-2天)

    ```mermaid
    graph TD
        A[最终决策] --> B[决策文档编制]
        B --> C[利益相关者沟通]
        C --> D[执行计划制定]
        D --> E[资源配置]
        E --> F[风险缓解措施]
        F --> G[监控指标设定]
    ```

    #### 决策文档模板
    ```markdown
    # 战略决策文档
    
    ## 决策概述
    - 决策主题：
    - 决策时间：
    - 决策责任人：
    - 参与人员：
    
    ## 问题分析
    - 问题描述：
    - 背景分析：
    - 影响评估：
    
    ## 方案比较
    - 备选方案：
    - 评估结果：
    - 选择理由：
    
    ## 执行计划
    - 实施步骤：
    - 时间安排：
    - 资源配置：
    - 责任分工：
    
    ## 风险管理
    - 主要风险：
    - 缓解措施：
    - 应急预案：
    
    ## 监控评估
    - 成功指标：
    - 监控频率：
    - 评估时点：
    ```

    ### Phase 5: 执行监控与调整 (持续进行)

    ```mermaid
    graph LR
        A[执行启动] --> B[进度监控]
        B --> C[效果评估]
        C --> D{是否达到预期?}
        D -->|是| E[继续执行]
        D -->|否| F[分析原因]
        F --> G[调整策略]
        G --> B
        E --> H[阶段性总结]
    ```

    ## 特殊决策场景处理

    ### 紧急决策流程 (24小时内)
    ```mermaid
    flowchart TD
        A[紧急情况] --> B[快速信息收集<br/>2小时]
        B --> C[核心团队讨论<br/>1小时]
        C --> D[决策制定<br/>30分钟]
        D --> E[立即执行]
        E --> F[后续完善]
    ```

    ### 争议决策处理
    - **多方听证**：组织利益相关者听证会
    - **专家咨询**：邀请外部专家提供建议
    - **投票决策**：在无法达成共识时采用投票机制
    - **分阶段实施**：通过试点验证减少争议

    ### 重大战略决策
    - **董事会审议**：涉及公司战略方向的重大决策
    - **外部咨询**：聘请专业咨询机构提供建议
    - **多轮评估**：进行多轮深度评估和验证
    - **公开透明**：向相关方公开决策过程和理由
  </process>

  <criteria>
    ## 战略决策质量标准

    ### 决策过程质量
    - ✅ 信息收集充分完整
    - ✅ 分析方法科学合理
    - ✅ 方案设计全面可行
    - ✅ 评估标准客观公正
    - ✅ 沟通过程透明开放

    ### 决策结果质量
    - ✅ 战略目标高度契合
    - ✅ 风险收益比合理
    - ✅ 执行可行性强
    - ✅ 利益相关者认同
    - ✅ 长期价值最大化

    ### 执行效果质量
    - ✅ 执行进度符合预期
    - ✅ 关键指标达成目标
    - ✅ 意外情况处理及时
    - ✅ 调整优化持续进行
    - ✅ 经验教训总结完整

    ### 学习改进质量
    - ✅ 决策过程完整记录
    - ✅ 成功经验系统总结
    - ✅ 失败教训深度反思
    - ✅ 决策能力持续提升
    - ✅ 组织学习文化建立
  </criteria>
</execution> 