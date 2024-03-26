<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 观看应用系统</font></font></h1><a id="user-content-watch-application-system-in-python" class="anchor" aria-label="永久链接：Python 中的手表应用系统" href="#watch-application-system-in-python"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<a name="user-content-introduction"></a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍</font></font></h2><a id="user-content-introduction" class="anchor" aria-label="永久链接：简介" href="#introduction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Wasp-os 是适用于基于 nRF52 系列微控制器的智能手表的固件，特别适合黑客友好的手表，例如 Pine64 PineTime。 Wasp-os 具有完整的心率监测和计步支持，以及多个钟面、秒表、闹钟、倒计时器、计算器和许多其他游戏和实用程序。所有这一切，仍然可以访问 MicroPython REPL 进行交互式调整、开发和测试。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Wasp-os 与基于 Adafruit NRF52 引导加载程序的强大引导加载程序完全集成。引导加载程序经过扩展，使其能够在没有重置按钮、电源开关、SWD 调试器或 UART 的外形设备上进行开发。这使我们能够自信地开发依赖蓝牙低功耗进行无线更新的密封设备。</font></font></p>
<a name="user-content-documentation"></a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2><a id="user-content-documentation" class="anchor" aria-label="永久链接：文档" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Wasp-os 拥有</font></font><a href="https://wasp-os.readthedocs.io" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">丰富的文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
，其中包括详细的</font></font><a href="https://wasp-os.readthedocs.io/en/latest/appguide.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序编写指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，可帮助您尽快开始为 wasp-os 进行编码。</font></font></p>
<a name="user-content-getting-started"></a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">入门</font></font></h2><a id="user-content-getting-started" class="anchor" aria-label="永久链接：开始使用" href="#getting-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Wasp-os 无需使用任何工具或拆卸即可安装到以下设备上：</font></font></p>
<blockquote>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">松64 松时间</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔米P8</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">千宝诺K9</font></font></li>
</ul>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用
</font></font><a href="https://wasp-os.readthedocs.io/en/latest/install.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
了解如何在这些设备上构建和安装 wasp-os。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装过程结束时，您的手表将显示时间 (03:00) 以及日期和电池电量表。当手表进入省电模式时，您可以使用按钮再次唤醒它。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此时，您还可以使用 Nordic UART 服务来访问 MicroPython REPL。您可以使用它</font></font><code>tools/wasptool --console</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
来访问 MicroPython REPL。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置时间并重新启动主应用程序：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">^</span><span class="pl-v">C</span>
<span class="pl-s1">watch</span>.<span class="pl-s1">rtc</span>.<span class="pl-en">set_localtime</span>((<span class="pl-s1">yyyy</span>, <span class="pl-s1">mm</span>, <span class="pl-s1">dd</span>, <span class="pl-v">HH</span>, <span class="pl-v">MM</span>, <span class="pl-v">SS</span>))
<span class="pl-s1">wasp</span>.<span class="pl-s1">system</span>.<span class="pl-en">run</span>()</pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者，如果您有合适的 GNU/Linux 工作站，只需使用：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./tools/wasptool --rtc</pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它可以自动运行这些命令。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如上所述，还有许多驱动程序和功能有待开发，请参阅</font></font><a href="#id1"><span id="user-content-id2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">:ref:`Roadmap`</font></font></span></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解当前状态。</font></font></p>
<a name="user-content-community"></a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区</font></font></h2><a id="user-content-community" class="anchor" aria-label="永久链接：社区" href="#community"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">wasp-os 社区以
</font></font><a href="https://github.com/wasp-os/wasp-os"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">github 项目为中心，并通过</font></font></a><font style="vertical-align: inherit;"></font><a href="https://matrix.to/#/#wasp-os:matrix.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">#wasp-os:matrix.org</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">频道中的即时消息进行补充
</font><font style="vertical-align: inherit;">
。如果您没有首选的 Matrix 聊天客户端，那么我们建议您尝试
</font></font><a href="https://app.element.io/#/room/#wasp-os:matrix.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Element Web 客户端</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
。点击 element 链接，如果您还没有 Matrix 帐户，请自行注册。这应该足以让你聊天了！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者，如果您更喜欢使用 IRC，出于所有
</font></font><a href="https://xkcd.com/1782/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常见原因</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，Matrix 通道也会桥接到 libera.chat 上的 #wasp-os IRC 通道。</font></font></p>
<a name="user-content-videos"></a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视频</font></font></h2><a id="user-content-videos" class="anchor" aria-label="永久链接：视频" href="#videos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>




