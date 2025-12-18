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
  <<< Author notes: Step 7 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Step 7: 创建发布版本 v1.0.1

_最后一步啦!_

### 最终发布

虽然你已经更新了源码，但用户还无法直接获取这些最新改动，我们还需要重新发版。

### 创建发布版本 v1.0.1

得益于之前撰写良好的拉取请求（Pull Request）和自动生成的发布说明（release notes），你不需要花太多时间手动编辑发布内容。
按照下面的步骤操作即可完成新版本的创建、生成发布说明并发布。

### :keyboard: 实操环节: 完成发布

1. 在浏览器中打开一个新的标签页，进入当前仓库的 **Releases** 页面。
2. 点击 **Draft a new release**（草拟新发布）按钮。
3. 将 **Target**（目标分支）设置为 `main`。遵守语义化版本号规则，新版本命名为 `v1.0.1`
4. 在描述输入框右上角，点击 **Generate release notes**（生成发布说明）。
5. 仔细查看生成的发布说明，如有需要可稍作修改，让内容更符合你的项目。
6. 点击 **Publish release**（发布版本）。
7. 等待大约 20 秒，然后刷新本页面（就是你正在阅读的这个教程页面）。[GitHub Actions](https://docs.github.com/en/actions) 会自动检测你的进度并进入下一步。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/release-based-workflow) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
