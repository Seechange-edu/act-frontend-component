# act-frontend-component

Public GitHub Pages runner for the private
[frontend-component](https://github.com/Seechange-edu/frontend-component)
design systems.

This repository holds the Pages workflow only. Product source stays in the
private repository. One site, one path per product (`/thinkinglab/`, then
`/<product>/` when that product has a `site/`).

The private repository dispatches `pages` with a commit sha. This workflow
checks out that sha and publishes
<https://seechange-edu.github.io/act-frontend-component/>.

## 说明

公开的 Pages 运行仓库。产品源码在私有仓库 `frontend-component`。这里只有发布用的 workflow。一个站点，每个产品一个路径。
