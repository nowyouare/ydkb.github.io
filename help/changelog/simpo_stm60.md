## Simpo系列和STM60系列

[+]新增 [-]删除 [^]升级 [#]修复 {}重要

两者固件是相近的。

##### 2020-07-27 (DK7R)
  - [#]修复: STM60的Win Lock无效的问题。
  - [+]新增：当一个按键设置为**Shift+KEY**时，如果再和**Shift**用，就直接输出**KEY**。举例来说就是一个按键被设置成了直接输出 **{**， 那么 **Shift+{** 就会输出 **[**。
  - [-] 取消默认命令按键里的 左右Shift+数字切换默认层，这个引起误操作时更多。一般默认层切换请自己设置按键。