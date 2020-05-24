## Использование OpenStreetMap в проекте Android Studio

В этой статье мы рассмотрим использование OpenStreetMap на примере android приложения WeekendMR.

Вся информация была взята из откртых источников. 

### Интеграция нужных библиотек

Для начала работы нужно интегрировать необходимые библиотеки в проект. Делать это нужно в файле _build.gradle (Module: app)_

```markdown
    implementation 'org.osmdroid:osmdroid-android:6.1.1'
    implementation 'org.osmdroid:osmdroid-wms:6.1.1'
    implementation 'org.osmdroid:osmdroid-mapsforge:6.1.1'
    implementation 'org.osmdroid:osmdroid-geopackage:5.6.4'
```
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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/WeekendMR/wrmosmd/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
