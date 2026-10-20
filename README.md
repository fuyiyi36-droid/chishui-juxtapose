# 四渡赤水图片对比页

这是一个可部署到 GitHub Pages 的静态网页，使用 Knight Lab 的 JuxtaposeJS 拖动滑块对比黑白原图和修复上色图。

## 放入图片

两张图片已放入 `images` 文件夹：

- `chishui-original.png`：黑白原图（720 × 684）
- `chishui-restored.png`：修复上色图（731 × 696）

两张图的画面比例几乎一致，主体位置对应。文件保留上传时的 PNG 原样，未裁切或改色。网页按图片比例显示。

## 发布到 GitHub Pages

1. 登录 GitHub，创建一个 **Public** 仓库，例如 `chishui-juxtapose`。
2. 将本文件夹内的 `index.html`、`README.md` 和 `images` 文件夹上传到仓库根目录；图片也必须上传。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 里选择 **Deploy from a branch**，分支选 `main`，目录选 `/(root)`，保存。
5. 等待 Pages 发布完成，在 **Settings → Pages** 复制页面网址。项目仓库通常会得到 `https://你的用户名.github.io/chishui-juxtapose/` 这种链接。
6. 用手机浏览器打开这个网址，确认图片显示且滑块可拖动。之后把这个网址放进易企秀。

GitHub 官方步骤：[Quickstart for GitHub Pages](https://docs.github.com/en/pages/quickstart)。本页面通过 Knight Lab CDN 加载 JuxtaposeJS，因此访问者需要能够访问该 CDN。

## 放进易企秀

1. 在易企秀作品编辑器中添加一段提示文字或按钮，例如“拖动查看修复前后对比”。
2. 选中文字或按钮，在右侧找到 **点击跳转**（部分编辑器显示为“交互 → 单击触发 → 打开链接”）。
3. 粘贴上一步得到的完整 `https://…` 公网页面地址并保存。
4. 发布易企秀作品后，用手机实际点开测试。读者点击后会打开独立的对比页；易企秀的普通跳转链接不会把网页直接嵌进当前画布。

## 图片配对检查

已检查配对：黑白原图为 720 × 684，修复上色图为 731 × 696；宽高比例分别约为 1.0526 和 1.0503，差异约 0.22%。河岸、树木和房屋在两张图中的位置对应，可直接用于滑块对比。

## 遵义会议影像对比

新增第二个页面：zunyi.html，使用 images/zunyi-original.png（655 × 556）和 images/zunyi-restored.png（652 × 555）。两张上传图片按原样保留，页面可从首页互相切换。发布后地址为仓库 Pages 网址后加 /zunyi.html。


## 血战湘江影像对比

新增页面 xiangjiang.html，配对图片为 images/xiangjiang-original.png（900 × 536）和 images/xiangjiang-restored.png（897 × 533）。两张上传图片原样保留。


