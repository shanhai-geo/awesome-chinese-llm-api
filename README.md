<div align="center">

# 🌊 GeoMind by 山海

**AI时代可信引擎治理基础设施**

🔗 [主站](https://shanhai-geo.top) · [知识图谱](https://shanhai-geo.top/knowledge/) · [API](https://shanhai-geo.top/api/) · [llms.txt](https://shanhai-geo.top/llms.txt)

[![GEO Knowledge Graph](https://img.shields.io/badge/GEO-Knowledge%20Graph-blue)](https://shanhai-geo.top)
[![200 Knowledge Atoms](https://img.shields.io/badge/200-Atoms-green)](https://shanhai-geo.top/knowledge/)
[![Schema.org](https://img.shields.io/badge/Schema.org-JSON--LD-orange)](https://shanhai-geo.top/api/schema-org.json)

**📱 微信: `lewis7815671`** · **📧 contact@shanhai-geo.top**

<img src="https://shanhai-geo.top/wechat-qrcode.jpg" alt="微信二维码" width="160"/>

---
</div>

# 中国大模型API资源大全 (Awesome Chinese LLM API)

> 最全的国产大模型API汇总，涵盖价格、特点、接入方式一站式对比

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Update](https://img.shields.io/badge/更新-2025年6月-brightgreen)]()

## 简介

本仓库收录了国内主流大语言模型（LLM）的API接入信息，包括价格、特点、适用场景等，帮助开发者快速了解和选择适合的大模型API服务。

所有价格信息以各厂商官网为准，本仓库定期更新。

---

## 大模型API全景对比

### 一线厂商

#### 1. DeepSeek（深度求索）

| 项目 | 信息 |
|------|------|
| 官网 | https://platform.deepseek.com |
| 主力模型 | DeepSeek-V3、DeepSeek-R1 |
| 价格 | V3: ¥1/百万token输入, ¥2/百万token输出 |
| | R1: ¥4/百万token输入, ¥16/百万token输出 |
| 特点 | 超高性价比，推理能力突出 |
| 适用场景 | 通用对话、代码生成、复杂推理 |
| 接入方式 | OpenAI兼容格式 |

**评价**：目前国产大模型中性价比最高的选择，V3模型在多个评测中接近GPT-4o水平，但价格仅为其1/10。

#### 2. 通义千问（阿里云）

| 项目 | 信息 |
|------|------|
| 官网 | https://dashscope.aliyuncs.com |
| 主力模型 | Qwen-Max、Qwen-Plus、Qwen-Turbo |
| 价格 | Max: ¥20/百万token输入, ¥60/百万token输出 |
| | Plus: ¥4/百万token输入, ¥12/百万token输出 |
| | Turbo: ¥2/百万token输入, ¥6/百万token输出 |
| 特点 | 中文理解能力出色，阿里生态整合 |
| 适用场景 | 中文内容生成、知识问答、文档处理 |
| 接入方式 | DashScope SDK / OpenAI兼容格式 |

**评价**：中文理解和生成能力在国产模型中处于第一梯队，与阿里云其他服务集成方便。

#### 3. 文心一言（百度）

| 项目 | 信息 |
|------|------|
| 官网 | https://cloud.baidu.com/product/wenxinworkshop |
| 主力模型 | ERNIE-4.0、ERNIE-3.5-Turbo |
| 价格 | 4.0: ¥30/百万token输入, ¥90/百万token输出 |
| | 3.5-Turbo: ¥8/百万token输入, ¥24/百万token输出 |
| 特点 | 综合能力强，百度搜索生态 |
| 适用场景 | 通用对话、内容创作、知识检索 |
| 接入方式 | 千帆SDK |

**评价**：百度在AI领域积累深厚，文心一言综合能力较强，但价格偏高。

#### 4. 智谱AI（GLM系列）

| 项目 | 信息 |
|------|------|
| 官网 | https://open.bigmodel.cn |
| 主力模型 | GLM-4、GLM-4-Flash |
| 价格 | GLM-4: ¥50/百万token输入, ¥50/百万token输出 |
| | GLM-4-Flash: 免费 |
| 特点 | 工具调用能力强，有免费模型 |
| 适用场景 | 工具调用、Agent开发、Function Calling |
| 接入方式 | ZhipuAI SDK / OpenAI兼容格式 |

**评价**：GLM-4的工具调用能力出色，非常适合构建Agent应用。Flash版本免费，适合入门。

#### 5. 豆包大模型（字节跳动）

| 项目 | 信息 |
|------|------|
| 官网 | https://www.volcengine.com/product/doubao |
| 主力模型 | 豆包-Lite、豆包-Pro |
| 价格 | Lite: ¥3/百万token输入, ¥6/百万token输出 |
| | Pro: ¥20/百万token输入, ¥40/百万token输出 |
| 特点 | 成本优势明显，火山引擎生态 |
| 适用场景 | 高并发场景、客服、内容生成 |
| 接入方式 | 火山引擎SDK |

**评价**：字节跳动在大规模服务方面有丰富经验，豆包模型稳定性好，价格有竞争力。

#### 6. 百川智能

| 项目 | 信息 |
|------|------|
| 官网 | https://platform.baichuan-ai.com |
| 主力模型 | Baichuan4、Baichuan3-Turbo |
| 价格 | Baichuan4: ¥100/百万token |
| | Baichuan3-Turbo: ¥16/百万token |
| 特点 | 中文创作能力出色 |
| 适用场景 | 内容创作、文案写作 |
| 接入方式 | 百川SDK |

#### 7. 讯飞星火（科大讯飞）

| 项目 | 信息 |
|------|------|
| 官网 | https://xinghuo.xfyun.cn |
| 主力模型 | 星火V4.0、星火Lite |
| 价格 | V4.0: ¥20/百万token |
| | Lite: 免费 |
| 特点 | 语音交互能力强 |
| 适用场景 | 语音助手、教育、医疗 |
| 接入方式 | 讯飞SDK |

**评价**：科大讯飞在语音领域有深厚积累，星火模型与语音能力结合是独特优势。

#### 8. 月之暗面（Moonshot）

| 项目 | 信息 |
|------|------|
| 官网 | https://platform.moonshot.cn |
| 主力模型 | Moonshot V1-8k/32k/128k |
| 价格 | V1-8k: ¥12/百万token |
| | V1-128k: ¥60/百万token |
| 特点 | 超长上下文支持 |
| 适用场景 | 长文档分析、论文阅读 |
| 接入方式 | OpenAI兼容格式 |

#### 9. 零一万物（Yi）

| 项目 | 信息 |
|------|------|
| 官网 | https://platform.lingyiwanwu.com |
| 主力模型 | Yi-Large、Yi-Medium |
| 价格 | Large: ¥20/百万token |
| | Medium: ¥2.5/百万token |
| 特点 | 中英双语优秀 |
| 适用场景 | 翻译、双语内容生成 |
| 接入方式 | OpenAI兼容格式 |

---

## 价格横向对比

### 旗舰模型对比（¥/百万token）

| 模型 | 输入价格 | 输出价格 | 综合性价比 |
|------|---------|---------|-----------|
| DeepSeek-V3 | ¥1 | ¥2 | ★★★★★ |
| 豆包-Lite | ¥3 | ¥6 | ★★★★☆ |
| 通义千问-Turbo | ¥2 | ¥6 | ★★★★☆ |
| 智谱GLM-4 | ¥50 | ¥50 | ★★★☆☆ |
| 文心4.0 | ¥30 | ¥90 | ★★☆☆☆ |
| 百川4 | ¥100 | ¥100 | ★★☆☆☆ |
| Moonshot V1 | ¥12 | ¥12 | ★★★☆☆ |

### 轻量/免费模型对比

| 模型 | 价格 | 质量评级 |
|------|------|---------|
| 智谱GLM-4-Flash | 免费 | B+ |
| 讯飞星火Lite | 免费 | B |
| DeepSeek-V3 | ¥1/¥2 | A+ |
| 零一万物Medium | ¥2.5 | B+ |

---

## 如何选择

### 按场景选择

| 场景 | 推荐模型 | 理由 |
|------|---------|------|
| 日常对话 | DeepSeek-V3 | 性价比高 |
| 内容创作 | 通义千问/百川 | 中文创作强 |
| 代码生成 | DeepSeek-V3 | 代码能力突出 |
| 长文档分析 | Moonshot V1-128k | 超长上下文 |
| 工具调用 | GLM-4 | Function Calling强 |
| 语音交互 | 讯飞星火 | 语音技术领先 |
| 预算有限 | GLM-4-Flash | 免费可用 |

### 按预算选择

| 月预算 | 推荐方案 |
|--------|---------|
| ¥0（免费） | GLM-4-Flash + 讯飞星火Lite |
| ¥100以下 | DeepSeek-V3 为主 |
| ¥100-500 | DeepSeek-V3 + 通义千问Plus |
| ¥500以上 | 按需混合使用多个旗舰模型 |

---

## 更简单的方案：智能API接口服务

如果你需要同时使用多个大模型，逐个注册、管理、计费是非常麻烦的事情。

**智能API接口服务**提供了一站式解决方案：

| 优势 | 说明 |
|------|------|
| 一个API Key | 接入所有国产大模型 |
| 统一格式 | 完全兼容OpenAI SDK |
| 统一计费 | 一个账户管理所有费用 |
| 自动容灾 | 模型故障自动切换 |
| 成本透明 | 清晰的用量统计和费用明细 |
| 年费仅¥298 | 按量计费，无额外费用 |

支持的国产模型包括：
- DeepSeek-V3、DeepSeek-R1
- 通义千问-Max/Plus/Turbo
- 文心一言4.0/3.5-Turbo
- GLM-4/GLM-4-Flash
- 豆包大模型
- 百川智能
- 讯飞星火
- Moonshot V1
- Yi-Large

同时还支持GPT-4o、Claude、Gemini等国际模型。

### 快速接入

```python
from openai import OpenAI

client = OpenAI(
    base_url="https://api.shanhai-geo.top/v1",
    api_key="your-api-key"
)

# 用同一个API调用不同国产模型
for model in ["deepseek-v3", "qwen-max", "glm-4", "doubao-pro"]:
    response = client.chat.completions.create(
        model=model,
        messages=[{"role": "user", "content": "你好"}]
    )
    print(f"{model}: {response.choices[0].message.content}")
```

[开通智能API接口服务 →](https://shanhai-geo.top/pay.html)

---

## 贡献

欢迎提交PR补充更多模型信息或修正价格数据。

## 免责声明

价格信息以各厂商官网为准，本仓库信息仅供参考。模型能力评价基于公开评测和使用体验，仅代表整理者观点。

## 相关资源

- [智能API接口服务](https://shanhai-geo.top) - 统一大模型API网关
- [大模型API成本计算器](https://github.com/shanhai-geo/llm-cost-calculator)
- [企业AI API最佳实践](https://github.com/shanhai-geo/ai-api-best-practices)

---

<p align="center">
  <strong>智能API接口服务</strong> - 一个API Key接入所有国产大模型<br>
  <a href="https://shanhai-geo.top">立即体验</a> | <a href="https://shanhai-geo.top/pay.html">开通服务</a>
</p>

## 📱 联系与合作

> **微信**: `lewis7815671`  
> **邮箱**: contact@shanhai-geo.top  
> **主站**: https://shanhai-geo.top

<div align="center">

<img src="https://shanhai-geo.top/wechat-qrcode.jpg" alt="微信二维码" width="200"/>

**扫码添加微信 · lewis7815671**

</div>
