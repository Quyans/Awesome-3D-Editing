# 贡献指南

感谢您对 Awesome 3D Editing 项目的关注和贡献！

## 🤝 如何贡献

### 贡献类型

我们欢迎以下类型的贡献：

1. **📚 添加新资源**
   - 最新的3D编辑相关论文
   - 开源代码实现
   - 实用工具和软件
   - 高质量数据集
   - 教程和课程资源

2. **🔧 改进现有内容**
   - 修复损坏的链接
   - 更新过时信息
   - 改善分类和组织
   - 添加更详细的描述

3. **📝 文档改进**
   - 修正错别字和语法错误
   - 改善文档结构
   - 添加遗漏的标签和元数据

### 提交步骤

1. **Fork 仓库**
   ```bash
   # 点击页面右上角的 Fork 按钮
   ```

2. **克隆到本地**
   ```bash
   git clone https://github.com/your-username/Awesome-3D-Editing.git
   cd Awesome-3D-Editing
   ```

3. **创建新分支**
   ```bash
   git checkout -b feature/add-new-paper
   # 或
   git checkout -b fix/broken-links
   ```

4. **进行修改**
   - 按照下面的格式要求添加内容

5. **提交更改**
   ```bash
   git add .
   git commit -m "Add: 新论文标题"
   # 或
   git commit -m "Fix: 修复失效链接"
   ```

6. **推送分支**
   ```bash
   git push origin feature/add-new-paper
   ```

7. **创建 Pull Request**
   - 在 GitHub 页面点击 "New Pull Request"
   - 填写详细的描述信息

## 📋 内容格式要求

### 论文条目格式

```markdown
- **论文标题** [[论文]](arxiv/会议链接) [[代码]](github链接) [[项目页面]](项目链接) [[演示]](演示链接)
  - *作者: 第一作者姓名 et al.*
  - *会议/期刊: ICCV 2024 / arXiv 2024*
  - *关键词: 关键词1, 关键词2, 关键词3*
  - *简介: 一句话总结该工作的主要贡献和创新点*
```

**示例:**
```markdown
- **DreamFusion: Text-to-3D using 2D Diffusion** [[论文]](https://arxiv.org/abs/2209.14988) [[代码]](https://github.com/ashawkey/stable-dreamfusion) [[项目页面]](https://dreamfusion3d.github.io/)
  - *作者: Ben Poole et al.*
  - *会议/期刊: ICLR 2023*
  - *关键词: 文本到3D, 扩散模型, NeRF*
  - *简介: 使用2D扩散模型优化Neural Radiance Fields实现文本驱动的3D内容生成*
```

### 工具条目格式

```markdown
| [工具名称](链接) | 简短描述 | 主要语言 | ![GitHub stars](https://img.shields.io/github/stars/owner/repo) | ![GitHub last commit](https://img.shields.io/github/last-commit/owner/repo) |
```

### 数据集条目格式

```markdown
| **数据集名称** | 详细描述 | 数据规模 | [下载链接](链接) |
```

## ✅ 内容质量标准

### 论文收录标准

1. **相关性**: 必须与3D编辑直接相关
2. **质量**: 发表在顶级会议/期刊或具有显著影响力
3. **可获取性**: 论文可以公开获取（至少有arXiv版本）
4. **时效性**: 优先收录近期（2020年后）的工作

**顶级会议/期刊包括但不限于:**
- **计算机图形学**: SIGGRAPH, SIGGRAPH Asia, Eurographics
- **计算机视觉**: CVPR, ICCV, ECCV, 3DV
- **机器学习**: NeurIPS, ICML, ICLR
- **期刊**: TOG, TVCG, TPAMI, IJCV

### 工具收录标准

1. **实用性**: 对3D编辑研究或应用有实际价值
2. **维护状态**: 项目活跃维护，最近6个月内有更新
3. **文档完整**: 有清晰的使用说明和示例
4. **开源优先**: 优先收录开源项目

### 数据集收录标准

1. **规模**: 具有一定的数据规模
2. **质量**: 数据质量良好，标注准确
3. **可获取**: 数据集可以合法获取
4. **相关性**: 与3D编辑任务直接相关

## 🏷️ 分类和标签规范

### 主要分类

1. **按技术类型**:
   - 神经辐射场编辑 (NeRF Editing)
   - 网格编辑 (Mesh Editing) 
   - 点云编辑 (Point Cloud Editing)
   - 体素编辑 (Voxel Editing)
   - 隐式表面编辑 (Implicit Surface Editing)

2. **按应用领域**:
   - 人物编辑 (Human Editing)
   - 场景编辑 (Scene Editing)
   - 物体编辑 (Object Editing)
   - 纹理编辑 (Texture Editing)
   - 动画编辑 (Animation Editing)

3. **按编辑方式**:
   - 文本驱动 (Text-driven)
   - 图像驱动 (Image-driven)
   - 交互式编辑 (Interactive)
   - 自动编辑 (Automatic)

### 关键词规范

使用统一的关键词标签，便于搜索和分类：

**技术关键词:**
- `NeRF`, `Gaussian Splatting`, `Diffusion Model`, `GAN`, `VAE`
- `Mesh`, `Point Cloud`, `Voxel`, `SDF`, `Occupancy`
- `Neural Rendering`, `Implicit Representation`

**应用关键词:**
- `Face Editing`, `Body Editing`, `Scene Editing`, `Object Editing`
- `Texture Synthesis`, `Material Editing`, `Lighting Editing`
- `Motion Editing`, `Deformation`

**方法关键词:**
- `Text-driven`, `Image-guided`, `Interactive`, `Real-time`
- `Few-shot`, `Zero-shot`, `Self-supervised`

## 🔍 内容审核流程

### Pull Request 审核标准

1. **格式检查**: 是否符合格式要求
2. **内容验证**: 链接是否有效，信息是否准确
3. **质量评估**: 是否符合收录标准
4. **分类合理性**: 是否放置在合适的分类中
5. **重复检查**: 是否已存在相同或类似内容

### 审核时间

- 一般情况下，我们会在 **48小时内** 审核 Pull Request
- 复杂的添加可能需要更长时间进行验证
- 如有问题，我们会在 PR 中留言说明

## 🚫 不接受的内容

1. **商业广告**: 纯粹的产品推广
2. **低质量内容**: 明显错误或误导性信息
3. **重复内容**: 已经存在的资源
4. **无关内容**: 与3D编辑无关的资源
5. **版权问题**: 侵犯版权的内容

## 💡 贡献建议

### 高质量贡献的特征

1. **详细描述**: 提供充分的背景信息和技术细节
2. **准确链接**: 确保所有链接都是有效的
3. **完整信息**: 包含作者、发表venue、关键词等完整信息
4. **合理分类**: 放置在最合适的分类中
5. **有用标签**: 添加有助于检索的关键词

### 贡献者认可

- 所有贡献者将在 README 中得到致谢
- 重大贡献者可能被邀请成为项目维护者
- 我们会定期统计和公布贡献排行榜

## 📞 联系方式

如果您有任何问题或建议，可以通过以下方式联系我们：

- **GitHub Issues**: 用于报告问题和功能请求
- **GitHub Discussions**: 用于一般讨论和问答
- **Email**: [维护者邮箱]

## 📜 行为准则

参与本项目，请遵守以下行为准则：

1. **尊重他人**: 保持友善和专业的态度
2. **建设性沟通**: 提供有帮助的反馈和建议
3. **诚信原则**: 确保提交内容的准确性
4. **协作精神**: 与其他贡献者友好合作

---

感谢您的贡献！让我们一起打造最好的3D编辑资源合集！🎨✨

