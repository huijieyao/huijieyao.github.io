---
title: Hextra 语法指南
date: 2020-01-01
authors:
  - name: John Doe
    link: https://example.com/johndoe
excludeSearch: true
---

{{< callout emoji="🌐" >}}
  Hugo 可用于创建各种类型的网站，包括博客、作品集、文档站点等。
{{< /callout >}}


{{< callout type="info" >}}
  请访问 GitHub 查看最新版本。
{{< /callout >}}


{{< callout type="warning" >}}
  **提示框** 是一段简短的文本，旨在吸引注意力。
{{< /callout >}}


{{< callout type="error" >}}
  出错了，系统即将崩溃。
{{< /callout >}}


{{< icon "github" >}}

{{< filetree/container >}}
  {{< filetree/folder name="content" >}}
    {{< filetree/file name="_index.md" >}}
    {{< filetree/folder name="docs" state="closed" >}}
      {{< filetree/file name="_index.md" >}}
      {{< filetree/file name="introduction.md" >}}
      {{< filetree/file name="introduction.fr.md" >}}
    {{< /filetree/folder >}}
  {{< /filetree/folder >}}
  {{< filetree/file name="hugo.toml" >}}
{{< /filetree/container >}}

{{< tabs items="JSON,YAML,TOML" >}}

  {{< tab >}}
  ```json
  { "hello": "world" }
  ```
  {{< /tab >}}

  ... 类似地添加其他标签页

{{< /tabs >}}






{{< cards >}}
  {{< card link="../callout" title="提示框" icon="warning" >}}
  {{< card link="../callout" title="带标签的卡片" icon="tag" tag= "自定义标签" >}}
  {{< card link="/" title="无图标" >}}
{{< /cards >}}