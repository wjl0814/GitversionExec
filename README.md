![gitversion](https://github.com/wjl0814/GitversionExec/workflows/gitversion/badge.svg)

# Gitversion Exec

GitVersion and GitHub Action Exec

# GitVersion 教程

1. 修改 `GitVersion.yml` 修改 `next-version` 为接下来要发布的版本
2. `git branch -m master feature/1.0.3` `git push origin feature/1.0.3`
3. `git branch -m master release/1.0.3`，提交分支， 将`feature/1.0.3`合并入`release/1.0.3`
4. 将 `release/1.0.3` 合并入 `master`

# 参考资料

- http://www.codewrecks.com/blog/index.php/2020/03/22/github-actions-plus-gitversion/
- https://blog.walterlv.com/post/automatically-semantic-versioning-using-git-version-task#%E9%85%8D%E7%BD%AE-gitversion
