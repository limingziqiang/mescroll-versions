## mescroll官网 : http://www.mescroll.com/
## mescroll文档 : https://github.com/mescroll/mescroll.git
<br/>
<br/>

## mescroll所有版本:
<br/>

### v 1.1.5 --- 2017-08-15 
1.取消down.resetShowDownScroll的配置项,少用且不易理解,取而代之的方法是mescroll.resetUpScroll(true);<br/>
2.简化mescroll.resetUpScroll(isShowLoading)重置列表的用法, 参数isShowLoading: 是否显示进度布局<br/>
  &nbsp;&nbsp; 2.1  默认null,不传参,则显示上拉加载的进度布局;<br/>
  &nbsp;&nbsp; 2.2  传参true, 则显示下拉刷新的进度布局 (等同于旧版本的down.resetShowDownScroll:true);<br/>
  &nbsp;&nbsp; 2.3  传参false, 则不显示上拉和下拉的进度 (常用于静默更新列表数据);
<br/>
<br/>

### v 1.1.4 --- 2017-08-10 
个人内测版,略过~
<br/>
<br/>

### v 1.1.3 --- 2017-08-06 
1.mescroll.endErr() 默认隐藏上拉加载中的布局<br/>
2.mescroll.resetUpScroll() 内部重置时间为null,而非原来的空串
<br/>
<br/>

### v 1.1.2 --- 2017-08-01 
1.PC端可自定义滚动条样式<br/>
2.可配置onScroll来监听滚动条的位置<br/>
3.主动触发下拉刷新mescroll.triggerDownScroll()显示下拉布局加入动画效果过渡<br/>
4.重置列表mescroll.resetUpScroll(isShowLoading)新加isShowLoading参数: 是否显示下拉或者上拉的进度布局<br/>
  &nbsp;&nbsp; 4.1 不传参或true,则显示进度布局;<br/>
  &nbsp;&nbsp; 4.2 传false,则不显示;常用于切换菜单时静默更新列表数据;
<br/>
<br/>

### v 1.1.1 --- 2017-07-15  
经过大半年的实践优化, 分享给大家的第一个稳定版本  
<br/>
<br/>

### v 1.0.0 --- 2016-10-10  
个人项目中使用