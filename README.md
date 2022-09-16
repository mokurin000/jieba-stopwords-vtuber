# jieba-stopwords-vtuber

## 生成词典

```bash
cat words/*/*txt > dict.txt
```

## 命名规范

该vtuber的常用名词放在 `words/[字母]/官方名.txt`

对于具有官方承认日文名的vtuber，使用日文罗马音首字母

对于具有官方承认中文名的vtuber，使用中文名第一个字拼音首字母

对于具有官方承认英文名的vtuber，使用英文名（First Name）首字母

对于其他语言的v，使用官方名称第一个字的UTF-8序列最后一个字节的后4位所对应的十六进制。

## 注意

Stop word不能包含Stop word

如果冲突会被盖掉
