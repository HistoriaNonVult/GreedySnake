# Contributing to Yanami-Anna-GreedySnake

感谢你对 Yanami-Anna-GreedySnake 项目的兴趣！通过贡献代码、报告问题或提供建议，你可以帮助我们改进这个项目。以下是一些贡献的基本规范，请仔细阅读。

---

## 🐛 提交 Issue

1. **搜索现有的 Issue**：在提交新 Issue 之前，请检查[现有的 Issue](https://github.com/HistoriaNonVult/Yanami-Anna-GreedySnake/issues)，以避免重复。

2. **描述清晰**：
   - 如果是 Bug 报告，请提供以下信息：
     - 复现步骤
     - 预期行为
     - 实际行为
     - 错误日志（如有）
   - 如果是功能请求，请说明功能的用例或场景。

3. **标记类型**：使用明确的标题，并根据内容为 Issue 添加标签（Bug、Feature Request、Question 等）。

---

## 🔧 提交 Pull Request

在提交代码之前，请确保遵循以下流程：

1. **Fork 仓库**：点击右上角的 `Fork` 按钮，将仓库 Fork 到你的账户下。

2. **创建分支**：
   - 从 `main` 分支创建一个新分支。
   - 分支命名建议使用以下格式：
     ```
     feature/your-feature-name
     fix/your-fix-description
     ```
   - 示例：`feature/add-sound-effects` 或 `fix/score-overflow-bug`。

3. **进行修改**：
   - 确保代码符合项目的代码规范。
   - 如果引入了新的功能，请编写相应的单元测试。
   - 如果修改了已有功能，请更新相关文档。

4. **本地测试**：运行项目的测试脚本，确保你的更改不会引入新问题：
   ```bash
   python -m unittest discover
   ```

5. **提交代码**：
   - 提交清晰的 Commit 信息：
     ```
     git commit -m "Fix: 修复得分溢出问题"
     ```

6. **创建 Pull Request**：
   - 在 Pull Request 的描述中清楚地说明你的更改目的和内容。
   - 如果更改解决了某个 Issue，请在描述中引用它，例如：`Closes #123`。

7. **响应反馈**：在 PR 审核过程中，及时响应维护者的评论并进行相应修改。

---

## 📝 代码规范

1. **语言**：本项目主要使用 Python 编写。

2. **风格指南**：遵循 [PEP 8](https://peps.python.org/pep-0008/) 代码风格规范。

3. **注释与文档**：
   - 函数和类必须添加 docstring。
   - 复杂逻辑需要额外的注释进行解释。

4. **变量命名**：
   - 使用有意义的英文命名（小写字母加下划线）。
   - 示例：`snake_position`、`game_score`。

5. **行长度**：限制在 80 字符以内。

6. **依赖管理**：
   - 确保新增的依赖项被添加到 `requirements.txt` 文件中。
   - 使用 `pip freeze > requirements.txt` 更新依赖列表。

---

## 🚀 开发环境设置

按照以下步骤配置开发环境：

1. **克隆仓库**：
   ```bash
   git clone https://github.com/HistoriaNonVult/Yanami-Anna-GreedySnake.git
   cd Yanami-Anna-GreedySnake
   ```

2. **创建虚拟环境**：
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows 使用 venv\Scripts\activate
   ```

3. **安装依赖**：
   ```bash
   pip install -r requirements.txt
   ```

4. **运行项目**：
   ```bash
   python main.py
   ```

5. **运行测试**：
   ```bash
   python -m unittest discover
   ```

---

## 📜 项目行为准则

参与项目时，请遵守我们的[行为准则](CODE_OF_CONDUCT.md)。

---

感谢你的贡献！如果有任何疑问或建议，请随时通过 Issue 或讨论区联系我们。

Happy coding! 🚀
