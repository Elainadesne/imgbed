# imgbed

关系者图床。通过 [jsDelivr](https://www.jsdelivr.com/) 访问：

```
https://cdn.jsdelivr.net/gh/Elainadesne/imgbed@main/img/<path>
```

备用域名（国内连通性更好时可以替换）：

- `https://fastly.jsdelivr.net/gh/Elainadesne/imgbed@main/img/`
- `https://gcore.jsdelivr.net/gh/Elainadesne/imgbed@main/img/`
- `https://testingcf.jsdelivr.net/gh/Elainadesne/imgbed@main/img/`

同名文件替换后 CDN 会缓存较久，更新请改文件名。

## 命名空间

`img/` 下四类内容各占独立命名空间，互不冲突：

| 路径 | 内容 | 格式 |
| --- | --- | --- |
| `img/<6位hash>.webp` | catbox 迁移过来的 189 张 | 有损 WebP q90 |
| `img/<角色名>.webp` | 气泡头像 | 无损 WebP（少数几张保留原 PNG） |
| `img/<角色名>立绘.webp` | 角色立绘 | 无损 WebP |
| `img/地点/[地区/]<地点名>.webp` | 场景地点图 | 无损 WebP |

新增文件前先确认同名文件不存在，避免覆盖已有内容。
