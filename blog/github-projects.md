昨天（2016年12月29日）发了开始开发的文章。本来晚上准备在 Coding.NET 上添加几个任务开始搞起了。可是真的开始用的时候才发现：Coding.NET 的任务功能只针对私有的任务开放。我想Coding.NET 团队可能是出于商业的目的做出这样的选择，但这样我就没法把开发的过程开放出来了。但总要有一个项目管理的方法来展(dun)示(cu)我进行开发，于是我首先想到的是之前在用的团队协作工具：Worktile。然而，Worktime 也是一个针对封闭团队的工具（团队里的每个人都需要确定下来，相互得“认识”），而我需要的是一个开放式的管理工具。

回到 GitHub 上来，在 2016 年的 9 月，GitHub 发布了新的合作工具——一个类似于看板的 Projects 功能。到我写这文章的时候，已经过去3个多月了，已经有很多的文章介绍过这个功能。简单来说，一个 repo 可以创建若干个 Project （其实我觉得 project 这个名字可能有歧义，其实这里并不是通常意义上的 Project，更像是一个 Mission），然后通过添加 Column 来控制开发的流程。

在尝试 GitHub 这个新的“黑科技”之前，我在 GitHub 上还找到另一个“黑科技”：ZenHub。这个是通过 GitHub 的 issue 来保存要做的事情，然后通过一个 Chrome 扩展来改变 GitHub 的主界面，可以展示成 4 个看板。但这里有一个问题就是：要把任务都保存到 issue 里，感觉有点不够清爽：好像我的项目有很多的问题一样（因为 issue 的 number 会增加）。

最终，我尝试使用 GitHub 的 Project 功能来进行项目管理。然而这样做的结果就成了：Coding.NET 这个 repo 变成了一个鸡肋。在我全面使用 GitHub 之后，Coding.NET 变成一个从库，GitHub 成了主库。不过，我通过配置 DaoCloud，使得 Coding.NET 稍微发挥一点功能，就是在 Linux 下的构建和测试。Travis 已经取消了 Linux 的构建，只能在 macOS 上运行，不过在我写文章的时候，还没有 pass。

明天是2016年最后一天，需要完成整个2016年的年终总结。所以就没时间开发了。