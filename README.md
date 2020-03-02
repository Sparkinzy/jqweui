# 用途

仅用于 更新地址库

# jQuery WeUI
jQuery WeUI 是专为微信公众账号开发而设计的一个简洁而强大的UI库，包含全部WeUI官方的CSS组件，并且额外提供了大量的拓展组件，丰富的组件库可以极大减少前端开发时间。

原官网： [http://lihongxun945.github.io/jquery-weui/](http://lihongxun945.github.io/jquery-weui/)

你可以 clone 这个仓库，自行编译，关于如何进行编译请参见下面的gulp章节。

所有编译后的代码都在 `dist` 目录下，为了减少垃圾文件，master默认忽略了这个目录，你可以自行编译或者切换到 `build` 分支就可以看到这个目录。

# gulp

使用 `gulp` 进行代码编译，如果你没有用过或者不想自行编译，可以切换到 `build` 分支即可。

关于如何使用 gulp 请参考 [http://gulpjs.com/](http://gulpjs.com/)

可用的 gulp 命令如下：

- `gulp` 进入开发模式，同时打开 `watch` 和 `server`任务
- `gulp build` 编译压缩代码

# 分支说明

- `master` 主分支，正式发布的代码才会进入master分支
- `build` 包含全部编译后代码的分支，和 `master` 分支同步，但是会包含 `dist` 目录
- `dev` 开发分支
- `gh-pages` 文档主分支
- `gh-pages-dev` 文档的开发分支

 

# LICENSE

[MIT](https://opensource.org/licenses/MIT)，尽情享受开源代码。

# Thanks

- [WeUI](http://weui.github.io/weui/#/)
- [Framework7](http://framework7.io/)
- [MSUI](http://m.sui.taobao.org/)
- [Jekyll](http://jekyllrb.com/)
- [gulp](http://gulpjs.com/)
 
