# 🔐 Sec Toolkit — 67 款单文件离线安全工具

纯前端、零依赖、离线可用的网络安全工具合集：每款工具一个独立仓库，双击 `index.html` 即用，数据不出本机。

- 🚀 单文件即开即用，可整体拷贝到 U 盘
- 🔒 所有计算在本地浏览器完成，无任何网络请求
- 🎨 暗色玻璃拟态现代界面，响应式布局
- 📚 每个仓库含 `index.html` + `README.md` + `使用说明.md` + `MIT LICENSE`

## 工具导航

### 🔐 密码学与编码（6 款）

1. [密码强度检测与生成套件](https://github.com/sheyunyang/password-strength-suite) — 评估任意密码的强度与破解时间，生成符合策略的强随机密码，并量化密钥随机性。
2. [哈希计算与类型识别](https://github.com/sheyunyang/hash-calculator-id) — 计算文本与文件的 SHA 摘要，识别未知哈希的算法类型，辅助泄露数据与完整性分析。
3. [编码解码工具箱](https://github.com/sheyunyang/codec-toolbox) — Base64 / URL / 十六进制 / 时间戳 / IP 混淆格式互转，排查乱码与编码痕迹。
4. [文件加密与本地密码本](https://github.com/sheyunyang/file-encrypt-vault) — AES-256-GCM 本地加密文件；主密码派生密钥的加密密码本，安全保存账号记录。
5. [JWT与动态口令解析](https://github.com/sheyunyang/jwt-totp-parser) — 解析 JWT 令牌结构与风险；演示 TOTP 双因子算法，辅助认证排障。
6. [古典密码与隐写实验室](https://github.com/sheyunyang/classic-crypto-stego-lab) — 凯撒/摩斯加解密、零宽字符隐写，用于密码学教学与 CTF 入门。

### 🌐 网络分析（6 款）

7. [子网与IP计算工具](https://github.com/sheyunyang/subnet-ip-calculator) — 子网划分、IP 合法性校验、公网私网判别、CIDR 包含关系核查，网络规划与防火墙白名单审核必备。
8. [端口协议与状态码速查](https://github.com/sheyunyang/ports-protocols-reference) — 80+ 常用端口、14 种 DNS 记录、HTTP 状态码的可搜索速查数据库。
9. [网络诊断与扫描助手](https://github.com/sheyunyang/network-diagnostics-assistant) — 按症状生成 Windows/Linux 诊断命令；构建授权扫描与 Wireshark 过滤器表达式。
10. [HTTP请求与设备识别](https://github.com/sheyunyang/http-request-device-fingerprint) — 解析原始 HTTP 请求与 User-Agent，识别爬虫、脚本与敏感字段泄露。
11. [无线与路由器安全](https://github.com/sheyunyang/wireless-router-security) — 家庭/办公 Wi-Fi 配置评分，路由器十步加固，堵住最常见的无线网络缺口。
12. [TLS与邮件域名安全](https://github.com/sheyunyang/tls-email-domain-security) — TLS 配置基线核查；生成 SPF/DKIM/DMARC 记录防邮件域名伪造。

### 🕸️ Web安全（4 款）

13. [HTTP安全头工具](https://github.com/sheyunyang/http-security-headers) — 粘贴响应头自动评分并列出缺失项，一键生成 Nginx/Apache/IIS 修复配置；Cookie 安全属性分析。
14. [Web漏洞原理实验室](https://github.com/sheyunyang/web-vulnerability-lab) — SQL 注入、CSRF、CORS、开放重定向的交互式原理演示，开发与培训两用。
15. [Web应用上线自检](https://github.com/sheyunyang/webapp-go-live-check) — OWASP Top 10 自查、服务器基线核查、敏感路径暴露检查，发布前的安全闸门。
16. [API密钥安全](https://github.com/sheyunyang/api-key-security) — 识别 AWS/GitHub/OpenAI 等常见密钥格式，评估泄露风险并给出处置流程。

### 🎭 钓鱼与社会工程防范（5 款）

17. [钓鱼链接与二维码检测](https://github.com/sheyunyang/phishing-url-qr-checker) — 12 项启发式特征静态分析可疑链接与二维码内容，全程不访问目标。
18. [钓鱼邮件与邮件头分析](https://github.com/sheyunyang/phishing-email-analyzer) — 解析邮件原文与邮件头，识别域名伪造、认证失败与话术特征并量化可疑度。
19. [短信与语音诈骗识别](https://github.com/sheyunyang/smishing-vishing-detector) — 短信 8 项特征评分、五大语音诈骗剧本拆解，'挂断+回拨'黄金法则。
20. [钓鱼防范互动测验](https://github.com/sheyunyang/phishing-awareness-quiz) — 10 道真实场景钓鱼识别题，即时判分讲解，适合全员安全意识考核。
21. [弱密码与双因子教育](https://github.com/sheyunyang/password-2fa-education) — 弱口令破解时间对照演示与 2FA 方案选型参谋，密码安全宣传配套。

### 🧮 漏洞与风险管理（5 款）

22. [CVSS与风险矩阵](https://github.com/sheyunyang/cvss-risk-matrix) — 完整 CVSS 3.1 计算器与 5×5 风险矩阵定级，输出处置策略。
23. [漏洞优先级与修复督办](https://github.com/sheyunyang/vulnerability-prioritization-tracker) — 漏洞清单按分数排序分级，按 CVSS 自动计算修复 SLA 并提示超期。
24. [补丁与资产管理](https://github.com/sheyunyang/patch-asset-management) — 补丁状态跟踪看板 + IT 资产台账登记导出，安全管理第一步。
25. [威胁建模与SBOM](https://github.com/sheyunyang/threat-modeling-sbom) — STRIDE 威胁建模记录 + 软件成分清单生成导出，设计阶段的安全左移。
26. [泄露成本与漏洞报告](https://github.com/sheyunyang/breach-cost-report) — 泄露损失量化估算（预算论证用）+ 结构化漏洞报告一键生成。

### 📊 日志监控与威胁检测（4 款）

27. [日志分析工作台](https://github.com/sheyunyang/log-analysis-workbench) — 粘贴任意日志自动统计并高亮攻击特征行；grep 场景速查；SIEM 查询组装。
28. [IOC提取与标准化](https://github.com/sheyunyang/ioc-extraction-normalizer) — 从报告/告警中提取 IP、域名、哈希、URL 并导出标准化 JSON 清单。
29. [Windows事件与告警分诊](https://github.com/sheyunyang/windows-event-triage) — 20 个高频事件 ID 速查 + 告警三要素 P1-P3 分诊与处置建议。
30. [监控基线与指标看板](https://github.com/sheyunyang/monitoring-baseline-dashboard) — 2σ/3σ 告警阈值计算 + 月度安全指标趋势看板，例会汇报可用。

### 🦠 恶意软件分析（4 款）

31. [样本行为与字符串分析](https://github.com/sheyunyang/malware-behavior-strings) — 从样本转储提取 URL/IP/可疑 API，按 MITRE 战术对行为特征评分。
32. [YARA规则与加壳识别](https://github.com/sheyunyang/yara-packer-detector) — 特征字符串生成 YARA 规则框架；常见加壳器与混淆特征速查。
33. [持久化机制排查](https://github.com/sheyunyang/persistence-mechanism-check) — Windows/Linux 常见持久化位置逐项排查清单，揪出隐藏后门。
34. [沙箱分析准备](https://github.com/sheyunyang/sandbox-analysis-prep) — 样本进沙箱前的隔离、快照、网络模拟与观察要点完整清单。

### 🚨 应急响应（6 款）

35. [应急决策与排查命令](https://github.com/sheyunyang/ir-decision-runbook) — 交互式应急决策树 + Windows/Linux 主机排查命令生成，深夜报警不再慌。
36. [事件时间线与证据链](https://github.com/sheyunyang/incident-timeline-evidence-chain) — 事件时间线自动排序、证据保管链登记、证据文件哈希完整性校验。
37. [复盘报告与钓鱼响应卡](https://github.com/sheyunyang/postmortem-phishing-response) — Post-Mortem 复盘报告生成 + 钓鱼事件三档分钟级处置卡。
38. [应急通讯录与值班](https://github.com/sheyunyang/ir-contact-duty-roster) — 应急联系人与值班排班登记，打印贴墙断网断电可用。
39. [备份容灾与RTO计算](https://github.com/sheyunyang/backup-dr-rto-calculator) — 3-2-1 备份核查 + RTO/RPO 容灾等级与年期望损失推算。
40. [响应SLA计时器](https://github.com/sheyunyang/incident-sla-timer) — 事件响应各阶段时限实时倒计时，超期高亮提醒。

### 🎯 渗透测试管理（4 款）

41. [授权与交战规则](https://github.com/sheyunyang/authorization-rules-of-engagement) — 生成渗透测试授权书要点与 ROE 交战规则确认表，测试合规底线。
42. [侦察计划与合规字典](https://github.com/sheyunyang/recon-planning-compliance) — 按测试类型生成侦察步骤清单；授权环境下的口令策略审计字典。
43. [发现记录与渗透报告](https://github.com/sheyunyang/findings-pentest-report) — 测试发现实时分级记录 + 渗透测试报告骨架一键生成。
44. [AD域安全检查](https://github.com/sheyunyang/active-directory-security-check) — Active Directory 十项核心安全检查，域环境的致命短板排查。

### 🛡️ 数据保护与隐私（3 款）

45. [数据脱敏与外发扫描](https://github.com/sheyunyang/data-masking-dlp-scan) — 敏感字段一键打码、外发内容扫描评级、外发审批 8 步检查单。
46. [数据分类分级与留存](https://github.com/sheyunyang/data-classification-retention) — 数据四级分类自动生成管控要求；法定留存期限速查。
47. [社交隐私与USB安全](https://github.com/sheyunyang/social-privacy-usb-security) — 社交媒体隐私收紧清单 + 移动介质管理核查，防社工与摆渡攻击。

### 💻 终端与移动安全（2 款）

48. [移动设备安全套件](https://github.com/sheyunyang/mobile-device-security) — 手机丢失黄金一小时处置流程 + App 权限风险画像。
49. [公共Wi-Fi安全指引](https://github.com/sheyunyang/public-wifi-safety-guide) — evil twin 识别与六项防护动作，出差出行场景适用。

### ☁️ 云与工控安全（4 款）

50. [云存储与IAM检查](https://github.com/sheyunyang/cloud-storage-iam-check) — S3/OSS 桶公开访问十项核查 + IAM 最小权限审计，云安全的头号防线。
51. [容器与SaaS安全](https://github.com/sheyunyang/container-saas-security) — K8s 集群十项基线 + SaaS 应用准入评估清单。
52. [IoT设备入网安检](https://github.com/sheyunyang/iot-device-onboarding-check) — 摄像头/智能设备入网前 8 项检查，防止成为内网跳板。
53. [工控协议与网络分区](https://github.com/sheyunyang/ics-protocol-network-segmentation) — 18 种工控协议速查 + Purdue 五层分区模型参考。

### 📜 合规与审计（5 款）

54. [等保自查工具](https://github.com/sheyunyang/classified-protection-check) — 等保二级/三级 × 六个安全域差距自查，输出整改优先级。
55. [ISO27001控制速查](https://github.com/sheyunyang/iso27001-controls-reference) — ISO/IEC 27001:2022 附录 A 控制项关键词速查。
56. [合规评分卡](https://github.com/sheyunyang/compliance-scorecard) — 多框架达标录入自动评分，输出补强建议。
57. [供应商安全尽调](https://github.com/sheyunyang/vendor-security-assessment) — 第三方安全 8 项问卷，按答复输出合作建议等级。
58. [制度与审计文档生成](https://github.com/sheyunyang/policy-audit-doc-generator) — 安全制度框架、审计计划、RACI 职责矩阵一键生成。

### 🔍 取证与威胁情报（5 款）

59. [证据完整性与取证报告](https://github.com/sheyunyang/evidence-integrity-forensic-report) — 证据文件哈希校验 + 结构化取证报告框架，内部调查可用。
60. [Windows取证工件速查](https://github.com/sheyunyang/windows-forensics-artifacts) — USB 记录、浏览器历史、最近文件等 18 类取证目标位置速查。
61. [ATT&CK与威胁狩猎](https://github.com/sheyunyang/attack-threat-hunting) — 14 个战术阶段速查 + 威胁狩猎假设卡模板，让狩猎可复现。
62. [品牌仿冒监测](https://github.com/sheyunyang/brand-impersonation-monitor) — 生成品牌域名的仿冒变体用于防御性注册监测。
63. [威胁情报源管理](https://github.com/sheyunyang/threat-intel-source-manager) — OSINT/商业/行业 feed 的质量评估与订阅轮换台账。

### 🎓 安全意识与运营（4 款）

64. [综合安全知识测验](https://github.com/sheyunyang/security-knowledge-quiz) — 8 道场景化安全题即时判分，入职培训与趣味竞赛两用。
65. [安全术语词典](https://github.com/sheyunyang/security-glossary) — 60+ 安全术语简明释义，随查随讲，新人扫盲必备。
66. [安全能力成熟度自评](https://github.com/sheyunyang/security-maturity-assessment) — 五维度五级成熟度自评，差距可视化作规划依据。
67. [个人工具箱导航](https://github.com/sheyunyang/personal-security-toolbox) — 把本机常用安全工具登记成个人导航页，应急随手开。

## ⚠️ 合法合规声明

本项目仅供**安全学习、防御加固与授权测试**使用。任何未经授权对他人系统的访问、扫描或测试均属违法行为，使用者需自行承担全部责任。

## 📄 许可证

全部仓库基于 [MIT License](LICENSE) 发布，可自由使用、修改与再分发。
