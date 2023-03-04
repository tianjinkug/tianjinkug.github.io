# 广州 KUG 站点

https://gzkug.com

## 快速搭建一个 KUG 站点步骤：
 - [创建 Organization](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch)
 - 在新创建的 Organization 下[创建 repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)，如果不使用自定义域名，name 需要是 `${organization_name}.github.io`，参见 [GitHub Pages](https://pages.github.com/)
 - [fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) 或者 `git clone` 此仓库
 - 修改 `config.yml` 文件中自定义内容
 - [设置 GITHUB_TOKEN 权限](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-github-actions-settings-for-a-repository#configuring-the-default-github_token-permissions)(如果无法设置读写权限，请到 Organization 下的 Settings 中找到对应的设置项)
 - push 修改内容到你的仓库中，等待 GitHub Action 自动发布
