<h1> Mobile Article Aggregator Platform (MAP)</h1><br><br><hr><br>

Mobile Article Aggregator Platform 是一个面向移动端内容聚合与分发场景的开源技术资源导航站。该项目定位于为开发者、技术研究人员以及内容运营团队提供结构化的移动端文章链接索引与快速检索能力，解决移动端技术文章分散、检索效率低下、域名迁移频繁导致链接失效等实际问题。

项目本身不存储任何文章内容，仅作为外链元数据的索引层与展示层，通过静态化的资源列表与分类标签体系，帮助用户在海量移动端技术文档中快速定位目标资源。目标用户包括移动端开发工程师、全栈技术学习者、技术博客维护者以及企业内部知识库管理人员。

<h2>功能概览</h2><br>

<p><h3>海量链接索引管理</h3>：支持对超过 250 条移动端技术文章链接进行集中存储与分类展示，覆盖多种技术子领域。</p>

<p><h3>静态化资源列表呈现</h3>：所有链接以纯 Markdown 形式维护于项目仓库中，无需数据库依赖，便于版本控制与协作编辑。</p>

<p><h3>分类标签体系</h3>：根据文章主题、技术栈或访问热度对链接进行逻辑分组，降低用户筛选成本。</p>

<p><h3>快速检索入口</h3>：提供基于文章 ID 或路径关键字的本地搜索功能，提升链接定位速度。</p>

<p><h3>链接状态检测工具</h3>：集成可选的定时检测脚本，自动标记可能失效或响应异常的链接，保障资源列表的有效性。</p>

<p><h3>移动端适配展示</h3>：前端模板针对手机和平板设备进行优化，确保在移动浏览器上获得良好的阅读与导航体验。</p>

<p><h3>开源协作扩展机制</h3>：支持社区用户通过提交 Issue 或 Pull Request 的方式新增、更新或删除链接条目，保持资源列表的时效性。</p>

<p><h3>轻量化部署能力</h3>：项目整体基于静态文件生成，可托管于任何支持 HTTP 服务的平台，包括 GitHub Pages、Cloudflare Pages 或自建 Nginx 服务器。</p>

<h2>应用场景</h2><br>

技术团队内部知识库建设：企业内部的技术团队可将本项目作为基础框架，整理团队内部积累的移动端技术文章链接，形成统一的知识索引入口，减少重复的文档查找工作。

个人技术博客的友情链接扩展：独立技术博客作者可利用本项目的资源列表作为博客侧边栏的补充，为读者提供更多外部阅读资源，同时降低博客维护外链的复杂度。

技术社区的内容聚合展示：技术社区运营方可基于本项目快速搭建文章推荐专区，将社区内的高质量技术帖按分类进行外链汇总，提升社区内容的曝光率与复用率。

技术培训课程的参考资料索引：培训机构或技术讲师可将本项目作为课程参考资料库，将课程中涉及的外部延伸阅读链接统一整理到项目列表中，方便学员课后查阅。

开源项目文档的关联资源导航：开源项目维护者可在项目文档中引用本项目的资源列表，为使用者提供相关的技术背景阅读材料，丰富项目的辅助信息生态。

<h2>快速开始</h2><br>

以下步骤将帮助您在本地环境快速部署并运行本项目的静态站点。

# 1. 克隆项目仓库到本地
git clone https://github.com/example/mobile-article-aggregator.git
cd mobile-article-aggregator

# 2. 安装项目依赖（基于 Node.js 环境）
npm install

# 3. 运行本地开发服务器，默认监听端口 3000
npm run dev

执行上述命令后，在浏览器中访问 `http://localhost:3000` 即可查看资源列表页面。如需构建生产环境静态文件，请执行 `npm run build`，生成的静态资源位于 `dist` 目录下。

<h2>安装要求</h2><br>

| 依赖项 | 必需版本 | 说明 |
|--------|----------|------|
| Node.js | 18.0 及以上 | 项目构建工具与开发服务器运行环境 |
| npm | 8.0 及以上 | Node.js 包管理器，用于安装项目依赖 |
| Git | 2.30 及以上 | 用于克隆仓库与版本管理 |
| 现代浏览器 | Chrome 90+ / Firefox 88+ | 前端页面访问与调试支持 |
| HTTP 服务器 | 任意静态文件服务 | 生产环境托管构建后的静态文件，如 Nginx、Caddy 或 Apache |
| 可选：Shell 环境 | Bash 4.0+ | 运行链接状态检测脚本（位于 scripts/ 目录） |

<h2>文档导航</h2><br>

| 层面 | 目录 | 回答的问题 |
|------|------|------------|
| 用户入门 | docs/getting-started.md | 如何使用本项目的资源列表？如何通过分类标签快速找到所需文章？ |
| 维护者指南 | docs/maintenance.md | 如何新增、修改或删除链接条目？链接格式校验规则是什么？ |
| 开发贡献 | docs/contributing.md | 如何搭建开发环境？代码风格规范与提交信息格式要求有哪些？ |
| 部署运维 | docs/deployment.md | 如何将站点部署到生产服务器？如何配置自定义域名与 HTTPS？ |

<h2>资源列表</h2><br>

<h3>移动端技术文章链接汇总</h3><br>

以下列表收录了本批次（第 8/24 批，共300 个资源链接）的全部移动端文章外链。所有链接均按照用户提供的原始格式原样呈现，未做任何协议、域名或路径的改动。

