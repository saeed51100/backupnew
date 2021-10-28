laravel 8 authentication:
Breeze or Jetstream instead of Laravel/ui :
https://redcherry.ir/%DA%A9%DB%8C%D8%AA-%D8%A7%D8%B3%D8%AA%D8%A7%D8%B1%D8%AA%D8%B1-%D9%84%D8%A7%D8%B1%D8%A7%D9%88%D9%84-%D8%A7%D8%AD%D8%B1%D8%A7%D8%B2-%D9%87%D9%88%DB%8C%D8%AA-laravel-starter-kits/
Please do not use them until the release of laravel LTS!

*********************************************************************************************
just files below copied to database/migrations :

2016_10_20_134031_create_tags_table.php
2016_10_20_134040_create_likes_table.php
2016_10_20_134246_create_posts_table.php
2016_11_05_090549_create_post_tag_table.php

other migrations should be reviewed. ( delete or not )
*********************************************************************************************
laravel 8 schema:dump:
Merge migrate files into one file. [optional] ( for big project use more 20 migrations ! )


1) php artisan schema:dump
2) php artisan migrate

to delete migration files too use flag prune:
php artisan schema:dump –prune

**********************************************************************************************
