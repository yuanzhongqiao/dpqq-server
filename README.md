<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p align="center" dir="auto">
    <a href="https://github.com/gotify/logo">
        <img height="370px" src="https://raw.githubusercontent.com/gotify/logo/master/gotify-logo.png" style="max-width: 100%;">
    </a>
</p>
<div class="markdown-heading" dir="auto"><h1 align="center" tabindex="-1" class="heading-element" dir="auto" _msttexthash="13616681" _msthash="351">gotify/服务器</h1><a id="user-content-gotifyserver" class="anchor" aria-label="永久链接： gotify/server" href="#gotifyserver" _mstaria-label="556296" _msthash="352"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p align="center" dir="auto">
    <a href="https://github.com/gotify/server/actions?query=workflow%3Abuild">
        <img alt="构建状态" src="https://github.com/gotify/server/workflows/build/badge.svg" style="max-width: 100%;" _mstalt="181376" _msthash="353">
    </a>
    <a href="https://codecov.io/gh/gotify/server" rel="nofollow">
        <img alt="Codecov 公司" src="https://camo.githubusercontent.com/2c8199158ed047e27e3c4b9354362b2350f3dfd61c668e8af62f67cb29a03b7b/68747470733a2f2f636f6465636f762e696f2f67682f676f746966792f7365727665722f6272616e63682f6d61737465722f67726170682f62616467652e737667" data-canonical-src="https://codecov.io/gh/gotify/server/branch/master/graph/badge.svg" style="max-width: 100%;" _mstalt="96798" _msthash="354">
    </a>
    <a href="https://goreportcard.com/report/github.com/gotify/server" rel="nofollow">
        <img alt="Go 成绩单" src="https://camo.githubusercontent.com/5c0bf09a4f6d24514abd4c1a702b31b1708e18f5f95e9bc0693f0cfa717949f2/68747470733a2f2f676f7265706f7274636172642e636f6d2f62616467652f6769746875622e636f6d2f676f746966792f736572766572" data-canonical-src="https://goreportcard.com/badge/github.com/gotify/server" style="max-width: 100%;" _mstalt="196274" _msthash="355">
    </a>
    <a href="https://matrix.to/#/#gotify:matrix.org" rel="nofollow">
        <img alt="矩阵" src="https://camo.githubusercontent.com/fdd7e64307c1d8e05e01fbb51883092a80424aa5152b963a43c4c11fdbec1369/68747470733a2f2f696d672e736869656c64732e696f2f6d61747269782f676f746966793a6d61747269782e6f72672e737667" data-canonical-src="https://img.shields.io/matrix/gotify:matrix.org.svg" style="max-width: 100%;" _mstalt="79222" _msthash="356">
    </a>
    <a href="https://hub.docker.com/r/gotify/server" rel="nofollow">
        <img alt="Docker 拉取" src="https://camo.githubusercontent.com/1f86c848a3137c7af745b7670dc960b1fa7f29491cba2c515bb5a0a2e3f98eec/68747470733a2f2f696d672e736869656c64732e696f2f646f636b65722f70756c6c732f676f746966792f7365727665722e737667" data-canonical-src="https://img.shields.io/docker/pulls/gotify/server.svg" style="max-width: 100%;" _mstalt="179205" _msthash="357">
    </a>
    <a href="https://github.com/gotify/server/releases/latest">
        <img alt="最新版本" src="https://camo.githubusercontent.com/b57b36aa8a126004b29853fa34236642a37cc45d38a280b586fba3de8150ed58/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f72656c656173652f676f746966792f7365727665722e737667" data-canonical-src="https://img.shields.io/github/release/gotify/server.svg" style="max-width: 100%;" _mstalt="234169" _msthash="358">
    </a>