https://github.com/bizimackio/lcdzshw/commit/6477d1a8232d85399f2d881e89dff065f59879c8?/GkE
<br>
https://github.com/bizimackio/mermleb/blob/main/2026%E6%9C%BA%E5%99%A8%E4%BA%BA%E6%8C%87%E5%8D%97%EF%BC%9A%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E4%BB%A3%E7%90%86%E2%80%94%E7%85%A7%E6%9C%BA%E8%B4%A2%E7%BB%8F.md?/337=015
<br>
https://github.com/bizimackio/mermleb/blob/main/2026%E6%9C%BA%E5%99%A8%E4%BA%BA%E6%8C%87%E5%8D%97%EF%BC%9A%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E4%BB%A3%E7%90%86%E2%80%94%E7%85%A7%E6%9C%BA%E8%B4%A2%E7%BB%8F.md?/zJ=TK4
<br>
https://github.com/bizimackio/mermleb/blob/main/2026%E6%9C%BA%E5%99%A8%E4%BA%BA%E6%8C%87%E5%8D%97%EF%BC%9A%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E4%BB%A3%E7%90%86%E2%80%94%E7%85%A7%E6%9C%BA%E8%B4%A2%E7%BB%8F.md?/Y2W
<br>
https://github.com/bizimackio/mermleb/blob/main/2026%E6%9C%BA%E5%99%A8%E4%BA%BA%E6%8C%87%E5%8D%97%EF%BC%9A%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E4%BB%A3%E7%90%86%E2%80%94%E7%85%A7%E6%9C%BA%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/bizimackio/mermleb/commit/6757fa646d0efd03d46111571965fac9d0ad7b6f?/64=IXE
<br>
https://github.com/bizimackio/mermleb/commit/6757fa646d0efd03d46111571965fac9d0ad7b6f?/0Uy=275
<br>
https://github.com/bizimackio/mermleb/commit/6757fa646d0efd03d46111571965fac9d0ad7b6f?/SwQ
<br>
https://github.com/sneunhreniyumno/dtfyaqf/blob/main/2026%E5%85%B7%E4%BD%93%E5%81%9A%E6%B3%95%EF%BC%9A%E6%96%B02%E4%BF%A1%E7%94%A8%E7%BD%91%E2%80%94%E5%BC%98%E5%AE%9E%E8%B4%A2%E7%BB%8F.md?/603=414
<br>
https://github.com/sneunhreniyumno/dtfyaqf/blob/main/2026%E5%85%B7%E4%BD%93%E5%81%9A%E6%B3%95%EF%BC%9A%E6%96%B02%E4%BF%A1%E7%94%A8%E7%BD%91%E2%80%94%E5%BC%98%E5%AE%9E%E8%B4%A2%E7%BB%8F.md?/qn=E8S
<br>
https://github.com/sneunhreniyumno/dtfyaqf/blob/main/2026%E5%85%B7%E4%BD%93%E5%81%9A%E6%B3%95%EF%BC%9A%E6%96%B02%E4%BF%A1%E7%94%A8%E7%BD%91%E2%80%94%E5%BC%98%E5%AE%9E%E8%B4%A2%E7%BB%8F.md?/6t0
<br>
https://github.com/sneunhreniyumno/dtfyaqf/blob/main/2026%E5%85%B7%E4%BD%93%E5%81%9A%E6%B3%95%EF%BC%9A%E6%96%B02%E4%BF%A1%E7%94%A8%E7%BD%91%E2%80%94%E5%BC%98%E5%AE%9E%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/sneunhreniyumno/dtfyaqf/commit/c7970fa7c07cab039ddcb7ccce55cb36be27f466?/82=PNR
<br>
https://github.com/sneunhreniyumno/dtfyaqf/commit/c7970fa7c07cab039ddcb7ccce55cb36be27f466?/kEi=924
<br>
https://github.com/sneunhreniyumno/dtfyaqf/commit/c7970fa7c07cab039ddcb7ccce55cb36be27f466?/CgA
<br>
https://github.com/yoandingspan/yxbldzu/blob/main/2026%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%EF%BC%9A%E6%96%B02%E7%99%BB1%E5%87%BA%E7%A7%9F%E2%80%94%E7%A7%89%E6%BA%90%E8%B4%A2%E7%BB%8F.md?/085=273
<br>
https://github.com/yoandingspan/yxbldzu/blob/main/2026%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%EF%BC%9A%E6%96%B02%E7%99%BB1%E5%87%BA%E7%A7%9F%E2%80%94%E7%A7%89%E6%BA%90%E8%B4%A2%E7%BB%8F.md?/Ei=CgA
<br>
https://github.com/yoandingspan/yxbldzu/blob/main/2026%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%EF%BC%9A%E6%96%B02%E7%99%BB1%E5%87%BA%E7%A7%9F%E2%80%94%E7%A7%89%E6%BA%90%E8%B4%A2%E7%BB%8F.md?/e8c
<br>
https://github.com/yoandingspan/yxbldzu/blob/main/2026%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%EF%BC%9A%E6%96%B02%E7%99%BB1%E5%87%BA%E7%A7%9F%E2%80%94%E7%A7%89%E6%BA%90%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/yoandingspan/yxbldzu/commit/ce1399da777472e3a338787663ae472fd70d1da4?/26=VHQ
<br>
https://github.com/yoandingspan/yxbldzu/commit/ce1399da777472e3a338787663ae472fd70d1da4?/6a4=877
<br>
https://github.com/yoandingspan/yxbldzu/commit/ce1399da777472e3a338787663ae472fd70d1da4?/Y2W
<br>
https://github.com/pieroacson/fdqxryn/blob/main/2026%E5%AE%98%E6%96%B9%E8%BD%BB%E5%90%AF%E5%B9%95%3A%E7%9A%87%E5%86%A0%E7%AE%A1%E7%90%86%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E2%80%94%E4%BC%9A%E8%AE%A1%E8%AE%BA%E5%9D%9B.md?/482=209
<br>
https://github.com/pieroacson/fdqxryn/blob/main/2026%E5%AE%98%E6%96%B9%E8%BD%BB%E5%90%AF%E5%B9%95%3A%E7%9A%87%E5%86%A0%E7%AE%A1%E7%90%86%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E2%80%94%E4%BC%9A%E8%AE%A1%E8%AE%BA%E5%9D%9B.md?/9d=7b5
<br>
https://github.com/pieroacson/fdqxryn/blob/main/2026%E5%AE%98%E6%96%B9%E8%BD%BB%E5%90%AF%E5%B9%95%3A%E7%9A%87%E5%86%A0%E7%AE%A1%E7%90%86%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E2%80%94%E4%BC%9A%E8%AE%A1%E8%AE%BA%E5%9D%9B.md?/Z3X
<br>
https://github.com/pieroacson/fdqxryn/blob/main/2026%E5%AE%98%E6%96%B9%E8%BD%BB%E5%90%AF%E5%B9%95%3A%E7%9A%87%E5%86%A0%E7%AE%A1%E7%90%86%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E2%80%94%E4%BC%9A%E8%AE%A1%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/pieroacson/fdqxryn/commit/b870af720ada96be8175b749acbdcb373bf01f4f?/43=PEZ
<br>
https://github.com/pieroacson/fdqxryn/commit/b870af720ada96be8175b749acbdcb373bf01f4f?/1Vz=402
<br>
https://github.com/pieroacson/fdqxryn/commit/b870af720ada96be8175b749acbdcb373bf01f4f?/TxR
<br>
https://github.com/pieroacson/zwalflh/blob/main/2026%E7%AC%AC%E4%B8%80%E8%93%9D%E7%9A%AE%E4%B9%A6%EF%BC%9A%E7%9A%87%E5%86%A0%E7%B3%BB%E7%BB%9F%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E2%80%94%E6%B7%9D%E6%B0%B4%E8%B4%A2%E7%BB%8F.md?/519=483
<br>
https://github.com/pieroacson/zwalflh/blob/main/2026%E7%AC%AC%E4%B8%80%E8%93%9D%E7%9A%AE%E4%B9%A6%EF%BC%9A%E7%9A%87%E5%86%A0%E7%B3%BB%E7%BB%9F%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E2%80%94%E6%B7%9D%E6%B0%B4%E8%B4%A2%E7%BB%8F.md?/fm=X4c
<br>
https://github.com/pieroacson/zwalflh/blob/main/2026%E7%AC%AC%E4%B8%80%E8%93%9D%E7%9A%AE%E4%B9%A6%EF%BC%9A%E7%9A%87%E5%86%A0%E7%B3%BB%E7%BB%9F%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E2%80%94%E6%B7%9D%E6%B0%B4%E8%B4%A2%E7%BB%8F.md?/F3A
<br>
https://github.com/pieroacson/zwalflh/blob/main/2026%E7%AC%AC%E4%B8%80%E8%93%9D%E7%9A%AE%E4%B9%A6%EF%BC%9A%E7%9A%87%E5%86%A0%E7%B3%BB%E7%BB%9F%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E2%80%94%E6%B7%9D%E6%B0%B4%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/pieroacson/zwalflh/commit/ebc4a98e3b4a5192c98a7ebd9c61b8bc6bf65bde?/98=YHS
<br>
https://github.com/pieroacson/zwalflh/commit/ebc4a98e3b4a5192c98a7ebd9c61b8bc6bf65bde?/uOs=292
<br>
https://github.com/pieroacson/zwalflh/commit/ebc4a98e3b4a5192c98a7ebd9c61b8bc6bf65bde?/MqK
<br>
https://github.com/sneunhreniyumno/dsmbgpe/blob/main/2026%E7%A7%91%E6%8A%80%E6%9C%8D%E5%8A%A1%E8%87%B3%E4%B8%8A%EF%BC%9A%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E4%BB%A3%E7%90%86%E2%80%94%E5%B7%A5%E4%B8%9A4.0%E8%AE%BA%E5%9D%9B.md?/049=665
<br>
https://github.com/sneunhreniyumno/dsmbgpe/blob/main/2026%E7%A7%91%E6%8A%80%E6%9C%8D%E5%8A%A1%E8%87%B3%E4%B8%8A%EF%BC%9A%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E4%BB%A3%E7%90%86%E2%80%94%E5%B7%A5%E4%B8%9A4.0%E8%AE%BA%E5%9D%9B.md?/Xo=sWq
<br>
https://github.com/sneunhreniyumno/dsmbgpe/blob/main/2026%E7%A7%91%E6%8A%80%E6%9C%8D%E5%8A%A1%E8%87%B3%E4%B8%8A%EF%BC%9A%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E4%BB%A3%E7%90%86%E2%80%94%E5%B7%A5%E4%B8%9A4.0%E8%AE%BA%E5%9D%9B.md?/UHO
<br>
https://github.com/sneunhreniyumno/dsmbgpe/blob/main/2026%E7%A7%91%E6%8A%80%E6%9C%8D%E5%8A%A1%E8%87%B3%E4%B8%8A%EF%BC%9A%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E4%BB%A3%E7%90%86%E2%80%94%E5%B7%A5%E4%B8%9A4.0%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/sneunhreniyumno/dsmbgpe/commit/32bcbca467f2011cf6ae81e29d7cf7694617a884?/11=ZAD
<br>
https://github.com/sneunhreniyumno/dsmbgpe/commit/32bcbca467f2011cf6ae81e29d7cf7694617a884?/8c6=674
<br>
https://github.com/sneunhreniyumno/dsmbgpe/commit/32bcbca467f2011cf6ae81e29d7cf7694617a884?/a4Y
<br>
https://github.com/bizimackio/lafgptr/blob/main/2026%E4%B8%93%E6%A0%8F%E6%AF%8F%E6%97%A5%E7%BB%8F%E9%AA%8C%EF%BC%9A%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E6%AD%A3%E7%BD%91%E2%80%94%E6%96%B0%E8%BD%A6%E8%AF%84%E6%B5%8B%E8%AE%BA%E5%9D%9B.md?/448=538
<br>
https://github.com/bizimackio/lafgptr/blob/main/2026%E4%B8%93%E6%A0%8F%E6%AF%8F%E6%97%A5%E7%BB%8F%E9%AA%8C%EF%BC%9A%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E6%AD%A3%E7%BD%91%E2%80%94%E6%96%B0%E8%BD%A6%E8%AF%84%E6%B5%8B%E8%AE%BA%E5%9D%9B.md?/5C=xxy
<br>
https://github.com/bizimackio/lafgptr/blob/main/2026%E4%B8%93%E6%A0%8F%E6%AF%8F%E6%97%A5%E7%BB%8F%E9%AA%8C%EF%BC%9A%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E6%AD%A3%E7%BD%91%E2%80%94%E6%96%B0%E8%BD%A6%E8%AF%84%E6%B5%8B%E8%AE%BA%E5%9D%9B.md?/VcM
<br>
https://github.com/bizimackio/lafgptr/blob/main/2026%E4%B8%93%E6%A0%8F%E6%AF%8F%E6%97%A5%E7%BB%8F%E9%AA%8C%EF%BC%9A%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E6%AD%A3%E7%BD%91%E2%80%94%E6%96%B0%E8%BD%A6%E8%AF%84%E6%B5%8B%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/bizimackio/lafgptr/commit/de4a4483ba3dc0f2b309e8d3d50b9b59b64f25ff?/70=RCW
<br>
https://github.com/bizimackio/lafgptr/commit/de4a4483ba3dc0f2b309e8d3d50b9b59b64f25ff?/qKo=710
<br>
https://github.com/bizimackio/lafgptr/commit/de4a4483ba3dc0f2b309e8d3d50b9b59b64f25ff?/ImG
<br>
https://github.com/frikter-mi/juogfiq/blob/main/2026%E6%95%B0%E5%AD%97%E6%B5%81%E7%A8%8B%E6%A8%A1%E5%9E%8B%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E4%BB%A3%E7%90%86%E5%87%BA%E7%A7%9F%E2%80%94%E7%BB%BF%E8%89%B2%E7%BB%8F%E6%B5%8E%E8%AE%BA%E5%9D%9B.md?/235=809
<br>
https://github.com/frikter-mi/juogfiq/blob/main/2026%E6%95%B0%E5%AD%97%E6%B5%81%E7%A8%8B%E6%A8%A1%E5%9E%8B%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E4%BB%A3%E7%90%86%E5%87%BA%E7%A7%9F%E2%80%94%E7%BB%BF%E8%89%B2%E7%BB%8F%E6%B5%8E%E8%AE%BA%E5%9D%9B.md?/2M=WN7
<br>
https://github.com/frikter-mi/juogfiq/blob/main/2026%E6%95%B0%E5%AD%97%E6%B5%81%E7%A8%8B%E6%A8%A1%E5%9E%8B%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E4%BB%A3%E7%90%86%E5%87%BA%E7%A7%9F%E2%80%94%E7%BB%BF%E8%89%B2%E7%BB%8F%E6%B5%8E%E8%AE%BA%E5%9D%9B.md?/b5Z
<br>
https://github.com/frikter-mi/juogfiq/blob/main/2026%E6%95%B0%E5%AD%97%E6%B5%81%E7%A8%8B%E6%A8%A1%E5%9E%8B%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E4%BB%A3%E7%90%86%E5%87%BA%E7%A7%9F%E2%80%94%E7%BB%BF%E8%89%B2%E7%BB%8F%E6%B5%8E%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/frikter-mi/juogfiq/commit/0e3f9f2ec0823e8edbf23045540fe75333536698?/10=SMB
<br>
https://github.com/frikter-mi/juogfiq/commit/0e3f9f2ec0823e8edbf23045540fe75333536698?/3X1=566
<br>
https://github.com/frikter-mi/juogfiq/commit/0e3f9f2ec0823e8edbf23045540fe75333536698?/VzT
<br>
https://github.com/bizimackio/cpppreq/blob/main/2026%E4%B8%93%E6%A0%8F%E5%B9%B4%E5%BA%A6%E6%8C%87%E5%8D%97%EF%BC%9A%E7%9A%87%E5%86%A0mos077%E5%BC%80%E6%88%B7%E2%80%94%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86%E6%9D%BF%E5%9D%97.md?/196=494
<br>
https://github.com/bizimackio/cpppreq/blob/main/2026%E4%B8%93%E6%A0%8F%E5%B9%B4%E5%BA%A6%E6%8C%87%E5%8D%97%EF%BC%9A%E7%9A%87%E5%86%A0mos077%E5%BC%80%E6%88%B7%E2%80%94%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86%E6%9D%BF%E5%9D%97.md?/ez=90k
<br>
https://github.com/bizimackio/cpppreq/blob/main/2026%E4%B8%93%E6%A0%8F%E5%B9%B4%E5%BA%A6%E6%8C%87%E5%8D%97%EF%BC%9A%E7%9A%87%E5%86%A0mos077%E5%BC%80%E6%88%B7%E2%80%94%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86%E6%9D%BF%E5%9D%97.md?/EiC
<br>
https://github.com/bizimackio/cpppreq/blob/main/2026%E4%B8%93%E6%A0%8F%E5%B9%B4%E5%BA%A6%E6%8C%87%E5%8D%97%EF%BC%9A%E7%9A%87%E5%86%A0mos077%E5%BC%80%E6%88%B7%E2%80%94%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86%E6%9D%BF%E5%9D%97.md
<br>
https://github.com/bizimackio/cpppreq/commit/bb4531a160ce817d073148412bf0eb17f7e001ea?/71=BJA
<br>
https://github.com/bizimackio/cpppreq/commit/bb4531a160ce817d073148412bf0eb17f7e001ea?/gAe=190
<br>
https://github.com/bizimackio/cpppreq/commit/bb4531a160ce817d073148412bf0eb17f7e001ea?/8c6
<br>
https://github.com/yoandingspan/kjvdplg/blob/main/2026%E7%AC%AC%E4%B8%80%E6%B1%BD%E8%BD%A6%E6%95%99%E7%A8%8B%EF%BC%9A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E5%87%BA%E5%94%AE%E2%80%94%E9%9D%A2%E8%AF%95%E8%AE%BA%E5%9D%9B.md?/529=700
<br>
https://github.com/yoandingspan/kjvdplg/blob/main/2026%E7%AC%AC%E4%B8%80%E6%B1%BD%E8%BD%A6%E6%95%99%E7%A8%8B%EF%BC%9A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E5%87%BA%E5%94%AE%E2%80%94%E9%9D%A2%E8%AF%95%E8%AE%BA%E5%9D%9B.md?/hB=f9d
<br>
https://github.com/yoandingspan/kjvdplg/blob/main/2026%E7%AC%AC%E4%B8%80%E6%B1%BD%E8%BD%A6%E6%95%99%E7%A8%8B%EF%BC%9A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E5%87%BA%E5%94%AE%E2%80%94%E9%9D%A2%E8%AF%95%E8%AE%BA%E5%9D%9B.md?/7b5
<br>
https://github.com/yoandingspan/kjvdplg/blob/main/2026%E7%AC%AC%E4%B8%80%E6%B1%BD%E8%BD%A6%E6%95%99%E7%A8%8B%EF%BC%9A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E5%87%BA%E5%94%AE%E2%80%94%E9%9D%A2%E8%AF%95%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/yoandingspan/kjvdplg/commit/f4965f302abaa6237684c1e22247eca29d8f78cd?/37=ZNY
<br>
https://github.com/yoandingspan/kjvdplg/commit/f4965f302abaa6237684c1e22247eca29d8f78cd?/Z3X=107
<br>
https://github.com/yoandingspan/kjvdplg/commit/f4965f302abaa6237684c1e22247eca29d8f78cd?/1Vz
<br>
https://github.com/sneunhreniyumno/nifeoup/blob/main/2026%E5%AE%98%E6%96%B9%E4%BA%91%E7%9B%9B%E4%BC%9A%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%B3%BB%E7%BB%9F%E5%87%BA%E7%A7%9F%E2%80%94%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F.md?/943=614
<br>
https://github.com/sneunhreniyumno/nifeoup/blob/main/2026%E5%AE%98%E6%96%B9%E4%BA%91%E7%9B%9B%E4%BC%9A%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%B3%BB%E7%BB%9F%E5%87%BA%E7%A7%9F%E2%80%94%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F.md?/Bf=9d7
<br>
https://github.com/sneunhreniyumno/nifeoup/blob/main/2026%E5%AE%98%E6%96%B9%E4%BA%91%E7%9B%9B%E4%BC%9A%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%B3%BB%E7%BB%9F%E5%87%BA%E7%A7%9F%E2%80%94%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F.md?/b5Z
<br>
https://github.com/sneunhreniyumno/nifeoup/blob/main/2026%E5%AE%98%E6%96%B9%E4%BA%91%E7%9B%9B%E4%BC%9A%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%B3%BB%E7%BB%9F%E5%87%BA%E7%A7%9F%E2%80%94%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/sneunhreniyumno/nifeoup/commit/2be24277aacf55439618cc51917bd5cadec91cd7?/62=VWO
<br>
https://github.com/sneunhreniyumno/nifeoup/commit/2be24277aacf55439618cc51917bd5cadec91cd7?/X1V=492
<br>
https://github.com/sneunhreniyumno/nifeoup/commit/2be24277aacf55439618cc51917bd5cadec91cd7?/zTx
<br>
https://github.com/frikter-mi/cdfgmjf/blob/main/2026%20%E7%A7%91%E6%99%AE%E9%87%91%E8%9E%8D%EF%BC%9A%E7%9A%87%E5%86%A0mos011%E5%BC%80%E6%88%B7%E2%80%94%E5%AE%88%E6%BA%90%E8%B4%A2%E7%BB%8F.md?/037=257
<br>
https://github.com/frikter-mi/cdfgmjf/blob/main/2026%20%E7%A7%91%E6%99%AE%E9%87%91%E8%9E%8D%EF%BC%9A%E7%9A%87%E5%86%A0mos011%E5%BC%80%E6%88%B7%E2%80%94%E5%AE%88%E6%BA%90%E8%B4%A2%E7%BB%8F.md?/Fj=DhB
<br>
https://github.com/frikter-mi/cdfgmjf/blob/main/2026%20%E7%A7%91%E6%99%AE%E9%87%91%E8%9E%8D%EF%BC%9A%E7%9A%87%E5%86%A0mos011%E5%BC%80%E6%88%B7%E2%80%94%E5%AE%88%E6%BA%90%E8%B4%A2%E7%BB%8F.md?/f9d
<br>
https://github.com/frikter-mi/cdfgmjf/blob/main/2026%20%E7%A7%91%E6%99%AE%E9%87%91%E8%9E%8D%EF%BC%9A%E7%9A%87%E5%86%A0mos011%E5%BC%80%E6%88%B7%E2%80%94%E5%AE%88%E6%BA%90%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/frikter-mi/cdfgmjf/commit/aea29eff753b242a998eac2f70063b0dc26b88cf?/52=QON
<br>
https://github.com/frikter-mi/cdfgmjf/commit/aea29eff753b242a998eac2f70063b0dc26b88cf?/7b5=271
<br>
https://github.com/frikter-mi/cdfgmjf/commit/aea29eff753b242a998eac2f70063b0dc26b88cf?/Z3X
<br>
https://github.com/sneunhreniyumno/umnbbod/blob/main/2026%E5%AE%98%E6%96%B9%E6%96%B0%E6%96%B9%E5%90%91%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E5%87%BA%E7%A7%9F%E2%80%94%E7%BB%9D%E5%8C%BA%E9%9B%B6%E7%A4%BE%E5%8C%BA.md?/366=467
<br>
https://github.com/sneunhreniyumno/umnbbod/blob/main/2026%E5%AE%98%E6%96%B9%E6%96%B0%E6%96%B9%E5%90%91%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E5%87%BA%E7%A7%9F%E2%80%94%E7%BB%9D%E5%8C%BA%E9%9B%B6%E7%A4%BE%E5%8C%BA.md?/ar=vZt
<br>
https://github.com/sneunhreniyumno/umnbbod/blob/main/2026%E5%AE%98%E6%96%B9%E6%96%B0%E6%96%B9%E5%90%91%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E5%87%BA%E7%A7%9F%E2%80%94%E7%BB%9D%E5%8C%BA%E9%9B%B6%E7%A4%BE%E5%8C%BA.md?/XKR
<br>
https://github.com/sneunhreniyumno/umnbbod/blob/main/2026%E5%AE%98%E6%96%B9%E6%96%B0%E6%96%B9%E5%90%91%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E5%87%BA%E7%A7%9F%E2%80%94%E7%BB%9D%E5%8C%BA%E9%9B%B6%E7%A4%BE%E5%8C%BA.md
<br>
https://github.com/sneunhreniyumno/umnbbod/commit/ac582a96cb7195c887a514a8963266e939cfe1ea?/55=SKL
<br>
https://github.com/sneunhreniyumno/umnbbod/commit/ac582a96cb7195c887a514a8963266e939cfe1ea?/Bf9=488
<br>
https://github.com/sneunhreniyumno/umnbbod/commit/ac582a96cb7195c887a514a8963266e939cfe1ea?/db5
<br>
https://github.com/frikter-mi/spzmcap/blob/main/2026%E6%93%8D%E4%BD%9C%E6%AD%A5%E9%AA%A4%EF%BC%9A%E7%9A%87%E5%86%A0mos066%E5%BC%80%E6%88%B7%E2%80%94SAT%E8%AE%BA%E5%9D%9B.md?/323=190
<br>
https://github.com/frikter-mi/spzmcap/blob/main/2026%E6%93%8D%E4%BD%9C%E6%AD%A5%E9%AA%A4%EF%BC%9A%E7%9A%87%E5%86%A0mos066%E5%BC%80%E6%88%B7%E2%80%94SAT%E8%AE%BA%E5%9D%9B.md?/NY=P9d
<br>
https://github.com/frikter-mi/spzmcap/blob/main/2026%E6%93%8D%E4%BD%9C%E6%AD%A5%E9%AA%A4%EF%BC%9A%E7%9A%87%E5%86%A0mos066%E5%BC%80%E6%88%B7%E2%80%94SAT%E8%AE%BA%E5%9D%9B.md?/a4Y
<br>
https://github.com/frikter-mi/spzmcap/blob/main/2026%E6%93%8D%E4%BD%9C%E6%AD%A5%E9%AA%A4%EF%BC%9A%E7%9A%87%E5%86%A0mos066%E5%BC%80%E6%88%B7%E2%80%94SAT%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/frikter-mi/spzmcap/commit/709ff9a3c933d2ea15d4cf67fef9dd78c141a139?/05=YSI
<br>
https://github.com/frikter-mi/spzmcap/commit/709ff9a3c933d2ea15d4cf67fef9dd78c141a139?/2W0=463
<br>
https://github.com/frikter-mi/spzmcap/commit/709ff9a3c933d2ea15d4cf67fef9dd78c141a139?/UyS
<br>
https://github.com/yoandingspan/xinuhsx/blob/main/2026%E5%B9%B4%E5%BA%A6%E6%9B%B4%E6%96%B0%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%9B%98%E4%BB%A3%E7%90%86%E2%80%94%E8%A7%88%E5%8A%BF%E8%B4%A2%E7%BB%8F.md?/411=490
<br>
https://github.com/yoandingspan/xinuhsx/blob/main/2026%E5%B9%B4%E5%BA%A6%E6%9B%B4%E6%96%B0%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%9B%98%E4%BB%A3%E7%90%86%E2%80%94%E8%A7%88%E5%8A%BF%E8%B4%A2%E7%BB%8F.md?/cJ=DYE
<br>
https://github.com/yoandingspan/xinuhsx/blob/main/2026%E5%B9%B4%E5%BA%A6%E6%9B%B4%E6%96%B0%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%9B%98%E4%BB%A3%E7%90%86%E2%80%94%E8%A7%88%E5%8A%BF%E8%B4%A2%E7%BB%8F.md?/8w3
<br>
https://github.com/yoandingspan/xinuhsx/blob/main/2026%E5%B9%B4%E5%BA%A6%E6%9B%B4%E6%96%B0%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%9B%98%E4%BB%A3%E7%90%86%E2%80%94%E8%A7%88%E5%8A%BF%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/yoandingspan/xinuhsx/commit/a65a9b78bc57fe036a06339c95b93979bdd2d806?/27=FLG
<br>
https://github.com/yoandingspan/xinuhsx/commit/a65a9b78bc57fe036a06339c95b93979bdd2d806?/nHl=562
<br>
https://github.com/yoandingspan/xinuhsx/commit/a65a9b78bc57fe036a06339c95b93979bdd2d806?/FjD
<br>
https://github.com/pieroacson/ufqzgbk/blob/main/2026%E7%AC%AC%E4%B8%80%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB%EF%BC%9A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%BD%91%E4%BB%A3%E7%90%86%E2%80%94A9VG%E7%94%B5%E7%8E%A9%E9%83%A8%E8%90%BD.md?/912=478
<br>
https://github.com/pieroacson/ufqzgbk/blob/main/2026%E7%AC%AC%E4%B8%80%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB%EF%BC%9A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%BD%91%E4%BB%A3%E7%90%86%E2%80%94A9VG%E7%94%B5%E7%8E%A9%E9%83%A8%E8%90%BD.md?/Oh=L9G
<br>
https://github.com/pieroacson/ufqzgbk/blob/main/2026%E7%AC%AC%E4%B8%80%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB%EF%BC%9A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%BD%91%E4%BB%A3%E7%90%86%E2%80%94A9VG%E7%94%B5%E7%8E%A9%E9%83%A8%E8%90%BD.md?/0Uy
<br>
https://github.com/pieroacson/ufqzgbk/blob/main/2026%E7%AC%AC%E4%B8%80%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB%EF%BC%9A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%BD%91%E4%BB%A3%E7%90%86%E2%80%94A9VG%E7%94%B5%E7%8E%A9%E9%83%A8%E8%90%BD.md
<br>
https://github.com/pieroacson/ufqzgbk/commit/4236b02a40f51e6c370d33a64256222002eb88c4?/56=ESO
<br>
https://github.com/pieroacson/ufqzgbk/commit/4236b02a40f51e6c370d33a64256222002eb88c4?/SwQ=193
<br>
https://github.com/pieroacson/ufqzgbk/commit/4236b02a40f51e6c370d33a64256222002eb88c4?/uOs
<br>
https://github.com/bizimackio/lyvtukg/blob/main/2026%E5%AE%98%E6%96%B9%E6%96%B0%E8%90%BD%E5%9C%B0%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%9B%98%E5%BC%80%E6%88%B7%E2%80%94%E7%94%9C%E5%93%81%E8%AE%BA%E5%9D%9B.md?/966=102
<br>
https://github.com/bizimackio/lyvtukg/blob/main/2026%E5%AE%98%E6%96%B9%E6%96%B0%E8%90%BD%E5%9C%B0%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%9B%98%E5%BC%80%E6%88%B7%E2%80%94%E7%94%9C%E5%93%81%E8%AE%BA%E5%9D%9B.md?/Os=MqK
<br>
https://github.com/bizimackio/lyvtukg/blob/main/2026%E5%AE%98%E6%96%B9%E6%96%B0%E8%90%BD%E5%9C%B0%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%9B%98%E5%BC%80%E6%88%B7%E2%80%94%E7%94%9C%E5%93%81%E8%AE%BA%E5%9D%9B.md?/oIm
<br>
https://github.com/bizimackio/lyvtukg/blob/main/2026%E5%AE%98%E6%96%B9%E6%96%B0%E8%90%BD%E5%9C%B0%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%9B%98%E5%BC%80%E6%88%B7%E2%80%94%E7%94%9C%E5%93%81%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/bizimackio/lyvtukg/commit/3075abe01106fabcf900658fe086bb3156017c22?/02=EHI
<br>
https://github.com/bizimackio/lyvtukg/commit/3075abe01106fabcf900658fe086bb3156017c22?/GkE=133
<br>
https://github.com/bizimackio/lyvtukg/commit/3075abe01106fabcf900658fe086bb3156017c22?/iCg
<br>
https://github.com/frikter-mi/ynbjgjo/blob/main/2026%E5%AE%98%E6%96%B9%E7%9B%9B%E5%BA%8F%E7%AB%A0%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%9B%98%E5%87%BA%E7%A7%9F%E2%80%94%E6%A3%92%E7%90%83%E8%AE%BA%E5%9D%9B.md?/538=547
<br>
https://github.com/frikter-mi/ynbjgjo/blob/main/2026%E5%AE%98%E6%96%B9%E7%9B%9B%E5%BA%8F%E7%AB%A0%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%9B%98%E5%87%BA%E7%A7%9F%E2%80%94%E6%A3%92%E7%90%83%E8%AE%BA%E5%9D%9B.md?/Tx=RvP
<br>
https://github.com/frikter-mi/ynbjgjo/blob/main/2026%E5%AE%98%E6%96%B9%E7%9B%9B%E5%BA%8F%E7%AB%A0%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%9B%98%E5%87%BA%E7%A7%9F%E2%80%94%E6%A3%92%E7%90%83%E8%AE%BA%E5%9D%9B.md?/tNr
<br>
https://github.com/frikter-mi/ynbjgjo/blob/main/2026%E5%AE%98%E6%96%B9%E7%9B%9B%E5%BA%8F%E7%AB%A0%3A%E7%9A%87%E5%86%A0%E4%BF%A1%E7%94%A8%E7%9B%98%E5%87%BA%E7%A7%9F%E2%80%94%E6%A3%92%E7%90%83%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/frikter-mi/ynbjgjo/commit/4ca775bc92ea44686731df2be6ecec7e9bf5906f?/06=SCG
<br>
https://github.com/frikter-mi/ynbjgjo/commit/4ca775bc92ea44686731df2be6ecec7e9bf5906f?/LpJ=641
<br>
https://github.com/frikter-mi/ynbjgjo/commit/4ca775bc92ea44686731df2be6ecec7e9bf5906f?/nHl
<br>
https://github.com/pieroacson/liwhqqw/blob/main/2026%E7%AC%AC%E4%B8%80%E6%97%85%E8%A1%8C%E6%8A%A5%E5%91%8A%EF%BC%9A%E7%9A%87%E5%86%A0mos022%E5%BC%80%E6%88%B7%E2%80%94%E8%BE%A8%E6%9C%BA%E8%B4%A2%E7%9C%BC.md?/307=743
<br>
https://github.com/pieroacson/liwhqqw/blob/main/2026%E7%AC%AC%E4%B8%80%E6%97%85%E8%A1%8C%E6%8A%A5%E5%91%8A%EF%BC%9A%E7%9A%87%E5%86%A0mos022%E5%BC%80%E6%88%B7%E2%80%94%E8%BE%A8%E6%9C%BA%E8%B4%A2%E7%9C%BC.md?/vP=tNr
<br>
https://github.com/pieroacson/liwhqqw/blob/main/2026%E7%AC%AC%E4%B8%80%E6%97%85%E8%A1%8C%E6%8A%A5%E5%91%8A%EF%BC%9A%E7%9A%87%E5%86%A0mos022%E5%BC%80%E6%88%B7%E2%80%94%E8%BE%A8%E6%9C%BA%E8%B4%A2%E7%9C%BC.md?/LpJ
<br>
https://github.com/pieroacson/liwhqqw/blob/main/2026%E7%AC%AC%E4%B8%80%E6%97%85%E8%A1%8C%E6%8A%A5%E5%91%8A%EF%BC%9A%E7%9A%87%E5%86%A0mos022%E5%BC%80%E6%88%B7%E2%80%94%E8%BE%A8%E6%9C%BA%E8%B4%A2%E7%9C%BC.md
<br>
https://github.com/pieroacson/liwhqqw/commit/7bcf3e4d9b85b0320e09034f8b6bef13afdfa3c4?/07=CNX
<br>
https://github.com/pieroacson/liwhqqw/commit/7bcf3e4d9b85b0320e09034f8b6bef13afdfa3c4?/nHl=662
<br>
https://github.com/pieroacson/liwhqqw/commit/7bcf3e4d9b85b0320e09034f8b6bef13afdfa3c4?/FjD
<br>
https://github.com/sneunhreniyumno/iwtdmtk/blob/main/2026%E4%B8%93%E6%A0%8F%E7%90%86%E8%B4%A2%E8%A7%82%E5%AF%9F%EF%BC%9A%E7%9A%87%E5%86%A0mos033%E5%BC%80%E6%88%B7%E2%80%94%E6%9A%B9%E7%BD%97%E8%B4%A2%E7%BB%8F.md?/453=567
<br>
https://github.com/sneunhreniyumno/iwtdmtk/blob/main/2026%E4%B8%93%E6%A0%8F%E7%90%86%E8%B4%A2%E8%A7%82%E5%AF%9F%EF%BC%9A%E7%9A%87%E5%86%A0mos033%E5%BC%80%E6%88%B7%E2%80%94%E6%9A%B9%E7%BD%97%E8%B4%A2%E7%BB%8F.md?/w3=Hos
<br>
https://github.com/sneunhreniyumno/iwtdmtk/blob/main/2026%E4%B8%93%E6%A0%8F%E7%90%86%E8%B4%A2%E8%A7%82%E5%AF%9F%EF%BC%9A%E7%9A%87%E5%86%A0mos033%E5%BC%80%E6%88%B7%E2%80%94%E6%9A%B9%E7%BD%97%E8%B4%A2%E7%BB%8F.md?/WJQ
<br>
https://github.com/sneunhreniyumno/iwtdmtk/blob/main/2026%E4%B8%93%E6%A0%8F%E7%90%86%E8%B4%A2%E8%A7%82%E5%AF%9F%EF%BC%9A%E7%9A%87%E5%86%A0mos033%E5%BC%80%E6%88%B7%E2%80%94%E6%9A%B9%E7%BD%97%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/sneunhreniyumno/iwtdmtk/commit/3ed53d88609d3e471ce30b82c4c14610870b8059?/77=OHH
<br>
https://github.com/sneunhreniyumno/iwtdmtk/commit/3ed53d88609d3e471ce30b82c4c14610870b8059?/Ae8=155
<br>
https://github.com/sneunhreniyumno/iwtdmtk/commit/3ed53d88609d3e471ce30b82c4c14610870b8059?/c6a
<br>
https://github.com/pieroacson/jgdoukd/blob/main/2026%E8%87%AA%E5%8A%A8%E9%A9%BE%E9%A9%B6%E7%83%AD%E6%90%9C%EF%BC%9A%E7%9A%87%E5%86%A0mos055%E5%BC%80%E6%88%B7%E2%80%94%E6%95%8F%E6%8D%B7%E5%BC%80%E5%8F%91%E8%AE%BA%E5%9D%9B.md?/607=793
<br>
https://github.com/pieroacson/jgdoukd/blob/main/2026%E8%87%AA%E5%8A%A8%E9%A9%BE%E9%A9%B6%E7%83%AD%E6%90%9C%EF%BC%9A%E7%9A%87%E5%86%A0mos055%E5%BC%80%E6%88%B7%E2%80%94%E6%95%8F%E6%8D%B7%E5%BC%80%E5%8F%91%E8%AE%BA%E5%9D%9B.md?/K8=l26
<br>
https://github.com/pieroacson/jgdoukd/blob/main/2026%E8%87%AA%E5%8A%A8%E9%A9%BE%E9%A9%B6%E7%83%AD%E6%90%9C%EF%BC%9A%E7%9A%87%E5%86%A0mos055%E5%BC%80%E6%88%B7%E2%80%94%E6%95%8F%E6%8D%B7%E5%BC%80%E5%8F%91%E8%AE%BA%E5%9D%9B.md?/kXe
<br>
https://github.com/pieroacson/jgdoukd/blob/main/2026%E8%87%AA%E5%8A%A8%E9%A9%BE%E9%A9%B6%E7%83%AD%E6%90%9C%EF%BC%9A%E7%9A%87%E5%86%A0mos055%E5%BC%80%E6%88%B7%E2%80%94%E6%95%8F%E6%8D%B7%E5%BC%80%E5%8F%91%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/pieroacson/jgdoukd/commit/59984bd56bc081aeeeb15a0be13d8e84f39238be?/61=SHP
<br>
https://github.com/pieroacson/jgdoukd/commit/59984bd56bc081aeeeb15a0be13d8e84f39238be?/OsM=933
<br>
https://github.com/pieroacson/jgdoukd/commit/59984bd56bc081aeeeb15a0be13d8e84f39238be?/qKo
<br>
https://github.com/sneunhreniyumno/dthfyin/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8B%86%E8%A7%A3%EF%BC%9A%E7%9A%87%E5%86%A0hga027%E5%BC%80%E6%88%B7%E2%80%94%E6%8E%A8%E6%BC%94%E8%B4%A2%E7%BB%8F.md?/641=016
<br>
https://github.com/sneunhreniyumno/dthfyin/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8B%86%E8%A7%A3%EF%BC%9A%E7%9A%87%E5%86%A0hga027%E5%BC%80%E6%88%B7%E2%80%94%E6%8E%A8%E6%BC%94%E8%B4%A2%E7%BB%8F.md?/5Z=3X1
<br>
https://github.com/sneunhreniyumno/dthfyin/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8B%86%E8%A7%A3%EF%BC%9A%E7%9A%87%E5%86%A0hga027%E5%BC%80%E6%88%B7%E2%80%94%E6%8E%A8%E6%BC%94%E8%B4%A2%E7%BB%8F.md?/VzT
<br>
https://github.com/sneunhreniyumno/dthfyin/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8B%86%E8%A7%A3%EF%BC%9A%E7%9A%87%E5%86%A0hga027%E5%BC%80%E6%88%B7%E2%80%94%E6%8E%A8%E6%BC%94%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/sneunhreniyumno/dthfyin/commit/b63d0370038c9898cafac50756f8cd314c25503f?/96=DBW
<br>
https://github.com/sneunhreniyumno/dthfyin/commit/b63d0370038c9898cafac50756f8cd314c25503f?/xRv=915
<br>
https://github.com/sneunhreniyumno/dthfyin/commit/b63d0370038c9898cafac50756f8cd314c25503f?/PtN
<br>
https://github.com/pieroacson/kzaqpqd/blob/main/2026%E7%AC%AC%E4%B8%80%E7%A7%91%E6%8A%80%E6%8A%A5%E5%91%8A%EF%BC%9Ahg1088%E5%AE%98%E7%BD%91%E5%BC%80%E6%88%B7%E2%80%94%E5%8C%97%E6%9E%81%E8%AE%BA%E5%9D%9B.md?/091=009
<br>
https://github.com/pieroacson/kzaqpqd/blob/main/2026%E7%AC%AC%E4%B8%80%E7%A7%91%E6%8A%80%E6%8A%A5%E5%91%8A%EF%BC%9Ahg1088%E5%AE%98%E7%BD%91%E5%BC%80%E6%88%B7%E2%80%94%E5%8C%97%E6%9E%81%E8%AE%BA%E5%9D%9B.md?/u2=mJr
<br>
https://github.com/pieroacson/kzaqpqd/blob/main/2026%E7%AC%AC%E4%B8%80%E7%A7%91%E6%8A%80%E6%8A%A5%E5%91%8A%EF%BC%9Ahg1088%E5%AE%98%E7%BD%91%E5%BC%80%E6%88%B7%E2%80%94%E5%8C%97%E6%9E%81%E8%AE%BA%E5%9D%9B.md?/VIP
<br>
https://github.com/pieroacson/kzaqpqd/blob/main/2026%E7%AC%AC%E4%B8%80%E7%A7%91%E6%8A%80%E6%8A%A5%E5%91%8A%EF%BC%9Ahg1088%E5%AE%98%E7%BD%91%E5%BC%80%E6%88%B7%E2%80%94%E5%8C%97%E6%9E%81%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/pieroacson/kzaqpqd/commit/2594b4804214319e6b7edc7c642fad23fea0983e?/88=WRT
<br>
https://github.com/pieroacson/kzaqpqd/commit/2594b4804214319e6b7edc7c642fad23fea0983e?/9d7=811
<br>
https://github.com/pieroacson/kzaqpqd/commit/2594b4804214319e6b7edc7c642fad23fea0983e?/b5Z
<br>
https://github.com/yoandingspan/grigaal/blob/main/2026%20%E7%A7%91%E6%99%AE%E5%8F%A4%E4%BB%A3%E5%B1%85%E6%89%80%EF%BC%9A%E7%9A%87%E5%86%A0hga030%E5%BC%80%E6%88%B7%E2%80%94%E7%AA%A5%E9%89%B4%E8%B4%A2%E7%BB%8F.md?/675=976
<br>
https://github.com/yoandingspan/grigaal/blob/main/2026%20%E7%A7%91%E6%99%AE%E5%8F%A4%E4%BB%A3%E5%B1%85%E6%89%80%EF%BC%9A%E7%9A%87%E5%86%A0hga030%E5%BC%80%E6%88%B7%E2%80%94%E7%AA%A5%E9%89%B4%E8%B4%A2%E7%BB%8F.md?/Mg=qhR
<br>
https://github.com/yoandingspan/grigaal/blob/main/2026%20%E7%A7%91%E6%99%AE%E5%8F%A4%E4%BB%A3%E5%B1%85%E6%89%80%EF%BC%9A%E7%9A%87%E5%86%A0hga030%E5%BC%80%E6%88%B7%E2%80%94%E7%AA%A5%E9%89%B4%E8%B4%A2%E7%BB%8F.md?/vPt
<br>
https://github.com/yoandingspan/grigaal/blob/main/2026%20%E7%A7%91%E6%99%AE%E5%8F%A4%E4%BB%A3%E5%B1%85%E6%89%80%EF%BC%9A%E7%9A%87%E5%86%A0hga030%E5%BC%80%E6%88%B7%E2%80%94%E7%AA%A5%E9%89%B4%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/yoandingspan/grigaal/commit/8fba709a212495797d1dd71cf000ecec82031452?/43=MXE
<br>
https://github.com/yoandingspan/grigaal/commit/8fba709a212495797d1dd71cf000ecec82031452?/NrL=401
<br>
https://github.com/yoandingspan/grigaal/commit/8fba709a212495797d1dd71cf000ecec82031452?/pJn
<br>
https://github.com/frikter-mi/fbdgccy/blob/main/2026%E5%AE%98%E6%96%B9%E4%BA%91%E8%AE%B2%E8%A7%A3%3A%E7%9A%87%E5%86%A0hga025%E5%BC%80%E6%88%B7%E2%80%94%E6%A5%9A%E6%B9%98%E8%B4%A2%E7%BB%8F.md?/896=373
<br>
https://github.com/frikter-mi/fbdgccy/blob/main/2026%E5%AE%98%E6%96%B9%E4%BA%91%E8%AE%B2%E8%A7%A3%3A%E7%9A%87%E5%86%A0hga025%E5%BC%80%E6%88%B7%E2%80%94%E6%A5%9A%E6%B9%98%E8%B4%A2%E7%BB%8F.md?/Kv=8ZT
<br>
https://github.com/frikter-mi/fbdgccy/blob/main/2026%E5%AE%98%E6%96%B9%E4%BA%91%E8%AE%B2%E8%A7%A3%3A%E7%9A%87%E5%86%A0hga025%E5%BC%80%E6%88%B7%E2%80%94%E6%A5%9A%E6%B9%98%E8%B4%A2%E7%BB%8F.md?/GN7
<br>
https://github.com/frikter-mi/fbdgccy/blob/main/2026%E5%AE%98%E6%96%B9%E4%BA%91%E8%AE%B2%E8%A7%A3%3A%E7%9A%87%E5%86%A0hga025%E5%BC%80%E6%88%B7%E2%80%94%E6%A5%9A%E6%B9%98%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/frikter-mi/fbdgccy/commit/835e4868b9243d74f215a77db73fea3652867810?/12=ETR
<br>
https://github.com/frikter-mi/fbdgccy/commit/835e4868b9243d74f215a77db73fea3652867810?/b5Z=948
<br>
https://github.com/frikter-mi/fbdgccy/commit/835e4868b9243d74f215a77db73fea3652867810?/3X1
<br>
https://github.com/sneunhreniyumno/qyoyuva/blob/main/2026%E5%AE%98%E6%96%B9%E5%A4%A7%E5%B0%8F%E8%AF%BE%E5%A0%82%3A%E7%9A%87%E5%86%A0hga035%E5%BC%80%E6%88%B7%E2%80%94%E9%AB%98%E6%9E%B6%E8%B4%A2%E7%BB%8F.md?/745=304
<br>
https://github.com/sneunhreniyumno/qyoyuva/blob/main/2026%E5%AE%98%E6%96%B9%E5%A4%A7%E5%B0%8F%E8%AF%BE%E5%A0%82%3A%E7%9A%87%E5%86%A0hga035%E5%BC%80%E6%88%B7%E2%80%94%E9%AB%98%E6%9E%B6%E8%B4%A2%E7%BB%8F.md?/fj=NhL
<br>
https://github.com/sneunhreniyumno/qyoyuva/blob/main/2026%E5%AE%98%E6%96%B9%E5%A4%A7%E5%B0%8F%E8%AF%BE%E5%A0%82%3A%E7%9A%87%E5%86%A0hga035%E5%BC%80%E6%88%B7%E2%80%94%E9%AB%98%E6%9E%B6%E8%B4%A2%E7%BB%8F.md?/8FT
<br>
https://github.com/sneunhreniyumno/qyoyuva/blob/main/2026%E5%AE%98%E6%96%B9%E5%A4%A7%E5%B0%8F%E8%AF%BE%E5%A0%82%3A%E7%9A%87%E5%86%A0hga035%E5%BC%80%E6%88%B7%E2%80%94%E9%AB%98%E6%9E%B6%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/sneunhreniyumno/qyoyuva/commit/a270e026fad7d9c6e4bf37c00cb3cf2813b358de?/59=TRZ
<br>
https://github.com/sneunhreniyumno/qyoyuva/commit/a270e026fad7d9c6e4bf37c00cb3cf2813b358de?/xRv=179
<br>
https://github.com/sneunhreniyumno/qyoyuva/commit/a270e026fad7d9c6e4bf37c00cb3cf2813b358de?/PtN
<br>
https://github.com/frikter-mi/ufjtgup/blob/main/2026%E4%B8%93%E6%A0%8F%E6%9C%88%E5%BA%A6%E6%94%BB%E7%95%A5%EF%BC%9A%E7%9A%87%E5%86%A0hga026%E5%BC%80%E6%88%B7%E2%80%94%E5%85%BB%E7%94%9F%E8%AE%BA%E5%9D%9B.md?/243=120
<br>
https://github.com/frikter-mi/ufjtgup/blob/main/2026%E4%B8%93%E6%A0%8F%E6%9C%88%E5%BA%A6%E6%94%BB%E7%95%A5%EF%BC%9A%E7%9A%87%E5%86%A0hga026%E5%BC%80%E6%88%B7%E2%80%94%E5%85%BB%E7%94%9F%E8%AE%BA%E5%9D%9B.md?/Cg=Ae8
<br>
https://github.com/frikter-mi/ufjtgup/blob/main/2026%E4%B8%93%E6%A0%8F%E6%9C%88%E5%BA%A6%E6%94%BB%E7%95%A5%EF%BC%9A%E7%9A%87%E5%86%A0hga026%E5%BC%80%E6%88%B7%E2%80%94%E5%85%BB%E7%94%9F%E8%AE%BA%E5%9D%9B.md?/c6a
<br>
https://github.com/frikter-mi/ufjtgup/blob/main/2026%E4%B8%93%E6%A0%8F%E6%9C%88%E5%BA%A6%E6%94%BB%E7%95%A5%EF%BC%9A%E7%9A%87%E5%86%A0hga026%E5%BC%80%E6%88%B7%E2%80%94%E5%85%BB%E7%94%9F%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/frikter-mi/ufjtgup/commit/25c23e13d996a48c4581fcc19954f3f991afa33b?/52=PDO
<br>
https://github.com/frikter-mi/ufjtgup/commit/25c23e13d996a48c4581fcc19954f3f991afa33b?/4Y2=740
<br>
https://github.com/frikter-mi/ufjtgup/commit/25c23e13d996a48c4581fcc19954f3f991afa33b?/W0U
<br>
https://github.com/bizimackio/xdebrir/blob/main/2026%E4%B8%93%E6%A0%8F%E6%AF%8F%E6%97%A5%E8%A7%A3%E8%AF%BB%EF%BC%9A%E7%9A%87%E5%86%A0%E4%BC%9A%E5%91%98%E5%BC%80%E6%88%B7%E6%B3%A8%E5%86%8C%E2%80%94%E8%87%AA%E9%A9%BE%E6%B8%B8%E8%AE%BA%E5%9D%9B.md?/147=163
<br>
https://github.com/bizimackio/xdebrir/blob/main/2026%E4%B8%93%E6%A0%8F%E6%AF%8F%E6%97%A5%E8%A7%A3%E8%AF%BB%EF%BC%9A%E7%9A%87%E5%86%A0%E4%BC%9A%E5%91%98%E5%BC%80%E6%88%B7%E6%B3%A8%E5%86%8C%E2%80%94%E8%87%AA%E9%A9%BE%E6%B8%B8%E8%AE%BA%E5%9D%9B.md?/iC=gAe
<br>
https://github.com/bizimackio/xdebrir/blob/main/2026%E4%B8%93%E6%A0%8F%E6%AF%8F%E6%97%A5%E8%A7%A3%E8%AF%BB%EF%BC%9A%E7%9A%87%E5%86%A0%E4%BC%9A%E5%91%98%E5%BC%80%E6%88%B7%E6%B3%A8%E5%86%8C%E2%80%94%E8%87%AA%E9%A9%BE%E6%B8%B8%E8%AE%BA%E5%9D%9B.md?/8c6
<br>
https://github.com/bizimackio/xdebrir/blob/main/2026%E4%B8%93%E6%A0%8F%E6%AF%8F%E6%97%A5%E8%A7%A3%E8%AF%BB%EF%BC%9A%E7%9A%87%E5%86%A0%E4%BC%9A%E5%91%98%E5%BC%80%E6%88%B7%E6%B3%A8%E5%86%8C%E2%80%94%E8%87%AA%E9%A9%BE%E6%B8%B8%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/bizimackio/xdebrir/commit/4726504945761c20e98166076297edc2c8fc10d3?/89=WSM
<br>
https://github.com/bizimackio/xdebrir/commit/4726504945761c20e98166076297edc2c8fc10d3?/a4Y=128
<br>
https://github.com/bizimackio/xdebrir/commit/4726504945761c20e98166076297edc2c8fc10d3?/2W0
<br>
https://github.com/sneunhreniyumno/clzwuqs/blob/main/2026%20%E7%A7%91%E6%99%AE%E7%87%83%E7%83%A7%EF%BC%9A%E7%9A%87%E5%86%A0hga050%E5%BC%80%E6%88%B7%E2%80%94%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F.md?/543=735
<br>
https://github.com/sneunhreniyumno/clzwuqs/blob/main/2026%20%E7%A7%91%E6%99%AE%E7%87%83%E7%83%A7%EF%BC%9A%E7%9A%87%E5%86%A0hga050%E5%BC%80%E6%88%B7%E2%80%94%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F.md?/hf=60J
<br>
https://github.com/sneunhreniyumno/clzwuqs/blob/main/2026%20%E7%A7%91%E6%99%AE%E7%87%83%E7%83%A7%EF%BC%9A%E7%9A%87%E5%86%A0hga050%E5%BC%80%E6%88%B7%E2%80%94%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F.md?/xls
<br>
https://github.com/sneunhreniyumno/clzwuqs/blob/main/2026%20%E7%A7%91%E6%99%AE%E7%87%83%E7%83%A7%EF%BC%9A%E7%9A%87%E5%86%A0hga050%E5%BC%80%E6%88%B7%E2%80%94%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/sneunhreniyumno/clzwuqs/commit/883d9b3e867051623c6986c39bf31e5a06ccbf34?/55=AWR
<br>
https://github.com/sneunhreniyumno/clzwuqs/commit/883d9b3e867051623c6986c39bf31e5a06ccbf34?/c6a=510
<br>
https://github.com/sneunhreniyumno/clzwuqs/commit/883d9b3e867051623c6986c39bf31e5a06ccbf34?/4Y2
<br>
https://github.com/bizimackio/ywlpubk/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A4%E7%9F%A5%EF%BC%9A%E7%9A%87%E5%86%A0hga038%E5%BC%80%E6%88%B7%E2%80%94%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%AF%8D%E5%A9%B4%E6%9D%BF%E5%9D%97.md?/328=581
<br>
https://github.com/bizimackio/ywlpubk/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A4%E7%9F%A5%EF%BC%9A%E7%9A%87%E5%86%A0hga038%E5%BC%80%E6%88%B7%E2%80%94%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%AF%8D%E5%A9%B4%E6%9D%BF%E5%9D%97.md?/PN=oi2
<br>
https://github.com/bizimackio/ywlpubk/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A4%E7%9F%A5%EF%BC%9A%E7%9A%87%E5%86%A0hga038%E5%BC%80%E6%88%B7%E2%80%94%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%AF%8D%E5%A9%B4%E6%9D%BF%E5%9D%97.md?/fTa
<br>
https://github.com/bizimackio/ywlpubk/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A4%E7%9F%A5%EF%BC%9A%E7%9A%87%E5%86%A0hga038%E5%BC%80%E6%88%B7%E2%80%94%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%AF%8D%E5%A9%B4%E6%9D%BF%E5%9D%97.md
<br>
https://github.com/bizimackio/ywlpubk/commit/70538f1e92a6917d54d98a80b66e4f077897d8a2?/44=XSB
<br>
https://github.com/bizimackio/ywlpubk/commit/70538f1e92a6917d54d98a80b66e4f077897d8a2?/KoI=717
<br>
https://github.com/bizimackio/ywlpubk/commit/70538f1e92a6917d54d98a80b66e4f077897d8a2?/mGk
<br>
https://github.com/pieroacson/txgtafg/blob/main/2026%E4%BA%92%E8%81%94%E7%BD%91%E4%BD%9C%E4%B8%9A%E5%AE%89%E5%85%A8%E8%A7%84%E7%A8%8B%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E5%BC%80%E6%88%B7%E2%80%94%E6%96%B0%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F.md?/221=035
<br>
https://github.com/pieroacson/txgtafg/blob/main/2026%E4%BA%92%E8%81%94%E7%BD%91%E4%BD%9C%E4%B8%9A%E5%AE%89%E5%85%A8%E8%A7%84%E7%A8%8B%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E5%BC%80%E6%88%B7%E2%80%94%E6%96%B0%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F.md?/Im=GkE
<br>
https://github.com/pieroacson/txgtafg/blob/main/2026%E4%BA%92%E8%81%94%E7%BD%91%E4%BD%9C%E4%B8%9A%E5%AE%89%E5%85%A8%E8%A7%84%E7%A8%8B%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E5%BC%80%E6%88%B7%E2%80%94%E6%96%B0%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F.md?/iCg
<br>
https://github.com/pieroacson/txgtafg/blob/main/2026%E4%BA%92%E8%81%94%E7%BD%91%E4%BD%9C%E4%B8%9A%E5%AE%89%E5%85%A8%E8%A7%84%E7%A8%8B%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E5%BC%80%E6%88%B7%E2%80%94%E6%96%B0%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/pieroacson/txgtafg/commit/93d07ffef9f91113bf69e77d4c23bbe8864fb49c?/00=IEC
<br>
https://github.com/pieroacson/txgtafg/commit/93d07ffef9f91113bf69e77d4c23bbe8864fb49c?/Ae8=355
<br>
https://github.com/pieroacson/txgtafg/commit/93d07ffef9f91113bf69e77d4c23bbe8864fb49c?/c6a
<br>
https://github.com/bizimackio/jrfetkt/blob/main/2026%20%E7%A7%91%E6%99%AE%E7%BB%BF%E7%94%B5%EF%BC%9A%E7%9A%87%E5%86%A0hga039%E5%BC%80%E6%88%B7%E2%80%94%E6%95%B0%E7%A0%81%E8%AE%BA%E5%9D%9B.md?/049=421
<br>
https://github.com/bizimackio/jrfetkt/blob/main/2026%20%E7%A7%91%E6%99%AE%E7%BB%BF%E7%94%B5%EF%BC%9A%E7%9A%87%E5%86%A0hga039%E5%BC%80%E6%88%B7%E2%80%94%E6%95%B0%E7%A0%81%E8%AE%BA%E5%9D%9B.md?/Bl=wmU
<br>
https://github.com/bizimackio/jrfetkt/blob/main/2026%20%E7%A7%91%E6%99%AE%E7%BB%BF%E7%94%B5%EF%BC%9A%E7%9A%87%E5%86%A0hga039%E5%BC%80%E6%88%B7%E2%80%94%E6%95%B0%E7%A0%81%E8%AE%BA%E5%9D%9B.md?/Rsj
<br>
https://github.com/bizimackio/jrfetkt/blob/main/2026%20%E7%A7%91%E6%99%AE%E7%BB%BF%E7%94%B5%EF%BC%9A%E7%9A%87%E5%86%A0hga039%E5%BC%80%E6%88%B7%E2%80%94%E6%95%B0%E7%A0%81%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/bizimackio/jrfetkt/commit/fafff5753cf3f78f7642c803ace42b43cdd56557?/18=CKY
<br>
https://github.com/bizimackio/jrfetkt/commit/fafff5753cf3f78f7642c803ace42b43cdd56557?/TxR=419
<br>
https://github.com/bizimackio/jrfetkt/commit/fafff5753cf3f78f7642c803ace42b43cdd56557?/vPt
<br>
https://github.com/yoandingspan/awcsdoo/blob/main/2026%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%99%BE%E7%A7%91%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB1%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E5%A4%A9%E6%B6%AF%E8%AE%BA%E5%9D%9B.md?/609=007
<br>
https://github.com/yoandingspan/awcsdoo/blob/main/2026%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%99%BE%E7%A7%91%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB1%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E5%A4%A9%E6%B6%AF%E8%AE%BA%E5%9D%9B.md?/gA=e8c
<br>
https://github.com/yoandingspan/awcsdoo/blob/main/2026%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%99%BE%E7%A7%91%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB1%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E5%A4%A9%E6%B6%AF%E8%AE%BA%E5%9D%9B.md?/6a4
<br>
https://github.com/yoandingspan/awcsdoo/blob/main/2026%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%99%BE%E7%A7%91%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB1%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E5%A4%A9%E6%B6%AF%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/yoandingspan/awcsdoo/commit/f8dad1cc79e9c25bb406473e0d77b8f99c76a3e2?/96=TEU
<br>
https://github.com/yoandingspan/awcsdoo/commit/f8dad1cc79e9c25bb406473e0d77b8f99c76a3e2?/Y2W=421
<br>
https://github.com/yoandingspan/awcsdoo/commit/f8dad1cc79e9c25bb406473e0d77b8f99c76a3e2?/0Uy
<br>
https://github.com/pieroacson/oriueid/blob/main/2026%E5%AE%98%E6%96%B9%E7%BE%8E%E7%9B%9B%E4%B8%BE%3A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E4%BB%A3%E7%90%86%E2%80%94%E6%98%8E%E8%BE%A8%E8%B4%A2%E7%BB%8F.md?/370=836
<br>
https://github.com/pieroacson/oriueid/blob/main/2026%E5%AE%98%E6%96%B9%E7%BE%8E%E7%9B%9B%E4%B8%BE%3A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E4%BB%A3%E7%90%86%E2%80%94%E6%98%8E%E8%BE%A8%E8%B4%A2%E7%BB%8F.md?/au=4vf
<br>
https://github.com/pieroacson/oriueid/blob/main/2026%E5%AE%98%E6%96%B9%E7%BE%8E%E7%9B%9B%E4%B8%BE%3A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E4%BB%A3%E7%90%86%E2%80%94%E6%98%8E%E8%BE%A8%E8%B4%A2%E7%BB%8F.md?/9d7
<br>
https://github.com/pieroacson/oriueid/blob/main/2026%E5%AE%98%E6%96%B9%E7%BE%8E%E7%9B%9B%E4%B8%BE%3A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E4%BB%A3%E7%90%86%E2%80%94%E6%98%8E%E8%BE%A8%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/pieroacson/oriueid/commit/64c5d63f08aa7f855ae04b94948a87ee6ffcaa42?/92=POT
<br>
https://github.com/pieroacson/oriueid/commit/64c5d63f08aa7f855ae04b94948a87ee6ffcaa42?/b5Z=726
<br>
https://github.com/pieroacson/oriueid/commit/64c5d63f08aa7f855ae04b94948a87ee6ffcaa42?/31V
<br>
https://github.com/yoandingspan/uqnyfaj/blob/main/2026%20%E7%A7%91%E6%99%AE%E5%A2%93%E8%91%AC%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E6%B5%B7%E5%A4%96%E5%8D%8E%E4%BA%BA%E8%AE%BA%E5%9D%9B.md?/300=079
<br>
https://github.com/yoandingspan/uqnyfaj/blob/main/2026%20%E7%A7%91%E6%99%AE%E5%A2%93%E8%91%AC%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E6%B5%B7%E5%A4%96%E5%8D%8E%E4%BA%BA%E8%AE%BA%E5%9D%9B.md?/hY=ImG
<br>
https://github.com/yoandingspan/uqnyfaj/blob/main/2026%20%E7%A7%91%E6%99%AE%E5%A2%93%E8%91%AC%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E6%B5%B7%E5%A4%96%E5%8D%8E%E4%BA%BA%E8%AE%BA%E5%9D%9B.md?/kEi
<br>
https://github.com/yoandingspan/uqnyfaj/blob/main/2026%20%E7%A7%91%E6%99%AE%E5%A2%93%E8%91%AC%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E6%B5%B7%E5%A4%96%E5%8D%8E%E4%BA%BA%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/yoandingspan/uqnyfaj/commit/3f9015efaaf372a6d3d0deea1991350428f29399?/33=ECC
<br>
https://github.com/yoandingspan/uqnyfaj/commit/3f9015efaaf372a6d3d0deea1991350428f29399?/CgA=715
<br>
https://github.com/yoandingspan/uqnyfaj/commit/3f9015efaaf372a6d3d0deea1991350428f29399?/e8c
<br>
https://github.com/frikter-mi/dwwuaxf/blob/main/2026%E5%82%A8%E8%83%BD%E7%B2%BE%E9%80%89%EF%BC%9A%E7%9A%87%E5%86%A0%E8%B6%B3%E7%90%83%E7%99%BB3%E7%A7%9F%E7%94%A8%E2%80%94%E8%A5%BF%E5%8C%97%E8%B4%A2%E7%BB%8F.md?/127=981
<br>
https://github.com/frikter-mi/dwwuaxf/blob/main/2026%E5%82%A8%E8%83%BD%E7%B2%BE%E9%80%89%EF%BC%9A%E7%9A%87%E5%86%A0%E8%B6%B3%E7%90%83%E7%99%BB3%E7%A7%9F%E7%94%A8%E2%80%94%E8%A5%BF%E5%8C%97%E8%B4%A2%E7%BB%8F.md?/gA=d7b
<br>
https://github.com/frikter-mi/dwwuaxf/blob/main/2026%E5%82%A8%E8%83%BD%E7%B2%BE%E9%80%89%EF%BC%9A%E7%9A%87%E5%86%A0%E8%B6%B3%E7%90%83%E7%99%BB3%E7%A7%9F%E7%94%A8%E2%80%94%E8%A5%BF%E5%8C%97%E8%B4%A2%E7%BB%8F.md?/5Z3
<br>
https://github.com/frikter-mi/dwwuaxf/blob/main/2026%E5%82%A8%E8%83%BD%E7%B2%BE%E9%80%89%EF%BC%9A%E7%9A%87%E5%86%A0%E8%B6%B3%E7%90%83%E7%99%BB3%E7%A7%9F%E7%94%A8%E2%80%94%E8%A5%BF%E5%8C%97%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/frikter-mi/dwwuaxf/commit/6d6454f1e962ed5d635ef483915778c9500d293e?/10=BWL
<br>
https://github.com/frikter-mi/dwwuaxf/commit/6d6454f1e962ed5d635ef483915778c9500d293e?/X1V=863
<br>
https://github.com/frikter-mi/dwwuaxf/commit/6d6454f1e962ed5d635ef483915778c9500d293e?/zTx
<br>
https://github.com/bizimackio/smsjbzh/blob/main/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%93%8D%E8%AF%BE%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E7%B3%BB%E7%BB%9F%E2%80%94%E8%81%8C%E5%9C%BA%E8%AE%BA%E5%9D%9B.md?/898=546
<br>
https://github.com/bizimackio/smsjbzh/blob/main/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%93%8D%E8%AF%BE%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E7%B3%BB%E7%BB%9F%E2%80%94%E8%81%8C%E5%9C%BA%E8%AE%BA%E5%9D%9B.md?/SF=M6a
<br>
https://github.com/bizimackio/smsjbzh/blob/main/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%93%8D%E8%AF%BE%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E7%B3%BB%E7%BB%9F%E2%80%94%E8%81%8C%E5%9C%BA%E8%AE%BA%E5%9D%9B.md?/4Y2
<br>
https://github.com/bizimackio/smsjbzh/blob/main/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%93%8D%E8%AF%BE%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E7%B3%BB%E7%BB%9F%E2%80%94%E8%81%8C%E5%9C%BA%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/bizimackio/smsjbzh/commit/aaa92940b88701bcf1ceb5bd5dd6bbe04293b382?/96=RCN
<br>
https://github.com/bizimackio/smsjbzh/commit/aaa92940b88701bcf1ceb5bd5dd6bbe04293b382?/WUy=014
<br>
https://github.com/bizimackio/smsjbzh/commit/aaa92940b88701bcf1ceb5bd5dd6bbe04293b382?/SwQ
<br>
https://github.com/yoandingspan/fjinpdf/blob/main/2026%E7%AC%AC%E4%B8%80%E6%B7%B1%E5%BA%A6%E9%98%85%E8%AF%BB%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E5%B9%B3%E5%8F%B0%E2%80%94%E4%B9%92%E4%B9%93%E7%90%83%E8%AE%BA%E5%9D%9B.md?/604=536
<br>
https://github.com/yoandingspan/fjinpdf/blob/main/2026%E7%AC%AC%E4%B8%80%E6%B7%B1%E5%BA%A6%E9%98%85%E8%AF%BB%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E5%B9%B3%E5%8F%B0%E2%80%94%E4%B9%92%E4%B9%93%E7%90%83%E8%AE%BA%E5%9D%9B.md?/Z3=X1V
<br>
https://github.com/yoandingspan/fjinpdf/blob/main/2026%E7%AC%AC%E4%B8%80%E6%B7%B1%E5%BA%A6%E9%98%85%E8%AF%BB%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E5%B9%B3%E5%8F%B0%E2%80%94%E4%B9%92%E4%B9%93%E7%90%83%E8%AE%BA%E5%9D%9B.md?/zTx
<br>
https://github.com/yoandingspan/fjinpdf/blob/main/2026%E7%AC%AC%E4%B8%80%E6%B7%B1%E5%BA%A6%E9%98%85%E8%AF%BB%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E5%B9%B3%E5%8F%B0%E2%80%94%E4%B9%92%E4%B9%93%E7%90%83%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/yoandingspan/fjinpdf/commit/2342bfbdc562c3c04e9e6fb1444fb9401f0933fd?/34=XMA
<br>
https://github.com/yoandingspan/fjinpdf/commit/2342bfbdc562c3c04e9e6fb1444fb9401f0933fd?/Icm=560
<br>
https://github.com/yoandingspan/fjinpdf/commit/2342bfbdc562c3c04e9e6fb1444fb9401f0933fd?/dNr
<br>
https://github.com/sneunhreniyumno/nrekhjx/blob/main/2026%E6%99%BA%E8%83%BD%E7%A6%8F%E5%88%A9%E5%A4%9A%E5%A4%9A%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB2%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E5%BD%92%E5%AE%9E%E8%B4%A2%E7%BB%8F.md?/962=509
<br>
https://github.com/sneunhreniyumno/nrekhjx/blob/main/2026%E6%99%BA%E8%83%BD%E7%A6%8F%E5%88%A9%E5%A4%9A%E5%A4%9A%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB2%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E5%BD%92%E5%AE%9E%E8%B4%A2%E7%BB%8F.md?/2A=uRV
<br>
https://github.com/sneunhreniyumno/nrekhjx/blob/main/2026%E6%99%BA%E8%83%BD%E7%A6%8F%E5%88%A9%E5%A4%9A%E5%A4%9A%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB2%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E5%BD%92%E5%AE%9E%E8%B4%A2%E7%BB%8F.md?/9w3
<br>
https://github.com/sneunhreniyumno/nrekhjx/blob/main/2026%E6%99%BA%E8%83%BD%E7%A6%8F%E5%88%A9%E5%A4%9A%E5%A4%9A%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB2%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E5%BD%92%E5%AE%9E%E8%B4%A2%E7%BB%8F.md
<br>
https://github.com/sneunhreniyumno/nrekhjx/commit/3d8d9b916cfeec8fd48cdead061c56ff5f46d6f0?/64=CLN
<br>
https://github.com/sneunhreniyumno/nrekhjx/commit/3d8d9b916cfeec8fd48cdead061c56ff5f46d6f0?/nHl=162
<br>
https://github.com/sneunhreniyumno/nrekhjx/commit/3d8d9b916cfeec8fd48cdead061c56ff5f46d6f0?/FjD
<br>
https://github.com/yoandingspan/purwnoy/blob/main/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E5%88%86%E6%9E%90%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E8%B6%B3%E7%90%83%E2%80%94IDC%E8%AE%BA%E5%9D%9B.md?/568=055
<br>
https://github.com/yoandingspan/purwnoy/blob/main/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E5%88%86%E6%9E%90%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E8%B6%B3%E7%90%83%E2%80%94IDC%E8%AE%BA%E5%9D%9B.md?/hB=f9d
<br>
https://github.com/yoandingspan/purwnoy/blob/main/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E5%88%86%E6%9E%90%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E8%B6%B3%E7%90%83%E2%80%94IDC%E8%AE%BA%E5%9D%9B.md?/b5Z
<br>
https://github.com/yoandingspan/purwnoy/blob/main/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E5%88%86%E6%9E%90%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E8%B6%B3%E7%90%83%E2%80%94IDC%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/yoandingspan/purwnoy/commit/94f89630e41cce750f45254803618cf280e17aaa?/26=SXE
<br>
https://github.com/yoandingspan/purwnoy/commit/94f89630e41cce750f45254803618cf280e17aaa?/3X1=817
<br>
https://github.com/yoandingspan/purwnoy/commit/94f89630e41cce750f45254803618cf280e17aaa?/VzT
<br>
https://github.com/sneunhreniyumno/vbtsbpv/blob/main/2026%20%E7%A7%91%E6%99%AE%E5%B0%84%E9%A2%91%EF%BC%9A%E7%9A%87%E5%86%A0%E8%B6%B3%E7%90%83%E7%99%BB2%E7%A7%9F%E7%94%A8%E2%80%94%E4%BC%81%E4%B8%9A%E8%AE%BA%E5%9D%9B.md?/203=340
<br>
https://github.com/sneunhreniyumno/vbtsbpv/blob/main/2026%20%E7%A7%91%E6%99%AE%E5%B0%84%E9%A2%91%EF%BC%9A%E7%9A%87%E5%86%A0%E8%B6%B3%E7%90%83%E7%99%BB2%E7%A7%9F%E7%94%A8%E2%80%94%E4%BC%81%E4%B8%9A%E8%AE%BA%E5%9D%9B.md?/Y2=W0U
<br>
https://github.com/sneunhreniyumno/vbtsbpv/blob/main/2026%20%E7%A7%91%E6%99%AE%E5%B0%84%E9%A2%91%EF%BC%9A%E7%9A%87%E5%86%A0%E8%B6%B3%E7%90%83%E7%99%BB2%E7%A7%9F%E7%94%A8%E2%80%94%E4%BC%81%E4%B8%9A%E8%AE%BA%E5%9D%9B.md?/ySw
<br>
https://github.com/sneunhreniyumno/vbtsbpv/blob/main/2026%20%E7%A7%91%E6%99%AE%E5%B0%84%E9%A2%91%EF%BC%9A%E7%9A%87%E5%86%A0%E8%B6%B3%E7%90%83%E7%99%BB2%E7%A7%9F%E7%94%A8%E2%80%94%E4%BC%81%E4%B8%9A%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/sneunhreniyumno/vbtsbpv/commit/04486880cc88326f3909e3721f6378c07685a224?/52=HQU
<br>
https://github.com/sneunhreniyumno/vbtsbpv/commit/04486880cc88326f3909e3721f6378c07685a224?/QuO=839
<br>
https://github.com/sneunhreniyumno/vbtsbpv/commit/04486880cc88326f3909e3721f6378c07685a224?/sMq
<br>
https://github.com/yoandingspan/rljagql/blob/main/2027%E5%AE%98%E6%96%B9%E5%A4%A7%E7%A7%92%E6%87%82%3A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E7%A7%9F%E7%94%A8%E2%80%94%E7%99%BD%E9%85%92%E8%AE%BA%E5%9D%9B.md?/881=669
<br>
https://github.com/yoandingspan/rljagql/blob/main/2027%E5%AE%98%E6%96%B9%E5%A4%A7%E7%A7%92%E6%87%82%3A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E7%A7%9F%E7%94%A8%E2%80%94%E7%99%BD%E9%85%92%E8%AE%BA%E5%9D%9B.md?/4Y=2W0
<br>
https://github.com/yoandingspan/rljagql/blob/main/2027%E5%AE%98%E6%96%B9%E5%A4%A7%E7%A7%92%E6%87%82%3A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E7%A7%9F%E7%94%A8%E2%80%94%E7%99%BD%E9%85%92%E8%AE%BA%E5%9D%9B.md?/UyS
<br>
https://github.com/yoandingspan/rljagql/blob/main/2027%E5%AE%98%E6%96%B9%E5%A4%A7%E7%A7%92%E6%87%82%3A%E7%9A%87%E5%86%A0%E7%99%BB0123%E5%87%BA%E7%A7%9F%E7%A7%9F%E7%94%A8%E2%80%94%E7%99%BD%E9%85%92%E8%AE%BA%E5%9D%9B.md
<br>
https://github.com/yoandingspan/rljagql/commit/fdbf35264c6de7a2b49da39540087a1af2e464e9?/24=DYA
<br>
https://github.com/yoandingspan/rljagql/commit/fdbf35264c6de7a2b49da39540087a1af2e464e9?/wQu=746
<br>
https://github.com/yoandingspan/rljagql/commit/fdbf35264c6de7a2b49da39540087a1af2e464e9?/OsM
<br>
https://github.com/frikter-mi/ijfpwde/blob/main/2026AI%E5%B9%B4%E5%BA%A6%E7%B2%BE%E9%80%89%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E9%99%87%E6%B1%80%E8%B4%A2%E8%AE%BA.md?/438=499
<br>
https://github.com/frikter-mi/ijfpwde/blob/main/2026AI%E5%B9%B4%E5%BA%A6%E7%B2%BE%E9%80%89%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E9%99%87%E6%B1%80%E8%B4%A2%E8%AE%BA.md?/9d=7b5
<br>
https://github.com/frikter-mi/ijfpwde/blob/main/2026AI%E5%B9%B4%E5%BA%A6%E7%B2%BE%E9%80%89%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E9%99%87%E6%B1%80%E8%B4%A2%E8%AE%BA.md?/Z3X
<br>
https://github.com/frikter-mi/ijfpwde/blob/main/2026AI%E5%B9%B4%E5%BA%A6%E7%B2%BE%E9%80%89%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E4%BF%A1%E7%94%A8%E7%A7%9F%E7%94%A8%E2%80%94%E9%99%87%E6%B1%80%E8%B4%A2%E8%AE%BA.md
<br>

