# mac微信防撤回

1. 在github上下载 **“WeChatTweak-CLI”** 插件   
   地址：[微信防撤回插件](https://github.com/sunnyyoung/WeChatTweak-CLI)   
   感谢Sunny Young、Joseph Hau大佬制作提供
2. 将下载的 **"WeChatTweak-CLI"** 插件放置在文稿或者不会**~~删除~~**的文件夹中
例如：
![01wechat20231120](photo/01wechat20231120.png)


3. 需要确认终端是否已加入到 **'完全磁盘访问权限'** (没有加入需要把终端加入到 **‘完全磁盘访问权限’** 中)
   ![04wechat20231120](photo/04wechat20231120.jpg)
   
4. 打开终端，使用cd命令进入到保存**WeChatTweak-CLI**插件的文件夹中
   例如：
   `cd /Users/macos/Documents`
   
5. 再依次执行一下命令行
   ```
   1. sudo xattr -d com.apple.quarantine wechattweak-cli
   2. chmod +x wechattweak-cli
   3. sudo ./wechattweak-cli install
   ```
   
6. 执行完成后，再次重启微信

7. 在微信的设置中会增加一个**Tweak**的配置，能在微信设置查看到该配置证明防撤回插件已安装，并已生效。
   ![02wechat220231120](photo/02wechat220231120.png)

效果展示
![03wechat20231120](photo/03wechat20231120.png)