</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5211505" _msthash="359">介绍</h2><a id="user-content-intro" class="anchor" aria-label="永久链接： Intro" href="#intro" _mstaria-label="277173" _msthash="360"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="1879742462" _msthash="361">我们想要一个简单的服务器来发送和接收消息（每个 WebSocket 实时发送）。为此，不存在的开源项目并不多，大多数现有的项目都被放弃了。此外，一个要求是它可以自托管。我们知道有许多免费和商业推送服务。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5209451" _msthash="362">特征</h2><a id="user-content-features" class="anchor" aria-label="永久链接：功能" href="#features" _mstaria-label="370552" _msthash="363"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/gotify/server/blob/master/ui.png"><img alt="Gotify UI 屏幕截图" src="/gotify/server/raw/master/ui.png" align="right" width="500px" style="max-width: 100%;" _mstalt="382252" _msthash="364"></a></p>
<ul dir="auto">
<li _msttexthash="33991581" _msthash="365">通过 REST-API 发送消息</li>
<li _msttexthash="33738302" _msthash="366">通过 WebSocket 接收消息</li>
<li _msttexthash="57315284" _msthash="367">管理用户、客户端和应用程序</li>
<li><a href="https://gotify.net/docs/plugin" rel="nofollow" _msttexthash="4427670" _msthash="368">插件</a></li>
<li _msttexthash="147342" _msthash="369">Web-UI -&gt; <a href="/gotify/server/blob/master/ui">./ui</a></li>
<li _msttexthash="25487748" _msthash="370">用于发送消息的 CLI -&gt; <a href="https://github.com/gotify/cli" _istranslated="1">gotify/cli</a></li>
<li _msttexthash="684034" _msthash="371">Android-App -&gt; <a href="https://github.com/gotify/android">gotify/android</a></li>
</ul>
<p dir="auto"><a href="https://play.google.com/store/apps/details?id=com.github.gotify" rel="nofollow"><img src="https://camo.githubusercontent.com/899b11c87da7fe33fedafd4a4cf80f9e63831b91b298465c28c411871591e7aa/68747470733a2f2f706c61792e676f6f676c652e636f6d2f696e746c2f656e5f67622f6261646765732f696d616765732f67656e657269632f656e5f62616467655f7765625f67656e657269632e706e67" alt="在 Google Play 上获取" width="150" data-canonical-src="https://play.google.com/intl/en_gb/badges/images/generic/en_badge_web_generic.png" style="max-width: 100%;" _mstalt="341523" _msthash="372"></a>
<a href="https://f-droid.org/de/packages/com.github.gotify/" rel="nofollow"><img src="https://camo.githubusercontent.com/0014f07b7f169b7232d26d242bb2f8ef598dea7169bd8766385d70d6be8127a1/68747470733a2f2f662d64726f69642e6f72672f62616467652f6765742d69742d6f6e2e706e67" alt="在 F-Droid 上获取" width="150" data-canonical-src="https://f-droid.org/badge/get-it-on.png" style="max-width: 100%;" _mstalt="235443" _msthash="373"></a></p>
<p dir="auto"><sub _msttexthash="92040637" _msthash="374">（Google Play 和 Google Play 徽标是 Google LLC 的商标。</sub></p>
<hr>
<p dir="auto"><strong><a href="https://gotify.net/docs" rel="nofollow" _msttexthash="5144373" _msthash="375">文档</a></strong></p>
<p dir="auto" _msttexthash="71111547" _msthash="376"><a href="https://gotify.net/docs/install" rel="nofollow" _istranslated="1">安装</a> ᛫ <a href="https://gotify.net/docs/config" rel="nofollow" _istranslated="1">配置</a> ᛫ <a href="https://gotify.net/api-docs" rel="nofollow" _istranslated="1">REST-API</a> ᛫ <a href="https://gotify.net/docs/dev-setup" rel="nofollow" _istranslated="1">设置开发环境</a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="6354283" _msthash="377">贡献</h2><a id="user-content-contributing" class="anchor" aria-label="永久链接： 贡献" href="#contributing" _mstaria-label="521066" _msthash="378"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="352266694" _msthash="379">我们欢迎各种贡献，包括 bug 报告、功能请求、文档改进、UI 改进等。查看 <a href="/gotify/server/blob/master/CONTRIBUTING.md" _istranslated="1">CONTRIBUTING.md</a> 以获取指南。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="11129911" _msthash="380">版本控制</h2><a id="user-content-versioning" class="anchor" aria-label="永久链接： 版本控制" href="#versioning" _mstaria-label="444028" _msthash="381"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="283288187" _msthash="382">我们使用 <a href="http://semver.org/" rel="nofollow" _istranslated="1">SemVer</a> 进行版本控制。有关可用版本，请参阅<a href="https://github.com/gotify/server/tags" _istranslated="1">此存储库上的标签</a>。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="9675445" _msthash="383">许可证</h2><a id="user-content-license" class="anchor" aria-label="永久链接：许可证" href="#license" _mstaria-label="331903" _msthash="384"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="206539268" _msthash="385">本项目根据 MIT 许可证获得许可 - 有关详细信息，请参阅 <a href="/gotify/server/blob/master/LICENSE" _istranslated="1">LICENSE</a> 文件</p>
</article></div>
