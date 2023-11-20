# mac微信防撤回

1. 在github上下载 **“WeChatTweak-CLI”** 插件   
   [微信防撤回插件](https://github.com/sunnyyoung/WeChatTweak-CLI)   
2. 将下载的 **"WeChatTweak-CLI"** 插件放置在文稿或者不会**~~删除~~**的文件夹中
例如：
![wechat防撤回截图20231120](media/17004514947437/wechat%E9%98%B2%E6%92%A4%E5%9B%9E%E6%88%AA%E5%9B%BE.png)


3. 打开终端，使用cd命令进入到保存**WeChatTweak-CLI**插件的文件夹中
   例如：
   `cd ~/Users/macos/Documents`
   
4. 再依次执行一下命令行
   ```
   1. xattr -d com.apple.quarantine wechattweak-cli
   2. chmod +x wechattweak-cli
   3. sudo ./wechattweak-cli install
   ```
   
5. 执行完成后，再次重启微信

6. 在微信的设置中会增加一个**Tweak**的配置，能在微信设置查看到该配置证明防撤回插件已安装，并已生效。
      ![微信防撤回2 20231020](media/17004514947437/%E5%BE%AE%E4%BF%A1%E9%98%B2%E6%92%A4%E5%9B%9E2%2020231020.png)
