# MeChat 的博客

博客地址：[https://mechatxx.github.io/](https://mechatxx.github.io/)

## 本地预览

站点是纯静态页面，克隆后起一个本地服务器即可预览：

```bash
python3 -m http.server 8000
```

然后访问 <http://localhost:8000/> 。文章数据来自构建时生成的 `assets/posts.json`，页面不再直接请求 GitHub API。

### 静态资源版本号

`assets/app.js` 在五个页面里都以 `?v=` 形式引用。修改 `app.js` 后，请把这些版本号统一换成一个新值（例如 `20261121b` → `20261121c`），否则浏览器可能继续使用旧缓存。

## 文章目录

<!-- articles:start -->
- [AI 新闻每日摘要 · 2026-11-26](https://github.com/mechatxx/mechatxx.github.io/issues/16)
- [AI 新闻每日摘要 · 2026-11-25](https://github.com/mechatxx/mechatxx.github.io/issues/15)
- [AI 新闻每日摘要 · 2026-11-24](https://github.com/mechatxx/mechatxx.github.io/issues/14)
- [AI 新闻每日摘要 · 2026-11-23](https://github.com/mechatxx/mechatxx.github.io/issues/13)
- [AI 新闻每日摘要 · 2026-11-22](https://github.com/mechatxx/mechatxx.github.io/issues/12)
- [AI 新闻每日摘要 · 2026-11-21](https://github.com/mechatxx/mechatxx.github.io/issues/11)
- [AI 新闻每日摘要 · 2026-11-20](https://github.com/mechatxx/mechatxx.github.io/issues/10)
- [Using dominance over subjugation](https://github.com/mechatxx/mechatxx.github.io/issues/8)
- [Accepting critical voices](https://github.com/mechatxx/mechatxx.github.io/issues/7)
- [If your ideas differ from those of the organization, don't consider it abnormal.](https://github.com/mechatxx/mechatxx.github.io/issues/6)
- [There is no need to be afraid of loneliness.](https://github.com/mechatxx/mechatxx.github.io/issues/5)
- [Superman is the Earth](https://github.com/mechatxx/mechatxx.github.io/issues/4)
- [Become a Superhuman](https://github.com/mechatxx/mechatxx.github.io/issues/3)
- [Things have no distinction between surface and interior](https://github.com/mechatxx/mechatxx.github.io/issues/2)
- [But I'm here](https://github.com/mechatxx/mechatxx.github.io/issues/1)
<!-- articles:end -->
