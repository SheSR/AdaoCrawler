# ac匿名版（A岛）首页图片爬虫 #

突发奇想地做了这么一个爬虫（毕竟图库特别有意思）

通过查看网页源代码可以看到这个

	<img src="http://cover.acfunwiki.org/cover.php" title="开放包容 理性客观 有事说事 就事论事 顺猴者昌 逆猴者亡"/>

也就是说**每次访问php链接看到的图片是随机的**

所以通过循环调用可以实现多次获取图片，在通过保存到本地实现图片爬虫

**缺点是不一定完整的把整个图库都爬取到（图片数量未知），而且可能获取到重复的图片**
</br>有待改进中。。。




	