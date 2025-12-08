# SimpleBeamerLZU

简洁的兰州大学 Beamer 演示文稿模板

## 快速开始

```bash
xelatex main.tex
```

## 切换比例

在 `main.tex` 第一行修改:

- **4:3 比例 (默认)**
  ```latex
  \documentclass{ldr-simple-gray}
  ```

- **16:9 比例**
  ```latex
  \documentclass[aspectratio169]{ldr-simple-gray}
  ```

- **16:10 比例**
  ```latex
  \documentclass[aspectratio1610]{ldr-simple-gray}
  ```

## 致谢

魔改自 [yuhldr-SimpleBeamerLZU](https://github.com/yuhldr/SimpleBeamerLZU)
