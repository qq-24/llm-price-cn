# 数据来源

所有链接均已按 2026-08-27 核对。价格快照如有出入，以官方页面为准。

| 渠道 | 官方页面 | 备注 |
| :--- | :--- | :--- |
| DeepSeek 官方直充 | <https://api-docs.deepseek.com/zh-cn/quick_start/pricing> | 模型与价格页：V4-Flash / V4-Pro 空闲/高峰单价表 |
| 智谱 GLM Coding Plan | <https://docs.bigmodel.cn/cn/coding-plan/overview> | 套餐概览：Lite/Pro/Max 周限额、GLM-5.3-Flash 抵扣系数、非高峰 5 折说明 |
| 智谱 GLM-5.3-Flash 模型 | <https://docs.bigmodel.cn/cn/guide/models/vlm/glm-5.3-flash> | 模型页；订阅入口 <https://www.bigmodel.cn/glm-coding> |
| 智谱官方直充（按量） | <https://open.bigmodel.cn/pricing> | API 定价页（需登录） |
| OpenCode Go 订阅 | <https://opencode.ai/docs/zh-cn/go> | $10/月、$15 初始额度、5h/周/月限额、各模型每 1M tokens 价格表 |
| 阿里云百炼（Qwen 3.8 Flash） | <https://help.aliyun.com/zh/model-studio/models> | 模型大全页；qwen3.8-flash 单模型详情见模型广场 |
| 阿里云百炼模型广场 | <https://bailian.console.aliyun.com/cn-beijing/?tab=model#/model-market/all> | 单模型定价需登录控制台查看 |

## 计算参数备注

- **智谱 Coding Plan**：GLM-5.3-Flash 抵扣系数 输入 2.3 / 缓存命中 0.56 / 输出 8；非高峰（周一至五 14:00-18:00 以外，含周末）按 50% 积分消耗。Lite/Pro/Max 周积分分别为 10,000 / 60,000 / 140,000。
- **DeepSeek 官方直充**：高峰时段为周一至五 9:00-12:00、14:00-18:00（北京时间），其余为空闲，空闲价格为高峰一半。
- **OpenCode Go**：限制为每 5 小时 $12 / 每周 $30 / 每月 $60（以美元价值计）；含 $15 初始额度。DeepSeek V4 Flash Off-Peak $0.22/$0.66/$0.007（输入/输出/缓存）。
- **GLM 官方直充 5 折**：限时优惠，有效期约两周，自 2026-08-26 起，到期后恢复原价。