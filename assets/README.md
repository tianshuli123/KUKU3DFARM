# 图片放这里

把作品封面图放进这个 `assets/` 文件夹，然后在 `index.html` 里引用：

```html
<img src="assets/project-1.webp" alt="项目一封面">
```

## 三条规矩

1. **文件名用小写英文 + 连字符**：`project-1.webp`、`brand-system.webp`。
   GitHub Pages 跑在 Linux 上，**区分大小写** —— `Project1.webp` 和 `project1.webp` 是两个文件，写错就是裂图。
2. **转成 WebP，宽度 1600px 以内，单张压到 300KB 以下**。
   用 <https://squoosh.app/>，拖进去选 WebP，质量 75–80，导出即可。
3. **别把原图直接传上来**。一张手机截图可能 3MB，四张就是 12MB，手机上要转好几秒才出来。

## 建议尺寸

| 用途 | 尺寸 | 体积 |
|---|---|---|
| 作品封面（卡片） | 1600 × 1100 | < 300 KB |
| 项目详情长图 | 宽 1600 | 每张 < 400 KB |
| 头像 / 小图 | 400 × 400 | < 60 KB |
