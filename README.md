# gitlab-ci-php-lint

在gitlab-ci中自动化PHP代码的语法检查和代码异味检查

find code smells in your php through gitlab-ci

## phplint

- 针对yii2资源无法安装问题调整了composer.json中require的顺序


## phpmd

- 调整规则，将一些常用的却会被查出问题的规则剔除，比如静态变量使用，短命名等不再提示