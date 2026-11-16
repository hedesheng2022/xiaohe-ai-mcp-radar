# 数据字段

| 字段 | 含义 |
| --- | --- |
| `rank` | 当前热度顺序，从 1 开始 |
| `slug` | 小贺 AI 详情页稳定标识 |
| `repository` | 可识别时的 GitHub `owner/repo` |
| `source_url` | 上游公开来源 |
| `directory_url` | 对应中文资料页 |
| `stars` | 采集时的 GitHub Stars 快照 |
| `star_delta_7d` | 有足够历史时的 7 日 Stars 增量 |
| `heat_score` | 用于目录排序的热度分 |
| `metadata_quality_score` | 公开元数据完整度，不是安全分 |
| `official_registry` | 是否来自 Official MCP Registry |
| `verification_level` | 本站实际完成的验证层级 |

时间和数值都是采集快照，可能随上游变化。引用时请同时保留 `metadata.captured_at`。
