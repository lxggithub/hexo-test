# Hexo Configuration
## Docs: https://hexo.io/docs/configuration.html
## Source: https://github.com/hexojs/hexo/

# Site ��վ
title: �ྲྀ�������		#��վ����
subtitle: ���������		#��վ������
description: hello,every body!~	#��վ����
author: Tengj Jun		#��������
language: zh-CN			#��վʹ�õ�����
timezone:			#��վʱ����Hexo Ĭ��ʹ�������Ե�ʱ��

# URL ��ַ
## ���������վ�������Ŀ¼�У����� http://yoursite.com/blog�����뽫���� url ��Ϊ http://yoursite.com/blog ���� root ��Ϊ /blog/��
url: http://tengj.github.io
root: /
permalink: :year/:month/:day/:title/
permalink_defaults:

# Directory Ŀ¼����
source_dir: source	 #Դ�ļ��У�����ļ�������������ݡ�
public_dir: public	 #�����ļ��У�����ļ������ڴ�����ɵ�վ���ļ���
tag_dir: tags		 #��ǩ�ļ���
archive_dir: archives	 #�鵵�ļ���
category_dir: categories #�����ļ���
code_dir: downloads/code #nclude code �ļ���
i18n_dir: :lang		 #���ʻ���i18n���ļ���
skip_render:		 #����ָ���ļ�����Ⱦ������ʹ�� glob ����ʽ��ƥ��·����

# Writing ����
new_post_name: :title.md # �½�����Ĭ���ļ���
default_layout: post     # Ĭ�ϲ���
titlecase: false # Transform title into titlecase
external_link: true # ���±�ǩ�д�һ���ⲿ���ӣ�Ĭ��Ϊtrue
filename_case: 0    #ת���ļ�����1����Сд��2������д��Ĭ��Ϊ0����˼���Ǵ������µ�ʱ���Ƿ��Զ�����ת���ļ�����Ĭ�Ͼ��У����岻��
render_drafts: false  #�Ƿ���Ⱦ_draftsĿ¼�µ����£�Ĭ��Ϊfalse
post_asset_folder: false #���� Asset �ļ���
relative_link: false	#�����Ӹ�Ϊ���Ŀ¼�����λַ��Ĭ��false
future: true		#��ʾδ�������£�Ĭ��false
highlight:	#����������
  enable: true
  line_number: true
  auto_detect: false
  tab_replace:

# Category & Tag ����ͱ�ǩ������
default_category: uncategorized		#Ĭ�Ϸ���
category_map:				#�������
tag_map:				#��ǩ����

# Date / Time format
## Hexo uses Moment.js to parse and display date
## You can customize the date format as defined in
## http://momentjs.com/docs/#/displaying/format/
date_format: YYYY-MM-DD
time_format: HH:mm:ss

# Pagination ��ҳ
## Set per_page to 0 to disable pagination
per_page: 10	#ÿҳ��ʾ�������� (0 = �رշ�ҳ����)
pagination_dir: page	#��ҳĿ¼

# Extensions
## Plugins: https://hexo.io/plugins/
## Themes: https://hexo.io/themes/
theme: jacman

# Deployment
## Docs: https://hexo.io/docs/deployment.html
deploy:
  type: git
  repository: https://github.com/tengj/tengj.github.com.git
  branch: master
����ĵ�_config.yml����

�����ļ� _config.yml λ�������Ŀ¼��,���������ҵ�����

##### Menu
menu:
  ��ҳ: /
  �鵵: /archives
  ��ǩ: /tags
  ����: /categories
## you can create `tags` and `categories` folders in `../source`.
## And create a `index.md` file in each of them.
## set `front-matter`as
## layout: tags (or categories)
## title: tags (or categories)
## ---

#### Widgets
widgets: 
- github-card
- category
- tag
- archive
- tagcloud
- rss
  ## provide eight widgets:github-card,category,tag,rss,archive,tagcloud,links,weibo



#### RSS 
rss: /atom.xml ## RSS address.

#### Image
imglogo:
  enable: true             ## display image logo true/false.
  src: img/logo.png        ## `.svg` and `.png` are recommended,please put image into the theme folder `/jacman/source/img`.
favicon: img/favicon.ico   ## size:32px*32px,`.ico` is recommended,please put image into the theme folder `/jacman/source/img`.     
apple_icon: img/jacman.jpg ## size:114px*114px,please put image into the theme folder `/jacman/source/img`.
author_img: img/author.jpg ## size:220px*220px.display author avatar picture.if don't want to display,please don't set this.
banner_img: #img/banner.jpg ## size:1920px*200px+. Banner Picture
### Theme Color 
theme_color:
    theme: '#2ca6cb'    ##the defaut theme color is blue

# �����������
# available: default | night
highlight_theme: default

#### index post is expanding or not 
index:
  expand: true           ## default is unexpanding,so you can only see the short description of each post.
  excerpt_link: Read More  

close_aside: false  #close sidebar in post page if true
mathjax: false      #enable mathjax if true

### Creative Commons License Support, see http://creativecommons.org/ 
### you can choose: by , by-nc , by-nc-nd , by-nc-sa , by-nd , by-sa , zero
creative_commons: none

