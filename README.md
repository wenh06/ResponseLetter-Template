# Response letter 模板

入口文件: [main.tex](main.tex)

## 用法

在某个文件夹, 例如 2026 (用年份比较好区分以及组织, 也可以用别的, 例如期刊/会议简称) 创建一个文件, 例如 `seizure-jocn-R1-202512.tex` (最好含有文章 ID, 或者其他容易区分的代号). 然后从模板文件夹 [templates](templates) 里面挑一个模板, 把文件内容复制到刚才创建的文件里, 把相关的占位符 (文章 ID, 标题, 作者等) 改掉, 去写就行了. 最后在入口文件 [main.tex](main.tex) 里面把其他行都注释掉, 添加上刚才创建的文件:

```latex
\input{2026/seizure-jocn-R1-202512.tex}
```

## 模板

- [advanced](templates/advanced.tex): 比较精致
- [simple](templates/simple.tex): 比较简约
- [numbda](templates/numbda.tex): Tsinghua Numbda 课题组 response letter 模板, 偏简约
