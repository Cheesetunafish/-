# -
2022.2.11寒假考核




## 2.12
感觉自己的思维很混乱，根本不知道从哪里开始下手。这种毫无进展的感觉让我压力崩的太大，学习的效率也很低。出现了一个BUG，有可能是导入第三方库的时候导致的，反复删除添加podfile也没有解决，网上搜了一些解决方案也没有解决。希望以后要对自己有信心，不要陷入怀疑自我的地步。

## 2.13
解决了pod报错问题之后，就终于可以通过运行看到自己的进度了，至少现在不是茫然地不知道该干什么的状态了。只不过总是在一个地方纠结太久，从而把当下应该做的事情给拖滞了，这也是我的老毛病了。按顺序做好，不要着急，调整好思路是最重要的。这样一件一件完成并做好计划中的事情，也会让学习效率大大提高。
#### 问题记录：
1.framework not found Pods_____问题
问题：报错
解决：把项目名字从中文改成英文后解决了。

2.Unknown class ViewController in Interface Builder file.报错
问题：删除了原本的ViewController，但是Mian.stroryboard中的 ViewController依然是继承它。
解决：让 Mian.stroryboard中的 ViewController 继承于一个存在的类。

3. “”-[__NSArrayI objectAtIndexedSubscript:]: index 6 beyond bounds [0 .. 5]"
问题：运行后，数组索引超出范围崩溃
解决：数组从0开始记录。调整数字大小。

## 2.15
#### 问题记录：
1.过往新闻date
2.上拉刷新下拉加载
