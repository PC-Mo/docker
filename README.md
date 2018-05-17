# Docker Repository
*改自laradock. 加点自己的东西。*

## 改动点
1. **workspace** 中加入 **oh-my-zsh**
    - .zshrc首行加入`source .bashrc`，确保加载.bashrc中的配置
    - 注释掉.bashrc中所有`shopt`命令，.zsh不支持
