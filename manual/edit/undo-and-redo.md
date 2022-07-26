# 撤销与重做

<!--TODO: 此处应有图片-->
<!--TODO: 待补充-->

**操作序列查看**按钮位于[信息栏](manual/edit/basic.md#信息栏)。

操作序列最多保存 $20$ 步。

## 修改操作序列

### 撤销操作

<!--TODO: 此处应有图片-->

- 点击**撤销**按钮。
- 按下 `Ctrl+Z` 键。

### 重做操作

<!--TODO: 此处应有图片-->

- 点击**重做**按钮。
- 按下 `Ctrl+Y` 键。

**撤销**操作后，进行任何新的操作都会导致历史撤销记录被清空。

## 支持操作

**撤销与重做**支持如下操作：

- [`note`](manual/edit/note.md) 与[事件](manual/edit/event.md)的：
  - 放置
  - 编辑（如果未开启编辑自动保存）
  - 删除
  - 剪切、粘贴
  - 批量编辑
  - 拖动
- `note` 的：
  - 执行列表
- 事件的：
  - 克隆、切割
- [音符填充](manual/edit/fill-note.md)
- [轨迹生成](manual/edit/generate-track.md)

**撤销与重做**不支持如下操作：

- 按住 `Ctrl` 键改变 `note` 宽度
- [删除判定线](manual/edit/manage-line.md#删除判定线)
- 更改[设置](manual/edit/settings.md)
