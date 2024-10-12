# x-Argus_x-Gorgon_x-Helios_x-khronos_x-Ladon_x-Medusa
抖音算法,抖音最新版算法,抖音6神,抖音点赞,抖音发作品,抖音播放视频,抖音修改资料,抖音评论,抖音私信,抖音采集,等等x-Argus,x-Gorgon,x-Helios,x-khronos,x-Ladon,x-Medusa

![PCZ)VM8~ZFURTQ8929%J75I](https://github.com/user-attachments/assets/42b7a29a-754c-4bd1-8e7c-d9fedddb21be)

先去抓包抖音最重要的就是抖音6神x-Argus,x-Gorgon,x-Helios,x-khronos,x-Ladon,x-Medusa，每个包都有这个6个参数，有这个6个就可以为所欲为了，
不管3721 先去idapro静态分析看看（砸壳抖音,发现可执行文件只有几百kb，肯定不是，最后frida动态调试,原来在framework里面，先看核心core）

![3YB~MI@ U$D0{AP%J`6)D%H](https://github.com/user-attachments/assets/fc02bf51-c48e-4eb5-a356-63b41d6afd86)

直接静态分析（差不多300mb.解析太费时间了，一个晚上）
![PM5T}K)N)OX~FL_W{SPVXGY](https://github.com/user-attachments/assets/b99e0e9b-4f63-4357-8ed7-62c542875fcf)

静态分析找太不容易了  都是混淆的  放弃   直接frida动态调试（过程直接太痛苦）
知道了x-Argus是sourceInfo和url?后面部分和data的md5加密和时间戳，和标识符等等加密出来的结果x-argus: hIQKZw==
X-Gorgon是简单一些是url?后面部分和时间戳和data的md5加密计算出来的
X-Medusa和x-Argus类似  这两个最难
X-Ladon是时间戳标识符组合
X-Khronos就是时间戳
不过还好,终于逆向出来直接上部分代码
![IW5TJ5DEVPP9QUI} PWKM_U](https://github.com/user-attachments/assets/3cfd5337-fc33-4c37-bb6b-da66115ec2a6)

测试没问题之后  开心  搭建服务器，可以不用手机做任何抖音操作了，

![ICF9L}8{G0H`~57CC67F UE](https://github.com/user-attachments/assets/0a82f366-5947-48df-99be-57fcf3918986)

需要抖音url和device_type（是什么手机）和did和lanusk和os_version和stub和抖音版本version和x-common-params-v2的值
有什么问题可以联系我！！！
随时可以找我测试！！！！！免费
随时可以找我测试！！！！！免费
随时可以找我测试！！！！！免费
随时可以找我测试！！！！！免费
本人飞机telegra:@dy_core
本人飞机telegra:@dy_core
本人飞机telegra:https://t.me/dy_core


