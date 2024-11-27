# 《矩阵潜袭》中文卡牌数据仓库镜像

## 项目简介

本仓库是 [NoahTheDuke/netrunner-data](https://github.com/NoahTheDuke/netrunner-data) 的镜像分支仓库，原仓库为 [jinteki.net](https://www.jinteki.net) 提供《矩阵潜袭》中文卡牌数据。

由于原仓库中文卡牌数据不完整，开发组 fork 了本镜像仓库，以便能够及时添加/更新卡牌数据，修改中文卡牌数据中发现的问题。

## 维护说明

本仓库的 `master` 分支保持与原仓库同步，不允许进行任何提交。

本仓库的 `mirror` 分支为开发分支，对本仓库的修改全部在 `mirror` 分支上进行。其它项目对本项目的引用（如：`git submodule`）也应当通过 `mirror` 分支进行。

`master` 分支上的变更都需要合并、同步到 `mirror` 分支。
