<header>

<!--
  <<< Author notes: Course header >>>
  Read <https://skills.github.com/quickstart> for more information about how to build courses using this template.
  Include a 1280×640 image, course name in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Next to "About", add description & tags; disable releases, packages, & environments.
  Add your open source license, GitHub uses the MIT license.
-->

[English](https://github.com/skills/release-based-workflow) | 中文

> 本课程翻译自 Github Skills，全部课程请点击 [这里查看](https://www.github-zh.com/getting-started)

# 创建一个基于发布的工作流程

_掌握以 GitHub Flow 为基础的发布型工作流程（release based workflow）。_


</header>

<!--
  <<< Author notes: Step 5 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Step 5: 完成最终发布

### 完成发布前的准备

在正式发布前，你需要确认哪些信息会在 GitHub 上公开显示。在之前的预发布（Pre-release）版本中，你已经能看到版本号和提交记录等内容。

![image](https://user-images.githubusercontent.com/13326548/47883578-bdba7780-ddea-11e8-84b8-563e12f02ca6.png)

### 语义化版本（Semantic Versioning）

**语义化版本号**是一种标准化的版本命名规则，用来表达兼容性与变更内容。
它由三部分组成： 

> 主版本号（major） · 次版本号（minor） · 修订号（patch）。

版本号的变化能直接体现代码的修改程度。例如：

| 代码状态              |   阶段    | 规则                          | 示例版本 |
|---------------------|-----------|------------------------------| ------- |
| 第一次发布            | 新产品     | 从 1.0.0 开始                 | 1.0.0   |
| 向下兼容的修复         | 修订版     | 第三位加一                     | 1.0.1   |
| 向下兼容的新功能       | 小版本更新  | 第二位加一，并将第三位归零        | 1.1.0   |
| 不兼容的更新          | 大版本更新  | 第一位加一，并将后两位归零        | 2.0.0   |

如果你想深入了解，可以阅读 [语义化版本规范（Semantic Versioning）](https://semver.org/)。

### 发布正式版本

现在，我们要将刚才保存为 *草稿* 的发布，更新为真正的 *正式版本*。

### :keyboard: 实操环节：完成发布

1. 打开一个新的浏览器标签页，进入当前仓库的 **Releases** 页面。
   - 提示：点击仓库顶部的 **Code** 标签页，然后在仓库描述下方的导航栏中，点击 **Releases** 链接。
2. 点击草稿发布右侧的 **Edit**（编辑）按钮。
3. 确认 *Target* 分支设置为 `main`。
4. 点击 **Publish release**（发布版本）。
5. 等待大约 20 秒后刷新此页面。[GitHub Actions](https://docs.github.com/en/actions) 会自动检测并进入下一步。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/release-based-workflow) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
