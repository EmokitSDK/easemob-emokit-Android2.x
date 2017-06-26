# 1. 简介
可以察言观色的环信IM

开心的妹子怎么搭讪？伤心的妹子怎么搭讪？招术一定不一样。   
愤怒的领导怎么汇报？焦虑的领导怎么回报？战术一定不一样。   
平和的客户怎么拿下？豁达的客户怎么拿下？话术一定不一样。   
呼叫中心的坐席人员哪句话刺激了顾客？顾客挂线时是否内心愉悦？   
那么，这些场景下的需求，不用发愁了，我们现在提供了一款可以察言观色的环信即时通讯SDK。   
我们知道，人与人之间的沟通，有三层功能，首先是接受内容，然后再是理解意图，当然还少不了读懂情绪。   
所以，借助强大的环信SDK，我们利用先进的Emokit5.0情绪识别算法，打造了这款绑定版SDK。具体包括以下功能：   
针对用户的对话自动断句，分析音频的语调、语速、停顿、音强的数据，识别双方情绪；   
未来还会利用表情识别技术，嵌入到环信的视频通讯功能里，不仅可以实时显示通讯各方的情绪，还能留下记录；   
此外，我们还提供表情包的API：针对每一种情绪，都有三国演义、红楼梦、晴天娃娃三套表情包；   
未来，还会开放根据情绪匹配音乐等功能。   
亲们，还犹豫什么，别浪费了环信SDK的强大性能，这款可以察言观色的绑定版SDK，相信借助您的代码，
一定能够实现更多更好玩的功能，满足更多更刺激的场景。永久免费哦！

# 2.	预备工作
第一步:使用Android Studio打开，导入 EaseUI


第二步: 添加AID和KEY  

初始化时候需要配置从EmoKit 开发者中心http://dev.emokit.com  申请的AID和 KEY。在AndroidManifest.xml中配置如下:

meta-data   
    android:name="EMOKIT_AID"   
    android:value="100001" 
  
meta-data
  
    android:name="EMOKIT_KEY"        
    android:value="98cd22f6f90141f8f1876dd2f5a27ea5"             
   

第三步:根据返回的情绪结果自定义功能  

在com.easemob.easeui.widget.chatrow.EaseChatRowVoice类onSetUpView()中自定义功能
可修改layout ease_row_sent_voice.xml, ease_row_received_voice.xml






# 3.	附录
3.1 情绪识别结果码表   
《EmoKit七种情绪描述》  

标签代码	情绪描述  	
K	平静；放松；专注；出神；  	
D	忧愁；疑惑；迷茫；无助；  
C	伤感；郁闷；痛心；压抑；  
Y	生气；失控；兴奋；宣泄；  	
M	开心；甜蜜；欢快；舒畅；  	
W	害怕；焦虑；紧张；激情；  	
T	厌恶；反感；意外；惊讶；  	


3.2 联系方式:   
反馈邮箱： feedback@emokit.com   
技术QQ群：125855917  

