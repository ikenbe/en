---
layout: post
title: 第一篇，新的开始
---
这是在 GitHub 上的第一篇日志，也是我希望自己能完成我的目标的开始。今天也是我的生日，今天起我就29岁了，有深深的触摸到了年轻的尾巴的感觉。在许多人都已经完成自己生命中的许多成就的年纪，我却即将迎来人生的重大转变。

放在这里的日志是由 Jekyll 处理的，所以接下来的时间我要先研究一下 Jekyll 的使用，最好能够摸索出合适的模板。目前通过[文档](http://jekyllrb.com/docs/) 和网络上一些文章知道的事情有：

- 文章放在 /_posts/ 支持 html 和 markdown 格式，以 yyyy-mm-dd-title.xx 格式命名
- 需要 Jekyll 处理的文件必须包含 yaml 文件头，里面的内容可以是空白的
- 预设布局放在 /_layouts/ 里面，所以每一篇文章都只需要包含正文。在文档里有 includes 的说明，暂时还不明确是不是有本质上的区别。
- 模板应该是基于 JS 和 CSS 的，不知道是否可以自己写一个。
- 由于是基于监视文件变化生成静态页面，体量过大的话会很慢，这一点以后如果出现问题的话再考虑解决的问题。

经过几个小时摸索，确定了 GitHub Pages 的使用不需要本地部署 Jekyll，我的老电脑逃过一劫。 尝试了在 VPS 上部署 Jekyll 之后发现把 repository push 到 GitHub 之后直接正常显示，本地部署的作用主要是实时预览或者别的我暂时没用到的功能，现阶段搁置不管。

今天的折腾就到这里，明天的首要目标是导航条和模板设置，另外还应该处理好页面们的CSS。 Markdown 的列表显示似乎没有效果，晚上回家可以看看 GFM， 应该可以解决。

另：以前也没有用过 Git，命令行的话每次 add，commit，push 都要三步，应该看一下是不是有捷径。

{{ page.date | date_to_string }}
