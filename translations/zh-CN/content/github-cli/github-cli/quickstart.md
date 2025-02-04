---
title: GitHub CLI 快速入门
intro: '开始使用 {% data variables.product.prodname_cli %} 在命令行中使用 {% data variables.product.company_short %}。'
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - CLI
type: overview
allowTitleToDifferFromFilename: true
shortTitle: Quickstart
ms.openlocfilehash: 004f848e973aa66d19b9de6b922d65dba76f1aea
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/05/2022
ms.locfileid: '145066714'
---
## 关于 {% data variables.product.prodname_cli %}

{% data reusables.cli.about-cli %}

## 入门

1. 在 macOS、Windows 或 Linux 上[安装](https://github.com/cli/cli#installation) {% data variables.product.prodname_cli %}。
1. 在命令行中，向 {% data variables.product.company_short %} 进行身份验证。

  ```shell
  gh auth login
  ```

  {% ifversion not fpt or ghec %} 若要向 {% data variables.product.product_location %} 进行身份验证，请使用 `--hostname` 标志。

  ```shell
  gh auth login --hostname <em>hostname</em>
  ```

  {% endif %}
1. 开始在命令行中使用 {% data variables.product.company_short %}。 例如，使用 `gh issue status` 或 `gh issue list --assignee @me` 查找要处理的问题。 使用 `gh pr create` 创建拉取请求。 使用 `gh pr checkout`、`gh pr diff` 和 `gh pr review` 查看拉取请求。

## 后续步骤

- 告诉 {% data variables.product.prodname_cli %} 哪个文本编辑器用于打开文本编辑器的命令。 例如，输入 `gh config set editor "code -w"` 将首选文本编辑器设置为 {% data variables.product.prodname_vscode %}。 有关详细信息，请参阅 [`gh config set`](https://cli.github.com/manual/gh_config_set)。

- 为通常运行的命令定义别名。 例如，如果运行 `gh alias set prd "pr create --draft"`，则你可以运行 `gh prd` 以快速打开草稿拉取请求。 有关详细信息，请参阅 [`gh alias`](https://cli.github.com/manual/gh_alias)。

- 使用 {% data variables.product.prodname_cli %} 扩展创建或添加自定义命令。 有关详细信息，请参阅“[使用 {% data variables.product.prodname_cli %} 扩展](/github-cli/github-cli/using-github-cli-extensions)”和“[创建 {% data variables.product.prodname_cli %} 扩展](/github-cli/github-cli/creating-github-cli-extensions)”。

- 有关可以使用 {% data variables.product.prodname_cli %} 运行的所有命令的详细信息，请参阅“[{% data variables.product.prodname_cli %} 参考](/github-cli/github-cli/github-cli-reference)”。
