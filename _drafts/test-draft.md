如果在写的blog暂时还不想发表，可以使用jekyll提供的draft功能。
为此需要在根目录创建一个名为_drafts的文件夹，并在其中新建草稿。

部分目录结构示例如下：
```shell
|-- xxx.github.io
    |-- _drafts
        |-- my_draft.md
    |-- _posts
        |-- my_blog.md
```

本地测试不开启draft功能时，只需要输入：

```shell
jekyll s
```

而开启draft功能时，需要输入：

```shell
jekyll s --drafts
```

