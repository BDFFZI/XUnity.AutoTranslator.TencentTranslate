# XUnity.AutoTranslator.TencentTranslate
使XUnity.AutoTranslator支持腾讯翻译的扩展插件。
## 优点（对比百度翻译）
- 更快的并发速度（每秒查询次数为5，百度只有1）
- 更多的翻译次数（每月支持5百万字符，百度只有5万）
## 问题
- 百度翻译也有该问题，翻译调用速度过快时，偶尔会出现无法翻译的情况，建议配合XUnity.AutoTranslator的失败回调功能处理。
- 在UnityInjector框架下无法识别到该后端，但BepInEx可以，尝试了混合使用，好在没有问题。
## 使用
放在XUnity.AutoTranslator插件目录的Translators文件夹下，翻译插件都是统一放在那的，相关信息在XUnity.AutoTranslator中都有说明。