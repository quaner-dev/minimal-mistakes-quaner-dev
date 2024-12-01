# MMistakes操作汇总

## Git更新MMistakes模板

### 添加远程分支

在进行MMistakes之前，需要确保有一个upstream remote，使用以下命令添加

```bash
git remote add upstream https://github.com/mmistakes/minimal-mistakes.git
```

### 拉取更新

切换到master分支上

```bash
git checkout master
```

拉取并更新远程分支中代码

```bash
git pull upstream master
```

### 修复冲突

如果你对于你的MMistakes进行了定制，那么可能会有一些冲突，请保证你修复所有冲突后再进行commit
