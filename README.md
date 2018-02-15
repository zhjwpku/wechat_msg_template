# Wechat Message Template

本项目的只有一个，就是微信群发信息带上接收者的备注或昵称

## Idea from

每年都会收到很多群发的信息，有时候别人可能觉得你没有诚意而忽略你的信息，本项目会增加祝福消息的回复率。

![Wechat templete idea from](imgs/wechat_template_idea_from.png)

## Requirements

* python3
* only tested on Mac

## Usage

```
pip3 install -r requirements.txt
## 编辑 wechat_msg_template 中的模板，然后运行
python3 wechat_msg_template.py
```

根据提示扫码登录，接下来就是等待别人的祝福吧 :)

## Code base

Most of the codes are borrowed from [WeixinBot](https://github.com/Urinx/WeixinBot), you should check the API from its README.
