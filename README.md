# Unicode CJK

整理所有 Unicode CJK 字符。

## 协作整理

由于疏忽、参考资料有误等，码表可能会存在一些错误，
如果你发现了错误请通过 [PR] 或者 [issues] 反馈给我。

+ 如果熟悉 Git 操作可在更正错误后发起 [PR]。
+ 如果不会 Git 操作可在 [issues] 中发起反馈。

[PR]: https://github.com/kitty-panics/unicode-cjk/pulls
[issues]: https://github.com/kitty-panics/unicode-cjk/issues

## 数据格式

每个文件一行一字，以 Tab (制表符) 进行分割，例：

```Text
U+4E00	一
```

## 文件列表

+ [CJK-All.txt](CJK-All.txt)
    + 整合下面 CJK-Basic/A/B/C/D/E/F/G/Compat/Compat-Supplement。
+ [CJK-Basic.txt](CJK-Basic.txt)
    + 基本区 (代码点：U+3007,U+4E00-U+9FFF (1+20992 个)，已使用：U+3007,U+4E00-U+9FFC (1+20989=20990 字))。
+ [CJK-A.txt](CJK-A.txt)
    + 扩展 A 区 (代码点：U+3400-U+4DBF (6592 个)，已使用：U+3400-U+4DBF (6592 字))。
+ [CJK-B.txt](CJK-B.txt)
    + 扩展 B 区 (代码点：U+20000-U+2A6DF (42720 个)，已使用：U+20000-U+2A6DD (42718 字))。
+ [CJK-C.txt](CJK-C.txt)
    + 扩展 C 区 (代码点：U+2A700-U+2B73F (4160 个)，已使用：U+2A700-U+2B734 (4149 字))。
+ [CJK-D.txt](CJK-D.txt)
    + 扩展 D 区 (代码点：U+2B740-U+2B81F (224 个)，已使用：U+2B740-U+2B81D (222 字))。
+ [CJK-E.txt](CJK-E.txt)
    + 扩展 E 区 (代码点：U+2B820-U+2CEAF (5776 个)，已使用：U+2B820-U+2CEA1 (5762 字))。
+ [CJK-F.txt](CJK-F.txt)
    + 扩展 F 区 (代码点：U+2CEB00-U+2EBEF (7488 个)，已使用：U+2CEB0-U+2EBE0 (7473 字))。
+ [CJK-G.txt](CJK-G.txt)
    + 扩展 G 区 (代码点：U+30000-U+3134F (4944 个)，已使用：U+30000-U+3134A (4939 字))。
+ [CJK-Compat.txt](CJK-Compat.txt)
    + 兼容表意文字区 (代码点：U+F900-U+FAFF (512 个)，已使用：U+F900-U+FA6D,U+FA70-U+FAD9 (472 字))。
+ [CJK-Compat-Supplement.txt](CJK-Compat-Supplement.txt)
    + 兼容表意文字补充区 (代码点：U+2F800-U+2FA1F (544 个)，已使用：U+2F800-U+2FA1D (542 字))。

**注：**

为方便管理，将争议汉字 "〇 (U+3007)" 由 "符号和标点区" 移动到 "基本区 (CJK-Basic.txt)"，并置于文件开头。

## 参考资料

参考资料可在 [参考资料] 目录下找到。其中非文件类的在线资料将转换成 PDF 快照存放。

+ [Blocks.txt - Unicode]

[参考资料]: 参考资料
[Blocks.txt - Unicode]: https://www.unicode.org/Public/UCD/latest/ucd/Blocks.txt

## 教程

无。

## 相关项目

### [cj-tables]

收集整理中国的国标汉字表，即 [通用规范汉字表]、[常用标准字体表 (甲表)]、
[次常用标准字体表 (乙表)]。

[cj-tables]: https://github.com/kitty-panics/cj-tables
[通用规范汉字表]: https://zh.wikipedia.org/wiki/%E9%80%9A%E7%94%A8%E8%A7%84%E8%8C%83%E6%B1%89%E5%AD%97%E8%A1%A8
[常用标准字体表 (甲表)]: https://zh.wikipedia.org/wiki/%E5%B8%B8%E7%94%A8%E5%9C%8B%E5%AD%97%E6%A8%99%E6%BA%96%E5%AD%97%E9%AB%94%E8%A1%A8
[次常用标准字体表 (乙表)]: https://baike.baidu.com/item/%E6%AC%A1%E5%B8%B8%E7%94%A8%E5%9B%BD%E5%AD%97%E6%A0%87%E5%87%86%E5%AD%97%E4%BD%93%E8%A1%A8

### [unicode-cjk]

收集整理所有 Unicode CJK 字符。

[unicode-cjk]: https://github.com/kitty-panics/unicode-cjk

### [unicode-cjk-ids]

备份 "[chise/ids.git]" 仓库。

[unicode-cjk-ids]: https://github.com/kitty-panics/unicode-cjk-ids
[chise/ids.git]: http://git.chise.org/git/chise/ids.git
