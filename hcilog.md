[mac adb](http://blog.csdn.net/chaoyue0071/article/details/42192305)

###hcidump
< Android 4.2

###hcilog [mac hci](http://www.aiuxian.com/article/p-497926.html)
>Android 4.2
各种级别的log 开关是在/etc/bluetooth/bt_stack.conf
 bt_stack.conf的文件内容如下

# Enable BtSnoop logging function
# valid value : true, false
BtSnoopLogOutput=true　//默认是false,如果需要抓取hcidump 的话,改成 true

# BtSnoop log output file
BtSnoopFileName=/sdcard/btsnoop_hci.log //默认写hcidump 的路径，btsnoop_hci.log 就是hcidump的log。可以按照你自己的需要修改。
(**diff vendor will difference motion ,may be nothing**)

###root
install software for your phone 
  
###adb (on Mac)
install android sdk
--
  adb path : .bashrc
  export PATH=$PATH{}:/Users/xxx/Library/Android/sdk/platform-tools
--
> * adb shell 
> * su (get root permission)
> * cd / (go root) 
> * cd /data/local (should su)
> * cat (lookup file)

－－
(> 4.3 bluedroid)
cat /data/misc/bluedroid/bt_config.xml [from:](http://www.aiuxian.com/article/p-576259.html)
－－



Post by **Kay**
Contact : kkkktan@163.com

###introduce
[What bluetooth](http://www.aiuxian.com/article/p-599365.html)
[Input bluetooth / profile](http://www.aiuxian.com/article/p-2851599.html)

  
