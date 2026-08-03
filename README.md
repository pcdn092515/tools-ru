# 俄语工具独立站（免费版）— ИнструментПро

完全免费的静态俄语网站，适合零基础卖电动工具和手动工具。

## 网站结构

```
russian-tools-site/
├── index.html          # 首页
├── catalog.html        # 产品目录
├── about.html          # 关于我们
├── contact.html        # 联系方式（核心下单入口）
├── products/
│   └── shurupovert.html # 示例产品详情页
├── css/
│   └── style.css       # 样式
└── README.md           # 本说明
```

## 你需要修改的地方（重要！）

1. **联系方式**（所有页面都要改）：
   - 把 `@oriente_tools` 换成你的真实 Telegram 用户名
   - 把 `+86 17853582501` 换成真实 WhatsApp 号码
   - 把 `mark@orient-manufacture.com` 换成真实邮箱

2. **价格**：根据你的实际成本改成真实售价（目前是示例价格）

3. **产品图片**：
   - 把产品照片放到 `images/` 文件夹
   - 在 HTML 里把 `.img-placeholder` 换成真正的 `<img src="images/xxx.jpg">`

4. **产品内容**：添加你真正卖的工具型号、参数、照片

5. **店名**：如果想改名，全局搜索 `ИнструментПро` 替换即可

## 如何免费上线（推荐两种方法）

### 方法一：GitHub Pages（最推荐，稳定）

1. 注册免费 GitHub 账号：https://github.com
2. 新建仓库（Repository），名字随便，例如 `tools-ru`
3. 把整个 `russian-tools-site` 文件夹里的文件上传到仓库
4. 进入仓库 Settings → Pages → Source 选择 main 分支
5. 几分钟后网站就上线了，地址类似：
   `https://你的用户名.github.io/tools-ru`

### 方法二：InfinityFree 免费主机

1. 注册：https://www.infinityfree.com
2. 创建网站，获得免费子域名
3. 用文件管理器或 FTP 上传所有文件
4. 把 `index.html` 设为首页

### 方法三：Netlify / Cloudflare Pages（也很简单）

拖拽整个文件夹上传即可。

## 后续升级建议（有订单后再做）

1. 注册自己的域名（.ru 或 .com），一年大约 50–100 元
2. 升级到 Tilda 付费版或 WordPress + WooCommerce，接入真正的购物车和支付
3. 对接 YooMoney / SBP 等俄罗斯本地支付
4. 做 Yandex SEO 和 VK / Telegram 广告

## 现在立刻可以做的事

1. 修改所有联系方式
2. 准备 5–10 个真实产品的照片和参数
3. 上线网站
4. 在 Telegram / VK 发链接开始获客

有问题随时问我，我可以继续帮你改页面、加产品、写俄语文案。
