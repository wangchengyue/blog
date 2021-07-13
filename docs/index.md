## 歡迎來到我的Blog-d.com

You can use the [editor on GitHub](https://github.com/wangchengyue/blog.github.io/edit/main/docs/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/wangchengyue/blog.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.


### Linux 系統上下載遠程的ftp服務器的文件以及文件夾

普通的ftp文件服務系統，並不能批量下載子目錄，我們可以使用wget 命令使用，
先創建好你要將文件保存到的目錄，然後執行的```wget``` 命令:
```#wget ftp://IP:PORT/* --ftp-user=xxx --ftp-password=xxx -r```
