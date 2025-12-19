```mermaid
graph TD
    A[新南门站多模式换乘系统] --> B[旅游散客流 主导性]
    A --> C[本地通勤/生活客流 基础性]
    A --> D[休闲购物客流 补充性]

    B --> B1[换乘特征|“瞬时集中·大件行李”]
    B1 --> B2[关键屏障|高峰时段设施超载]
    B2 --> B3[瞬时需求冲击|大巴泊位/单车/即停即走区]
    
    C --> C1[换乘特征|“规范游移·高效便捷”]
    C1 --> C2[关键屏障|被旅游客流挤压]
    C2 --> C3[空间资源竞争|入口/通道/公交]
    
    D --> D1[换乘特征|“夜间活跃·灵活随意”]
    D1 --> D2[关键屏障|夜间接驳·服务不足]
    D2 --> D3[时间匹配错位|公交收班早/出租车少]

    class A,B,C,D box;
    class B1,B2,B3,C1,C2,C3,D1,D2,D3 info;
    class box fill:#f1f1f1,stroke:#4C4C4C;
    class info fill:#E6F3FF,stroke:#B0B0B0;

# flow-chart-demo
展示mermaid图形
