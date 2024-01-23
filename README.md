<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div align="center" dir="auto">
    <br>
    <a href="https://github.com/sissbruecker/linkding">
        <img src="/sissbruecker/linkding/raw/master/docs/header.svg" height="50" style="max-width: 100%;">
    </a>
    <br>
</div>
<h2 tabindex="-1" dir="auto"><a id="user-content-overview" class="anchor" aria-hidden="true" tabindex="-1" href="#overview"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概述</font></font></h2>
<ul dir="auto">
<li><a href="#introduction"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍</font></font></a></li>
<li><a href="#installation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></a>
<ul dir="auto">
<li><a href="#using-docker"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Docker</font></font></a></li>
<li><a href="#using-docker-compose"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Docker 组合</font></font></a></li>
<li><a href="#user-setup"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户设置</font></font></a></li>
<li><a href="#reverse-proxy-setup"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">反向代理设置</font></font></a></li>
<li><a href="#managed-hosting-options"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">托管选项</font></font></a></li>
</ul>
</li>
<li><a href="#documentation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a></li>
<li><a href="#browser-extension"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">浏览器扩展</font></font></a></li>
<li><a href="#community"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区</font></font></a></li>
<li><a href="#acknowledgements--donations"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">致谢+捐赠</font></font></a></li>
<li><a href="#development"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发展</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-introduction" class="anchor" aria-hidden="true" tabindex="-1" href="#introduction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">linkding 是一个您可以自己托管的书签管理器。</font><font style="vertical-align: inherit;">它的设计目标是最小化、快速且易于使用 Docker 设置。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">名字来源于：</font></font></p>
<ul dir="auto">
<li><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链接</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，通常用作通用语言中 URL 和书签的同义词</font></font></li>
<li><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ding</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是德语，意为“东西”</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">...基本上是管理链接的东西</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">功能概述：</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">干净的用户界面优化了可读性</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用标签组织书签</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Markdown 添加注释</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">稍后阅读功能</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与其他用户共享书签</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">批量编辑</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动提供已添加书签的网站的标题、描述和图标</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动创建</font></font><a href="https://archive.org/web/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Internet Archive Wayback Machine上添加书签的网站的快照</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以 Netscape HTML 格式导入和导出书签</font></font></li>
<li><font style="vertical-align: inherit;"></font><a href="https://addons.mozilla.org/firefox/addon/linkding-extension/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Firefox</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://chrome.google.com/webstore/detail/linkding-extension/beakmhbijpdhipnjhnclmhgjlddhidpe" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Chrome</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的扩展</font><font style="vertical-align: inherit;">以及小书签</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">浅色和深色主题</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于开发第三方应用程序的 REST API</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于用户自助服务和原始数据访问的管理面板</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Docker 和 SQLite 数据库轻松设置，并可选择 PostgreSQL</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示： https: </font></font></strong> <a href="https://demo.linkding.link/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">//demo.linkding.link/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（</font><font style="vertical-align: inherit;">如果访问遇到问题，</font></font><a href="https://github.com/sissbruecker/linkding/issues/408" data-hovercard-type="issue" data-hovercard-url="/sissbruecker/linkding/issues/408/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅此处）</font></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">截屏：</font></font></strong></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/sissbruecker/linkding/blob/master/docs/linkding-screenshot.png?raw=true"><img src="/sissbruecker/linkding/raw/master/docs/linkding-screenshot.png?raw=true" alt="截屏" title="截屏" style="max-width: 100%;"></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-installation" class="anchor" aria-hidden="true" tabindex="-1" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">linkding 设计为与</font></font><a href="https://docs.docker.com/get-started/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等容器解决方案一起运行。</font><font style="vertical-align: inherit;">Docker镜像与ARM平台兼容，因此可以在Raspberry Pi上运行。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链接默认使用 SQLite 数据库。</font><font style="vertical-align: inherit;">或者链接支持 PostgreSQL，请参阅</font></font><a href="/sissbruecker/linkding/blob/master/docs/Options.md#LD_DB_ENGINE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据库选项</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以获取更多信息。</font></font></p>
<details>
<summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🧪 基于 Alpine 的图像</font></font></summary>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认的 Docker 镜像（</font></font><code>latest</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标签）基于 Debian Linux 的精简版本。</font><font style="vertical-align: inherit;">另外，还有一个基于 Alpine Linux（</font></font><code>latest-alpine</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标签）的镜像，其尺寸较小，因此下载量较小，所需磁盘空间也较少。</font><font style="vertical-align: inherit;">目前，Alpine 映像的压缩大小约为 45 MB，而 Debian 映像的压缩大小约为 130 MB。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要使用它，请将</font></font><code>latest</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标签替换为</font></font><code>latest-alpine</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，无论是在使用 Docker 时在下面的 CLI 命令中，还是在</font></font><code>docker-compose.yml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 docker-compose 时在文件中。</font></font></p>
<blockquote>
<p dir="auto">[!WARNING]
The image is currently considered experimental in order to gather feedback and iron out any issues.
Only use it if you are comfortable running experimental software or want to help out with testing.
While there should be no issues with creating new installations, there might be issues when migrating existing installations.
If you plan to migrate your existing installation, make sure to create proper <a href="https://github.com/sissbruecker/linkding/blob/master/docs/backup.md">backups</a> first.</p>
</blockquote>
</details>
<h3 tabindex="-1" dir="auto"><a id="user-content-using-docker" class="anchor" aria-hidden="true" tabindex="-1" href="#using-docker"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Docker</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要使用 Docker 安装链接，您只需</font><font style="vertical-align: inherit;">从 Docker Hub运行</font></font><a href="https://hub.docker.com/repository/docker/sissbruecker/linkding" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最新的映像即可：</font></font></a><font style="vertical-align: inherit;"></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker run --name linkding -p 9090:9090 -v {host-data-folder}:/etc/linkding/data -d sissbruecker/linkding:latest</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run --name linkding -p 9090:9090 -v {host-data-folder}:/etc/linkding/data -d sissbruecker/linkding:latest" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在上面的命令中，将</font></font><code>{host-data-folder}</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">占位符替换为主机系统上要存储链接数据库的文件夹的绝对路径。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果一切成功完成，应用程序现在应该正在运行，并且可以通过</font></font><a href="http://localhost:9090" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://localhost:9090</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行访问。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要将安装升级到新版本，请删除现有容器，拉取链接 Docker 映像的最新版本，然后使用上面使用的相同命令启动新容器。</font><font style="vertical-align: inherit;">有一个</font></font><a href="https://github.com/sissbruecker/linkding/blob/master/install-linkding.sh"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">shell 脚本</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可用于自动执行这些步骤。</font><font style="vertical-align: inherit;">可以使用环境变量配置脚本，也可以直接修改它。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要完成设置，您仍然需要</font></font><a href="#user-setup"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建一个初始用户</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，以便您可以访问您的安装。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-using-docker-compose" class="anchor" aria-hidden="true" tabindex="-1" href="#using-docker-compose"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Docker 组合</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要使用</font></font><a href="https://docs.docker.com/compose/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker Compose</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装链接，您可以使用该</font></font><a href="https://github.com/sissbruecker/linkding/blob/master/docker-compose.yml"><code>docker-compose.yml</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件。</font><font style="vertical-align: inherit;">将文件复制</font></font><a href="https://github.com/sissbruecker/linkding/blob/master/.env.sample"><code>.env.sample</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到</font></font><code>.env</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，配置参数，然后运行：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker-compose up -d</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker-compose up -d" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要完成设置，您仍然需要</font></font><a href="#user-setup"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建一个初始用户</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，以便您可以访问您的安装。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-user-setup" class="anchor" aria-hidden="true" tabindex="-1" href="#user-setup"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户设置</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">出于安全原因，链接 Docker 映像不提供初始用户，因此您必须在设置安装后创建一个用户。</font><font style="vertical-align: inherit;">为此，请替换以下命令中的凭据并运行它：</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">码头工人</font></font></strong></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker <span class="pl-c1">exec</span> -it linkding python manage.py createsuperuser --username=joe --email=joe@example.com</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker exec -it linkding python manage.py createsuperuser --username=joe --email=joe@example.com" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker 组合</font></font></strong></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker-compose <span class="pl-c1">exec</span> linkding python manage.py createsuperuser --username=joe --email=joe@example.com</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker-compose exec linkding python manage.py createsuperuser --username=joe --email=joe@example.com" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该命令将提示您输入安全密码。</font><font style="vertical-align: inherit;">命令完成后，您可以使用您的凭据登录 UI 来开始使用该应用程序。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="/sissbruecker/linkding/blob/master/docs/Options.md#LD_SUPERUSER_NAME"><code>LD_SUPERUSER_NAME</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者，您可以使用选项</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在启动时自动创建初始超级用户</font><font style="vertical-align: inherit;">。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-reverse-proxy-setup" class="anchor" aria-hidden="true" tabindex="-1" href="#reverse-proxy-setup"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">反向代理设置</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用反向代理（例如 Nginx 或 Apache）时，您可能需要配置代理以正确地将标头转发</font></font><code>Host</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到链接，否则某些请求（例如登录）可能会失败。</font></font></p>
<details>
<summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阿帕奇</font></font></summary>
<p dir="auto">Apache2 does not change the headers by default, and should not
need additional configuration.</p>
<p dir="auto">An example virtual host that proxies to linkding might look like:</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>&lt;VirtualHost *:9100&gt;
    &lt;Proxy *&gt;
        Order deny,allow
        Allow from all
    &lt;/Proxy&gt;

    ProxyPass / http://linkding:9090/
    ProxyPassReverse / http://linkding:9090/
