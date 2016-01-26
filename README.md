# NodeschoolSantiago
Nodeschool Santiago Site Generator

Construido con [Hexo](https://hexo.io/)

Como correr
---
* `npm install`
* `hexo server`

Como agregar un Post
---
* hexo new [layout] <title>
(post is the default layout, but you can supply your own. You can change the default layout by editing the default_layout setting in _config.yml.)

Layout  -	  Path
post	  -   source/_posts
page    -   source
draft	  -   source/_drafts


Setear Entorno
---
Agregar el remote de nodeschool
* `git remote add nodeschool git@github.com:nodeschool/Santiago.git`

Como deployear 
---
* Crear Branch
* `git add -A`
* `git commit -m "msg"`
* `git push`
* Mergear branch
* `git checkout master && git pull -f`
* `git push nodeschool gh-pages -f`
