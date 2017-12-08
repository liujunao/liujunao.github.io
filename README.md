## hexo搭建教程

- [官网教程](https://hexo.io/zh-cn/docs/setup.html)
- [优秀博客教程](http://blog.csdn.net/chwshuang/article/details/52350518)
- [优秀主题设计讲解教程](https://github.com/Sam618/hexo-theme-sam#%E6%8F%92%E4%BB%B6%E5%87%86%E5%A4%87)



### 解决README.md文件上传问题

> 将创建好的README.md文件放入到根目录下面的sources文件夹中，然后再配置根目录下面的 _config.yml文件的 
>
> ````
> skip_render: 
>   - README.md
> ```

### 解决每次 hexo deploy 后都会出现的 404页面访问错误

> 在根目录下面的sources文件夹中创建 CNAME文件，并写上自己博客的网址，如：www.yoursite.com **只能有一个域名**, 然后再在根目录下面的 _config.yml 文件中配置
>
> ```
> skip_render:
>   - CNAME
> ```

