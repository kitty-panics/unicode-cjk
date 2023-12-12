# Unicode-CJK

整理所有 [Unicode CJK] 字符。

## 协作整理

由于疏忽、参考资料有误等，码表可能会存在一些错误，如果你发现了错误请通过
[Issues] 或者 [PR] 反馈给我。

+ 如果不会 Git 操作可在 [Issues] 中发起反馈。
+ 如果熟悉 Git 操作可在更正错误后发起 [PR]。

[Issues]: https://github.com/kitty-panics/unicode-cjk/issues
[PR]: https://github.com/kitty-panics/unicode-cjk/pulls

## 数据格式

每个文件一行一字，以 Tab (制表符) 进行分割，例：

```Text
U+2E80	⺀
U+2E81	⺁
U+2E82	⺂
U+2E83	⺃
```

## 文件列表

+ [All.txt] (按顺序整合下面所有字表)
+ [CJK-Radicals-Supplement.txt] (中日韩汉字部首补充)
    + 代码点：U+2E80-U+2EFF (128 个)
    + 已使用：U+2E80-U+2E99, U+2E9B-U+2EF3 (115 个)
+ [Kangxi-Radicals.txt] (康熙部首)
    + 代码点：U+2F00-U+2FDF (224 个)
    + 已使用：U+2F00-U+2FD5 (214 个)
+ [CJK-Symbols-and-Punctuation.txt] (中日韩符号和标点)
    + 代码点：U+3000-U+303F (64 个)
    + 已使用：U+3007 (1 个)
+ [CJK-Strokes.txt] (中日韩笔画)
    + 代码点：U+31C0-U+31EF (48 个)
    + 已使用：U+31C0-U+31E3 (36 个)
+ [CJK-Unified-Ideographs-Extension-A.txt] (中日韩统一表意文字扩展区 A)
    + 代码点：U+3400-U+4DBF (6592 个)。
    + 已使用：U+3400-U+4DBF (6592 个)。
+ [CJK-Unified-Ideographs.txt] (中日韩统一表意文字)
    + 代码点：U+4E00-U+9FFF (20992 个)。
    + 已使用：U+4E00-U+9FFF (20992 个)。
+ [CJK-Compatibility-Ideographs.txt] (中日韩兼容表意文字)
    + 代码点：U+F900-U+FAFF (512 个)。
    + 已使用：U+F900-U+FA6D, U+FA70-U+FAD9 (472 个)。
+ [CJK-Unified-Ideographs-Extension-B.txt] (中日韩统一表意文字扩展区 B)
    + 代码点：U+20000-U+2A6DF (42720 个)。
    + 已使用：U+20000-U+2A6DF (42720 个)。
+ [CJK-Unified-Ideographs-Extension-C.txt] (中日韩统一表意文字扩展区 C)
    + 代码点：U+2A700-U+2B73F (4160 个)。
    + 已使用：U+2A700-U+2B739 (4154 个)。
+ [CJK-Unified-Ideographs-Extension-D.txt] (中日韩统一表意文字扩展区 D)
    + 代码点：U+2B740-U+2B81F (224 个)。
    + 已使用：U+2B740-U+2B81D (222 个)。
+ [CJK-Unified-Ideographs-Extension-E.txt] (中日韩统一表意文字扩展区 E)
    + 代码点：U+2B820-U+2CEAF (5776 个)。
    + 已使用：U+2B820-U+2CEA1 (5762 个)。
+ [CJK-Unified-Ideographs-Extension-F.txt] (中日韩统一表意文字扩展区 F)
    + 代码点：U+2CEB0-U+2EBEF (7488 个)。
    + 已使用：U+2CEB0-U+2EBE0 (7473 个)。
+ [CJK-Compatibility-Ideographs-Supplement.txt] (中日韩兼容表意文字增补)
    + 代码点：U+2F800-U+2FA1F (544 个)。
    + 已使用：U+2F800-U+2FA1D (542 个)。
+ [CJK-Unified-Ideographs-Extension-G.txt] (中日韩统一表意文字扩展区 G)
    + 代码点：U+30000-U+3134F (4944 个)。
    + 已使用：U+30000-U+3134A (4939 个)。
+ [CJK-Unified-Ideographs-Extension-H.txt] (中日韩统一表意文字扩展区 H)
    + 代码点：U+31350-U+323AF (4192 个)。
    + 已使用：U+31350-U+323AF (4192 个)。
