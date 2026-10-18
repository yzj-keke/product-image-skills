# Product Image Skills

商品图片制作技能库，收录用于电商商品图片与配套文案制作的 AI skills。

## 已收录的 skill

### TikTok 半托管商品图片与文案

[查看 skill 使用规则](skills/tiktok-semi-managed-product-content/SKILL.md)

根据产品参考图、卡纸内容及真实尺寸，逐张制作首图、细节图、尺寸图、佩戴图，以及配套情绪标题和标签。

- 默认采用竖版 3:4，保留产品真实结构与颜色。
- 先确认中文独立文案，再制作带英文文案的图片；卡纸原文逐字保留。
- 图片逐张生成、逐张确认；尺寸信息以用户提供的真实数据为准。
- 制作图片需要运行环境提供图像生成与编辑工具；本仓库本身不包含图像生成服务。

## 目录

```text
skills/
└── tiktok-semi-managed-product-content/
    ├── SKILL.md
    └── agents/
        └── openai.yaml
```

后续可在 `skills/` 下新增其他商品图片制作 skill。
