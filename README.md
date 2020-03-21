FORK FROM ctftraining/base_image_nginx_mysql_php_73

# Base Image LNMP

- L: Linux alpine
- N: Nginx
- M: MySQL
- P: PHP 7.3
- PHP MySQL Ext
    + mysql
    + mysqli

## Usage

### Files

- src 网站源码
    + index.php
    + ...etc
- Dockerfile
- docker-compose.yml 可选

### Dockerfile

```
FROM docimg/baseimg_mysql_php73_nginx

```
默认端口：80

默认web目录：/var/www/html

mysql root用户默认密码：root
