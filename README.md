# RimeCustom

本来想用英文，不过我觉得用的都是国人吧，用回中文

The yaml file for Rime suitable for myself

The main file is


* squirrel.custom.yaml
* default.custom.yaml
* luna_pinyin_simp.custom.yaml
* luna_pinyin.custom.yaml
* installation.yaml


配置输入法外观和特性的几个文件：

* squirrel.custom.yaml ，自定义皮肤；
* default.custom.yaml ，设定备选词数量，定义输入方案；
* luna_pinyin_simp.custom.yaml ，定义扩充词库、加载符号库、模糊拼音。明月拼音·简化字输入方案配置文件，明月拼音对应的文件是 luna_pinyin.custom.yaml；
* installation.yaml，定义配置文件保存到 Dropbox 文件夹


扩展词库涉及到的几个配置文件，参照扩展词库内容，你可以自己定义类似词库：

* luna_pinyin.extended.dict.yaml，扩展词库主文件，其他词库都需要在这个主文件中定义才能被调用，如果不想加载某个词库在此文件中注释掉即可（在所在行前加 # 井号）
* luna_pinyin.sgmain.dict.yaml，搜狗细胞词库
* luna_pinyin.cn_en.dict.yaml，英文、中英文混合短语和名词
* luna_pinyin.emoji.dict.yaml，表情符号
* luna_pinyin.hanyu.dict.yaml，汉语大词典
* luna_pinyin.kaomoji.dict.yaml，颜文字表情符号
* luna_pinyin.poetry.dict.yaml，唐诗宋词、千家集、楚辞、诗经

词库文件是相对单独的，「鼠须管」中挂载词库的方式比以前更灵活，而且编辑起来也方便，在 luna_pinyin.extended.dict.yaml 这个词库主文件中定义并关联其他词库，而扩展词库的加载则是由 luna_pinyin_simp.custom.yaml 这个文件来决定。

现在的模板是双拼加模糊音，适合我个人，你可以根据自己的情况做调整。



