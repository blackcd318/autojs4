# autojs4
autojs4.1.1alpha2改了几个bug，加了几个添加任务的函数，仿照pro版的，不过只是基础的功能，凑合能用
1.有些界面使用id()不能得到控件
2.开机后不手动启动app而使得device.height和device.width返回值为0的不正确
3.添加了timers.addDisposableTask, timers.addDailyTask, timers.addWeeklyTask, timers.addIntentTask几个函数使脚本可以添加定时任务。使用方法参照pro版本(例子我放进去了）,只有基础功能
4.删掉了社区和市场(只是简单的不显示，初始化没改，代码挺复杂的，不想折腾)
5.把版本号加了1
