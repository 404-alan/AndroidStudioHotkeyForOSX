
# 几个有用但是冷门的快捷键

[取自写代码的猴子](https://jaeger.itscoder.com/android/2016/02/14/android-studio-tips.html)

### 合并行和文本（Join Lines and Literals）

  * 描述：这个操作比起在行末使劲按删除键爽多了！该操作遵守格式化规则，同时：
    * 合并两行注释，同时移除多余的//；
    * 合并多行字符串，移除+和双引号；
    * 合并字段的声明和初始化赋值；
  * 快捷键：Ctrl + Shift + J；

  <p align="center">
  <img src="https://github.com/404-alan/Hotkey/blob/master/images/%E5%90%88%E5%B9%B6%E8%A1%8C%E5%92%8C%E6%96%87%E6%9C%AC.gif"/>
  </p>

### 取反补全（Negation Completion）

  * 描述：有时你自动补全一个布尔值，然后回到该值的前面添加一个感叹号来完成取反操作，现在通过使用输入!代替enter完成补全操作，就可以跳过这些繁琐的操作了。
  * 快捷键：代码补全的时候，按下!即可（有时需要上下键选中候选项）;
  
  <p align="center">
   <img src="https://github.com/404-alan/Hotkey/blob/master/images/%E5%8F%96%E5%8F%8D%E8%A1%A5%E5%85%A8.gif"/>
  </p>

### 分号/点 补全（Semicolon Dot Completion）

   * 描述：代码补全这个功能太棒啦！我们大概都对以下这种情况很熟悉：开始输入点什么东西，接着从IDE得到一些建议的选项，然后通过Enter或者Tab来选择我们想要的补全代码。其实还有另外一种方法来选择补全的代码：我们可以输入一个点(.)或者一个分号(;)。这样就会完成补全，添加所选字符。这在结束一条语句补全或者快速链式调用方法的时候特别有用。
   * 注意点：如果你要代码补全的方法需要参数，这些参数会被略过。
   * 快捷键：Autocomplete + “.” 或者 “;”

<p align="center">
   <img src="https://github.com/404-alan/Hotkey/blob/master/images/%E5%88%86%E5%8F%B7%3A%E7%82%B9%20%E8%A1%A5%E5%85%A8.gif"/>
  </p>

### 包裹代码（Surround With）

   * 描述： 该操作可以用特定代码结构包裹住选中的代码块，通常是if语句，循环，try/catch语句或者runnable语句。 如果你没有选中任何东西，该操作会包裹当前一整行。

   * 快捷键：Cmd + Alt + T

<p align="center">
   <img src="https://github.com/404-alan/Hotkey/blob/master/images/%E5%8C%85%E8%A3%B9%E4%BB%A3%E7%A0%81.gif"/>
  </p>

### 提取变量（Extract Variable）

  * 描述：这是一个提取变量的快捷操作。当你在没有写变量声明的直接写下值的时候，这是一个很方便生成变量声明的操作，同时还会给出一个建议的变量命名。
  * 调用：Menu → Refactor → Extract → Variable
  * 快捷键：Cmd + Alt + V
  * 更多：当你需要改变变量声明的类型，例如使用 List 替代 ArrayList，可以按下Shift + Tab，就会显示所有可用的变量类型。

<p align="center">
   <img src="https://github.com/404-alan/Hotkey/blob/master/images/%E6%8F%90%E5%8F%96%E5%8F%98%E9%87%8F.gif"/>
  </p>
  
### 快速查看类实现（Quick Definition Lookup）
 * 快捷键：Alt + Space / Cmd + Y
 
 <p align="center">
   <img src="https://github.com/404-alan/Hotkey/blob/HEAD/images/%E5%BF%AB%E9%80%9F%E6%9F%A5%E7%9C%8B%E7%B1%BB%E5%AE%9A%E4%B9%89.gif"/>
  </p>
  
### Select-in
 * 快捷键：Alt + F1
 <p align="center">
   <img src="https://github.com/404-alan/Hotkey/blob/d1fd9b0674728ef4148f0d9d7816b49abbe2e5a6/images/select-in.gif"/>
  </p>
  
### 块选择
 * 快捷键：Cmd + Shift + 8
 <p align="center">
   <img src="https://github.com/404-alan/Hotkey/blob/d1fd9b0674728ef4148f0d9d7816b49abbe2e5a6/images/%E5%BF%AB%E9%80%89%E6%8B%A9.gif"/>
  </p>
  
### 提取参数
 * 快捷键：Cmd + Alt + P
 <p align="center">
   <img src="https://github.com/404-alan/Hotkey/blob/d1fd9b0674728ef4148f0d9d7816b49abbe2e5a6/images/%E6%8F%90%E5%8F%96%E5%8F%82%E6%95%B0.gif"/>
  </p>
 
###  移除包裹代码
 * 快捷键：Cmd + Shift + Delete
 <p align="center">
   <img src="https://github.com/404-alan/Hotkey/blob/d1fd9b0674728ef4148f0d9d7816b49abbe2e5a6/images/%E7%A7%BB%E9%99%A4%E5%8C%85%E8%A3%B9%E4%BB%A3%E7%A0%81.gif"/>
  </p>
 