<tbody valign="top">
<tr><td><div dir="auto">
<a href="https://www.youtube.com/watch?v=nps8Kd2qPzs" rel="nofollow"><img alt="wasp-os：wasp-os 新应用程序之旅" src="https://github.com/wasp-os/wasp-os/raw/master/res/thumbnail-nps8Kd2qPzs.jpg" style="width: 95%; max-width: 100%;"></a>
<p dir="auto"><a href="https://www.youtube.com/watch?v=nps8Kd2qPzs" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">浏览 wasp-os 的新应用程序</font></font></a></p>
</div>
</td>
<td><div dir="auto">
<a href="https://www.youtube.com/watch?v=lIo2-djNR48" rel="nofollow"><img alt="wasp-os：Pine64 PineTime 的开源心率监测" src="https://camo.githubusercontent.com/e9d6b6150d875c98d4cfc1eeaa1a56cd2519452e72544a1e07d432d75b9bceab/68747470733a2f2f696d672e796f75747562652e636f6d2f76692f6c496f322d646a4e5234382f302e6a7067" style="width: 95%; max-width: 100%;" data-canonical-src="https://img.youtube.com/vi/lIo2-djNR48/0.jpg"></a>
<p dir="auto"><a href="https://www.youtube.com/watch?v=lIo2-djNR48" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pine64 PineTime 的开源心率监测</font></font></a></p>
</div>
</td>
</tr>
<tr><td><div dir="auto">
<a href="https://www.youtube.com/watch?v=YktiGUSRJB4" rel="nofollow"><img alt="在 Pine64 PineTime 上运行的 M2 预发行版" src="https://camo.githubusercontent.com/f051e0474ba9dbfe36b60ac6012a700a6981396cdc2de8e39cbdb06a25e05020/68747470733a2f2f696d672e796f75747562652e636f6d2f76692f596b7469475553524a42342f302e6a7067" style="width: 95%; max-width: 100%;" data-canonical-src="https://img.youtube.com/vi/YktiGUSRJB4/0.jpg"></a>
<p dir="auto"><a href="https://www.youtube.com/watch?v=YktiGUSRJB4" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Pine64 PineTime 上运行的 M2 预发行版</font></font></a></p>
</div>
</td>
<td><div dir="auto">
<a href="https://www.youtube.com/watch?v=tuk9Nmr3Jo8" rel="nofollow"><img alt="如何在 Pine64 PineTime 上开发 wasp-os python 应用程序" src="https://camo.githubusercontent.com/6cb70fa5073c2af8be112e11cc1e04def6c8c4a70edf854a9d1ae9680da9a426/68747470733a2f2f696d672e796f75747562652e636f6d2f76692f74756b394e6d72334a6f382f302e6a7067" style="width: 95%; max-width: 100%;" data-canonical-src="https://img.youtube.com/vi/tuk9Nmr3Jo8/0.jpg"></a>
<p dir="auto"><a href="https://www.youtube.com/watch?v=tuk9Nmr3Jo8" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何在 Pine64 PineTime 上开发 wasp-os python 应用程序</font></font></a></p>
</div>
</td>
</tr>
<tr><td><div dir="auto">
<a href="https://www.youtube.com/watch?v=kf1VHj587Mc" rel="nofollow"><img alt="使用 wasp-os 和 MicroPython 进行 Pine64 PineTime 开发" src="https://camo.githubusercontent.com/91398d12fb4fb55158c89199beab34783fe7ee57dd8b8c0b1413fe8f8d18c17f/68747470733a2f2f696d672e796f75747562652e636f6d2f76692f6b663156486a3538374d632f302e6a7067" style="width: 95%; max-width: 100%;" data-canonical-src="https://img.youtube.com/vi/kf1VHj587Mc/0.jpg"></a>
<p dir="auto"><a href="https://www.youtube.com/watch?v=kf1VHj587Mc" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 wasp-os 和 MicroPython 进行 Pine64 PineTime 开发</font></font></a></p>
</div>
</td>
<td>&nbsp;</td>
</tr>
</tbody>
</table>
<a name="user-content-custom-builds"></a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">定制构建</font></font></h2><a id="user-content-custom-builds" class="anchor" aria-label="永久链接：自定义构建" href="#custom-builds"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Wasp-os 旨在允许用户轻松创建自己的自定义版本。只需修改 wasp.toml 文件即可包含您最喜欢的应用程序和表盘。有关如何构建 wasp-os 的更多信息，请参阅文档。</font></font></p>
<a name="user-content-screenshots"></a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">截图</font></font></h2><a id="user-content-screenshots" class="anchor" aria-label="永久链接：屏幕截图" href="#screenshots"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Pine64 PineTime 上运行的数字时钟应用程序（旧版本）：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/clock_app.jpg"><img alt="在 PineTime 上运行的 wasp-os 数字时钟应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/clock_app.jpg" style="width: 233px; max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">wasp-os 模拟器上运行的可用应用程序的屏幕截图：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/Bootloader.png"><img alt="引导加载程序初始屏幕覆盖在模拟器手表艺术上" src="https://github.com/wasp-os/wasp-os/raw/master/res/Bootloader.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">表盘：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/ClockApp.png"><img alt="在 wasp-os 模拟器上运行的数字时钟应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/ClockApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/WeekClockApp.png"><img alt="在 wasp-os 模拟器上运行的数字时钟应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/WeekClockApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/ChronoApp.png"><img alt="在 wasp-os 模拟器中运行的模拟时钟应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/ChronoApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/DualClockApp.png"><img alt="在 wasp-os 模拟器中运行的另一个时钟应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/DualClockApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/FibonacciClockApp.png"><img alt="在 wasp-os 模拟器中运行的斐波那契时钟应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/FibonacciClockApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/WordClockApp.png"><img alt="在 wasp-os 模拟器中将时间显示为单词" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/WordClockApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/ResistorClockApp.png"><img alt="在 wasp-os 模拟器中运行的电阻颜色代码时钟应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/ResistorClockApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">游戏：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/Play2048App.png"><img alt="让我们来玩 2048 游戏（在 wasp-os 模拟器中）" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/Play2048App.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/GameOfLifeApp.png"><img alt="在 wasp-os 模拟器中运行的生命游戏" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/GameOfLifeApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/SnakeApp.png"><img alt="在 wasp-os 模拟器中运行的贪吃蛇游戏" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/SnakeApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/Puzzle15App.png"><img alt="15 在 wasp-os 模拟器中运行的谜题" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/Puzzle15App.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/FourInARowApp.png"><img alt="在 wasp-os 模拟器中运行的四个连续" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/FourInARowApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">时间管理应用程序：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/AlarmApp.png"><img alt="在 wasp-os 模拟器中运行的闹钟应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/AlarmApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/StopwatchApp.png"><img alt="在 wasp-os 模拟器上运行的秒表应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/StopwatchApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/TimerApp.png"><img alt="在 wasp-os 模拟器中运行的倒计时器应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/TimerApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">系统应用程序：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/DisaBLEApp.png"><img alt="用于禁用蓝牙以节省电量并增强安全性的小应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/DisaBLEApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/LauncherApp.png"><img alt="在 wasp-os 模拟器上运行的应用程序启动器" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/LauncherApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/SettingsApp.png"><img alt="在 wasp-os 模拟器上运行的设置应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/SettingsApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/SoftwareApp.png"><img alt="在 wasp-os 模拟器上运行的软件选择应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/SoftwareApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/FacesApp.png"><img alt="切换表盘" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/FacesApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他应用程序：（“空白”白色屏幕截图是手电筒应用程序）</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/BeaconApp.png"><img alt="相对较强的 HRS LED 反复闪烁" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/BeaconApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/CalculatorApp.png"><img alt="在 wasp-os 模拟器中运行的计算器" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/CalculatorApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/DemoApp.png"><img alt="简单的始终在线演示，用于在会议和表演中展示 wasp-os" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/DemoApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/FlashlightApp.png"><img alt="在 wasp-os 模拟器上运行的 Torch 应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/FlashlightApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/GalleryApp.png"><img alt="在 wasp-os 模拟器上运行的 Gallery 应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/GalleryApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/HeartApp.png"><img alt="在 wasp-os 模拟器上运行的心率应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/HeartApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/HaikuApp.png"><img alt="在 wasp-os 模拟器中运行的 Haiku 应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/HaikuApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/LevelApp.png"><img alt="在 wasp-os 模拟器中将时间显示为单词" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/LevelApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/MorseApp.png"><img alt="在 wasp-os 模拟器上运行的莫尔斯翻译器/记事本应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/MorseApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/PomodoroApp.png"><img alt="可定制的番茄工作法应用程序具有随机振动模式，以确保您注意到" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/PomodoroApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/PhoneFinderApp.png"><img alt="通过让手机响铃来查找您的手机" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/PhoneFinderApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/SportsApp.png"><img alt="体育应用，秒表和计步器组合" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/SportsApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/StepCounterApp.png"><img alt="在 wasp-os 模拟器上运行的计步器应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/StepCounterApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/TestApp.png"><img alt="在模拟器上运行渲染基准的自测试应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/TestApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/MusicPlayerApp.png"><img alt="在 wasp-os 模拟器中运行的音乐播放器" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/MusicPlayerApp.png" style="width: 179px; max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/wasp-os/wasp-os/blob/master/res/screenshots/WeatherApp.png"><img alt="在 wasp-os 模拟器中运行的天气应用程序" src="https://github.com/wasp-os/wasp-os/raw/master/res/screenshots/WeatherApp.png" style="width: 179px; max-width: 100%;"></a></p>

</article></div>
