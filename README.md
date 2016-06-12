网络爬虫
==========================
>
爬虫听起来很高大上，一直觉得很神秘
>
所以亲自实践下（ 其实是照着https://github.com/alsotang/node-lessons/tree/master/lesson3  ）过了遍代码
>
原来指定网页的爬虫很简单 就是用请求该网页拿到网页内容（superagent(http://visionmedia.github.io/superagent/ ，是个 http 方面的库，可以发起 get 或 post 请求）
>
然后在用cheerio  （cheerio(https://github.com/cheeriojs/cheerio ， 大家可以理解成一个 Node.js 版的 jquery）解析出想要的数据
>
感谢原作者
>
扩展：
   如何实现适用于所有的爬虫？
