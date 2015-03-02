Wordpress の環境
=====================

- インスタンス1台に1Wordpressな構成を作る
- セキュリティがっちり
- 自動化で楽ちん運用

アーキテクチャ
------------

- CentOS 7
- nginx
- PHP 5.6
- Mariadb 10.0

Wordpress
---------

- Wordpress 4.1.1
- WP-CLI

構成管理
-------

- Chef-Zero
- Capistrano

開発ツール
--------

- Vagrant
- Composer
- PHPUnit
- PHP_CodeSniffer
  - WordPress Coding Standards for PHP_CodeSniffer
- phpDocumentor
- PHPMD

セキュリティ
----------

- firewalld
- SELinux
- Fail2Ban
- WPScan
