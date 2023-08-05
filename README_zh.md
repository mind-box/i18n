# 灵感盒子国际化（显示语言的翻译）

> 我们的[官网地址](https://www.mindbox.cc)，你在官网上可以了解更多关于灵感盒子的内容
> 

## 添加新的语言

首先在`locale-identifiers.json`文件中查找你所在国家或地区的`Locale Identifier: zh`(以zh为例)。看是否在`locales`文件夹中是否已有以`zh`命名的文件夹，如果没有，请创建以`zh`文件夹，并将`en`文件夹中的文件复制到`zh`文件夹中，将`translation.json`文件中的字段值翻译成你想翻译的语言。注意，在翻译过程中，保留`{{count}}`文本。

## 提升已有语言的翻译

由于灵感盒子在不断迭代，所以会添加一些新的文本，因此已有的翻译很有可能已经过时，当你在使用灵感盒子的过程中，发现过时或缺失的翻译时，我们非常欢迎你修改或添加新的翻译，在`locales/en`文件夹的`translation.json`文件，可以找到所有需要翻译的文本，当然这个文件中的语法也会有错误，欢迎改正

## 感谢

- English: [Jocs](https://github.com/Jocs)
- Simplified Chinese: [Jocs](https://github.com/Jocs)