&lt;/VirtualHost&gt;
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="<VirtualHost *:9100>
    <Proxy *>
        Order deny,allow
        Allow from all
    </Proxy>

    ProxyPass / http://linkding:9090/
    ProxyPassReverse / http://linkding:9090/
</VirtualHost>" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">For a full example, see the docker-compose configuration in <a href="https://github.com/jhauris/linkding/tree/apache2-reverse-proxy">jhauris/apache2-reverse-proxy</a></p>
<p dir="auto">If you still run into CSRF issues, please check out the <a href="/sissbruecker/linkding/blob/master/docs/Options.md#LD_CSRF_TRUSTED_ORIGINS"><code>LD_CSRF_TRUSTED_ORIGINS</code> option</a>.</p>
</details>
<details>
<summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">球童2</font></font></summary>
<p dir="auto">Caddy does not change the headers by default, and should not need any further configuration.</p>
<p dir="auto">If you still run into CSRF issues, please check out the <a href="/sissbruecker/linkding/blob/master/docs/Options.md#LD_CSRF_TRUSTED_ORIGINS"><code>LD_CSRF_TRUSTED_ORIGINS</code> option</a>.</p>
</details>
<details>
<summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">nginx</font></font></summary>
<p dir="auto">Nginx by default rewrites the <code>Host</code> header to whatever URL is used in the <code>proxy_pass</code> directive.
To forward the correct headers to linkding, add the following directives to the location block of your Nginx config:</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>location /linkding {
    ...
    proxy_set_header Host $host;
    proxy_set_header X-Forwarded-Proto $scheme;
}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="location /linkding {
    ...
    proxy_set_header Host $host;
    proxy_set_header X-Forwarded-Proto $scheme;
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以使用选项配置要从中访问链接实例的 URL，而不是在代理中配置标头  </font></font><a href="/sissbruecker/linkding/blob/master/docs/Options.md#LD_CSRF_TRUSTED_ORIGINS"><code>LD_CSRF_TRUSTED_ORIGINS</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">转发</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-managed-hosting-options" class="anchor" aria-hidden="true" tabindex="-1" href="#managed-hosting-options"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">托管选项</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自托管 Web 应用程序仍然需要大量技术知识和维护承诺，以保持一切最新且安全。</font><font style="vertical-align: inherit;">本节旨在以托管解决方案的形式提供简单的替代方案。</font></font></p>
<ul dir="auto">
<li><a href="https://github.com/fspoettel/linkding-on-fly"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">linkding on Fly.io - 在</font></font></a><font style="vertical-align: inherit;"></font><a href="https://fly.io" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fly.io</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上托管链接安装的指南</font><font style="vertical-align: inherit;">. </font><font style="vertical-align: inherit;">通过</font></font><a href="https://github.com/fspoettel"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">fspoettel</font></font></a></li>
<li><a href="https://www.pikapods.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PikaPods.com</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 用于链接的托管托管，适用于欧盟和美国地区。</font></font><a href="https://www.pikapods.com/pods?run=linkding" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一键设置链接</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（</font></font><a href="#pikapods"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">披露</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-documentation" class="anchor" aria-hidden="true" tabindex="-1" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://github.com/sissbruecker/linkding/blob/master/docs/Options.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">列出可用选项，并描述如何应用它们</font></font></td>
</tr>
<tr>
<td><a href="https://github.com/sissbruecker/linkding/blob/master/docs/backup.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">备份</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何备份链接数据库</font></font></td>
</tr>
<tr>
<td><a href="https://github.com/sissbruecker/linkding/blob/master/docs/troubleshooting.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">故障排除</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解决常见问题的建议</font></font></td>
</tr>
<tr>
<td><a href="https://github.com/sissbruecker/linkding/blob/master/docs/how-to.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用链接的提示和技巧</font></font></td>
</tr>
<tr>
<td><a href="https://github.com/sissbruecker/linkding/blob/master/docs/shortcuts.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">键盘快捷键</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可用键盘快捷键列表</font></font></td>
</tr>
<tr>
<td><a href="https://github.com/sissbruecker/linkding/blob/master/docs/Admin.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管理文档</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管理 UI 的用户文档</font></font></td>
</tr>
<tr>
<td><a href="https://github.com/sissbruecker/linkding/blob/master/docs/API.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API文档</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">REST API 的文档</font></font></td>
</tr>
</tbody>
</table>
<h2 tabindex="-1" dir="auto"><a id="user-content-browser-extension" class="anchor" aria-hidden="true" tabindex="-1" href="#browser-extension"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">浏览器扩展</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">linkding 附带了官方的浏览器扩展，可以快速添加书签，并通过浏览器的地址栏搜索书签。</font><font style="vertical-align: inherit;">您可以在此处获取扩展名：</font></font></p>
<ul dir="auto">
<li><a href="https://addons.mozilla.org/firefox/addon/linkding-extension/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mozilla 插件商店</font></font></a></li>
<li><a href="https://chrome.google.com/webstore/detail/linkding-extension/beakmhbijpdhipnjhnclmhgjlddhidpe" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Chrome 网上应用店</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该扩展也是开源的，可以</font></font><a href="https://github.com/sissbruecker/linkding-extension"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-community" class="anchor" aria-hidden="true" tabindex="-1" href="#community"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本部分按字母顺序列出了有关使用链接的社区项目。</font><font style="vertical-align: inherit;">如果您有一个项目想要与链接社区共享，请随时提交 PR 以将您的项目添加到此部分。</font></font></p>
<ul dir="auto">
<li><a href="https://github.com/bachya/aiolinkding"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">aiolinkding</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个 Python3 异步库，用于与链接 REST API 交互。</font><font style="vertical-align: inherit;">通过</font></font><a href="https://github.com/bachya"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">巴奇亚</font></font></a></li>
<li><a href="https://codeberg.org/strubbl/feed2linkding" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">feed2linkding</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个命令行实用程序，用于通过 API 调用将所有网络提要项目链接添加到链接。</font><font style="vertical-align: inherit;">作者：</font></font><a href="https://github.com/Strubbl"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">斯特鲁布尔</font></font></a></li>
<li><a href="https://charts.pascaliske.dev/charts/linkding/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Helm Chart</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于在 Kubernetes 集群内部署链接的 Helm Chart。</font><font style="vertical-align: inherit;">通过</font></font><a href="https://github.com/pascaliske"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">帕斯卡利斯克</font></font></a></li>
<li><a href="https://gist.github.com/andrewdolphin/a7dff49505e588d940bec55132fab8ad"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 API 和标记的 iOS 快捷方式</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用链接 API（无需额外登录）的 iOS 快捷方式，可提取以前使用的标签并允许在创建链接时进行标记。</font></font></li>
<li><a href="https://github.com/cmsax/linka"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">林卡！</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Web 应用程序（也是 PWA），用于在链接中快速搜索和打开书签，支持多关键字、排除模式和其他高级选项。</font><font style="vertical-align: inherit;">通过</font></font><a href="https://github.com/cmsax"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cmsax</font></font></a></li>
<li><a href="https://github.com/bachya/linkding-cli"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">linkding-cli</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于与链接 REST API 交互的命令行界面 (CLI)。</font></font><a href="https://github.com/bachya/aiolinkding"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由aiolinkding</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供支持</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">通过</font></font><a href="https://github.com/bachya"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">巴奇亚</font></font></a></li>
<li><a href="https://github.com/jeroenpardon/linkding-extension"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">linkding-extension</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包装链接书签的 Chrom 兼容扩展。</font><font style="vertical-align: inherit;">使用 Chrome、Edge、Brave 进行测试。</font><font style="vertical-align: inherit;">通过</font></font><a href="https://github.com/jeroenpardon"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">杰罗恩帕登</font></font></a></li>
<li><a href="https://github.com/Fivefold/linkding-injector"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">linkding-injector</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将链接的搜索结果注入到搜索页面（如 google 和 duckduckgo）的侧边栏中。</font><font style="vertical-align: inherit;">使用 Firefox 和 Chrome 进行测试。</font><font style="vertical-align: inherit;">通过</font></font><a href="https://github.com/Fivefold"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">五倍</font></font></a></li>
<li><a href="https://apps.apple.com/us/app/linkthing/id1666031776" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LinkThing</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于链接的 iOS 客户端。</font><font style="vertical-align: inherit;">通过</font></font><a href="https://github.com/amoscardino"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阿莫斯卡迪诺</font></font></a></li>
<li><a href="https://gist.github.com/ukcuddlyguy/336dd7339e6d35fc64a75ccfc9323c66"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开所有链接小书签 浏览器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">小书签，用于在新选项卡中打开当前链接页面上的所有链接。</font><font style="vertical-align: inherit;">通过</font></font><a href="https://github.com/ukcuddlyguy"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ukcuddlyguy</font></font></a></li>
<li><a href="https://gist.github.com/gingerbeardman/f0b42502f3bc9344e92ce63afd4360d3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Postman 收集</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一组保存的请求模板用于 API 测试。</font><font style="vertical-align: inherit;">作者：</font></font><a href="https://github.com/gingerbeardman"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">姜胡子人</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-acknowledgements--donations" class="anchor" aria-hidden="true" tabindex="-1" href="#acknowledgements--donations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">致谢+捐赠</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-pikapods" class="anchor" aria-hidden="true" tabindex="-1" href="#pikapods"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">鼠兔豆荚</font></font></h3>
<p dir="auto"><a href="https://www.pikapods.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PikaPods</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与该项目签订了收入共享协议，共享其托管链接实例的部分收入。</font><font style="vertical-align: inherit;">我不打算从这个项目中获得经济利益，所以我反过来捐出这笔收入。</font><font style="vertical-align: inherit;">非常感谢 PikaPods 使这一切成为可能。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">捐款清单见下表。</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来源</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数量</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">捐赠给</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://www.pikapods.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">鼠兔豆荚</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linkding 托管 2022 年 6 月 - 2023 年 9 月</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">163.50 美元</font></font></td>
<td><a href="/sissbruecker/linkding/blob/master/docs/donations/2023-10-11-internet-archive.png"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">互联网档案馆</font></font></a></td>
</tr>
</tbody>
</table>
<h3 tabindex="-1" dir="auto"><a id="user-content-jetbrains" class="anchor" aria-hidden="true" tabindex="-1" href="#jetbrains"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">捷脑公司</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://www.jetbrains.com/idea/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JetBrains 此前已提供IntelliJ IDEA</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的开源许可</font><font style="vertical-align: inherit;">用于 linkding 的开发。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-development" class="anchor" aria-hidden="true" tabindex="-1" href="#development"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发展</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该应用程序是开源的，因此您可以自由修改或贡献。</font><font style="vertical-align: inherit;">该应用程序是使用 Django Web 框架构建的。</font><font style="vertical-align: inherit;">您可以通过查看优秀的</font></font><a href="https://docs.djangoproject.com/en/4.1/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Django 文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来开始。</font><font style="vertical-align: inherit;">该</font></font><code>bookmarks</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件夹包含实际的书签应用程序，</font></font><code>siteroot</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是 Django 根应用程序。</font><font style="vertical-align: inherit;">除此之外，代码应该是不言自明的/标准的 Django 东西 🙂。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-prerequisites" class="anchor" aria-hidden="true" tabindex="-1" href="#prerequisites"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">先决条件</font></font></h3>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 3.10</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Node.js</font></font></li>
</ul>
<h3 tabindex="-1" dir="auto"><a id="user-content-setup" class="anchor" aria-hidden="true" tabindex="-1" href="#setup"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为应用程序创建虚拟环境（</font></font><a href="https://docs.python.org/3/tutorial/venv.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://docs.python.org/3/tutorial/venv.html</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 -m venv ~/environments/linkding
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 -m venv ~/environments/linkding" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">激活 shell 的环境：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>source ~/environments/linkding/bin/activate[.csh|.fish]
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="source ~/environments/linkding/bin/activate[.csh|.fish]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在活动环境中从应用程序文件夹安装应用程序依赖项：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip3 install -Ur requirements.txt
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip3 install -Ur requirements.txt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装前端依赖项：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>npm install
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="npm install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始化数据库：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>mkdir -p data
python3 manage.py migrate
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="mkdir -p data
python3 manage.py migrate" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为前端创建用户：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 manage.py createsuperuser --username=joe --email=joe@example.com
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 manage.py createsuperuser --username=joe --email=joe@example.com" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用以下命令启动 Node.js 开发服务器（用于编译 JavaScript 组件，例如标签自动完成）：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>npm run dev
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="npm run dev" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用以下命令启动 Django 开发服务器：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 manage.py runserver
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 manage.py runserver" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">前端现在可以在</font></font><a href="http://localhost:8000" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://localhost:8000下使用</font></font></a></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-devcontainers" class="anchor" aria-hidden="true" tabindex="-1" href="#devcontainers"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发容器</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该存储库还支持 DevContainers：</font></font><a href="https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=git@github.com:sissbruecker/linkding.git" rel="nofollow"><img src="https://camo.githubusercontent.com/e6401658dbb8e1a4e8f56b32e3573072d7e030d4673c06a19478d45f2cd3c1cb/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d52656d6f74652532302d253230436f6e7461696e657273266d6573736167653d4f70656e26636f6c6f723d626c7565266c6f676f3d76697375616c73747564696f636f6465" alt="在远程 - 容器中打开" data-canonical-src="https://img.shields.io/static/v1?label=Remote%20-%20Containers&amp;message=Open&amp;color=blue&amp;logo=visualstudiocode" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">签出后，只需要以下命令即可开始：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为前端创建用户：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 manage.py createsuperuser --username=joe --email=joe@example.com
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 manage.py createsuperuser --username=joe --email=joe@example.com" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用以下命令启动 Node.js 开发服务器（用于编译 JavaScript 组件，例如标签自动完成）：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>npm run dev
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="npm run dev" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用以下命令启动 Django 开发服务器：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 manage.py runserver
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 manage.py runserver" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">前端现在可以在</font></font><a href="http://localhost:8000" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://localhost:8000下使用</font></font></a></p>
</article></div>
