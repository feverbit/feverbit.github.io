# feverbit.github.io

域名 `feverbit.github.io` 的**根路径**托管仓库。

唯一用途：提供 Universal Link 的校验文件
`https://feverbit.github.io/.well-known/apple-app-site-association`。

iOS 只从域名**根路径**读取 AASA，GitHub Pages 的项目站
（`feverbit.github.io/fastisslow-website`）无法在根路径托管，因此单独建本站点。

- 绑定 App：`57J7J3738Y.com.valueinvestment.app`（价值投资 / FastIsSlow）
- 匹配路径：`/fastisslow-website/app/*`（与微信开放平台登记的 Universal Link 一致）
- 修改 AASA 后需等待 CDN 刷新，并用 Apple 的缓存接口复核：
  `https://app-site-association.cdn-apple.com/a/v1/feverbit.github.io`
