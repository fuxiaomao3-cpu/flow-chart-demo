```mermaid
graph TD
    A[新南门站多模式换乘系统] --> B[旅游散客流 主导性]
    A --> C[本地通勤/生活客流 基础性]
    A --> D[休闲购物客流 补充性]

    B --> B1[换乘特征]
    B1a["瞬时集中"]
    B1b["大件行李"]
    B1 --> B1a
    B1 --> B1b
    
    B --> B2[关键屏障]
    B2a["高峰时段设施超载"]
    B2 --> B2a

    B --> B3[瞬时需求冲击]
    B3a["大巴泊位"]
    B3b["单车"]
    B3c["即停即走区"]
    B3 --> B3a
    B3 --> B3b
    B3 --> B3c
    
    C --> C1[换乘特征]
    C1a["规范游移"]
    C1b["高效便捷"]
    C1 --> C1a
    C1 --> C1b
    
    C --> C2[关键屏障]
    C2a["被旅游客流挤压"]
    C2 --> C2a
    
    C --> C3[空间资源竞争]
    C3a["入口"]
    C3b["通道"]
    C3c["公交"]
    C3 --> C3a
    C3 --> C3b
    C3 --> C3c
    
    D --> D1[换乘特征]
    D1a["夜间活跃"]
    D1b["灵活随意"]
    D1 --> D1a
    D1 --> D1b
    
    D --> D2[关键屏障]
    D2a["夜间接驳"]
    D2b["服务不足"]
    D2 --> D2a
    D2 --> D2b
    
    D --> D3[时间匹配错位]
    D3a["公交收班早"]
    D3b["出租车少"]
    D3 --> D3a
    D3 --> D3b

    class A,B,C,D box;
    class B1,B2,B3,C1,C2,C3,D1,D2,D3 info;
    class box fill:#f1f1f1,stroke:#4C4C4C;
    class info fill:#E6F3FF,stroke:#B0B0B0;


# flow-chart-demo
展示mermaid图形
