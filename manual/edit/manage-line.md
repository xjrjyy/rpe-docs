# 判定线管理

<!--TODO: 此处应有图片-->
<!--TODO: 待补充-->

**判定线管理**按钮位于[信息栏](manual/edit/basic.md#信息栏)。

## 判定线筛选

<!--TODO: 此处应有图片-->
<!--TODO: 待补充-->

### 分组筛选

<!--TODO: 此处应有图片-->

左侧下拉框可选择显示某一组的判定线。

### 状态筛选

<!--TODO: 此处应有图片-->

右侧下拉框可选择显示处于某一状态的判定线。

- `All`：列出所有判定线。
- `VisL`：列出透明度 $>0$ 的判定线。
- `VisN`：列出有音符在可视范围内的判定线。
- `OnEve`：列出正在执行事件的判定线。

## 当前状态

<!--TODO: 此处应有图片-->
<!--TODO: 待补充-->

状态栏左侧的编号按钮即为[线号](basic/line.md#线号)，黄底按钮为当前编辑的判定线。

可以通过点击编号按钮切换当前编辑的判定线。

第一行（$\color{yellow}\texttt{Untitled}\ \color{pink}\texttt{Default}$）为判定线的名称和组别。

第二行（$(x,y)\ {\alpha}^{\circ}\ a\texttt{A}\ v\texttt{V}\ c\texttt{C}$）从左到右为：

- $(x,y)$：判定线[锚点](basic/line.md#锚点)的位置。
- ${\alpha}^{\circ}$：判定线的[角度](basic/line.md#角度)。
- $a\texttt{A}$：判定线的[透明度](basic/line.md#透明度)。
- $v\texttt{V}$：判定线的[基准速度](basic/line.md#基准速度)。
- $c\texttt{C}$：判定线的[遮罩](basic/line.md#遮罩)。
  - $c=1$ 为 `Cover`。
  - $c=0$ 为 `UnCover`。

第三行（$\texttt{UnJudged:}\ t\texttt{t}\ d\texttt{d}\ f\texttt{f}\ h\texttt{h}\ e\texttt{Events}$）从左到右为：

- $t\texttt{t}$：该判定线上未被判定（完）的 `Tap` 数量。
- $d\texttt{d}$：该判定线上未被判定（完）的 `Drag` 数量。
- $f\texttt{f}$：该判定线上未被判定（完）的 `Flick` 数量。
- $h\texttt{h}$：该判定线上未被判定（完）的 `Hold` 数量。
- $e\texttt{Events}$：该判定线上未被判定（完）的事件数量。

### 增加判定线

<!--TODO: 此处应有图片-->

点击**添加**按钮，可以添加一条空的判定线。

每种事件都会预留一个垫底，你不应该删除垫底事件。

### 删除判定线

<!--TODO: 此处应有图片-->

点击**删除**按钮，会二次确认是否删除正在编辑的线。

**删除**操作**无法撤销**。

## 全局状态

<!--TODO: 此处应有图片-->
<!--TODO: 待补充-->
