#测验
##2019年9月24日08:44:07
###参与人:

1.获取元素的方法有哪些?并简单描述该方法.
答:
   有四种方法
   用选择器   querySelector()和querySelectorAll()
   类名    设置class，用getElementsByTagName()
   标签名   用getElementsByTagName()来获取标签名
   ID      设置id，并获取getElementsById()来获取
   
2.如果有10个div元素,在不给元素设置id的情况下如何找到第4个div元素?
答:
     var div=document.getElementsByTagName('div');
   console.log(div[3])

3.querySelector()和querySelectorAll()的区别?
答:
   前者只能找到元素列表的第一个元素,后者可以全部找到
4.如何给元素div内增加一个子元素<a href="#">去百度</a>?
答:     设置一个div，id为sg，用innerHTML引入
       var sg = document.getElementById('sg');
       console.log(sg.innerHTML);
       sg.innerHTML = '<a href="#">去百度</a>';
5.<div class="box red">,在css中box类设定了宽度和高度,red类设定了div的背景颜色.如何通过改变类名blue改变背景颜色,请写出代码?
答:   var div=document.getElementsByTagName('div');
      console.log(div.className);
      div.className='box blue';
     