+ [CJK-Unified-Ideographs-Extension-I.txt] (中日韩统一表意文字扩展区 I)
    + 代码点：U+2EBF0-U+2EE5F (624 个)。
    + 已使用：U+2EBF0-U+2EE5D (622 个)。

[All.txt]: All.txt
[CJK-Radicals-Supplement.txt]: CJK-Radicals-Supplement.txt
[Kangxi-Radicals.txt]: Kangxi-Radicals.txt
[CJK-Symbols-and-Punctuation.txt]: CJK-Symbols-and-Punctuation.txt
[CJK-Strokes.txt]: CJK-Strokes.txt
[CJK-Unified-Ideographs-Extension-A.txt]: CJK-Unified-Ideographs-Extension-A.txt
[CJK-Unified-Ideographs.txt]: CJK-Unified-Ideographs.txt
[CJK-Compatibility-Ideographs.txt]: CJK-Compatibility-Ideographs.txt
[CJK-Unified-Ideographs-Extension-B.txt]: CJK-Unified-Ideographs-Extension-B.txt
[CJK-Unified-Ideographs-Extension-C.txt]: CJK-Unified-Ideographs-Extension-C.txt
[CJK-Unified-Ideographs-Extension-D.txt]: CJK-Unified-Ideographs-Extension-D.txt
[CJK-Unified-Ideographs-Extension-E.txt]: CJK-Unified-Ideographs-Extension-E.txt
[CJK-Unified-Ideographs-Extension-F.txt]: CJK-Unified-Ideographs-Extension-F.txt
[CJK-Compatibility-Ideographs-Supplement.txt]: CJK-Compatibility-Ideographs-Supplement.txt
[CJK-Unified-Ideographs-Extension-G.txt]: CJK-Unified-Ideographs-Extension-G.txt
[CJK-Unified-Ideographs-Extension-H.txt]: CJK-Unified-Ideographs-Extension-H.txt
[CJK-Unified-Ideographs-Extension-I.txt]: CJK-Unified-Ideographs-Extension-I.txt

## 参考资料

参考资料可在 [参考资料] 目录下找到。其中非文件类的在线资料将转换成 PDF 快照存放。

+ [Blocks.txt]
+ [字符集 - 字海网，叶典网]
+ [中日韩统一表意文字 - 维基百科]

[参考资料]: 参考资料
[Blocks.txt]: https://www.unicode.org/Public/UCD/latest/ucd/Blocks.txt
[字符集 - 字海网，叶典网]: http://www.yedict.com/zsts.htm
[中日韩统一表意文字 - 维基百科]: https://zh.wikipedia.org/wiki/%E4%B8%AD%E6%97%A5%E9%9F%93%E7%B5%B1%E4%B8%80%E8%A1%A8%E6%84%8F%E6%96%87%E5%AD%97

## 相关项目

### [cn-tables]

整理中国大陆简中、中国台湾繁中的国标汉字表。

[cn-tables]: https://github.com/kitty-panics/cn-tables

### [unicode-cjk]

整理所有 [Unicode CJK] 字符。

[unicode-cjk]: https://github.com/kitty-panics/unicode-cjk
[Unicode CJK]: https://www.unicode.org/Public/UCD/latest/ucd/Blocks.txt

### [unicode-cjk-98wubi]

整理 Unicode CJK 字符的 [五笔98] 编码。

[unicode-cjk-98wubi]: https://github.com/kitty-panics/unicode-cjk-98wubi
[五笔98]: http://98wb.ysepan.com

### [unicode-cjk-cangjie5]

整理 Unicode CJK 字符的 [仓颉5] 编码。

[unicode-cjk-cangjie5]: https://github.com/kitty-panics/unicode-cjk-cangjie5
[仓颉5]: https://github.com/Jackchows/Cangjie5

### [unicode-cjk-ids]

备份、修补 [chise/ids]。

[unicode-cjk-ids]: https://github.com/kitty-panics/unicode-cjk-ids
[chise/ids]: https://gitlab.chise.org/CHISE/ids.git

### [unicode-cjk-zhlf]

整理 Unicode CJK 字符的 [字海两分] 编码。

[unicode-cjk-zhlf]: https://github.com/kitty-panics/unicode-cjk-zhlf
[字海两分]: http://cheonhyeong.com/Simplified/download.html
