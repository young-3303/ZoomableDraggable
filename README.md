# PanZoomControl

## 概览

由于最近工作开发需要，故开发了一个可以将 HTML 元素变为可缩放和可拖动对象工具类，就像我们平时对图像进行缩放、拖动一样

## 特点

- 使用鼠标滚轮进行平滑缩放，以光标为中心。
- 可拖动功能，允许使用鼠标移动元素。
- 自动边界限制，在缩放和拖动时保持元素在其容器内。

## 示例

![image](https://github.com/ZhengYaWei1992/ZWProgressView/blob/master/Untitled3.gif)
说明：
https://github.com/ZhengYaWei1992/ZWProgressView/blob/master/Untitled3.gif
这个链接网址是你上传gif图片后在，github中显示的链接网址。

#### options参数：

| 参数       | 说明                               | 类型          | 默认值 |
| ---------- | ---------------------------------- | ------------- | :----: |
| element    | 应用缩放和拖动功能的 HTML 元素。   | `HTMLElement` |        |
| container  | 限制目标元素缩放和拖动的容器元素。 | `HTMLElement` |        |
| maximum    | 最大缩放比例                       | number        |        |
| minimum    | 最小缩放比例                       | number        |        |
| deltaScale | 缩放灵敏度                         | number        |  0.1   |





