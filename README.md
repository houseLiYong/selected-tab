# selected-tab
选项卡插件 <br>
js实现选项卡思路：点击选项卡按钮切换到相应的内容，就是通过点击按钮把内容通过display(block none)来实现切换。<br>
1、首先获取选项卡和显示内容的元素。<br>
2、通过for循环遍历选项卡li元素添加onclick或者onmousemove事件。<br>
3、因为点击当前li时，会以高亮状态显示，所以再通过for循环遍历把所有的li样式，设置为空，把所有的div的display设置为none。<br>
4、把当前的li添加样式active,把当前div显示出来，display设置为block。<br>
注：给多个元素添加多个事件要用for循环遍历。如选项卡是点击切换，当前li高亮，点击和高亮就是两个事件，所以要两个for循环遍历。<br>
<br>
<br>
<br>
<br>
通过封装函数来调用，第一个参数id是整个大的div的id，第二个参数id是内容的整个部分的id。只需传入这两个参数即可。<br>
基本功能可以实现。<br>