#### Author information
author:
  intro_line1:  "����Ա�ϱ��Ӷ�����������ʹ"    ## your introduction on the bottom of the page
  intro_line2:  "This is my blog,Try to do better."  ## the 2nd line
  weibo:      ## e.g. wuchong1014 or 2176287895 for http://weibo.com/2176287895
  weibo_verifier: b3593ceb    ## e.g. b3593ceb Your weibo-show widget verifier ,if you use weibo-show it is needed.
  tsina:      ## e.g. 2176287895  Your weibo ID,It will be used in share button.
  douban:     ## e.g. wuchong1014 or your id for https://www.douban.com/people/wuchong1014
  zhihu:      ## e.g. jark  for http://www.zhihu.com/people/jark
  email:      ## e.g. imjark@gmail.com
  twitter:    ## e.g. jarkwu for https://twitter.com/jarkwu
  github: tengj    ## e.g. wuchong for https://github.com/wuchong
  facebook:   ## e.g. imjark for https://facebook.com/imjark
  linkedin:   ## e.g. wuchong1014 for https://www.linkedin.com/in/wuchong1014
  google_plus:    ## e.g. "111190881341800841449" for https://plus.google.com/u/0/111190881341800841449, the "" is needed!
  stackoverflow:  ## e.g. 3222790 for http://stackoverflow.com/users/3222790/jark
## if you set them, the corresponding  share button will show on the footer

#### Toc
toc:
  article: true   ## show contents in article.
  aside: true     ## show contents in aside.
## you can set both of the value to true of neither of them.
## if you don't want display contents in a specified post,you can modify `front-matter` and add `toc: false`.

#### Links
links:
#### Comment
duoshuo_shortname: ��MD   ## e.g. wuchong   your duoshuo short name.
disqus_shortname:    ## e.g. wuchong   your disqus short name.

#### Share button
jiathis:
  enable: false ## if you use jiathis as your share tool,the built-in share tool won't be display.
  id:    ## e.g. 1889330 your jiathis ID. 
  tsina: ## e.g. 2176287895 Your weibo id,It will be used in share button.

#### Analytics
google_analytics:
  enable: false
  id:        ## e.g. UA-46321946-2 your google analytics ID.
  site:      ## e.g. wuchong.me your google analytics site or set the value as auto.
## You MUST upgrade to Universal Analytics first!
## https://developers.google.com/analytics/devguides/collection/upgrade/?hl=zh_CN
baidu_tongji:
  enable: true
  sitecode: e6d1f421bbc9962127a50488f9ed37d1 ## e.g. e6d1f421bbc9962127a50488f9ed37d1 your baidu tongji site code
cnzz_tongji:
  enable: false
  siteid:    ## e.g. 1253575964 your cnzz tongji site id

#### Miscellaneous
ShowCustomFont: true  ## you can change custom font in `variable.styl` and `font.styl` which in the theme folder `/jacman/source/css`.
fancybox: true        ## if you use gallery post or want use fancybox please set the value to true.
totop: true           ## if you want to scroll to top in every post set the value to true


#### Custom Search
google_cse: 
  enable: false
  cx:   ## e.g. 018294693190868310296:abnhpuysycw your Custom Search ID.
## https://www.google.com/cse/ 
## To enable the custom search You must create a "search" folder in '/source' and a "index.md" file
## set the 'front-matter' as
## layout: search 
## title: search
## ---
baidu_search:     ## http://zn.baidu.com/
  enable: false
  id:   ## e.g. "783281470518440642"  for your baidu search id
  site: http://zhannei.baidu.com/cse/search  ## your can change to your site instead of the default site
  
tinysou_search:     ## http://tinysou.com/
  enable: false
  id:  ## e.g. "4ac092ad8d749fdc6293" for your tiny search id
  
  
  ˵��:

menu Ĭ��û������ /tags �� /categories ҳ�棬�����Ҫ�������ڲ���Ŀ¼�µ� source �ļ����зֱ��� tags �� categories �ļ���ÿ���ļ����зֱ����һ�� index.md �ļ�������Ϊ��
layout: tags (��categories)
title: tags (��categories)
---
��Ϊ�������Ѿ�������������ҳ���ģ�壬�������ǻᱻ��ȷ�Ľ���������

widgets: �ṩ��8��С���ߡ�
rss: ����д�㲩�͵�RSS��ַ��
theme_color: Ĭ��������ɫ���޸�һ�¾��ܸı���������������ɫ���������ģ��Ƽ�������ɫ #2ca6cb #ea6753 #589baf
ShowCustomFont: �����Զ������壬�������һ��ǰ�˻��������޸� font.styl �滻Ϊ��ϲ�������塣
toc: �Ƿ������������л������е�Ŀ¼���ܡ����߿��Զ�Ϊ true ��Ϊ false ��ͬʱ�������ϣ�����ض���ĳһƪ�����йر�Ŀ¼����������������ļ���ͷ�е� front-matter �м���һ�� toc: false ��
fancybox: Ĭ�Ϲرգ������ʹ��Hexo��������Gallery���͵����£���ô������Ϊ true ��ͬʱ��Ҫ���� fancybox.js ����Ĳ���Ŀ¼��scripts�ļ����У���ps: �Һ������Hexo���������������ꡣ
author: ������Ϣ�����龡����д���������� tsina ���������΢��ID����ͬ���û�����΢����ҳ��ַ������������Ժ������û���΢���Ϸ��������µ�ͬʱ���Զ�@�㡣
duoshuo_shortname: ��дduoshuo_shortname��˵���û��������ö�˵����ϵͳ���ڴ�½���������õ�����ϵͳ
jiathis: ��������ϵͳ��Ĭ�Ϲرգ���Ϊ�����Ѿ�������ԭ���ķ������ܡ�
google_analytics: Google Analytics׷�ٴ��롣��ע�⣺*Google Analytics�Ѿ���������Universal Analytics������ǰ����̨�������Google Analytics�汾��������׷�ٴ��� ������Ϣ���������˽⡣
google_cse: Google�Զ�����������������Զ���������Ҫ�ȵ�¼Google CSE�����ú����վ�㣬����ô��Զ���������ID����������Ҫ�ڲ���Ŀ¼�µ�source�ļ����н���search�ļ��в�����һ�� index.md �ļ�������Ϊ��
layout: search
title: search
---