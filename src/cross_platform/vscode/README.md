# VSCode

## 文件对比

VSCode中，可以选择2个文件后去比较。

步骤：

先右键某文件->`选择以进行比较`

![vscode_right_menu_select_cmp](../../assets/img/vscode_right_menu_select_cmp.png)

被比较文件，右键->`与已选择项目进行比较`：

![vscode_compare_to_selected](../../assets/img/vscode_compare_to_selected.png)

可以方便的对比内容差异的：

![vscode_show_diff](../../assets/img/vscode_show_diff.png)

## 举例

### 安卓手机中微信中公众号搜搜页面的xml源码对比

同时选中2个文件后，右键，`将已选项进行比较`

![vscode_compare_selected_two](../../assets/img/vscode_compare_selected_two.png)

![vscode_show_diff_xml](../../assets/img/vscode_show_diff_xml.png)

显示效果也还是不错的，至少基本够用。

### ga的js对比

ga的2个js选择后：`将已选项进行比较`

![vscode_cmp_ga_two_js](../../assets/img/vscode_cmp_ga_two_js.png)

![vscode_ga_js_diff](../../assets/img/vscode_ga_js_diff.png)

此处有语法高亮，但会报错，导致看起来很乱

干脆去掉，变成普通text文本，再去对比：

![vscode_diff_as_text](../../assets/img/vscode_diff_as_text.png)

更容易看清楚区别了。

### uiautomator2调试的弹框广告的属性对比

![vscode_diff_u2_ad_cmp](../../assets/img/vscode_diff_u2_ad_cmp.png)

-》对比容易看出2次小米应用市场登录后的弹框的安卓元素属性有何区别

详见：

【未解决】用uiautomator2自动点击关闭小米应用市场登录后的广告弹框

## 左右双窗口显示模拟文件对比

另外VSCode的中还有个功能：`左右双窗口显示`

-》如果没有对比功能，则可以借用这个 双窗口显示 间接部分实现文件内容对比

之前某次去对比，正常 和 不正常 的xml：

![vscode_left_right_compare](../../assets/img/vscode_left_right_compare.png)

