# DWZ
这是一个短网址程序
主要实现：短网址生成，页面跳转，短链访问信息统计，跳转页面渲染。带有用户登陆模块。
<br>
数据库mongodb使用findandmodify进行id自增。
这是一个简单的短链程序。
//发现的问题有：proxy层的认识：模型代理：
对主要的数据库操作进行封装：
<br> @moqiu 的解释：<br>
一天老板突发奇想，觉得我们改版了，这个版本之前的内容都不要显示了。
怎么办？每个find都加一个时间条件？加！一二三四五六七，都加上了。
万一下回他又觉得这个时间不太好，换个时间。
怎么办？改！一二三四五六，哎？忘了一个。
叮咣一顿骂╮(╯▽╰)╭
对model层的操作封装的作用如此。