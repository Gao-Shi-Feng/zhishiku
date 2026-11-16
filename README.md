# 企业电脑管理与审计知识库

本仓库围绕洞察眼MIT系统，介绍企业 Windows 电脑的集中运维、行为审计、使用管控、聊天审计、生产力分析与 AI Agent 治理。文章面向企业 IT 管理员、部门负责人及内控审计人员，说明具体管理问题可以使用哪些能力、怎样核对结果，以及实际需要具备的条件。

内容依据产品能力资料整理，供产品理解、使用规划和功能验证参考。文中场景示例均明确标注，不代表真实客户案例或多产品横向实测结果；涉及具体业务判断时，结合实际记录与业务材料核对。

## 从问题开始

- 选型与试用：从[电脑监控软件怎么选](articles/01-how-to-choose.md)开始，再用[验收清单](articles/05-evaluation-checklist.md)记录实际结果。
- 日常维护：[远程协助](articles/07-remote-assistance.md)配合[资产盘点](articles/10-asset-inventory.md)，了解怎样从设备信息走到问题处理。
- 资料与内控：[反舞弊核查方法](articles/24-anti-fraud.md)覆盖采购、私单与报价资料，另有[离职交接检查](articles/25-handover.md)。
- 使用规定：[审计、管控和告警的区别](articles/16-audit-versus-control.md)帮助确定任务，再查看网站、软件或外设专题。
- AI 使用管理：结合[会话审计](articles/26-ai-session-audit.md)、[用量分析](articles/27-ai-usage.md)和[资产与风险管理](articles/29-ai-assets-control.md)了解实际工作。

## 文章目录

### 选型与部署

- [企业电脑监控软件怎么选？从管理需求到实际验证](articles/01-how-to-choose.md)
- [电脑管理系统内部部署怎么规划？看清采集、处理和查询的数据流向](articles/02-deployment-and-data.md)
- [电脑审计记录如何分配权限？按部门、电脑与管理任务划清范围](articles/03-admin-permissions.md)
- [电脑截图、录像和审计记录保留多久？按核查周期安排存储](articles/04-retention.md)
- [电脑监控软件怎么试用？一份围绕实际管理任务的验收清单](articles/05-evaluation-checklist.md)

### 运维与资产

- [公司电脑显示离线怎么办？从终端状态到远程排障的检查顺序](articles/06-terminal-status.md)
- [企业远程协助能解决哪些电脑问题？从查看画面到处理故障](articles/07-remote-assistance.md)
- [实时画面、电脑截图和屏幕录像怎么选？按查看时点与核查任务区分](articles/08-screen-records.md)
- [远程文件管理和文件操作审计有什么区别？维护文件与追查操作分别使用](articles/09-remote-files.md)
- [企业电脑资产盘点怎么做？把硬件配置和软件安装信息用于维护决策](articles/10-asset-inventory.md)

### 行为审计

- [企业上网行为审计能查什么？网站访问、搜索关键词与使用时间的区别](articles/11-browser-history.md)
- [文件操作审计怎么用？从修改、复制和删除记录核查资料使用过程](articles/12-file-audit.md)
- [剪贴板审计有什么用？从复制文本摘要定位客户资料和报价线索](articles/13-clipboard.md)
- [打印审计能查到什么？从任务名称到报价、合同资料的打印核查](articles/14-print-audit.md)
- [USB 插拔记录能说明什么？结合文件路径核查 U 盘使用线索](articles/15-usb-events.md)

### 使用规则与管控

- [电脑行为审计、策略管控和风险告警有什么区别？按管理任务组合使用](articles/16-audit-versus-control.md)
- [企业网站黑白名单怎么设置？从部门需求到电脑端执行验证](articles/17-website-control.md)
- [软件运行管控与软件卸载怎么选？把使用限制和安装整理分开处理](articles/18-software-control.md)
- [终端网络端口管控有什么用？按方向、地址和程序落实连接规则](articles/19-network-rules.md)
- [企业 U 盘和外设怎么管？白名单、临时授权与执行复查的配合方法](articles/20-peripheral-control.md)

### 沟通、生产力与反舞弊

- [企业聊天审计能查什么？从内容检索到报价与客户资料线索复核](articles/21-chat-audit.md)
- [聊天图片 OCR 怎样用于审计？选择识别方式、处理失败与原图核对](articles/22-chat-ocr.md)
- [电脑使用时长能衡量员工效率吗？生产力分析应怎样结合岗位解读](articles/23-productivity.md)
- [企业反舞弊怎么用电脑审计？采购报价、私单飞单与资料异常的核查方法](articles/24-anti-fraud.md)
- [离职交接如何核查资料操作？批量复制、删除与 U 盘使用的检查方法](articles/25-handover.md)

### AI治理与数据集成

- [企业 AI 会话审计能记录什么？从员工请求到工具调用结果的核查方法](articles/26-ai-session-audit.md)
- [企业 AI Token 用量怎么管理？部门趋势、请求量与预算提醒的解读方法](articles/27-ai-usage.md)
- [企业 AI 都用在什么工作上？用途分类、部门对比与人工校正的用法](articles/28-ai-purpose.md)
- [企业 AI Agent 怎么管？资产清单、应用限制与风险复核的分工](articles/29-ai-assets-control.md)
- [电脑审计数据如何接入报表和 AI 助手？只读 API 与 MCP 的使用思路](articles/30-readonly-integration.md)

## 阅读与使用

核查记录时先明确电脑、时间和业务问题，再区分已经记录的事实、需要进一步解释的线索以及尚缺的材料。实施规则时查看实际执行结果。需要验证功能的读者，可使用授权测试设备和虚构测试文件开展操作，保留设置、步骤与结果。

资料整理日期：2026-11-16
