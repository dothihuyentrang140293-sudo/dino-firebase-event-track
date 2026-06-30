# Dino English V1.3.0 · Firebase 埋点验收清单

基于《Dino English V1.3.0 数据埋点协议 V0.21》整理的交互式验收清单，供验收人员逐项打勾、标记「已完成 / 未完成」并填写问题描述，便于技术按问题跟踪修复。

## 在线访问

启用 GitHub Pages 后访问：`https://<用户名>.github.io/dino-firebase-event-track/`

## 功能

- 覆盖公共属性、用户属性，以及 14 个业务事件（first_open、button_click、step_submitted、signup/login_result、teacher_selected/changed、class_lesson_start/end、trial_lesson_complete、class_stage_progress、class_answer_submit、dino_assistant_progress、subscription_checkout_start/purchase_result）。
- 每个事件含「上报时机 / 行为校验 / 逐属性（必填·枚举·隐私）」检查项。
- 每行可选状态（未测 / 已完成 / 未完成 / 不适用）+ 问题描述输入框。
- 顶部进度统计、按状态筛选、自动保存（localStorage，按「端」分别保存）。
- 支持导出 CSV / JSON、导入 JSON、清空。

## 说明

- 纯静态单文件（`index.html`），无后端、无外部依赖，所有数据仅存于使用者本地浏览器。
- 不包含任何真实业务数据或密钥，仅为验收模板。
