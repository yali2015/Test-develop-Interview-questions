##滴滴
1、首先自我介绍<br>
2、算法题：<br>
  两个有序链表合并成一个有序链表<br>
  选出一个数组中的素数<br>
3、Linux常用命令<br>
4、数据库sql语句<br>
测试题<br>
怎么测试一只笔，写测试用例<br>
<br>
1、简历上写的项目，实验室的、实习的，要说清楚；<br>
2、c++知识<br>
   多态是如何实现的<br>
   多线程与多进程<br>
   c++继承、多态、封装多看一看<br>
   面向对象的三个基本特征：封装、继承、多态<br>
   封装性：封装实现了类的接口和实现的分离，封装后的类隐藏了它的实现细节，就是说类的用户只需要使用接口而不需要访问实现的部分，实现代码的模块化。<br>
   <br>
   继承性：一个类可以创建它的子类，子类可以使用父类的方法和属性，而无需重新定义。<br>
   <br>
   多态性：多态是指可以将子类对象指针赋给父类对象指针，就是可以将父类对象指向子类的对象。从而实现一个接口多种实现方式，动态绑定。<br>
   实现多态有两种方式：覆盖和重载。覆盖是指子类重新定义父类的虚函数，重载是定义多个同名函数，但是返回类型和参数不同。<br>
3、多线程和多进程<br>
   多进程：就是同一时间里多个任务同时执行。比如我可以一边听歌，一边看新闻。一个进程可以有多个线程组成，每个线程都是可以独立运行。<br>
   分配资源的时候是以进程为单位，cpu调度以线程为单位。<br>
   进程开销大，线程开销小。<br>
4、算法<br>
   问了二分查找，这里寻找中间的值我说的是(low+high)/2,但是他指出这样不好。<br>
   数据量很大时，很容易超出int的最大值，所有用low+(high-low)/2<br>
5、linux:写出20个Linux常用命令<br>
   ls 显示文件目录 ll 显示更详细的文件目录，包括时间，文件是否可读写等 cd 切换根目录 cd .. 返回上一级目录 <br>
   pwd 显示当前路径 make 变异 clear 清除临时文件 ps 显示进程状态 kill 杀死进程 ipconfig 查看网络状况 shutdown 关机<br>
   mkdir 创建目录 cp 拷贝 mv 移动 rm -rf 删除 find 查找文件 ping测试网络连通 reboot重启<br>
6、测试相关问题<br>
   水杯的测试<br>
   滴滴app的测试（差不多从app的基本功能、异常请求、每秒最大能响应的请求次数）<br>
   1、首先测试app的基本功能是否正常：<br>
   比如刚打开一个app界面，会有当前位置的地图信息和出租车信息，测试显示是否正常。<br>
   界面上有出租车、快车、顺风车等，点击各个按钮是否正常跳转。<br>
   个人信息里面的各个设置是否可以正常设置。<br>
   下一个订单，看是否按照设定的那样，输入目的地，点击呼叫，看是否会得到响应并在地图上正确的显示出租车的位置信息。<br>
   2、响应时间，比如在不同场景下，打开最快和最慢的请求时间。<br>
   3、稳定性测试，会不会突然卡死闪退等。<br>
   4、兼容性测试，新老版本兼容，不同手机型号是否都可以正常运行。<br>
   <br>
##网易
   1、首先做了半个小时笔试题<br>
      斐波那契数列，编程实现求第n个数。<br>
      Linux查看网络状态的命令是什么。  netstat 
      数据库sql语句，两个表联合查询。<br>
      软件测试的目的是什么。<br>
      如何测试微博发布框。<br>
      给一段程序，有两个if判断语句，怎么做到条件覆盖。<br>
    2、自我介绍<br>
    3、简历上的项目挑一个具体的讲。<br>
    4、测试相关<br>
       如何测试微信语音功能，从哪些方面考虑。<br>
       如果老师让你买一批书，你应该如何实施。<br>
    5、其他<br>
       如果遇到了难以解决的问题，是怎么做的<br>
       如果给你一项任务，本来需要一周时间完成，现在让你三天内完成，你能想到什么办法，你会怎么做。<br>
       你的人生职业规划是什么。<br>
       你觉得你最大的优点和缺点是什么，举例说明。<br>
       为什么选择做测试，你觉得做测试你的优势是什么。<br>
       有没有看过面经之类的书籍，有没有了解过测试相关的知识，读过测试相关的书籍。<br>
       <br>
##百度
    1、自我介绍<br>
    2、简历上的项目，挑一个讲<br>
    3、Linux常用命令<br>
    4、c++相关<br>
       进程线程的区别和联系<br>
       TCP UDP的区别是什么，哪个是面上连接的<br>
       静态变量和动态变量存放地址是否一样<br>
       Malloc函数和new的区别<br>
       数组指针和指针数组如何表示<br>
       堆栈相关知识<br>
       纯虚函数和虚函数的区别<br>
       继承和多态的区别<br>
     5、算法<br>
       怎么把一串数字转成字符串<br>
       如果一个文件很大，10G内容，每一行都有一串数字，求出这个文件中前10个最大的数。<br>
     6、手写代码。<br>
       合并两个有序链表<br>
       读取文件的第n行内容<br>
     7、测试相关<br>
       如何测试微信发消息的功能。<br>
       如果给对方发送消息，显示已发送，但是对方没有收到，会是什么原因导致的。<br>
       找出原因后，应该怎么去测试是否是这个原因。<br>
       一个很大的代码平台，如何测试其中一个特定的模块。<br>
      8、其他
       最大的优点和缺点<br>
       职业规划<br>
       为什么要做测试<br>
      <br>
      <br>
      1、简历上写了的自己一定要会；<br>
      2、c++知识，多线程、多态、实现封装的好处<br>
      3、算法<br>
      句子逆序 string str = "today is sunday" 换成 "sunday is today"<br>
      4、linux我只写了了解，实习的时候用过基本的命令，没有多问。<br>
      5、测试<br>
      微信的测试<br>
      功能性测试微信包含的基本功能<br>
      异常测试：比如所发的信息特别长，是否可以正确收到，比如图片；对方网络突然断了，收发情况<br>
      性能测试：每秒可以收发的请求次数<br>
      稳定性测试：突然卡死、闪退等<br>
      兼容性测试：新老版本，不同手机机型是否都可以运行<br>
      6、测试<br>
      电梯的测试（问的频率很高）
   
