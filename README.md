# hexo-generator-category-enhance

[![NPM version](https://badge.fury.io/js/hexo-generator-category-enhance.svg)](http://badge.fury.io/js/hexo-generator-category-enhance)

Category generator for [Hexo].

## Installation

``` bash
$ npm install hexo-generator-category-enhance --save
```

## Options

``` yaml
category_generator:
  per_page: 10
  enable_index_page: true
```

- **per_page**: Posts displayed per page. (0 = disable pagination)
- **enable_index_page**: 
  该值设置为 true 时, 将会创建一个分类的主页面，同时你还需要创建一个 hexo 的布局模板，模板命名为：category-index.ejs 或其他模板引擎后缀。
  Generate category index page if set true, and first you should creat hexo layout templete file named: "category-index.ejs" or other template engine extension. (false = don't generate)
## License

MIT

[Hexo]: http://hexo.io/