<h2>项目结构</h2><br>

项目目录采用模块化分层设计，便于维护与扩展。各子目录职责清晰，核心资源列表与前端展示逻辑分离。


mobile-article-aggregator/
├── public/                          # 静态资源目录，无需构建直接复制
│   ├── favicon.ico                  # 站点图标文件
│   └── robots.txt                   # 搜索引擎爬虫规则，屏蔽非生产环境路径
├── src/                             # 源代码主目录
│   ├── assets/                      # 前端资源文件（图片、字体、全局样式）
│   │   ├── images/                  # 项目用到的矢量图与位图素材
│   │   └── styles/                  # 全局基础样式与 CSS 变量定义
│   ├── components/                  # 可复用的 UI 组件
│   │   ├── LinkList.vue             # 链接列表核心渲染组件，支持分页与过滤
│   │   ├── SearchBar.vue            # 关键字搜索输入组件
│   │   └── CategoryFilter.vue       # 分类标签筛选组件
│   ├── data/                        # 数据层，存放静态链接资源列表
│   │   ├── links.json               # 主链接索引文件，包含全部 250 条记录
│   │   └── categories.json          # 分类映射表，定义标签与链接 ID 的对应关系
│   ├── layouts/                     # 页面布局模板
│   │   ├── default.vue              # 默认两栏布局（侧边栏 + 主内容区）
│   │   └── full-width.vue           # 全宽布局，用于搜索与统计页面
│   ├── pages/                       # 路由页面入口
│   │   ├── index.vue                # 首页，展示全部资源列表与分类概览
│   │   ├── about.vue                # 项目介绍与使用说明页面
│   │   └── stats.vue                # 链接统计信息页面（总数、分类分布）
│   ├── utils/                       # 工具函数库
│   │   ├── validator.js             # 链接格式校验与规范化工具
│   │   └── filter.js                # 数组过滤与排序辅助函数
│   └── main.js                      # 应用入口文件，初始化 Vue 实例与插件
├── scripts/                         # 运维与辅助脚本
│   ├── check-links.sh               # 批量检测链接可用性的 Bash 脚本
│   └── generate-sitemap.js          # 生成站点地图 XML 文件的 Node 脚本
├── tests/                           # 单元测试与集成测试
│   ├── unit/                        # 组件与函数的单元测试用例
│   └── e2e/                         # 端到端测试脚本（基于 Playwright）
├── .gitignore                       # Git 版本忽略规则文件
├── package.json                     # Node.js 项目依赖与脚本定义
├── README.md                        # 项目说明文档（本文件）
├── LICENSE                          # MIT 许可证全文
└── vite.config.js                   # Vite 构建工具配置文件


