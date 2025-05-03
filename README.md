# 概述
  

- 如果你还没有下载termux可以点击[这里](https://f-droid.org/en/packages/com.termux/)


- 假如你在代码使用的过程中出现类似于的选项。
>Do you want to continue? [Y/n]
>
- 直接回车enter即可



# 一键代码使用
   ## 短信轰炸
  
  `source <(curl -L https://raw.githubusercontent.com/cat-bucket/cat-osint/main/sms.txt)`
- 直接粘贴代码进入即可，后续可以直接使用下列指令（不要更新接口）

- 基本版
  `cd cat-osint;python easy.py`
  
- 不同参数（同原版smsboom）
  `cd cat-osint;python main.py run -t 64 -p 184****9269 -f 60 `

  ## 邮箱轰炸
  
  在使用之前配置
  
 `pkg install git -y && pkg install php -y && pkg install python -y && git clone https://github.com/cat-bucket/mail-bomber && cd mail-bomber
`
 

### 无需邮箱但无法指定内容
   
更新接口（可选）

`php index.php update-nodes`

后续使用

`cd mail-bomber;php index.php start-bombing 邮箱`

替换要轰炸的邮箱




# 免责声明
本库为对各种程序的简单调用提供，仅供参考，禁止用于商业及非法用途。使用一键指令可能造成的事故与损失，短信轰炸并不安全，警遵中国法律。


