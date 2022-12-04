# AUR JetBrains IDE

[JetBrains IDE] 的 [PKGBUILD] 打包脚本。

[JetBrains IDE]: https://www.jetbrains.com/products/
[PKGBUILD]: https://man.archlinux.org/man/PKGBUILD.5

## 介绍

[AUR] 中的 JetBrains IDE 打包脚本都太粗糙了，比如 WebStorm、PhpStorm……
额外拆分了 jre 包，但 PyCharm、Rider…… 又没拆分。又比如绝大部分包都装在
`/opt/` 下，但 RubyMine 却装在了 `/usr/share/` 下。

相比之下本仓库的打包脚本更规范，风格更统一。

[AUR]: https://aur.archlinux.org/

## 使用

本仓库提供了两种版本的 JetBrains IDE 打包脚本，并且不与 [AUR] 中相关的包相冲突。

+ 跟随官网不断更新
    - jetbrains-clion         `v2022.3`
    - jetbrains-datagrip      `v2022.3`
    - jetbrains-goland        `v2022.3`
    - jetbrains-intellij-idea `v2022.3`
    - jetbrains-phpstorm      `v2022.2.4`
    - jetbrains-pycharm       `v2022.3`
    - jetbrains-rider         `v2022.2.4`
    - jetbrains-rubymine      `v2022.3`
    - jetbrains-webstorm      `v2022.3`
+ 永远停留在 `2021.2.X`
    - [jetbrains-clion-old]         `v2021.2.2`
    - [jetbrains-datagrip-old]      `v2021.2.2`
    - [jetbrains-goland-old]        `v2021.2.3`
    - [jetbrains-intellij-idea-old] `v2021.2.2`
    - [jetbrains-phpstorm-old]      `v2021.2.2`
    - [jetbrains-pycharm-old]       `v2021.2.2`
    - [jetbrains-rider-old]         `v2021.2.2`
    - [jetbrains-rubymine-old]      `v2021.2.2`
    - [jetbrains-webstorm-old]      `v2021.2.2`

[jetbrains-clion-old]: https://github.com/kitty-panics/aur-jetbrains-ide/releases/tag/v2021.2.X
[jetbrains-datagrip-old]: https://github.com/kitty-panics/aur-jetbrains-ide/releases/tag/v2021.2.X
[jetbrains-goland-old]: https://github.com/kitty-panics/aur-jetbrains-ide/releases/tag/v2021.2.X
[jetbrains-intellij-idea-old]: https://github.com/kitty-panics/aur-jetbrains-ide/releases/tag/v2021.2.X
[jetbrains-phpstorm-old]: https://github.com/kitty-panics/aur-jetbrains-ide/releases/tag/v2021.2.X
[jetbrains-pycharm-old]: https://github.com/kitty-panics/aur-jetbrains-ide/releases/tag/v2021.2.X
[jetbrains-rider-old]: https://github.com/kitty-panics/aur-jetbrains-ide/releases/tag/v2021.2.X
[jetbrains-rubymine-old]: https://github.com/kitty-panics/aur-jetbrains-ide/releases/tag/v2021.2.X
[jetbrains-webstorm-old]: https://github.com/kitty-panics/aur-jetbrains-ide/releases/tag/v2021.2.X