<h2> 贡献指南</h2><br>

我们欢迎社区开发者以多种形式参与本项目的维护与改进。所有贡献需遵守项目行为准则，并按照以下流程操作。

第一步：查阅现有 Issue 与 Pull Request。在提交新贡献之前，请先浏览 GitHub 上的现有议题，确认无人正在处理相同问题或功能请求，避免重复劳动。

第二步：Fork 项目并创建功能分支。将本仓库 Fork 至个人账号下，然后基于 `main` 分支创建一个新的分支，分支命名建议采用 `feature/功能描述` 或 `fix/问题简述` 的格式。

第三步：完成代码或文档修改。请遵循项目既定的代码风格（ESLint 配置）与提交信息规范（使用 Conventional Commits 格式）。若涉及链接列表的增删，请同步更新 `src/data/links.json` 中的对应条目。

第四步：编写或更新测试用例。对于新增的功能或修复的缺陷，请在 `tests/` 目录下补充相应的单元测试或端到端测试，确保代码覆盖率不下降。

第五步：提交 Pull Request。推送本地分支到远程仓库后，向本项目的 `main` 分支发起 Pull Request，并在描述中清晰说明修改内容、动机以及相关 Issue 编号。项目维护者会在三个工作日内进行审阅。

<h2>常见问题</h2><br>

问：如何快速判断某条链接是否仍然有效？

答：项目根目录下的 `scripts/check

> 外链数量: 350 | 生成时间:2026年09月18日03时19分10秒
