=======
cssbook
=======

CSS参考手册——[飘零雾雨](http://css.doyoe.com)

本站同步更新预览，cssbook：[http://pandoraui.github.io/cssbook](http://pandoraui.github.io/cssbook/)

## 版权声明 Copyright

本手册由[飘零雾雨](http://css.doyoe.com)编写。版权所有者为飘零雾雨。

您可以免费的使用、分发本手册。但未经飘零雾雨的授权许可不得擅自进行篡改、反编译，及将其全部或部分用于商业用途。

本手册受著作权法和国际公约的保护，作者保留对本手册及本声明的最终修改权。

本手册的部分内容参考了苏沈小雨版的CSS2.0手册及World Wide Web Consortium (W3C)公开的网络文档。


### Git 分支操作

    //关联远程分支
    $ cd your_repo_root/repo_name
    $ git fetch origin
    $ git checkout gh-pages


    //推送分支到远程
    git push --set-upstream origin gh-pages

### github中如何撤销上一次的提交？

在Github中，如果你发现上一次的提交有错误，希望撤销，可以按照下面的步骤：

首先在本地撤销。输入下面的命令，在编辑界面删除第2行文字：

    $ git rebase -i HEAD~2
    Successfully rebased and updated refs/heads/master.

然后撤销服务器上的提交：

    $ git push origin +master

参考文章：[http://stackoverflow.com/questions/448919/how-can-i-remove-a-commit-on-github]()
