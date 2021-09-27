# JavaBlog
基于Springboot的多人博客


### 二、技术栈
#### 1.前端
- Markdown编辑器
- Node.js

#### 2.后端
- 核心框架：Spring Boot
- 项目构建：jdk1.8、Maven 
- 持久层框架：Mybatis-Plus
- Jwt + Redis：
>1.用token令牌的登陆方式，访问认证速度快，session共享，保证了安全性
>2.redis实现令牌和用户信息的关系，给用户做缓存，灵活控制用户过期，续期，同时更安全
- ThreadLocal：保存，获取用户信息，实现线程隔离。之后做了value删除，防止内存泄漏

#### 3.数据库
- MySQL 

### 三、功能需求
博客后台待开发，权限系统待开发。
<br>

- 文章信息：文章列表、文章标题、文章内容、发布时间、访问量以及评论等信息
![image](https://github.com/njuptzx/JavaBlog/blob/main/picture/%E4%B8%BB%E9%A1%B5.PNG?raw=true)
![image](https://github.com/njuptzx/JavaBlog/blob/main/picture/%E6%96%87%E7%AB%A0%E8%AF%A6%E6%83%85.PNG?raw=true)
![image](https://github.com/njuptzx/JavaBlog/blob/main/picture/%E6%96%87%E7%AB%A0%E8%AF%A6%E6%83%852.PNG?raw=true)
<br>

- 分类文章：分类列表、分类文章信息
![image](https://github.com/njuptzx/JavaBlog/blob/main/picture/%E6%96%87%E7%AB%A0%E5%88%86%E7%B1%BB.PNG?raw=true)
<br>

- 文章归档：按时间文章归档
![image](https://github.com/njuptzx/JavaBlog/blob/main/picture/%E6%96%87%E7%AB%A0%E5%BD%92%E6%A1%A3.PNG?raw=true)
<br>

- 最热文章，最新文章，最热标签

![image](https://github.com/njuptzx/JavaBlog/blob/main/picture/%E6%9C%80.PNG?raw=true)
<br>

- 评论并回复
![image](https://github.com/njuptzx/JavaBlog/blob/main/picture/%E8%AF%84%E8%AE%BA1.PNG?raw=true)
![image](https://github.com/njuptzx/JavaBlog/blob/main/picture/%E8%AF%84%E8%AE%BA2.PNG?raw=true)
<br>

- 撰写文章并发布
![image](https://github.com/njuptzx/JavaBlog/blob/main/picture/%E5%86%99%E6%96%87%E7%AB%A0.PNG?raw=true)
<br>

- 用户注册，登录
![image](https://github.com/njuptzx/JavaBlog/blob/main/picture/%E6%B3%A8%E5%86%8C.PNG?raw=true)
![image](https://github.com/njuptzx/JavaBlog/blob/main/picture/%E7%99%BB%E5%BD%95.PNG?raw=true)
