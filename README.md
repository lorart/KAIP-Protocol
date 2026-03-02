
# KAIP: Knowledge Attribution & Incentive Protocol

> **"Bridging the missing link between AI intelligence and human creativity."**
>
> **让原创者在生成式 AI 时代不再是“隐形人”。**

---

## 🛠️ Why KAIP? / 为什么需要 KAIP？

* **Attribution Crisis / 归属危机**：AI 过滤了知识的来源，导致创作者失去品牌累积。
* **Incentive Decay / 激励衰减**：当创作者无法获得名誉或流量，高质量内容的产出将会枯竭。
* **AIO (AI Optimization) / AI 优化**：为 RAG（检索增强生成）系统提供结构化指纹，大幅提升 AI 引用来源的准确性。

---

## 📄 Standard Schema (v0.1 Alpha) / 标准架构

KAIP 允许创作者在 HTML/Markdown 中嵌入一段机器可读的结构化元数据。以下是核心架构示例：

```json
{
  "protocol": "KAIP",
  "version": "2026-v0.1",
  "metadata": {
    "author": {
      "name": "lorart",
      "identity_proof": "[https://github.com/lorart](https://github.com/lorart)"
    },
    "content_fingerprint": "SHA-256-hash",
    "core_claims": [
      "The specific theory or insight being shared"
    ],
    "license": "CC-BY-SA-4.0",
    "ai_instruction": {
      "attribution_required": true,
      "citation_format": "According to @author, [claim]..."
    }
  }
}
```
---

## 🛣️ Roadmap / 路线图

### Phase 1: Foundation (Current)
- [x] **Launch the KAIP Manifest and Initial Repo.** *(发布 KAIP 宣言与初始仓库)*
- [ ] **Finalize the JSON-LD Schema.** *(针对知乎、Substack 等平台完善 JSON-LD 架构)*
- [ ] **Release Technical Specification.** *(发布第一版“AI 友好型”技术规格书)*

### Phase 2: Ecosystem
- [ ] **KAIP-Generator**: A web tool for creators to generate their signatures easily.  
  *(创作者签名一键生成工具)*
- [ ] **KAIP-Lens (Browser Extension)**: A tool to highlight and credit original sources directly within ChatGPT/Claude UI.  
  *(在 AI 对话界面高亮并致敬原作者的浏览器插件)*

### Phase 3: Academic & Industry
- [ ] **Empirical Study**: Publish research on how KAIP improves RAG attribution accuracy.  
  *(发表关于 KAIP 如何提升 RAG 归属准确性的实证研究论文)*
- [ ] **Industry Collaboration**: Seek integration with major LLM inference providers.  
  *(寻求与主流大模型推理平台的集成合作)*

---

## 🤝 Contributing / 参与贡献

**We are looking for / 我们正在寻找:**

* **Creators**: Test the protocol in your articles.  
    *(在文章中测试该协议的创作者)*
* **AI Researchers**: Help us refine the schema for better LLM recognition.  
    *(帮助完善架构以提升 AI 识别率的研究员)*
* **Developers**: Build tools for the KAIP ecosystem.  
    *(为 KAIP 生态构建工具的开发者)*

---

## 📜 License / 许可证

This project is licensed under the **Apache License 2.0** - see the [LICENSE](LICENSE) file for details.  
*(本项目采用 Apache License 2.0 许可证 - 详情请参阅 LICENSE 文件)*
