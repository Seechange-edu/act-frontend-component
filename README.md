# act-frontend-component

Public GitHub Pages runner for the private
[frontend-component](https://github.com/Seechange-edu/frontend-component)
design systems.

This repository holds the Pages workflow only. Product source stays in the
private repository. One site, one path per product (`/thinkinglab/`, then
`/<product>/` when that product has a `site/`).

A tag push on the private repository dispatches `pages` with that commit's
sha. This workflow checks out the sha and publishes
<https://seechange-edu.github.io/act-frontend-component/>.
Pushing `main` does not publish.

## 说明

公开的 Pages 运行仓库。产品源码在私有仓库 `frontend-component`。这里只有发布用的 workflow。一个站点，每个产品一个路径。私有仓推送 tag 后才会发布，推送 `main` 不会。
